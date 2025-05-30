﻿# 🧘🏽 Shega Data Engineering Internship Assignment

This project is a solution to Shega's Data Engineering Intern assignment. It involves building a data pipeline to ingest, clean, transform, and analyze weather data using Python,Jupyter Notebook and Matplotlib for visualization.

---

## 📁 Folder Structure

```bash
shega-data-engineering/
├── data/
│ └── weather_data.csv # Data provided by Shega
├── outputs/
│ ├── cleaned_weather_data.csv # Cleaned and transformed data
│ └── top_5_.txt # Report of top 5 cities by average temperature in degree celcius 
├── visualizations/
│ └── avg_temp_bar_chart.png # Bar chart of average temperature per city
├── climate.ipynb # Main Notebook (python) 
└── README.md # Project documentation
```
.....🚣🏾     ....🚣🏾        🚣🏾       .🚣🏾       🚣🏾      ..🚣🏾     🚣🏾      🚣🏾     .....🚣🏾

## 🚀 How to Run the Pipeline Locally

### 1. Clone the Repository

```bash
git clone https://github.com/itsdagi/shega-data-engineering.git
cd shega-data-engineering 
```
For this particular project I recommend to use vertual environment and installation of pytohon verstion 3 or above

## Install Dependencies

This project uses python pandas and matplotlib.

In the root folder of the project install both using ur terminal 

```bash
pip install pandas
pip install matplotlib
pip install numpy # just incase 😊
```

This are for pip package manager if you prefer other package managers to install them please review their documentation to install them.

## Run the program 🏃🏾‍♂️‍➡️

This project is jupter Notebook first you should install and configure jupyter notebook to run this project locally 
```bash
pip install jupyterlab # this will do the job to setup jupyter notebook
```
after installation navigate to the project folder and in the climate.ipynb run each code cell by cell.
-------------------------------------------------------------------------------------------------------------------------

### My Approach

- I started by loading the weather data using Pandas into a variable named data which is a dataframe I created. I   cleaned the data by removing rows with missing dates and filled missing temperature values using the average temperature of each city(I used mean imputation) and stored this data in a defferent dataframe called imputed_data. Then I formatted the dates to a standard format and added a new column for temperature in Fahrenheit. I also filtered out rows with unknown or missing weather conditions. After that, I saved the cleaned data in to another data frame called 'cleaned_weather_data' and exported this to a csv file and created a simple text report showing the top 5 hottest cities. Finally, I added a bonus bar chart using Matplotlib there are 3 countries but who is counting.

🤺...          ....🤺
 ### The visualization
 ![ave_temp_bar_chart](https://github.com/user-attachments/assets/6c91102d-2f1b-4c6c-ae0c-1401f0a501a7)


Thanks 🫂
-

