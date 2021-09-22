# Linear Regression Proposal
## Joseph Brazzale (9/22/21)

### Question
- By taking a look at over 1000 historical film releases, can we predict how successful a film will be before it is released?
  I will be measuring a film's success by how much revenue it generates. I will also find which parameters will best predict
  a movie's success. 
- This project will be geared towards a movie studio. It will allow them to determine which projects to invest in.

### Data
- I am planning on obtaining two data sets for this project. All of my data on revenue from films will come from Boxofficemojo.
  All other film details (release date, genre, country) will come from IMDB. 
- All data will be obtained via a webscrape, I will use Beautifulsoup to parse the data into a dataframe.
- Each individual film will serve as our unit of analysis, I will be examining at least 1000 movies. The film budget and box office 
  revenue will be our most important features. 

### Tools 
- I plan to use BeautifulSoup alongside of Python to scrape the data from the websites.
- I will then use Python and a few of its libraries like scikit-learn and Pandas to analyze the data.
- Any visualizations will be made using Seaborn. 

### MVP 
- My minimum viable product will consist of a cleaned dataframe of at least 1000 films. I also plan on having a scatter plot that 
  illustrates which parameters have the strongest correlation with success. 
