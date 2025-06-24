# numpy
## codigo
```
import numpy as np
import pandas as pd 
b = np.array([[1,2],[3,4],[5,6]])
a = np .array([0,1,2,3,4,5,6,7,8,9,10])
print(a, b)
```

# pandas
## codigo
```import numpy as np
import pandas as pd
b = np.array([[1,2],[3,4],[5,6]])
df = pd.DataFrame(b, index=['FILA1', 'FILA2', 'FILA3'], columns=['COLUMNA1', 'COLUMNA2'])
provincia = ['Cordoba', 'San Luis', 'Buenos Aires','Rioja', 'Tucuman']
poblacion = [6000000,5000000,8000000,4000000,1000000]
diccionario = {'Provicia': provincia,'Poblacion': poblacion}
df2 = pd.DataFrame(diccionario)
print(df2)
```

# actividad 1
## explicacion de las colunas
```import pandas as pd 
df = pd.read_csv('StudentsPerformance.csv')
print(df) #muestra los primeros y ultimos de todas las colunas)  
print (df['lunch']) #para mostrar los primeros y ultimos de una coluna que digas
print(df.head()) #muestra los primeros de todas las colunas
print(df.tail()) #muestra los ultimos de todas las colunas
print(df.head()) #()dentro la cantidad de nuumeros muestra los primeros de todas las colunas
print(df.tail()) #()dentro la cantidad de nuumeros muestra los ultimos de todas las colunas
```
