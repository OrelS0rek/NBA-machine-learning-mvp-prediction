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
![image](https://github.com/user-attachments/assets/2a609bce-ceee-472b-be7a-c81355a90e7d)
![image](https://github.com/user-attachments/assets/c0e76c2d-6e7d-4c9c-a9cd-f1f214c5e5b3)
![image](https://github.com/user-attachments/assets/ae60aa2f-be72-47eb-a26f-34a9953814ef)

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

![image](https://github.com/user-attachments/assets/ab321c87-dfdf-4af7-b4b6-610c39b519bb)

Random Forest Regression:

![image](https://github.com/user-attachments/assets/db2f4a7d-053e-4c3c-9cd3-b4aa658ea20e)

Decision Tree Regression:

![image](https://github.com/user-attachments/assets/d887b3d6-49c5-43ed-aebb-1abaa637cf37)


Linear Regression:

![image](https://github.com/user-attachments/assets/e819514a-4868-4bde-b672-ac1c23388d85)

K-Nearest-Neighbours:

![image](https://github.com/user-attachments/assets/6fd978bb-2886-4614-b937-66e4261d6468)

The Actual TOP 5 was:
1. Nikola Jokic
2. Shai Gilgeous Alexander
3. Luka Doncic
4. Giannis Antetokunmpo
5. Jalen Brunson

I feel like i made most objectives. with learning and getting comfortable with the libraries definitely boosting after the project. and also getting
comfortable with some machine learning concepts. while also getting pretty accurate results for the MVP prediction.

