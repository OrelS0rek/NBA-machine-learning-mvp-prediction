# NBA-machine-learning-mvp-prediction

**objective** 

correctly predict the top 5 finalists for the 2024 NBA season using machine learning algorithms.
get some experience with common machine learning algorithms and get comfortable with them and with common
machine learning libraries . like:
* numpy
* Grid Search
* sklearn
* matplot
* pandas
while also trying to see how the game i watch from the TV translates to statistics and Data. which a machine can learn from.
The most important objective was to get an introduction to machine learning. with this being my first introduction with machine
learning and my first model.


**Data Selection**

i scraped the data using 2 scraping resources: selenium and BeautifulSoup.
i scraped all of the data from the website BasketBall-Reference, the full Dataset is available at:
[https://www.kaggle.com/datasets/orelsorekml](https://www.kaggle.com/datasets/orelsorekml/nba-player-stats-including-mvp-share)

**Exploratory Data Analysis**



i used some features from the *pandas* library like '.describe()' or 'groupby' to analyze and explore the data.
i also used matplotlib to create some plots to learn about the data and visualize it and make some correlations 
between the features.
![image](https://github.com/user-attachments/assets/e804db4f-fca9-4927-a4f7-1b7bba51b9a5)
![image](https://github.com/user-attachments/assets/e5f50ea7-e243-4dcc-bd5d-e8d81bd1e947)
![image](https://github.com/user-attachments/assets/6e1678a2-8cad-4d0d-a9ac-f14e645c8082)

**model training and learning**


i used the 'scikit-learn' library to split the data, and create the models. i used 5 algorithms for the model:
* Support Vector Regression
* Random Forest Regression
* Decision Tree Regression
* Linear Regression
* K Nearest Neighbours
i have used some optimization techniques like Hyper Parameters tuning with Grid Search, Cross-Validation to
make sure the model is not underfitted/overfitted.
and some metrics to value the model like R-Squared and Mean-Squared-Error.


**Results**

while testing the model on the stats of the Season 2024, the model gave good predictions, with most
algorithms having an almost identical prediction to the official NBA MVP-race prediction.
the results are as such:

Support Vector Regression:

![image](https://github.com/user-attachments/assets/f324aaea-36b5-49dc-b6b5-09350c014f75)

Random Forest Regression:

![image](https://github.com/user-attachments/assets/d2ff24cc-bc1d-4cdd-be99-46fda21ad758)

Decision Tree Regression:

![image](https://github.com/user-attachments/assets/ac3d493e-db14-4a5a-ad7a-bb4e3610ba8f)


Linear Regression:

![image](https://github.com/user-attachments/assets/e88daf9c-34c1-4dd3-9d91-7e2c7b303641)

K-Nearest-Neighbours:

![image](https://github.com/user-attachments/assets/5bdc44b7-b2a4-433f-b101-424d2d8ed98b)

The Actual TOP 5 was:
1. Nikola Jokic
2. Shai Gilgeous Alexander
3. Luka Doncic
4. Giannis Antetokunmpo
5. Jalen Brunson

I feel like i made most objectives. with learning and getting comfortable with the libraries definitely boosting after the project. and also getting
comfortable with some machine learning concepts. while also getting pretty accurate results for the MVP prediction.

