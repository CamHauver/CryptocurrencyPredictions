# CryptocurrencyPredictions
#This project involves creating an unsupervised learning model to predict if cryptocurrencies are affected by 24hr or 7day price changes, utilizing Python, pandas, hvplot, and sklearn.

#Original code sources: Data Analytics course Module 19 Challenge files. Data Analytics course instructor, Andrew Hoang's, speed run Zoom recording for Module 19 Challenge.

#Code for the model can be found in Crypto_Clustering.ipynb

#Data source file is crypto_market_data.csv

#1) Data was prepared using the StandardScaler() mmodule from scikit-learn to normalize the data from the csv file
#2) The best k value was found using the elbow method on the scaled data
#3) Data was clustered using the KMeans method
#4) Clustering was then optimized using a Principal Component Analysis (PCA)
#5) The best k value was found using the elbow method on the PCA data
#6) PCA data was clustered using the KMeans method
#7) Results from both clustering methods was visualized and compared to determine the best approach