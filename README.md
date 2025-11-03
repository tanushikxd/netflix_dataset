This project explores how Netflix content has evolved over time and highlights key trends on the platform. I mainly used Pandas, Matplotlib, and Seaborn, with some SQL for validation and aggregation.


Dataset source: 

Publicly available on Kuggle.com


Project Overview

Compared the number of movies vs. TV shows available on Netflix

Analyzed how much content is added each year (with clear growth trends)

Identified the most common genres featured on the platform




Tools Used

I primarily worked in Python (Pandas) for data cleaning and organization.
The dataset was already in good shape, but I removed whitespace, fixed formatting issues, and structured the data by genre and runtime for easier analysis.



Visualizations

All dashboards and charts created with Matplotlib and Seaborn are available in the Visuals folder.

Python Notebook (Google Colab)



Key steps included:

Cleaning and preparing the dataset

Converting date fields into proper datetime format

Creating new features (category grouping, runtime segmentation)

Visualizing content distribution and trends over time

Notebook: analysis.ipynb



SQL Queries

Used sample SQL queries to cross-check and validate insights, including:

Counting movies vs. TV shows

Identifying countries with the most available content

Ranking the most common parental ratings

Listing the top-rated 15 titles (movies and TV shows)

How to Run This Project

Clone the repository:

git clone https://github.com/tanushikxd/netflix_dataset


Open the notebook in Jupyter or Google Colab and run the cells.



Conclusion

This project helped me better understand how Netflix’s content strategy has changed over time.
By cleaning and analyzing the dataset, I was able to see:

A clear rise in the amount of content added each year

A growing emphasis on TV shows compared to movies

Strong trends in genre popularity over time

It was a great hands-on experience working with real streaming-platform data.
In the future, I’d like to expand the analysis by incorporating IMDb ratings, performing sentiment analysis on show descriptions, and forecasting future content trends.