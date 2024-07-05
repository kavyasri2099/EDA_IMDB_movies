# EDA_IMDB_movies  

Project Overview:  
This project involves web scraping IMDb data to perform exploratory data analysis (EDA). The goal is to extract information about movies, analyze trends, and visualize the data using various techniques.  

Dataset:  
The dataset was scraped from IMDb and contains information about movies, including:  
- Title  
- Genre  
- Director  
- Cast  
- Rating  
- Number of Reviews  
- Release Year  

Requirements:  
The following Python libraries are required to run the code:  
numpy  
pandas  
matplotlib  
seaborn  
requests  
BeautifulSoup  
wordcloud  

Web Scraping: Data was scraped from IMDb using BeautifulSoup.  
Data Storage: The scraped data was stored in a CSV file for further analysis.  

*Data Preprocessing:  
Loading the Data: The dataset is loaded using pandas.  
Handling Missing Values: The dataset is checked for missing values and duplicates.  
Data Cleaning: The data is cleaned to remove any inconsistencies and ensure it is in a usable format.

*Exploratory Data Analysis (EDA):  
Descriptive Statistics: Summary statistics are computed for numerical columns.  
Visualizations: Various plots are created to visualize the data, including:  
Histograms  
Bar Charts  
Box Plots  
Word Cloud for genres  
Word Cloud Visualization  
A word cloud was created to visualize the most common genres in the dataset. The WordCloud library was used to generate the word cloud.  

*Files:  
imdb_data.csv: The dataset containing information about movies.  
imdb_webscraping_eda.ipynb: Jupyter Notebook containing the code for web scraping, data preprocessing, and EDA.  
imdb_eda_presentation.pptx: PowerPoint presentation summarizing the project.  

*Conclusion:  
This project demonstrates the process of web scraping data from IMDb, cleaning and preprocessing the data, and performing exploratory data analysis. The visualizations provide insights into the trends and distributions of movie genres, ratings, and other features.  

