<p align="center" width="300">
   <h3 align="center"> Project ETL</h3>
</p>
<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2019.01.37.png?raw=true>
</div>

   <h3 align="center"> Nicolás Villanova</h3>

</p>

## Project:
- In this project I must extract, clean and upload to a database that i will create.
- I am required to use two methods, such as BeautifulSoup or selenium, and three sources.
- As a bonus we are asked to make an analysis.
- We are allowed to choose freely the theme of the project.

## Electric Vehicles:
<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2019.02.37.png?raw=true>
</div>


### Cars population:

1. From kaggle I extract a dataset containing registered electric vehicles.
2. Erase duplicates and columns which i determine irrelevant for the study.
3. I clean the electric utility column by applying a function that normalises the unique values.
4.  Transforming the Electric vehicle type column to make it easier to understand.
5. Erasing special characters from location column
6. Creating new column latitude with coordinates.
7. Creating new column longitude with coordinates.

#### Analysis:




<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2017.15.44.png?raw=truee>
</div>
1. The amount of electric and plug-in hybrids
<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2017.15.58.png?raw=true>
</div>
2. Percentage of population per Make
<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2017.15.29.png?raw=true>
</div>
3. Amount of electric cars per Business


<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2017.16.36.png?raw=true>
  
</div>
4. Amount of electric cars per Make


<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2017.16.23.png?raw=true>
</div>
5. Amount of electric cars per model
<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2017.16.11.png?raw=true>
</div>
6. Amount of electric cars per year

### Cars Price:

1. Using beautiful soup I scrap data about electric cars and prices.
2. Place the data into a table format
3. Apply a function so that the models are divided into two columns: make and model.
4. Erase duplicates.

#### Analysis:

<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2017.24.58.png?raw=true>

  
</div>
1. Average price per Make.
<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2017.25.09.png?raw=true>
</div>
2. Lowest price per make.
<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2017.24.47.png?raw=true>
</div>
3. Highest price per make.
<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2017.24.37.png?raw=true>
</div>
4. Amount of electric models per make.

### Charging Stations:

1. Extract the data from data.gov.
2. Identifying NaN values.
3. Erasing and cleaning NaN columns.
4. Cleaning Access Days Time column by applying a function that returns either open 24 hours or not. 
5. Extracting coordinates from New Georeferenced Column.
6. Creating columns latitude and longitude.
7. Rename columns and change types.
8. Used folium to create a map with markers per station.

#### Map:

<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2017.03.25.png?raw=true>
</div>
Map with the location of the charging stations.

## DataBase:
- Using alchemy from python.
- Created Database 'EV_Cars'
- Created tables.
- Inserted the data previously extracted and transformed 

<div style="display: flex; justify-content: center;">
  <img width="478" alt="Principal" src=https://github.com/nicovilla23/Project_Music_ETL/blob/main/Images/Captura%20de%20Pantalla%202023-08-06%20a%20las%2018.38.35.png?raw=true>
</div>

