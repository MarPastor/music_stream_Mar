
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

---

## Phase 4: Visual Presentation (Demo)

The final phase consisted of a visual presentation of the results obtained, created in slides, where the most relevant findings are summarized through a diagram, tables, and image visualizations that facilitate understanding of the analysis performed

---

## Technologies Used


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) 

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Spotify](https://img.shields.io/badge/Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white) ![Last.fm](https://img.shields.io/badge/last.fm-D51007?style=for-the-badge&logo=last.fm&logoColor=white)  ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)

---

## Instructions for use

1. Clone the repository
2. Run the main file: `project_cozymusic.ipynb`
3. Follow the instructions in the file to extract data, create CSV files, create the database, and perform MySQL queries
4. Create new queries to learn more about the songs and artists in the database

---

## Repository structure

```
music_stream_Mar

├── README.md
├── 01_notebooks/
│   └── project_cozymusic.ipynb
├── 02_resources/
│   ├── cozy_diagram_v.PNG
│   ├── cozy_diagram.PNG
│   ├── db_cozy_musical.sql
│   ├── query1.PNG
│   └── query2.PNG
└── 03_data/
    ├── artist_data.csv
    ├── artist.csv
    ├── similar_artist_data.csv
    └── songs.csv

```

---

## Authors

[Andreina Teixeira](https://github.com/AndreinaTeixeira)

[Marta Morell ](https://github.com/martamorell)

[Mar Pastor](https://github.com/MarPastor)

[Julia Becaria Coquet](https://github.com/juliabeco)

[Estefanía Moreno Delmo](https://github.com/fany_data)

---

## Project status

Completed

---