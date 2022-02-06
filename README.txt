Introduction:
This project implementes a range of ML classification technques on socioeconomic data with the aim of predicting binary income category of the respondends (income >50k or <50k). 
The range of ML classification techniques include KNN, Decision Trees, Adaboost, Support Vector Classifier & Feed-Forward Neural Netowrk. 
Due to class imbalances, performance is evaluated on the basis of F1 score. Performance is also analysed with respect to bias/variance trade-off. 

Data:
The data is sourced from the 1994  US Annual census, available: 
The data is downloaded in two files, namely, training and testing set. 
It includes 48,842 observations, a total of 14 categorical and continuous features

To run:
1. Install the libraries detail below. 
2. Run 'Main.ipynb' to observe the processed data & tuned models. 
	Data pre-processing is contained in 'Data ipynb'
	Model Tuning is contained in the respective 'Model {}' files. 

Technical Requirements:
python ==3.6
numpy==1.18.5
pandas==1.1.5
sklearn==0.24.2
seaborn==0.11.1
matplotlib==3.2.1
imblearn==0.8.0