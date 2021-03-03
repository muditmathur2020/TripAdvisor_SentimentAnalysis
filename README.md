## WHERE TO EAT IN EUROPE?

### SENTIMENT ANALYSIS ON TRIPADVISOR RESTAURANTS INFO FOR 31 EUROPEAN CITIES.

### Dataset and Attribute information:
This dataset contains information scrapped from the TripAdvisor (TA) website about restaurants in 31 European cities. The cities listed are from different European countries: Amsterdam (NL), Athens (GR), Barcelona (ES), Berlin (DE), Bratislava (SK), Bruxelles (BE), Budapest (HU), Copenhagen (DK), Dublin (IE), Edinburgh (UK), Geneva (CH), Helsinki (FI), Hamburg (DE), Krakow (PL), Lisbon (PT), Ljubljana (SI), London (UK), Luxembourg (LU), Madrid (ES), Lyon (FR), Milan 
(IT), Munich (DE), Oporto (PT), Oslo (NO), Paris (FR), Prague (CZ), Rome (IT), Stockholm (SE), Vienna (AT), Warsaw (PL), and Zurich (CH).

There are 125527 restaurants listed in the dataset. The attributes with respect to each restaurant are:

1. Name: Name of the restaurant.
2. City: City location of the restaurant.
3. Cuisine Style: Cuisine style(s) of the restaurant, as a Python list.
4. Ranking: Rank of the restaurant among the total number of restaurants in the city, as a float object.
5. Rating: Rate of the restaurant on a scale of -1 to 5, as a categorical type.
6. Price Range: Price range of the restaurant among 3 categories, as a categorical type.
7. Number of Reviews: Number of reviews that customers have given to the restaurant, as a float object.
8. Reviews: Reviews given by the customers to the restaurant, as a list of list object where the first list contains the 2 reviews, and the  second, the dates when these reviews were written.
9. URL_TA: A part of the URL of the detailed restaurant page that comes after 'www.tripadvisor.com' as a string object. 
10. ID_TA: Identification of the restaurant in the TA database.

There are missing information about the restaurants in the dataset, as NAN.

### Sentiment Analysis:
Sentiment Analysis is a field of Natural Language Processing (NLP) that builds models that try to identify and classify attributes of the expression.

### Visualization:
Analysis of various features like price range, ratings and reviews to find out the best restaurants in different cities in Europe, which offer good food for its customers.  

### Install:
This project requires Python 3.6 and the following libraries for training:
* Numpy
* Pandas
* sklearn
* Natural language toolkit
* Keras

The following for visualization:
* Matplotlib
* Seaborn
* Plotly
* WordCloud

It also requires a software installed to run and execute the Jupyter Notebook.

### Output (desired traget):
Classifying the reviews into 6 different classes of rating, there by predicting the sentiment associated with it.
The ratings and the sentiments of the customers:
5 - Excellent
4 - Very Good
3 - Good
2 - Average
1 - Bad
0 - Terrible

### Model trained on:
The model is trained on Neural Network using Keras. The accuracy of the model using different algorithms is: 
1. Neural Nertwork (relu as the activation function and adam as the optimimzer):
    * Train data = 64.69% 
    * Test data = 62.34%

2. SVM:
	* Train data = 64.49%
	* Test data = 61.84%

3. Logistic Regression:
	* Train data = 64.51%
	* Test data = 61.42%	







