
# 🎧 Proyecto MusicStream 

## Descripción General

Stream Music es un proyecto de análisis de datos musicales cuyo objetivo es extraer información proveniente la APIs Spotify y Last.fm para explorar el comportamiento de los oyentes, tendencias de géneros musicales, artistas y canciones entre 2020 y 2022. 
Este proyecto se divide en cuatro fases principales: extracción de datos, modelado de base de datos, análisis mediante SQL y visualización de resultados.

---

## Fase 1: Extracción de Datos

En esta fase se lleva a cabo la recopilación de información desde fuentes externas:

- API de Spotify: Se extrae información relevante sobre artistas, canciones, géneros musicales, tipo (canción o álbum), nombre de la canción, año de lanzamiento, etc.

- API de Last.fm: Se obtiene información complementaria como biografías de artistas, popularidad y estadisticas de reproducción, artistas similares, etc.

- Almacenamiento: Los datos recopilados son procesados y almacenados en archivos CSV estructurados, que servirán como fuente para la posterior carga en la base de datos.

---

## Fase 2: Modelado de Base de Datos

Esta fase comprende la modelización y carga de los datos:

- Diseño del modelo relacional: Se definen las entidades principales (artistas, canciones, géneros, años, etc.) y sus relaciones.

- Creación de la base de datos: Implementación del modelo de manera automatico en lenguaje Python.

- Carga de datos: Inserción de los datos provenientes de los archivos CSV en las tablas correspondientes usando Python.

---

## Fase 3: Análisis de Datos (Consultas SQL)

El objetivo de esta fase fue extraer conocimiento útil a partir de los datos almacenados. Se desarrollaron diversas consultas para responder preguntas generales y específicas del comportamiento musical:

### Ejemplos de consultas:

¿Cuál es el artista más popular y a qué género pertenece?
![Texto alternativo](resources/query2.png)

¿Cuántas canciones y artistas tenemos en nuestra BBDD? 
![Texto alternativo](resources/query1.png)

---

## Fase 4: Presentación Visual (Demo)

La última fase consistió en una presentación visual de los resultados obtenidos, creada en unas diapositivas, donde se resumen los hallazgos más relevantes mediante un diagrama, tablas y visualizaciones de imagenes que facilitan la comprensión del análisis realizado.

---

## Tecnologías Utilizadas


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) 

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Spotify](https://img.shields.io/badge/Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white) ![Last.fm](https://img.shields.io/badge/last.fm-D51007?style=for-the-badge&logo=last.fm&logoColor=white)  ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)

---

## Instrucciones de uso

1. Clona el repositorio
2. Ejecuta el archivo principal: `proyect_cozymusic.ipynb`
3. Sigue las instrucciones en el archivo para la extracción de datos, creación de los archivos CSV, para la creacióon de la BBDD y realizar las consultas a MySQL.
4. Crea nuevas consultas para conocer más sobre las canciones y artistas de la BBDD.

---

## Estructura del repositorio
```
da-project-promo-54-modulo-2-team-2/

├── README.md
│ 
├── data/
│   ├── artist_data.csv
│   ├── artist.csv
│   ├── similar_artist_data.csv
│   └── songs.csv
│ 
├── notebooks/
│   └── project_cozymusic.ipynb
│ 
├── resources/
│   ├── cozy_diagram_v.PNG
│   ├── cozy_diagram.PNG
│   ├── query1.PNG
│   └── query2.PNG
```

---

## Autoras

[Andreina Teixeira](https://github.com/AndreinaTeixeira)

[Marta Morell ](https://github.com/martamorell)

[Mar Pastor](https://github.com/MarPastor)

[Julia Becaria Coquet](https://github.com/juliabeco)

[Estefanía Moreno Delmo](https://github.com/fany_data)

---

## Estado del proyecto

    Version beta finalizada
---

## Capturas de pantalla

- Diagrama

![Texto alternativo](resources/cozy_diagram.PNG)
---