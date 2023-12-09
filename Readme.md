#  **<p align="center">Proyecto Individual N° 2 de Data Science</p>** 

<img src="Imagenes\21.jpg" width="1010" height="300">

# <p align="center">Data Analyst</p>


## *1. Descripción del Proyecto*

Proyecto individual N° 2 de la etapa de labs de la carrera de Data Science de la academia SoyHenry.

El objetivo de este proyecto es desarrollar un proceso de Data Analytics y aplicar técnicas para analizar un dataset de la plataforma del Ente Nacional de Comunicaciones de la República Argentina (ENACOM).


## *2. Requerimientos del Proyecto*

Se deberá hacer un trabajo situándose en el rol de un Data Analyst. 

En este contexto, una empresa prestadora de servicios de telecomunicaciones le encarga a usted la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. Considere que la principal actividad de la empresa es brindar acceso a internet, pero también es importante considerar el comportamiento asociado al resto de los servicios de comunicación, con el fin de orientar a la empresa en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.

## *3. Desarrollo del Proyecto*

El proyecto cuenta con las carpetas:

- Datasets
- Datasets_ETL
- Imagenes

Y archivos: 

- 1_ETL.ipynb
- 2_EDA.ipynb
- Dashbord.pbix
- Readme.md

Breve descripción de lo desarrollados en los Notebooks: 

**1_ETL**

A los archivos originales descargados de la plataforma del ENACOM se les realizó un EDA preliminar (Analisis Exploratorio de los Datos) y ETL (Extraccion Transformación y Carga), creando de esta forma cinco archivos .csv.

**2_EDA**

Usando los archivos .csv creados anteriormente se realizó un EDA, se graficaron y analizaron cada grafico (reseñas al pie de cada grafico):

- Acceso a internet por cada 100 hogares (Año/Accesos).
- Acceso a internet por cada 100 hogares (Trimestre/Accesos).
- Velocidad media de bajada de internet.
- Rangos de velocidad de bajada de internet.
- Velocidad de bajada "HASTA 512 kbps".
- Velocidad de bajada "+ 512 Kbps - 1 Mbps".
- Velocidad de bajada "+ 1 Mbps - 6 Mbps".
- Velocidad de bajada "+ 6 Mbps - 10 Mbps".
- Velocidad de bajada "+ 10 Mbps - 20 Mbps".
- Velocidad de bajada "+ 20 Mbps - 30 Mbps".
- Velocidad de bajada "+ 30 Mbps".
- Velocidad de bajada de internet para el año 2022.
- Tipos de conexion a internet (grafico de barras).
- Tipos de conexion a internet (grafico de torta).
- Tipo de conexion a internet por provincia para el año 2022.
- Evolución del tipo de conexión a internet por año (2014 a 2022).

Breve descripción de lo desarrollados DEL Dashboard:

**Dashbord**

En base a los archivos que se encuentran en la carpeta Datasets_ETL se desarrollo el Dashbord.

En mi caso simule ser una empresa de inversiones que analiza los datos del ENACOM, para mostrar nichos de negocios con potencial de crecimientos.

- Con el uso de Power BI se cargo la base de datos para ser analizada. Se empezó por relacionar los distintos dataframe por medio de la columna "Año_trimestre".

- Se crearon dos indicador clave de rendimiento (KPI-Key Performance Indicator):
     - KPI 1 = 0.02, para accesos a internet cada 100 hogares por trimestre.
     - KPI 2 = 0.01, para velocidad meadia de internet por trimestre.

- Se grafico: 
     - Accesos a internet cada 100 hogares acumulados por trimestre por provincia desde el año 2014 al año 2023.
     - Velocidad media de conexión a internet por trimestre por provincia desde el año 2014 al año 2023.
     - Tipos de acceso a internet por trimestre desde el año 2014 al año 2022.
     - Distribucion del tipo de acceso a internet actual (2022). ** Aca se muestra la oportunidad de inversion **

- Se muestran las empresas involugradas en el acceso a internet satelital en Argentina (cada imagen tiene un index).

- Se citan las bibliografias consultadas (cada imagen tiene un index).


## *4. Datasets*

Fueron brindados por Henry la dirección de la base de datos del ENACOM:

- ENACOM. [https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/)

En base a los archivos originales se crearon cinco archivos en formato .csv:

- 1_internet_100hogares_por_provincia.csv
- 2_internet_rangovelocidad_velocidadm_provincia.csv
- 3_internet_portecnologia_porlocalidad.csv
- 4_Calendario_Fechas.csv
- 5_internet_portecnologia_porprovincia.csv

## *5. Conclusíones*

Durante el proceso del trabajo se afinzaron muchos conociminetos en cuanto a la limpieza de datos, su transformación, el uso de Power query, DAX y Power BI. 

En base a los datos analizados se puede concluir que en pocos trimestres se cumplen con el objetivo del KPI propuestos. 

El acceso a internet cada 100 hogares y la velocidad de conexión a internet tiende a la alza. 

Y que se encontro como "Oportunidad de negocio" **el servicio de internet satelital**, por lo que presenta una gran perspectiva de crecimiento en el ambito rural y agropecuario (Esto se jutifica en la presentación del dashbord).

<img src="Imagenes\Conexion.png" width="1010" height="700">

## *6. Autor*

- **Hernán Pizarro**
- Mail: hern4npizarro@gmail.com
- Linkedin: [www.linkedin.com/in/hernán-pizarro-683679268](www.linkedin.com/in/hernán-pizarro-683679268)
