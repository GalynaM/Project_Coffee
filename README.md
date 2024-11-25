## Project_Coffee analyses the retail coffee industry's popularity in the United States

### Data Source 
* Yelp https://www.yelp.com/dataset
* Used Athena to upload JSON files from Yelp dataset to filter and clean the data and get CSV files to create SQLite DB

### Used
* AWS S3, Athena
* SQLite
* Python, libraries: pandas, numpy, flask, sqlite3
* HTML, CSS, JavaScript: D3, canvasJS, Chart.js
* JSON, SQL

### Investigation on how coffee shop business players can adapt to the existing niche
#### Evaluation of the popularity of coffee over years
![image](https://github.com/user-attachments/assets/192168a9-3556-442f-8541-e37c0ba76bb7)
* As we can see the popularity of coffee was pretty stable since year 2015, but it dropped in 2020 which can be explained by covid.
This assumption gives us a reason to assume that coffee is still popular.

#### Finding out Coffee Shops of which categories are in demand in different States
![image](https://github.com/user-attachments/assets/5cbf7b3e-4a1b-4641-84ad-b13c9e928379)
* Coffee&Tea shops turned out to be the most popular
![image](https://github.com/user-attachments/assets/a8fd1e2f-d502-4586-9607-b254a2b5ba32)
* Massachusets obviousely like Donuts)


#### The coverage of different features of Shops in different States
![image](https://github.com/user-attachments/assets/da53c9e0-1f2d-4c2e-a0df-09a6fbb7a9ad)
* The chart shows variation of features coverage among States from min to max for each attribute.
  ![image](https://github.com/user-attachments/assets/7303ab24-2365-4388-bf85-77fcfb4572d8)
* The visual for selected attribute - Texas covers 'DogAllowed' feature the most amongst available states.
