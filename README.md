# NXU-BAN6420-Module-4-Assignment-Netlix-Data-Visualization

The Zipped folder named 'Module 4 - Data Visualization in R and Python for Data Analysis' contains 3 files;
- nextflix_data.zip - a zipped folder containing Netflix data showing details of Movies and TV shows from 1925 to 2020.
- Netflix Data Visualization (a Jupyter Notebook file) containing code for;
  - Data Preparation - Unzips a zip folder named 'netflix_data' and renames the file to 'Netflix_shows_movies.csv'.
  - Data Cleaning - Creates a Data Frame and Replaces and delete records with missing values in the Data Frame and checks for duplicates.
  - Data Exploration - Describe the data, display data information, and Statistical Analysis (Mode) to find;
      - The Director with the Highest Number of Movies/TV shows on NetFlix from 1925 - 2020
      - The Most Featured Actor on NetFlix from 1925 - 2020
      - The Year with the Most Movies/TV Shows released on NetFlix.
      - The Most watched Movies/TV Shows Genre on NetFlix between 1925 to 2020.
  - Data Visualization to display;
      - Top 10 Most watched genres
      - Movies/TV Shows Ratings distribution
- R Integration for Visualization - an R script that contains code for;
     - Imports the necessary packages and python libraries using the reticulate library.
     - loads the 'Netflix_shows_movies.csv' file.
     - Uses seaborn countplot() in R to visualize the Movies/TV Shows Ratings distribution.
