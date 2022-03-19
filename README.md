# Wine_Type_Classification
In this dataset, there are 6497 observations and in total 12 features. A Model has been trained to classify the type of Wine i.e. Red or White. The name and description of the 12 features are as follows:  

Fixed acidity: Amount of acidity in the wine 

Volatile acidity: Amount of acetic acid present in the wine 

Citric acid: Amount of citric acid present in the wine 

Residual sugar: Amount of sugar after fermentation 

Chlorides: Amount of salts present in the wine 

Free sulfur dioxide: Amount of free form of SO2 

Total sulfur dioxide: Amount of free and bound forms of S02 

Density: Density of the wine (mass/volume) 

pH: pH of the wine ranging from 0-14 

Sulphates: Amount of sulfur dioxide gas (S02) levels in the wine 

Alcohol: Amount of alcohol present in the wine 

Quality: Final quality of the wine mentioned

In order to handle imbalanced data, SMOTE has been used from imblearn library and then trained the Model using Random Forest Classifier which is giving an Accuracy of around 98%

Libraries Used: Pandas, Numpy, Matplotlib, Seaborn, Sklearn, imblearn
