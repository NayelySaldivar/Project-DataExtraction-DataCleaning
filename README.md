<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Project-DataExtraction-DataCleaning
*Nayely Saldivar*

*DAPT 2020, Ciudad de México, Noviembre 2020*

<a name="project-description"></a>

## Monitor de Fraudes Financieros - CONDUSEF
Con ayuda de Selenium, se recopiló la información de los reportes registrados en el Monitor de Fraudes.

Para delimitar la búsqueda y con mira en el proyecto final se buscó guardar solo los resultados según su fuente:

- 'face': para fraudes en Facebook
- 'redes': para los fraudes por medio de todas las redes sociales

Para la recopilación de información se creó un *WebScrapper* ([Web Scrapping](#Web_Scrapping))

Para la limpieza, manipulación y publicación del reporte se hizo un CleaningPipeline ([Data Cleaning Pipeline](#Data_Cleaning_Pipeline))

<a name="Web_Scrapping"></a>
## Web Scrapping
Función principal **Portal_Fraude_Scrapper** 

Funciones complementarias: *Collect_Path, Collect_Data y Create_DF*

<a name="Data_Cleaning_Pipeline"></a>
## Data Cleaning Pipeline
Función principal **Portal_Fraude_CleaningPipe**

Funciones complementarias: *ConcatDF, CleaningDF y FilteringDF*

<a name="Referencia"></a>
## Sitios web
Monitor de Fraudes Financieros:
https://phpapps.condusef.gob.mx/fraudes_financieros/monitor.php

Selenium with Python:
https://selenium-python.readthedocs.io/index.html
