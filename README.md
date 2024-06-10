![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=flat&logo=jupyter)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat&logo=seaborn)
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=powerbi)
![Streamlit](https://img.shields.io/badge/Streamlit-deploy-brightgreen?style=flat&logo=streamlit&logoColor=red&logoSize=auto)
![Scikitlearn](https://img.shields.io/badge/Scikitlearn-F7931E?style=flat&logo=scikitlearn&logoColor=white&logoSize=auto)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white&logoSize=auto)
![Folium](https://img.shields.io/badge/Folium-F8C517?style=flat&logo=folium&logoColor=white&logoSize=auto)
![GoogleBigQuery](https://img.shields.io/badge/Google%20Big%20Query-669DF6?style=flat&logo=googlebigquery&logoColor=white&logoSize=auto)
![GoogleCloudStorage](https://img.shields.io/badge/Google%20Cloud%20Storage-AECBFA?style=flat&logo=googlecloudstorage&logoColor=white&logoSize=auto)

## **HOLA! SOY MANUEL DAVID** 

# Quien soy? #
¡Hola! 👋 Soy Manuel David, Ingeniero Eléctrico y Electrónico 👷‍♂️con una sólida trayectoria de más de 9 años en estudios eléctricos⚡. Mi pasión por los datos y su análisis 📊📈 me ha llevado a explorar constantemente nuevas herramientas y tecnologías para potenciar mi carrera profesional. Recientemente, he estado inmerso en la adquisición de habilidades clave como Python, Docker, Google Cloud Platform, PowerBI, Streamlit y Tableau, con el objetivo de ofrecer soluciones más eficientes y avanzadas en mi campo. 😊 Estoy emocionado de conectar con colegas y profesionales afines para compartir conocimientos y experiencias en este apasionante mundo de la ingeniería y la tecnología. ¡Espero poder conectar contigo pronto!💻

 ## **Contexto**

LLos siniestros viales, también conocidos como accidentes de tráfico o tránsito, son eventos que implican vehículos en las vías públicas y pueden ser causados por diversas razones, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, choques contra objetos fijos o volcamientos. Estos incidentes pueden resultar en daños materiales, lesiones graves o incluso la muerte de los involucrados.

En Argentina, aproximadamente 4.000 personas mueren cada año en siniestros viales. A pesar de los esfuerzos para reducir la cantidad de accidentes de tránsito, este sigue siendo la principal causa de muertes violentas en el país. Según los informes del Sistema Nacional de Información Criminal (SNIC) del Ministerio de Seguridad de la Nación, entre 2018 y 2022 se registraron 19.630 muertes en accidentes de tránsito en todo el país, lo que equivale a un promedio de 11 víctimas fatales por día.

Buenos Aires, la capital y la ciudad más poblada de Argentina, tiene una superficie de poco más de 200 km2 y un perímetro de 60 km. La ciudad está dividida político-administrativamente en quince comunas, con una densidad de población de más de 15.000 habitantes por kilómetro cuadrado. Las zonas centro y norte son las áreas más densamente pobladas. Según el censo de 2022, la población de la ciudad es de 3.120.612 habitantes.

Solo en el año 2022, se registraron 3.828 muertes en siniestros viales en la ciudad de Buenos Aires. Los expertos señalan que en Argentina, la probabilidad de que una persona muera en un accidente de tránsito es dos o tres veces mayor que en un incidente de inseguridad delictiva.

## **Desarrollo**

### Datos

Para este proyecto se trabajó con la **Bases de Víctimas Fatales en Siniestros Viales** que se encuentra en formato de Excel y contiene dos pestañas de datos:

 * **HECHOS**:  `homicidios.xlsx` - Hoja: HECHOS. Cuenta con 21 Columnas y 696 filas
Cada registro contiene 21 características o columnas.  Las columnas son:

1. "ID": identificador unico del siniestro (String)
2. "N_VICTIMAS": cantidad de víctimas (númerico)
3. "FECHA": fecha en formato dd/mm/aaaa (numérico)
4. "AAAA":	año (numérico)
5. "MM": mes (numérico)
6. "DD": día del mes (numérico)
7. "HORA": 	hora del siniestro (String)
8. "HH": franja horaria entera (String)
9. "LUGAR_DEL_HECHO": Dirección del hecho (string)
10. "TIPO_DE_CALLE"	Tipo de arteria. En el caso de intersecciones a nivel se clasifica según la de mayor jerarquía
11. "Calle":	nombre de la arteria donde se produjo el hecho
12. "Altura":	altura de la arteria donde se produjo el hecho
13. "Cruce":	cruce en caso de que sea una encrucijada
14. "Dirección Normalizada":	direccion en formato normalizado USIG
15. "COMUNA":	Comuna de la ciudad (1 a 15)
16. "XY (CABA)":	geocodificación plana
17. "pos x":	longitud con separador punto. WGS84
18. "pos y":	latitud con separador punto. WGS84
19. "PARTICIPANTES":	conjunción de víctima y acusado
20. "VICTIMA":	Vehículo que ocupaba quien haya fallecido a se haya lastimado a raíz del hecho, o bien peatón/a. Clasificación agregada del tipo de vehículos.
21. "ACUSADO":	Vehículo que ocupaba quien resultó acusado/a del hecho, sin implicar culpabilidad legal

 * **VICTIMAS**: `homicidios.xlsx` - Hoja: VICTIMA. Cuenta con 17 Columnas y 717 filas
Cada registro contiene 17 características o columnas.  Las columnas son:
1. "ID_hecho":	identificador unico del siniestro
2. "FECHA":	fecha en formato dd/mm/aaaa
3. "AAAA":	año
4. "MM":	mes
5. "DD":	día del mes
6. "ROL":	Posición relativa al vehículo que presentaba la víctima en el momento del siniestro
7. "VICTIMA":	Vehículo que ocupaba quien haya fallecido a se haya lastimado a raíz del hecho, o bien peatón/a. Clasificación agregada del tipo de vehículos.
8. "SEXO":	Sexo informado por fuente policial de la víctima
9. "EDAD":	Edad de la víctima al momento del siniestro
10. "FECHA_FALLECIMIENTO":	Fecha de fallecimiento de la víctima


-`Proceso de ETL (Extracción, limpieza y carga de datos)` se realiza la extraccíon y limpieza de los datos de los dos dataset `HECHOS` y `VICTIMAS`, a tráves de la utilización de Pandas y Jupyter Notebook.[ETL](ETL_Homicidios_H.ipynb) y (ETL_Homicidios_V.ipynb) Eliminando nulos, duplicados, con transformaciones necesarias como cambio en los tipos de datos, eliminación de columnas y unión de las tablas en un archivo `homicidios_T_EDA.xlsx` [archivo](data/homicidios_T_EDA.xlsx).

-`Proceso de EDA (Análisis Exploratorio de los datos)` una vez que los datos están limpios, es momento de revisar las relaciones que existen entre las variables numéricas y categóricas de los datasets, encontrar si hay presencia de outliers o anomalías (que no tienen que ser errores necesariamente), y se verificó si hay algún patrón o conocimiento que sirva en un análisis posterior. [EDA](EDA.ipnyb)

### Análisis de los datos

- Se analizan las variables numéricas del dataset su correlación por medio de una matriz, donde se encuentra una relación positiva entre las variables `Edad`y `Hora`
- La máyoria de los siniestros resultan con una víctima fatal, rara vez involucran 3 víctimas.
  
-`Análisis Temporal:` 

En el transcurso de los años, los accidentes con víctimas fatales muestran: para el período 2016-2018 una tendencia alta y estacionaria, que luego se convierte en bajista (teniendo en cuenta el comienzo de la Pandemia por COVID19 durante 2020); puede verse un pico de siniestros durante Diciembre de 2021 y se retoma la tendencia bajista.
Los meses con más victimas fatales son **Diciembre** (86) y **Agosto**(71); mientras que los días de la semana **Sábado** (114) y **Domingo** (114) tienen la mayor cantidad de víctimas.


![Mapa de Calor](/imagenes/mapaDeCalor.PNG)

Los horarios críticos de los siniestros viales están relacionados con los momentos del ingreso a la jornada laboral (5-9h), el momento del almuerzo (12-14h) y la salida del trabajo (17-18h). Mientras que los fines de semana están relacionados con las salidas nocturnas (4-7h)

-`Análisis Demográfico y Geográfico:`

Edad de las víctimas : La distribución del rango etario de víctimas, resulta para los `Masculinos` entre 20 y 40 años; mientras que para los `Femeninos` entre 40, 60 y 80 años.

![Rango etario](/imagenes/DistribucionEdadVSexo.png)

El patrón de correlación Edad y Hora de las variables númericas se analiza agregando la variable Sexo, de lo que resulta la conclusión que los horarios en que los accidentes son protagonizados por Masculinos es al horario de ingreso y egreso laboral, mientras que para los Femeninos es en el horario cercano al almuerzo.

![Relacion edad hora](/imagenes/Edad_Hora_Sexo.png)

Utilizando la herramienta GeoPandas y extrayendo los datos de los detalles de los Barrios que conforman las 15 comunas de CABA; resulta el análisis de las coordenadas geográficas y comunas de CABA, que demostro que las comunas con más siniestos son las 1, 4 , 9, 8 y 7. 

![Tabla comuna](/imagenes/Comunas.PNG)

Los siniestros se producen en 62% de los casos en el tipo de calle `Avenida` y en el 82% de los casos se corresponden con un Cruce entre calles. Lo que resulta un patrón que se repite a lo largo de los años.

-`Análisis Participativo:`

Para el caso de la variable `Participantes` de los sinietros; se analiza a `Acusados`, como el vehículo que tiene la responsabilidad del hecho, de lo que resultan los Autos, Colectivos y Vehículos de Carga como mayores involucrados. Para el análisis de las `Victimas`, que en momento del accidente resultaban mayormente en el **Rol** de Conductor o Peatón; y el siniestro se produce en la mayoría de los casos en Motos y luego como Peaton.

### Indicadores de Rendimiento Clave KPI

Una vez finalizado el Análisis Exploratorio, se utiliza el dataset resultante [Siniestros](data/homicidios_T_EDA.xlsx) y los extraidos de la página oficial de CABA con los datos de las comunas [Comunas](data/comunas.xlsx); para trabajar en la herramienta PowerBi a fin de obtener los KPI (Indicadores de Rendimiento Clave) y un `dashboard` de presentación del informe y Visualización de datos.
Se utliza la herramienta NovyPro para mostrar el `dashboard` resultante de manera interactiva. [link](https://app.powerbi.com/view?r=eyJrIjoiM2ZhNGJhMDctMDU3Ni00YjZkLWEwNDAtNWVjMDhkMjEyOTYwIiwidCI6Ijc1MDRlMzE4LThlMWUtNGQ1NS1iZmZkLTg3NWI0ZGVlODI2MCIsImMiOjR9)

KPI Propuestos

![KPI](/imagenes/KPIS.PNG)

 - **Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior**

Se define la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico. Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000

Número de Homicidios de Siniestros = Tomando la variable `Num víctimas` del dataset
Población Total = Tomada del Censo 2022. (Fuente:INDEC)

 - **Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior**

Se define la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100

Cantidad de Accidentes Mortales en Moto = Tomando la variable `Victima` que se iguale a el campo [MOTO] del dataset 



 - **Reducir en un 15% la cantidad de accidentes con víctimas fatales de autos en el último semestre, en CABA, respecto al semestre anterior.**

Se define la cantidad de accidentes fatales de autos en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que circulaban a pie en un determinado periodo temporal. Su fórmula para medir la evolución de los accidentes mortales con víctimas auto es: (Número de accidentes mortales con víctimas auto en el semestre anterior - Número de accidentes mortales con víctimas auto en el semestre actual) / (Número de accidentes mortales con víctimas auto en el semestre anterior) * 100

Cantidad de Accidentes Mortales en auto = Tomando la variable `Victima` que se iguale a el campo [AUTO] del dataset 


![Indicadores](/imagenes/kpisindicadores.PNG)


## **Conclusiones**

Tras analizar minuciosamente los datos y visualizarlos en un dashboard de PowerBi, se determina que entre los años 2016 y 2021, se registraron un total de 717 víctimas fatales debido a accidentes de tránsito. La franja horaria con mayor incidencia de siniestros corresponde al horario de entrada laboral (5-9h), almuerzo (12-14h) y regreso a casa (17-18h). Durante los fines de semana, especialmente los sábados y domingos, los accidentes son más frecuentes durante las salidas nocturnas (3-7h). El 76% de las víctimas son hombres, con edades comprendidas entre los 20 y 40 años.

En cuanto al rol de las víctimas masculinas en los accidentes, la mayoría se desempeñaba como conductores. Las motocicletas son los vehículos más comunes involucrados en los accidentes con víctimas, seguidos por los peatones. Por otro lado, los autos, colectivos y vehículos de carga son los más frecuentes entre los acusados.

Los accidentes tienden a ocurrir principalmente en avenidas a lo largo de los años, así como en cruces de calles. Se observa un patrón en relación con la edad, el horario y el sexo de las víctimas masculinas, que se concentran entre los 20 y 40 años durante las horas de entrada y salida laboral, así como durante las salidas nocturnas de los fines de semana.

Se sugiere mejorar las señales y controles de tránsito en las avenidas, especialmente en las comunas 1 y 4 de CABA, y desarrollar campañas de prevención dirigidas específicamente a hombres de entre 20 y 40 años.

<div align="center">
  <a href='https://www.linkedin.com/in/mdtrujillo73//'>
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"alt="Linkedin"/>
  </a>
  <a href='mailto:md.trujillo73@gmail.com'>
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</div>
