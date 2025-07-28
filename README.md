**1.Project Topic: Potential Crime Type Prediction**



In this project; by using past crime information, we're predicting potential crime type happening in a certain time series (e.g. 7 or 10 days)



**2.Datasets**



We have used 2 datasets for this project:



\- Vancouver Crime Dataset: https://www.kaggle.com/datasets/wosaku/crime-in-vancouver

\- Los Angeles Crime Dataset: https://www.kaggle.com/datasets/gauravkumar2525/crime-data-from-2020-2025



Datasets have been taken from Kaggle





**3.Files**



**Train\_LA.ipynb**



* Los Angeles Crime Dataset has been used
* Building Summary (Daily) has been made
* Time Series Optimization has been made (Which window size is the best to be chosen)
* Rare Label Filtering has been made (by Min-Max count, For RNN we looked num of classes)
* 5 Different Models have been used (For RNN we used LSTM)
* Outputs





**Train\_Van.ipynb**



* Vancouver Crime Dataset has been used
* Building Summary (Daily) has been made
* Time Series Optimization has been made(Which window size is the best to be chosen)
* Rare Label Filtering (by Percentile for Traditional MLs, For RNN we looked num of classes)
* 5 Different Models have been used (For RNN we used LSTM)
* Outputs



**Test\_LA.ipynb**



* Models (pkl files) have been used, saved in Train\_LA.ipynb
* Label Encoder and Scaler pkl files have also been used to apply encoding and scaling
* Model Evaluations by using pkl files of models (Accuracy vb)





**Test\_Van.ipynb**



* Models (pkl files) have been used, saved in Train\_Van.ipynb
* Label Encoder and Scaler pkl files have also been used to apply encoding and scaling
* Model Evaluations by using pkl files of models (Accuracy vb)





**Libraries**



* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* XGBoost (For XGBoost model)
* Torch (For Method_2)



**Platform and Language**



* Python and Jupyter Notebook











