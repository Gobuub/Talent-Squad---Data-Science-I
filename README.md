# Talent-Squad---Data-Science-I
Talent Squad - Data Science I for NUWE


## Background | Problema a solucionar

Aproximadamente 300 sensores están conectados al cohete y al lanzador móvil para detectar, registrar y transmitir la información». SpaceX está lanzando una nueva cadena de cohetes con un nuevo propósito de negocio, rocket-commerce. Para poder conseguirlo, Elon Musk quiere predecir el estado de los cohetes para poder ajustar costes de forma dinámica. Para ello nos ha proporcionado los datos de varios sensores y su estado. ¿El objetivo? Crea un modelo que sea capaz de predecir el estado.

El objetivo de este reto será ayudar a Elon realizando el modelado predictivo a partir de un dataset que contiene las mediciones hechas por sus sensores y tipos.

### Datasets
Variables del dataset:

    Features: El dataset contiene 6 features en 6 columnas, que son los parámetros medidos de los diferentes sensores. Estos corresponden a las vibraciones detectadas en el cohete.

    Target: El target corresponde al 'label' que clasifica los tipos de estados del cohete en función de los features medidos por los sensores.

        Target 0 corresponde a Estable
        Target 1 corresponde a Turbulencia Ligera
        Target 2 corresponde a Turbulencia Moderada
        Target 3 corresponde a Turbulencia Severa
        Target 4 corresponde a Turbulencia Extrema
### Archivos:

    Incluidos en la carperta data del repositorio:

        space_X_train.csv: Este dataset contiene tanto las variables predictoras como el tipo de estado.

        space_X_test.csv: Este dataset contiene las variables predictoras con las que se tendrá que predecir el tipo de estado.

## Resultados y analásis 

La solución se encuentra en el archivo 'results.csv'.

El modelo seleccionado después de varias pruebas es un randomforest clasiffier.

El mejor resultado obtenido después de entrenar varios modelos es de un 0,79 f1_score.


## Solución adoptada

El set entregado estaba balanceado y no se ha aplicado ninguna técnica de balanceo ya que los modelos seleccionados basádos en arboles de decisión tienen un rendimiento muy optimo sin tener en cuenta si los datos están desbalanceados.

En la carpeta de data están los set propuestos para el caso, tanto el de entrenamiento como el de test.

Se adjunta el jupyter notebook donde se ha realizado el estudio de los datos y el entrenamiento de los modelos predictivos, y el resultado final del modelo seleccionado.


## Contact info | Not required | Recommended

Puede visitar mi [web](https://enriquerevueltagarcia.com) para ver más proyectos mios.

o explorar mi [github](https://github.com/Gobuub)