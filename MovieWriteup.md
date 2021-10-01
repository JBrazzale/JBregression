## Predicting Box Office Success With Linear Regression (Joseph Brazzale)


### Abstract




### Design
For this project, I wanted to extract the data for 1000 films and run a linear regression model on that data. I chose 
to scrape my data from Boxofficemojo.com because their data is well structured and is easily accessed because it is organized 
by year. I used Scrapy to scrape the data because it generates a file that outlines all of the necessary steps for a scrape. 
I then removed all of the columns that contained multiple NUll values using SQlite. The majority of my features from my movies 
were not in a format that will function well in a linear model. Using Pandas, I changed all of my string values to integers, 
and assigned "dummy variables" to my categorical data

### Data
My inital scrape returned the data for over 2300 movies. After removing all movies with multiple NUll values and all of the 
duplicate titles, I was left with 1100 movies. From these movies, I was able to select 19 independent features for modeling. 
After an initial examination in a pair plot, I discovered that a lot of these features will not work for modeling. This left 
me with 6 core features to test against my target value. 

### Algorithms



### Tools
- Scrapy for webscraping using Lxml to target specific HTML Xpaths from Boxofficemojo
- SQLite to remove Null values
- Python and its associated libraries(numpy,sklearn)
- Seaborn and Matplotlib for vizualization

### Communication
This project will be presented to the client using a powerpoint presentation. I will include a few relevant figures along 
with some vizualization of my data. 
