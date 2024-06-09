Datos para el aprendizaje automático con R
Machine Learning with R de Brett Lantz es un libro que proporciona una introducción al aprendizaje automático con R. Por lo que puedo decir, Packt Publishing no crea sus conjuntos de datos disponible en línea a menos que compre el libro y cree una cuenta de usuario, lo que puede ser un problema si está sacando el libro de la biblioteca o tomando prestado el libro de un amigo. Todos estos conjuntos de datos son de dominio público, pero simplemente necesitaban un poco de limpieza y recodificación para que coincidieran con el formato del libro.

Cómo descargar los datos
En su entorno Mac o Linux, abra una terminal y cambie al directorio donde desea que se descarguen sus datos.
Vaya a la página de github en la que desea descargar sus datos (por ejemplo, los datos del retador en el capítulo 6: https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/challenger.csv)
En el lado derecho, encontrarás un botón llamado "raw". Haz clic en él.
Copie la url que obtendrá para la nueva página (en nuestro ejemplo obtuve https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/challenger.csv)
Coloque el siguiente comando en la pantalla del terminal wget name_of_url
Así que en nuestro ejemplo debería ser así wget https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/challenger.csv

Capítulo 1
No se utilizan conjuntos de datos

Capítulo 2
usedcars.csv no se pudo encontrar en línea

Capítulo 3
wisc_bc_data.csv de https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/

Capítulo 4
sms_spam.csv de http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/

Capítulo 5
credit.csv de https://archive.ics.uci.edu/ml/machine-learning-databases/statlog/german/

mushrooms.csv de https://archive.ics.uci.edu/ml/machine-learning-databases/mushroom/

Capítulo 6
challenger.csv de https://archive.ics.uci.edu/ml/machine-learning-databases/space-shuttle/

insurance.csv no se pudo encontrar en línea

whitewines.csv de https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/

Capítulo 7
concrete.csv de https://archive.ics.uci.edu/ml/machine-learning-databases/concrete/compressive/

letterdata.csv de https://archive.ics.uci.edu/ml/machine-learning-databases/letter-recognition/

Capítulo 8
groceries.csv es de un paquete de reglas, pero probablemente sea más fácil de llamar library(arules); data(Groceries)

Capítulo 9
snsdata.csv no se pudo encontrar en línea

Capítulo 10
sms_results.csv es probable que provenga del objeto del capítulo 4, pero es difícil estar seguro.sms_test_pred

credit.csv probable sea el mismo archivo del Capítulo 5.

Capítulo 11
credit.csv del Capítulo 5 se reutiliza.

Capítulo 12
No se utilizan conjuntos de datos
