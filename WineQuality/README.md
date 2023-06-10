# Machine-Learning

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c0/Red_Wine_Glass.jpg/321px-Red_Wine_Glass.jpg" alt="alt text" width="320" height="180">

The aim of our project is to determine the factors affecting the quality of red wine and to obtain
tips for increasing the optimal quality. For this, I used the dataset in the csv file in the Red Wine
Quality header on the Kaggle website. Due to some privacy issues in the Data Set, only
physicochemical factors are considered as factors affecting the quality of red wine and estimates
have been made for this. In other words, there is no information about the grape type used, brand,
price, place of production, date. Focused on chemical properties only. The classification method
was used in the project to make a quality estimation. From the classification algorithms; Logistic
Regression, Decision Tree Classifier, Random Forest Classifier, K Neighbors Classifier and SVC
are used


There are 12 features in the dataset. One of them is quality, the others are factors that determine
quality. These factors are:

fixed acidity: Most acids involved with wine or fixed or nonvolatile.

volatile acidity: The amount of acetic acid in wine, which at too high of levels can lead to an
unpleasant, vinegar taste.

citric acid: found in small quantities, citric acid can add ‘freshness’ and flavor to wines.

residual sugar: The amount of sugar remaining after fermentation stops, it’s rare to find wines
with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet.

chlorides: The amount of salt in the wine.

free sulfur dioxide: The free form of SO2 exists in equilibrium between molecular SO2 (as a
dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine.

total sulfur dioxide: Amount of free and bound forms of S02; in low concentrations, SO2 is
mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident
in the nose and taste of wine.

density: The density of water is close to that of water depending on the percent alcohol and sugar
content.

pH: Describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic);
most wines are between 3-4 on the pH scale.

sulphates: A wine additive which can contribute to sulfur dioxide gas (S02) levels, which acts as
an antimicrobial and antioxidant.

alcohol: The percent alcohol content of the wine.



There are two separate preprocessing parts in our project. The first preprocessing part is the part
where the quality score variety is 6, and the classification algorithms and accuracy rates used
later are according to these 6 types.
The second preprocessing part belongs to the reduced quality score variety to 3 pieces. Reducing
the quality score variety from 6 to 3 also increased the accuracy of the classification algorithms.


Accuracy rates were measured by applying both standard scaler and minmax scaler to both types
of quality variations (ie, 6 and 3).
The purpose of using StandardScaler is to standardize and ensure that the features in the dataset
are at the same scale. This helps the model perform better
The purpose of using MinMaxScaler is to ensure that the features in the dataset are within a
certain range. This process removes the imbalance that occurs when the features in the dataset are
of different scales and helps the model perform better.