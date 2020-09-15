# redwinequalityclassification
Este proyecto se compone de un análisis exploratorio de las variables del conjunto de datos, así como de la construcción de un modelo de clasificación de la calidad del vino.
Se puede encontrar información acerca del conjunto de datos, ejemplos y más en Kaggle: https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009
Por conveniencia, en este repositorio se encuentra el conjunto de datos en CSV para su uso, perteneciente en su totalidad a Kaggle y a sus respectivos autores.

## Objetivos
- Llevar a cabo un análisis exploratorio univariante y multivariante.
- Comprender más acerca de distintos conceptos relacionados con la enología.
- Aplicar diferentes conceptos estadísticos. En mi caso, me he apoyado en el libro ThinkStats 2.
- Construir un modelo de predicción de tipo clasificación para la calidad del vino.

## Proceso de trabajo
Los primeros pasos iban encaminados, como se hace normalmente, a entender el conjunto de datos y aprender conceptos relacionados con la enología para ampliar el conocimiento sobre nuestras variables.
Se ha hecho un análisis de cada variable a nivel individual y, posteriormente, multivariante.
Para finalizar la exploración de los datos, se ha realizado un pequeño contraste de hipótesis para arrojar luz sobre una variable concreta (grados de alcohol).
En el último apartado, se han construido tres modelos diferentes de aprendizaje automático (decision tree, random forest y regresión logística).
He trabajado en el ajuste de los modelos, por medio de la aplicación de normalizadores de los datos e ingeniería de variables.
El modelo de regresión logística alcanza un poder predictivo del 75 %.
Aunque hay margen de mejora en el modelo en sí, los diferentes ajustes permiten ver cómo afectan a las métricas (accuracy, precision, recall, F1-score).

Generalmente, este trabajo he llevado un proceso de aprendizaje continuo, con el cual he ido incorporando nuevos conceptos a medida que el trabajo avanzaba.
Puede verse en los comentarios que se van haciendo a lo largo del cuaderno.

El notebook se ha trabajado completamente en VS Code.

## Versiones
· Python 3.7.6
· Numpy 1.18.1
· Pandas 1.0.1
· Matplotlib 3.1.3
· Seaborn 0.10.0
· Scipy 1.4.1
· Scikit-learn 0.23.2
