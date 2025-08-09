
# 🎧 MusicStream Project

## General Description

Stream Music is a music data analytics project, extracting information from the Spotify and Last.fm APIs to explore listener behavior and trends in music genres, artists, and songs between 2020 and 2022

This project is divided into four main phases: data extraction, database modeling, SQL analysis, and results visualization

---

## Phase 1: Data Extraction

In this phase, information is collected from external sources:

- Spotify API: Relevant information is extracted about artists, songs, musical genres, type (song or album), song name, release year, etc.

- Last.fm API: Additional information is obtained such as artist biographies, popularity and streaming statistics, similar artists, etc.

- Storage: The collected data is processed and stored in structured CSV files, which will serve as a source for subsequent upload to the database

---

## Phase 2: Database Modeling

This phase includes data modeling and loading:

- Relational model design: The main entities (artists, songs, genres, years, etc.) and their relationships are defined

- Database creation: The model is automatically implemented in Python

- Data loading: Inserting data from the CSV files into the corresponding tables using Python

---

## Phase 3: Data Analysis (SQL Queries)

The objective of this phase was to extract useful knowledge from the stored data. Various queries were developed to answer general and specific questions about musical behavior:

### Examples of queries:

Who is the most popular artist and what genre does he belong to?
![Alternative text](02.%20resources/query2.png)

How many songs and artists do we have in our database?
![Alternative text](02.%20resources/query1.png)

---

## Phase 4: Visual Presentation (Demo)

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