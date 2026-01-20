## Datos del proyecto

Esta carpeta contiene los datasets finales utilizados en el modelo de datos
y en las visualizaciones desarrolladas en Power BI.

### Tablas de hechos
Los siguientes archivos CSV corresponden a las tablas de hechos del modelo,
todas ellas agregadas a nivel de comunidad autónoma y año:

- Ense_All_Clean.csv
- Pib_ccaa_2017_2020_2023_Final.csv
- Hospitales_Agregado_All.csv

### Tablas de dimensiones
- dim_ccaa.csv: dimensión territorial utilizada para normalizar las comunidades autónomas.

La dimensión temporal se limita a tres años concretos (2017, 2020 y 2023) y ha sido
gestionada directamente en Power BI mediante el campo Año, sin la creación de una
tabla calendario independiente, al no ser necesaria para el alcance del análisis.

### Nota sobre la tabla de población

La información de población por comunidad autónoma se obtuvo a partir de fuentes
oficiales del INE. Los datos originales disponibles cubrían únicamente los años
2017 y 2020.

El valor correspondiente a 2023 fue incorporado posteriormente y la tabla final
de población, con los tres años del estudio (2017, 2020 y 2023), fue construida
directamente en Power BI como parte del proceso de modelado, por lo que no se
incluye como archivo CSV independiente en este repositorio.

