import numpy as np
import pandas as pd 
b = np.array([[1,2],[3,4],[5,6]])
a = np .array([0,1,2,3,4,5,6,7,8,9,10])
print(a, b)

import numpy as np
import pandas as pd
df = pd.DataFrame(b, index=['FILA1', 'FILA2', 'FILA3'], columns=['COLUMNA1', 'COLUMNA2'])
provincia = ['Cordoba', 'San Luis', 'Buenos Aires','Rioja', 'Tucuman']
poblacion = [6000000,5000000,4000000,1000000]
diccionario = {'provicia': provincia,'poblacion: poblacion}
df2 = Pd.Dataframe(diccionario)
print(df2)
