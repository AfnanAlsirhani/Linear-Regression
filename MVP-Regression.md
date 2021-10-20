# IMDb Regression

**Goal of the project**
The core objective of this project is to predict the revenue for each movie through the actor score.




## pre-work

1.  Web Scrapping two website IMDB Website and Numbers website.
2.  Dropped all duplicated rows and unneeded columns.
3.  Removed nulls.
4.  Converting object-type columns into numeric.


> we scraped data from two websites: IMDB Website and Numbers website. Rows were created for 10,000 movies represented in IMDB Website, the columns represented: movie title, genres, IMDB Rating, Budget, Actors, Runtime, and MPAA Rating. As for the data obtained from Numbers website, they were regarding the top 500 most paid actors. After that, we created a column to calculate the number of top 500 actors participating in each movie. 


The number of columns and rows before cleaning were **51 and 10,000** After cleaning up the data the number of columns and rows are **24 and 1500**


![heatmapforIMDB%20%281%29.png](attachment:heatmapforIMDB%20%281%29.png)



The correlation between all numeric columns was calculated. As shown in the heatmap graph there are a lot of columns that are highly correlated with another for example Budget and Worldwide Gross.




![image.png](attachment:image.png)

you can notice in the above graph athe high correlation  between budget with gross, the adventures movies had the highest budget.


## Future work:
building a **Linear Regression Model** to predict the revenues.
