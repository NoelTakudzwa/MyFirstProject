# MyFirstProject

Data Information :
fixed acidity: :most acids involved with wine or fixed or nonvolatile.
volatile acidity: the amount of acetic acid in wine.
citric acid: found in small quantities, citric acid can add 'freshness' and flavor to wines.
residual sugar: the amount of sugar remaining after fermentation stops.
chlorides: the amount of salt in the wine.
free sulfur dioxide: the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion.
total sulfur dioxide: amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine.
density: the density of wine is close to that of water depending on the percent alcohol and sugar content.
pH: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic).
sulphates: a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant.
alcohol: the percent alcohol content of the wine.
quality: output variable (based on sensory data, score between 0 and 10).



i used the the mothod of multiple linear regression at first, then after obtaining my model i was under the presumption that if i ufurther clean and analyse my data and use the most correlated features on a relative scale instead of all the features theat would make the model better but that was not it.

Most of the wines get a quality rating of five or six, while having good and bad wines seems more unlikely. Excellent wines >8 are absent.There was absence of strong correlation between features and quality.Citric_acid, alcohol and sulphates correlate most positivily while volatile_acidity correlates the most negative.

