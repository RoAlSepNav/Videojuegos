# Videojuegos 🎮

<img src="https://tecolotito.elsiglodetorreon.com.mx/i/2023/04/1676517.jpeg" width='100' height='10'>


## Tabla de contenidos

1. [Descripción del Proyecto](#descripción-del-proyecto-clipboard)
2. [Herramientas Utilizadas](#herramientas-utilizadas-wrench)
3. [Estructura del Proyecto](#estructura-del-proyecto-open_file_folder)
4. [Cómo usar este proyecto](#cómo-usar-este-proyecto-question)


### Descripción del Proyecto :clipboard:
Este proyecto se basa en la utilización de datos provenientes de la API de aves chilenas, la cual se encuentra disponible en https://aves.ninjas.cl/api/birds. Mediante un archivo Jupyter Notebook se extraen estos datos y se genera un archivo CSV para su posterior uso en Power BI. Con esta información, se desarrolla un buscador de aves chilenas que facilita su identificación y estudio.


### Herramientas Utilizadas :wrench:
- Python 3.9.17
- Biblioteca de acceso a API: Requests
- Biblioteca de manipulación de datos en formato CSV: CSV
- Herramienta de visualización de datos: Power BI
  
### Estructura del Proyecto :open_file_folder:
- aves.ipynb: Archivo Jupyter Notebook para consumir la API y generar el archivo CSV.
- info_aves.csv: Archivo CSV con los datos extraídos de la API.
- aves.pbix: Reporte de Power BI basado en los datos extraídos.
  

### Cómo usar este proyecto :question:
Para utilizar este proyecto, sigue estos pasos:
1. Asegúrate de tener instalado Python 3.9.17 en tu sistema.
2. Ejecuta el Jupyter Notebook `aves.ipynb` para consumir la API de aves chilenas y generar el archivo `info_aves.csv` con los datos extraídos. Puedes hacerlo mediante Jupyter Notebook abriendo el archivo `aves.ipynb` y ejecutando las celdas.
3. Una vez que se ha generado el archivo info_aves.csv, puedes utilizarlo en Power BI para crear visualizaciones y análisis. Abre el archivo aves.pbix con Power BI y carga el archivo CSV como fuente de datos.
4. Explora el reporte generado en Power BI para identificar y estudiar las aves chilenas utilizando las herramientas de visualización y análisis disponibles.

