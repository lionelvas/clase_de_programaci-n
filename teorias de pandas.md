# Características clave de un DataFrame:
Filas y Columnas: Al igual que una tabla, un DataFrame tiene filas y columnas. Las columnas pueden tener diferentes tipos de datos (por ejemplo, enteros, cadenas de texto, fechas).

Indexado: Cada fila en un DataFrame tiene un índice (por defecto es un rango numérico desde 0, pero se puede personalizar).

Acceso a los datos: Puedes acceder a los datos de un DataFrame de diversas maneras:

Por nombre de la columna: df['columna']

Por índice de fila: df.iloc[0] o df.loc[0]

Con condiciones: df[df['columna'] > valor]

Manipulación fácil: Puedes agregar, eliminar o modificar columnas y filas, así como realizar operaciones matemáticas o estadísticas sobre las columnas de manera eficiente.
