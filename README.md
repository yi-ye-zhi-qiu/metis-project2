## The Liam-o-meter 🥭 ![Python version](https://img.shields.io/badge/python-%E2%89%A53.6-blue.svg?style=flat-square&logo=python&logoColor=white)

### Linear regression analysis of IMDb Movie Ratings as an interpretive model for audience score based on genre & distributor

![Metis logo](metis.png) Metis data-science bootcamp project 2, **Jan. 11-22 2021**

** [See the final product](http://34.212.100.77/liamometer) **


**Abstract:**  FlaskApp of movies rated using a k- (5-) fold cross-validation lasso multiple linear regression model of IMDb scores (n=2316) scraped off the web, where we chose to use two features: genre (Action, Adventure, etc.) and movie distributor (Disney, Paramount, Other defined as <=7 movies/year) to analyze for a 2016-2020 timeframe. This model is interpretive and the use case is: "I can see how well a movie did on IMDb, how does that rating compare to if I were to *only* care about a categorical subset of variables, if I were to only consider that it's a Disney Animation, for instance?"

- Want graphs & written analysis, not just a flimsy jupyter notebook? 🤔️ Check "download more stats" - there's a report there. Alternatively, see [Linear Regression of IMDb ratings pdf](Linear regression of IMDB ratings.pdf).

----

Contributors:
- Liam
- Liam's Dad (helped run code after I got IP-banned from RottenTomatoes)

----

Requirements to run locally:

The scrapy spider & data analysis:

- `Python 3.6` or greater
- `jupyter notebook`
- `Scrapy` `(pip3 install scrapy)`
- other modules: `pandas` `scikit-learn` `matplotlib` `seaborn` `numpy` `json` `regex` `fuzzywuzzy`
- ~8 hours of time start->finish
- Strong willingness to get IP-banned from RottenTomatoes (just for a few days)

The WebApp:

- The FlaskApp is running on Ubuntu on an AWS AmazonLightsail server.

*Note:* we do not focus here on or include the code for deployment of a FlaskApp onto AWS, let alone the html/css/javascript used to display the data. This is because the FlaskApp is a part of my personal portfolio, and including all of the code for that here seems tangential to the point at hand: web scraping and linear regression. If you are interested, to view the code used to create the app see [here](https://github.com/yi-ye-zhi-qiu/personalwebsite).

----

Project Map   

This project is split into data collection, exploratory data analysis (EDA), data cleaning,

### Data collection
