# Predicting a Player's Position using the FIFA 19 Dataset  ![](https://img.shields.io/badge/python-3.7+-pink.svg)

This is a binary classification project which uses various machine learning algorithms in an effort to predict one of two classes: 0 (offense), 1 (defense). 


The final report and presentation can be viewed in the `reports` folder.  


This project aims to predict a player’s position through skills-based attributes like sprint speed, field kick accuracy, and ball control all while exploring various machine learning algorithms that optimize our classification strategies. This is an important task because like any sport, it must be fluid in terms of changing with the times especially when you have players that are able to play multiple positions with the same output. This can have a drastic effect on how the game is played especially when we are able to introduce flex players that can play multiple positions.


The FIFA 19 Dataset can be found here: [FIFA 19 Dataset](https://www.kaggle.com/karangadiya/fifa19)


There are 17 unique positions in the dataset and they were strategically assigned to one of two classes:  (offense), 1 (defense), as mentioned above. To predict which positions fell in which class, 34 features, physical and skills-based, were extracted from the main dataset and preprocessed. 

  


Python version:   
Python 3.9.7
packaged by conda-forge Clang 11.1.0


Pageckage version:  
numpy==1.21.1  
pandas==1.3.1  
scikit-learn==0.24.2  
shap==0.39.0  
matplotlib==3.4.2  
xgboost==1.3.1   
