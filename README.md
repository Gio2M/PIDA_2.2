## Accidentes Aereos

Este repositorio contiene un proyecto relacionado con el análisis y visualización de datos sobre accidentes aereos de varios paises con datos historicos desde el año 1918 hasta el año 2021, para lo cual se ulilizaron diversas herramientas en Python para hacer el EDA y entender las tendencias presentes y Power BI para el la visualizacion despliege y monitoreo de los datos.

## Descripción

Este proyecto tiene como objetivo principal obtener, explorar y analizar datos recogidos por las entidades aeronauticas conpetentes sobre los siniestros aereos. Además, se utilizan herramientas de Python como Pandas y Matplotlib para realizar análisis y visualizaciones significativas. Las carpetas y archivos principales del proyecto son los siguientes:

## Estructura del Repositorio

- `Dashboard_siniestros.pbix`: Archivo de Power BI que podría contener visualizaciones y análisis adicionales.
- `Data`: Carpeta que contiene tanto los datos fuente proporcinados por la ciudad como los datos resultado del EDA, generados o procesados y exportados a formato .xlsx pora el proyecto los cuales se utilizan para realizar las diferentes visualizaciones en Power BI.
- `EDA`: Carpeta que contiene el notebook con análisis exploratorio de datos para el para las variables que tienen algun tipo de relevancia para el proyecto.
- `README.md`: Este archivo que proporciona información detallada sobre el proyecto.

# Conclusiones y Resumen del Proyecto

En este análisis exploratorio de datos, hemos examinado detalladamente el dataset Accidentes Aereos proporcionados por para realizar el proyecto. El objetivo de este EDA era comprender mejor la estructura y las características de los datos, así como identificar patrones y tendencias importantes. A continuación, se resumen las principales conclusiones y hallazgos obtenidos:

## Resumen General del Conjunto de Datos

El conjunto de datos contiene un total de 5008 registros de los cuales finalmete se utilizaron 4554 registros y 16 variables.
Las variables incluidas en el conjunto de datos son:
- Columnas de df_hechos: 'fecha', 'HORA declarada', 'Ruta', 'OperadOR', 'flight_no', 'route', 'ac_type', 'registration', 'all_aboard', 'PASAJEROS A BORDO', 'crew_aboard', 'cantidad de fallecidos', 'passenger_fatalities' 'crew_fatalities', 'ground', 'summary'
Desde el principio se analizaron solo las variables que presentaban algun potencial que pudiera contribuir con el objetivo final de el proyecto que analizar la evolucion de los sinientros aereos.


## Estadísticas Descriptivas

Se calcularon estadísticas descriptivas, como la media, la mediana, la desviación estándar y los percentiles, para las variables numéricas clave. Algunos de los hallazgos clave incluyen:
- Las estadisticas descriptivas que se obtuvieron de las dos variable importantes para este analisis en los dos dataset que son crew_aboard y cantidad de fallecidos nos muestran que el 75% de los accidentes involucran hasta 5 tripulantes como victimas fatales y que el promedio de victimas fatales por cada siniestro aereo es de 22 lo que nos indica que las tripulaciones representan un numero considerable de victimas en los accidentes aereos.


## Visualizaciones

Se crearon varias visualizaciones para explorar las relaciones y patrones en los datos. Algunos de los hallazgos visuales más destacados incluyen:
- La cantidad de victimas fatales hacia los ultimos meses del año entra una tendencia de aumento dos veces al año de abril a septiembre y de octubre a diciembre.
- Durante las diferentes horas del dia tambien se encuentran patrones de ocurrencia siendo la franja de tiempo que va desde las 5 a las 23 horas la que presenta mayor accidentalidad y en las horas de la mañana hay una caida drastica; comenzando desde las 0 hasta las 4 horas y luego nuevamente comienza el ciclo a las 5 horas. 


## Correlaciones

En esta matriz de correlacion podemos observar la fuerte dependencia entre la cantidad total de fallecidos y el numero de pasajeros fallecidos, asi como tambien la dependencia entre la cantidad de personas a bordo y el numero total de pasajeros a bordo.


## Conclusiones Generales

A medida que continuamos con el análisis y la interpretación de estos datos, es importante recordar que el EDA es un proceso iterativo y que se pueden realizar análisis más detallados en el futuro.

Existe una evidente correlacion entre el mes del año y la hora del en el resultado de un siniestro faltal pero cada una una de estas variables se analiza por separado para tratar de entender su comportamiento y la forma en que se puede relacionar con otras variables.

Este análisis exploratorio de datos proporciona una sólida comprensión de los dataset accidentes aereos que se pone a disposicion para realizar el proyecto. Despues de realizar una inspeccion detallada se puede entender claramente como se compone el dataset y como interpretarlo lo que ayuda mucho para lograr el objetivo de este proyecto. Asi mismo debemos considerar que este mismo dataset nos puede servir como base para futuros análisis y toma de decisiones relacionados con estos datos.

## Contribuciones
¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, por favor crea un pull request.

## Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

## Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de gio75388@gmail.com.

## Créditos
Pandas
Matplotlib
Power BI
Soyhenry.com
Otros recursos y bibliotecas utilizados en el análisis y visualización de datos.
