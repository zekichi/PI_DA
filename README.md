![An old rock in the desert](https://www.revistaautocrash.com/wp-content/uploads/2022/06/SV-1.jpg)
#  Siniestros viales Data Analitics


En este proyecto analizaremos y visualizaremos datos sobre los siniestros viales en la Ciuadad Autónoma de Buenos Aires dentro de los año 2016 y 2021. Las bases de daos fueron proporcionadas por el Observatorio de Movilidad y Seguridad Vial de la Ciudad de Buenos Aires (OSMV), la cual toma como su principal funte de información datos de policiales.
En este proyecto se trabajo con diferentes herramientas para un analisis exahustivo.

## Repositorio

* **assets**: Carpeta de recursos adicionales.
* **data**: Aarpeta con los conjuntos de datos originales.
* **datasets**: Carpeta con conjuntos de datos procesados y analizados.
* **Power BI**: Carpeta donde se encuentra el dashboard de PowerBI y un pdf del mismo dashboard.
* **ETL**: Archivo en el cual se llevo a cabo un preprocesamiento a los datos originales.
* **EDA**: Archivo en el cual se realizo un análisis exploratorio a los dataset preprocesados.

## Enfoque con el cuál se trabajo

**Objetivos del análisis de datos:**

* Comprender la naturaleza de los siniestros viales en Buenos Aires.
* Identificar patrones y factores de riesgo.
* Proporcionar recomendaciones basadas en evidencia para mejorar la seguridad vial.

**Metodología:**

* **Análisis de datos:**
    * Análisis exhaustivo de los datos disponibles sobre siniestros viales.
    * Desarrollo de un dashboard interactivo para la exploración dinámica y visual de los datos.
* **Informe de hallazgos:**
    * Presentación de hallazgos y conclusiones en un informe detallado.
    * Destaque de los principales insights derivados del análisis de datos.

**Contexto:**
* Alta tasa de mortalidad por siniestros viales en Argentina.
* Comparación con otros tipos de violencia.
* Datos recopilados por el Sistema Nacional de Información Criminal (SNIC).

## Pasos a llevar a cabo

**1. Exploración de Datos**

* Revisa los diccionarios de datos para comprender las variables.
* Examina las tablas de datos "hechos" y "víctimas" para identificar la estructura y el contenido.
* Identifica variables clave relacionadas con siniestros viales (por ejemplo, fecha, hora, ubicación, tipo de vehículo).

**2. Limpieza y Preparación de Datos**

* Identifica y trata los datos faltantes (por ejemplo, imputación, eliminación).
* Convierte los datos al formato adecuado para el análisis (por ejemplo, numérico, categórico).

**3. Análisis de Datos**


* Corrige las inconsistencias en los datos (por ejemplo, valores atípicos, errores ortográficos).
* Realiza un análisis exploratorio de datos para identificar patrones y tendencias.
* Utiliza técnicas estadísticas para analizar la frecuencia, distribución y correlaciones de las variables.
* Identifica factores que contribuyen a los siniestros viales (por ejemplo, exceso de velocidad, conducción bajo los efectos del alcohol).

**4. Dashboard Interactivo**

* Desarrolla un dashboard interactivo que permita a los usuarios:
* Explorar los datos mediante gráficos interactivos (por ejemplo, histogramas, gráficos de dispersión).
* Filtrar los datos por variables específicas (por ejemplo, tipo de vehículo, ubicación).
* Ver tablas resumen que proporcionen estadísticas clave (por ejemplo, número de víctimas fatales por año).

**5. Informe y Presentación**

* Documenta los hallazgos y conclusiones en un informe detallado.
* Resalta los principales patrones y tendencias identificados en el análisis de datos.
* Proporciona recomendaciones claras para las autoridades locales basadas en los hallazgos.
* Prepara una presentación que resuma los aspectos más importantes del análisis y las recomendaciones.

**Objetivo Final:**

Proporcionar información valiosa que ayude a las autoridades a implementar medidas efectivas para reducir las víctimas fatales en los siniestros viales.

## ETL
Se llevo a cabo un pequeño trabajo de preprocesamiento de datos para normalizar columnas y valores. Del Cual salieron los archivos para el EDA.

## EDA
En el archivo EDA se análiso el conjunto de datos proveniente del ETL, en cual se le hizo tratamientos a valores atípicos o outliers. En este nuestro principal objetivo era la busqueda de patrones y tendencias en los conjuntos de datos, donde se encontraron insights valiosos para la creación de KPIs en PowerBI.

## Dashboard PowerBI
Se utilizo la herramienta de Microsoft, PowerBI, para la creación de un dashboard interactivo, para facilitar la vizualización de los datos. En este mismo se llevo a cabo la creación de KPIs para el análisis de la situación de los siniestros viales en la ciudad de Buenos Aires.

## Adicionales
Adicionalemente a laos conjuntos de datos que se nos proporcionaron, se hizo uso de un conjunto de datos que nos específicaba la cantidad de población por comuna de la Ciudad. Este conjunto de datos fue extraido de la página de base de datos de la Ciudad Autonoma de Buenos. [Link](https://data.buenosaires.gob.ar/dataset/estructura-demografica/resource/a24fc775-ad6e-4bb0-8a7a-2283c2adea34).
