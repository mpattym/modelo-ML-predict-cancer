# modelo-ML-predict-cancer
1mar2023 A partir de un conjunto de datos de muestras se aplicarán modelo machine learning para predecir si un paciente tiene o no cáncer de mama.


Prueba Final (Opción A)

**modelos de machine learning que se pueden utilizar para predecir si un paciente tiene o no cáncer de mama**

Supongamos que usted trabaja en el servicio de salud y recibe muestras que provienen de mujeres con cáncer de mama. Los médicos han extraído características y las han anotado, su trabajo es crear un modelo que sea capaz de identificar si un paciente tiene o no cáncer. Recordemos que un falso positivo no es tan preocupante como un falso negativo, ya que en el futuro se le hacen más pruebas a las pacientes y hay oportunidades de descubrir que estábamos en un error. Sin embargo, un falso negativo puede llevar a que el cáncer se desarrolle sin supervisión durante más tiempo del necesario y podría llevar a daños más graves o incluso la muerte de la paciente.

Teniendo esto en cuenta, desarrolla un modelo que funcione lo mejor posible y explica qué decisiones has tomado en su elaboración y por que. A entregar obligatoriamente:

Link a un repositorio público de Github que contenga al menos:
Un archivo Jupyter Notebook con todas las celdas ejecutadas en orden. Es decir, que antes de subir el archivo a github habéis limpiado el notebook (Kernel restart and clear output) y luego lo habéis ejecutado desde el principio).
Un archivo Readme en el que se explica el proyecto y el ejercicio. Tened en cuenta que este repositorio puede serviros como CV en el futuro y que los recruiters suelen mirar los archivos Readme.md
Una carpeta data con el dataset. En el notebook debe aparecer el proceso de preprocesado de datos desde los archivos originales a ser posible. En el notebook debéis probar al menos con 3 modelos, evaluarlos y decidir cual es el mejor, justificando la respuesta en base a las matrices de confusión que aparecen al evaluar el error en training y en test. El dataset y su descripción aparecen aquí: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29


Razonamientos:

Existen varios modelos de machine learning que se pueden utilizar para predecir si un paciente tiene o no cáncer de mama a partir de un conjunto de datos de muestras. A continuación se mencionan algunos de ellos:

Árboles de decisión: los árboles de decisión son modelos de clasificación que dividen los datos en ramas, tomando decisiones en cada nodo. Este modelo es útil cuando los datos son heterogéneos y tienen muchos atributos.

Regresión logística: la regresión logística es un modelo de clasificación que predice la probabilidad de que un paciente tenga cáncer de mama. Es útil cuando se tiene una gran cantidad de datos y cuando los datos tienen una distribución normal.

Support Vector Machines (SVM): las SVM son un modelo de clasificación que encuentra el mejor hiperplano que separa los datos. Es útil cuando se tiene un conjunto de datos linealmente separable.

Redes neuronales: las redes neuronales son modelos de aprendizaje profundo que se basan en la estructura del cerebro humano para clasificar los datos. Este modelo es útil cuando se tienen datos complejos y no lineales.

Cada modelo tiene sus ventajas y desventajas, y es importante evaluar su rendimiento en el conjunto de datos específico antes de decidir cuál utilizar. Además, es importante tener en cuenta que un solo modelo no puede proporcionar una predicción precisa en todos los casos, por lo que puede ser útil combinar varios modelos para mejorar la precisión de la predicción.
