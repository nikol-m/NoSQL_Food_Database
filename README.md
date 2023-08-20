# NoSQL_Food_Database

# Exploring a Food Database with MongoDB
#### Skills Used: NoSQL database, MongoDB, JSON, Pandas

## Overview
In this project, I engaged with a MongoDB database to extract insights about various establishments across the UK for a food magazine. My journey involved the following key steps:
- Initialized a MongoDB database by importing data from a JSON file using the `mongoimport` tool.
- Enriched the database by adding a new restaurant through the `insert_one` function.
- Performed data cleaning operations to enhance the quality of specific fields.
- Expunged irrelevant data entries to streamline the database's relevance to the magazine's objectives.

## Exploratory Analysis
With a refined database at my disposal, I embarked on addressing pertinent inquiries from the editorial team.

1. **Identifying Establishments with Hygiene Score of 20**
    - The investigation revealed that there are 41 establishments boasting a hygiene score of 20. Notable entities include "The Chase Rest Home" and "Seaford Pizza".

2. **London Establishments with Rating ≥ 4**
    - Among the establishments nestled within London, a total of 33 met the criteria of having a rating equal to or greater than 4. Noteworthy names encompass "Charlie's," "Benfleet Motor Yacht Club," and "Tilbury Seafarers Centre".

3. **Top 5 Establishments with Rating of 5, Proximate to New Restaurant**
    - The analysis showcased the foremost five establishments with a stellar rating of 5, situated in close proximity to the new restaurant:
        - Volunteer
        - Plumstead Manor Nursery
        - Iceland
        - TIWA N TIWA African Restaurant Ltd.
        - Howe and Co Fish and Chips - Van 17

4. **Count of Establishments with Hygiene Score 0 in Each Local Authority Area**
    - Delving into the dataset's Local Authority divisions, I discovered the top five areas with the highest count of establishments bearing a hygiene score of 0:
        - Thanet - 1130 establishments
        - Greenwich - 882 establishments
        - Maidstone - 713 establishments
        - Newham - 711 establishments
        - Swale - 686 establishments
