# Analisis del Riesgo Relativo en el Banco "Super Caja".
Se realiza una exploracion de los datos del banco "Super Caja"con el objetivo de segmentar y evaluar la situación crediticia de sus clientes. El objetivo del análisis es armar un score crediticio a partir de un análisis de datos 
y la evaluación del riesgo relativo que pueda clasificar a los solicitantes en diferentes categorías de riesgo basadas en su probabilidad de incumplimiento. 
Esta clasificación permitirá al banco tomar decisiones informadas sobre a quién otorgar crédito, reduciendo así el riesgo de préstamos no reembolsables. 
En este proyecto, Se busca obtener:

  - Conexion de datos en Bigquery.
  - Limpieza de datos y outliers en Google Colab. 
  - Union de tablas, creacion de nuevas variables y generacion de tablas auxiliares.
  - Generacion de tablas dinamicas y graficas para el analisis exploratorio.
  - Analisis Exploratorio de datos en Looker Studio:
    - Generacion de graficos basicos y avanzados.
    - Medidas de tendencia central.
    - Generacion de Histograma.
    - Boxplots.
    - Pivot Tables.      
  - Segmentacion de cuartiles y categorizacion.
  - Calculo del Riesgo Relativo.
  - Validacion de Hipotesis.
  - Creacion de dashboard en Looker Studio.
  - Creacion de presentacion que resuma de manera efectiva los resultados del análisis de datos.

## Instrucciones de uso:
En el archivo Presentacion_Resultados.pptx de powert point encontraras la presentacion de los resultados y recomendaciones.
En la carpeta de "dataset_banco" podras encontrar los datos originales del proyecto (antes de su analisis).
En la carpeta de "dataset_banco_mod" podras encontrar los datos finales del proyecto (despues de su analisis).
En el archivo analisys_book.ipynb podras encontrar el codigo de phyton utilizado en Google Colab.


## Proceso de trabajo.
Siguiendo una lógica de pasos en secuencia, en este proyecto se aplicaron las siguientes fases:
  - Procesar y preparar la limpieza de datos.
  - Hacer un analisis exploratorio.
  - Aplicar tecnica de analisis.
  - Validacion de Hipotesis.
  - Resumir informacion en un dashboard.
  - Presentacion de resultados con las partes interesadas.


## Base de Datos.
Se trabajo con una base de datos con 4 tablas :
  - default. Informacion de los clientes con varible flag que identifica a usuarios de impagos.
  - user_info. Informacion demografica de los usuarios.
  - loans_detail. Informacion de numeros de impago y porcentaje de deuda por cliente.
  - loans_outstanding. Informacion de la cantidad de creditos por cliente.
    
## Herramientas utilizadas.
  - BigQuery (SQL)
  - Microsoft Power Point.
  - Google Colab (Phyton).
  - Google Looker Studio.

    
 ## Imagenes de Resultados:
 ### Validacion de Hipotesis.
 ![](https://github.com/ter2016/Proyecto-4-Riesgo-Relativo/blob/main/imgs/Hip1.jpg)
 ![](https://github.com/ter2016/Proyecto-4-Riesgo-Relativo/blob/main/imgs/Hip1_2.jpg)
 
 ### Dashboard general.
 ![](https://github.com/ter2016/Proyecto-4-Riesgo-Relativo/blob/main/imgs/D1.jpg)

 
## Archivos y Links de acceso
Externo: Dashboard Looker Studio  https://lookerstudio.google.com/u/0/reporting/6afd5b48-1a27-4e46-85f2-c0f7c21fa999/page/p_wh6db8qwdd

Repositorio: Querys.docx.docx  https://github.com/ter2016/Proyecto-4-Riesgo-Relativo/blob/main/Querys.docx

Repositorio: analisys_book.ipynb  https://github.com/ter2016/Proyecto-4-Riesgo-Relativo/blob/main/analisys_book.ipynb

Repositorio: Presentacion_Resultados.pptx  https://github.com/ter2016/Proyecto-4-Riesgo-Relativo/blob/main/Presentacion_Resultados.pptx

