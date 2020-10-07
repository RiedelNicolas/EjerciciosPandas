# Pandas

### Nicolas Riedel

### [Repo con ejercicios](https://github.com/RiedelNicolas/EjerciciosPandas)


## Cheat sheet

*	Siempre importar : 
	-	import *pandas* as pd
	-	import *numpy* as np
 
*	Leemos el CSV
	
	df = pd.read_csv(path, encoding='latin-1'(u otro) )

*	Si queremos levantar solo algunas columnas:  	
	df_short = pd.read_csv(path,usecols= \[nombre de col1', 'col2', ... ])
				
*	pantallazo de como esta formado el data frame
	df.info()
	
*	Metodos que devuelven partes de la estructura :
	-	indice : df.index
	-	columnas : df.columns
	-	toda la data : df.values
	-	
*	 serie.value_counts() : 
	 Cuenta las ocurrencias que tiene cada elemento perteneciente a la serie.
 *	Acceder a una columna
	 df\['nombre de la columna']
	 
*	llevar serie a data frame:
		serie.to_frame()
*	.head(n)
	aplicable tanto a series como df nos da los primeros n elementos.
	
*	Forma del data frame
	-	size (cantidad elementos)
	-	shape (filas x columnas)
	-	count (valores !null x columna)
* .hasnans
	aplicable a serie o DF booleano que responde si hay NaN
* .fillna(x)
	filleamos los NaN con el valor que querramos
*	dropna
	remueve los elementos NaN (comun en series)
*	Estadisticos a series
	-	.count() 
	-	.mean()
	-	.std()
	-	.min,max()
	-	.describe() (Me da una lista con todos los prev)
	-	value_counts()
	-	
*	
	
	