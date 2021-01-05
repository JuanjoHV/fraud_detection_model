# Fraud Detection Model for Credit Card Transactions

The fraud in banking cards issue impacts in banks, sellers and customers alike. It is a competition between financial institutions and fraudsters: the former developing new practices and regulations in order to avoid fraudulent payments, for example, the two factor authentication (SCA) for payments introduced by EU's PDS2 that makes more difficult the fraudsters to size stolen card data, or real time transaction checking through machine learning models that detects the frauds, identifying the fraudulent payments patterns. The latter, looking for new ways to stole the customer's data everyday, and thinking up new patterns that dodge these real time controls.

We choose this project due to our interest in banking and the processes of prevention of fraud in payments, as well as other related subjects as anti money laundering and terrorism financing schemes. The train and test datasets found could satisfy our objetive in a two week, end of data science bootcamp project. They were a challenge too.  We evaluate applying the CRISP-DM methodology that we learn, using the phases that apply and leaving those that we could not due to the time we had. We expect to improve this work in our knowledge and practice in data science grows. We include a memory of this project (currently, only in Spanish, sorry).

Datasets that we have use comes from the Kaggle competition  IEEE-CIS Fraud Detection: https://www.kaggle.com/c/ieee-fraud-detection

The code is a series of Notebooks, that can be run in Kaggle. I am affraid that the size of the data is too much for our GitHub licence. You are also free to check our code through the following kaggle addresses:

[0. FRAUD_DETECTION: Memory Reduction - script](https://www.kaggle.com/sergiomananas/memory-reduction-script)  
[1. FRAUD_DETECTION: Memory Reduction](https://www.kaggle.com/juanjohernandez/1-fraud-detection-memory-reduction)  
[2.1 FRAUD_DETECTION: Customer Detection](https://www.kaggle.com/juanjohernandez/2-1-fraud-detection-customer-detection)  
[2.2 FRAUD_DETECTION: Columns Exploration](https://www.kaggle.com/sergiomananas/2-2-fraud-detection-columns-exploration)  
[3. FRAUD_DETECTION: Preprocessing](https://www.kaggle.com/juanjohernandez/3-fraud-detection-preprocessing)  
[4.1 FRAUD_DETECTION: Modelling with LightGBM](https://www.kaggle.com/sergiomananas/4-1-fraud-detection-modelling-with-lightgbm)  
[4.2 FRAUD_DETECTION: Modelling with XGBoost](https://www.kaggle.com/juanjohernandez/4-2-fraud-detection-modelling-with-xgboost)  
[5. FRAUD_DETECTION: Results](https://www.kaggle.com/sergiomananas/5-fraud-detection-results)

The project is structured in the following way:

### docs
Project memory and presentation in Spanish.

    Modelo_deteccion_fraude.pdf
    Modelo_deteccion_fraude_ppt.pdf

### notebooks
    1-fraud-detection-memory-reduction.ipynb
    2-1-fraud-detection-customer-detection.ipynb
    2-2-fraud-detection-columns-exploration.ipynb
    3-fraud-detection-preprocessing.ipynb
    4-1-fraud-detection-modelling-with-lightgbm.ipynb
    4-2-fraud-detection-modelling-with-xgboost.ipynb
    5-fraud-detection-results.ipynb


### scr
	1-fraud-detection-memory-reduction.py  
	2-1-fraud-detection-customer-detection.py  
	2-2-fraud-detection-columns-exploration.py  
	3-fraud-detection-preprocessing.py  
	4-1-fraud-detection-modelling-with-lightgbm.py  
	4-2-fraud-detection-modelling-with-xgboost.py  
	5-fraud-detection-results.py
  
	0-memory-reduction-script.py 
Code used to reduce csv memory, thanks to https://www.kaggle.com/alexeykupershtokh/safe-memory-reduction

### Authors
Sergio Mañanas López ( [GitHub](https://github.com/sergiomlop) | [LinkedIn](https://www.linkedin.com/in/sergiomananaslopez/) )  
Juan José Hernández Villar ( [GitHub](https://github.com/JuanjoHV) | [LinkedIn](https://www.linkedin.com/in/juan-jose-hernandez-villar-571a6a22/) )
