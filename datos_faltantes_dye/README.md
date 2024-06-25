# Manejo de datos faltantes: Deteccion y Exploracion

Ignorar los valores faltnates puede introducir sesgos en los analisis y los modelos.  
Se puede sobreestimar o subestimar si existen datos faltantes. Ademas los algoritmos probalmente fallaran.  
  
## Operaciones con datos faltantes  

En el caso de Python, es posible que se ignore.
  
```python
import pandas as pd
s = pd.Series([1, 2, 3, 4, 5, None])
s.mean()
#> 3.0
```  
