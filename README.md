# SC1015 Project - Movie Success Determination
***
Movie Success Determination Mini-Project for SC1015 - Introduction to Data Science and Artificial Intelligence

![](https://github.com/SC11-Grp3/SC1015-Movie-Success/blob/main/main.png)

## Introduction
***
This is a Mini-Project for NTU Course SC1015 (Introduction to Data Science and Artificial Intelligence) 2022. In this project, we will showcase if a movie's success can be determined by various factors. The dataset we will be using is [**The Movies Dataset**](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) from [Kaggle](https://www.kaggle.com/).

*'Success' definition - Generated revenue is higher than budget spent to produce the movie*

For a detailed walkthrough please view the source code in order **WARNING! CODE DOES NOT WORK SEPARATELY, THIS IS ONLY FOR DETAILING THE DIFFERENT SECTIONS**:
1. [Data Importation & Description](https://github.com/SC11-Grp3/SC1015-Movie-Success/blob/main/Data%20Importation%20%26%20Description.ipynb)
2. [Data Extraction & Cleaning](https://github.com/SC11-Grp3/SC1015-Movie-Success/blob/main/Data%20Extraction%20%26%20Cleaning.ipynb)
3. [Exploratory Data Analysis & Visualisation](https://github.com/SC11-Grp3/SC1015-Movie-Success/blob/main/Exploratory%20Data%20Analysis%20%26%20Visualisation.ipynb)
4. [Linear Regression](https://github.com/SC11-Grp3/SC1015-Movie-Success/blob/main/Linear%20Regression.ipynb)
5. [XGBoost](https://github.com/SC11-Grp3/SC1015-Movie-Success/blob/main/XGBoost.ipynb)
6. [Bonus(Recommendation System Based On Content)](https://github.com/SC11-Grp3/SC1015-Movie-Success/blob/main/Bonus(Recommendation%20System%20Based%20On%20Content).ipynb)

### OR

View the code as a whole:  
[Whole Code](https://github.com/SC11-Grp3/SC1015-Movie-Success/blob/main/Miniproject_Group3_SC1015.ipynb)

## Contributors
***
SC1015 SC11 Group 3:
1. @Justt-In
2. @tquean15012003
3. @dabluegem

## Problem Definition
***
1. Can a movie's success be determine by the following factors:
 1. Pre-Elements variables
 2. Post-Element variables
 3. Pre & Post Element Variables
2. Which model would be the best to predict?

## Models Used
***
1. Linear Regression
2. XGBoost Algorithm

## Conclusion
***
A movie's success cannot be determine solely on pre-production and post-production elements alone. But it is likely possible that it can be determined using a combination of both factors. Hence, a combination of both marketing and production resources are key to creating a vibrant and engaging movie.  

A successful movie can be made with little budget and lesser known cast and crew e.g. SAW(2004), Rocky(1976). Thus pre-production elements is not a strong indicator.  
<img src="https://media-cache.cinematerial.com/p/500x/g2qj7zv9/saw-movie-poster.jpg?v=1456231666" alt="drawing" width="200"/>
<img src="https://cdn.shopify.com/s/files/1/1416/8662/products/rocky_1976_40x60_original_film_art_48aa4697-ba9d-4404-a39f-284b94e0cecd_5000x.jpg?v=1633548517" alt="drawing" width="200"/>   

An unsuccessful movie can still happen even with high budget, popularity and well renowned cast, e.g. Transformers: The Last Knight(2017), The Mummy(2017)  
<img src="https://m.media-amazon.com/images/M/MV5BN2YwOWM4ODgtZTMzMi00ZmFmLTk5NTEtNmY4ZDcwNzQxNDhjXkEyXkFqcGdeQXVyNTI0NzAyNjY@._V1_.jpg" alt="drawing" width="200"/>
<img src="https://static.wikia.nocookie.net/dark-universe-universal-monsters/images/2/2f/The_Mummy_%282017%29_poster.jpg/revision/latest?cb=20171223070021" alt="drawing" width="200"/>  


## What did we learn from this project?
***
Data Extraction & Cleaning  
Data Visualisation  
Uni & Multi Variate Analysis  
Linear Regression Models  
XGBoost Algorithm  

## References
***
Brownlee, Jason. “How to Remove Outliers for Machine Learning.” Machine Learning Mastery, 18 Aug. 2020, machinelearningmastery.com/how-to-use-statistics-to-identify-outliers-in-data/.  

WillKoehrsen. “WillKoehrsen/Data-Analysis.” GitHub, github.com/WillKoehrsen/Data-Analysis/tree/master/random_forest_explained.  

Sangeetha, Jame. “Json Parsing & Linear Regression Analysis.” Kaggle, Kaggle, 28 Mar. 2018, www.kaggle.com/sanjames/json-parsing-linear-regression-analysis.  

F.koglu, et al. “How Can I Increase the Accuracy of My Linear Regression Model?(Machine Learning with Python).” Stack Overflow, 1 Sept. 1966, stackoverflow.com/questions/47577168/how-can-i-increase-the-accuracy-of-my-linear-regression-modelmachine-learning.  

“Sklearn.linear_model.RidgeCV¶.” Scikit, scikit-learn.org/stable/modules/generated/sklearn.linear_model.RidgeCV.html.  

“Sklearn.linear_model.RidgeCV¶.” Scikit, scikit-learn.org/stable/modules/generated/sklearn.linear_model.RidgeCV.html.  

“Sklearn.svm.LinearSVR¶.” Scikit, scikit-learn.org/stable/modules/generated/sklearn.svm.LinearSVR.html.  

Kushbhatnagar. “Movie Recommendation System.” Kaggle, Kaggle, 6 Apr. 2021, www.kaggle.com/kushbhatnagar/movie-recommendation-system.  

Burak Ergenc,"Predictions with XGboost and Linear Regression", https://www.kaggle.com/code/mburakergenc/predictions-with-xgboost-and-linear-regression/notebook  
