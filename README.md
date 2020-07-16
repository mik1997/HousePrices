# Housing Prices Prediction - Kaggle natjecanje

link na natjecanje: [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

Pri učenju su korišteni podaci iz `new_train.csv`, a za submisiju podaci iz `new_test.csv`. Način na koji se dobe ti podaci opisan je u bilježnici `HousePricesPrediction.ipynb`. Tokom učenja je korišten GPU kako bi se ubrzao proces učenja pa kod moguće reprodukcije rezultata treba uključiti GPU na Kaggle serveru.

Glavna bilježnica je `HousePricesPrediction.ipynb`, te još postoji bilježnica `GridSearchCV.ipynb` gdje su dobiveni najbolji parametri za pojedini model.

Glavni modeli koji su se koristili:
* **XGBoostRegressor**
* **LightGBMRegressor**
* **SVR**
* **ElasticNet**
* Ansambli gornjih modela

Najbolji rezultat koji je dobiven na Kaggle submissionu: 0.12435 (**LightGBMRegressor**)


