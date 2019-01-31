This project: "ProjectPython" is about analyzing the data of top ranked Universities in the World.
The project uses data retrieved from Kaggle.com as a CSV file.

Data to be analyzed/Questions to be answered:
  1. Top 100 Universities by Country
    - By analyzing data/graph it was found that the few large countries like China even though doing well economically need to improve in Education
    - By analyzing data/graph it can be concluded that a small Country like Israel is doing exceptionally well in Education
  2. I wanted to see the top 10 Universities and their national rank in the World  

Pandas data frame was used to read the CSV file. And SQLite3 was used to create a Database. The file read by Pandas data frame was inserted into SQLite3 database so that SQL queries could be run against the database to narrow down search results. The results from SQL queries were used to create bar graphs using Matplotlib.

This project, from the Jupyter Notebook, uses matplotlib to visualize the data as follows:

  1. a graph to plot the top 10 Universities in the World
  2. a graph to plot which Country has the top most Universities

I have used the following tools and frameworks with this project
  - Anaconda
  - Jupyter Notebook
  - SQLite3
  - Pandas
  - Matplotlib.pyplot
