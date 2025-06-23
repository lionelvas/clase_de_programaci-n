# Características clave de un DataFrame:
Filas y Columnas: Al igual que una tabla, un DataFrame tiene filas y columnas. Las columnas pueden tener diferentes tipos de datos (por ejemplo, enteros, cadenas de texto, fechas).

Indexado: Cada fila en un DataFrame tiene un índice (por defecto es un rango numérico desde 0, pero se puede personalizar).

Acceso a los datos: Puedes acceder a los datos de un DataFrame de diversas maneras:

Por nombre de la columna: df['columna']

Por índice de fila: df.iloc[0] o df.loc[0]

Con condiciones: df[df['columna'] > valor]

Manipulación fácil: Puedes agregar, eliminar o modificar columnas y filas, así como realizar operaciones matemáticas o estadísticas sobre las columnas de manera eficiente.
# dataset
Uno de los usos más comunes de la biblioteca Pandas en Python es el análisis de datos utilizando datasets conocidos.Este conjunto de datos es ideal para aprender a cargar, explorar y procesar información con Pandas.Para trabajar con este dataset, primero se importa la librería Pandas y se carga el archivo CSV desde una URL pública, como la que proporciona GitHub o Kaggle.
# las diferencias
Un DataFrame es una estructura de datos tabular, bidimensional, que organiza la información en filas y columnas, similar a una tabla de base de datos o una hoja de cálculo. Es muy popular en bibliotecas de análisis de datos como Pandas en Python o Spark DataFrame en Apache Spark. Los DataFrames permiten manipular, transformar y analizar datos de forma flexible y eficiente, y pueden contener diferentes tipos de datos en sus columnas. En resumen, un DataFrame es una representación concreta de datos organizados para facilitar su manejo y análisis.

Por otro lado, el término Dataset es más general y se refiere a un conjunto de datos relacionados que se agrupan para ser analizados o procesados. Un dataset puede adoptar diferentes formatos: puede ser una colección de imágenes, archivos de texto, registros de bases de datos, o también tablas estructuradas. En algunos entornos como Apache Spark, un Dataset es una abstracción que combina las ventajas de los DataFrames con la seguridad de tipos de datos que ofrece la programación orientada a objetos.
