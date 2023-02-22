# cyberbullying_twitter By Sameer Mankotia

This app predicts the nature of the tweet into 6 Categories.

* Age
* Ethnicity
* Gender
* Religion
* Other Cyberbullying
* Not Cyberbullying

## Tools and Technologies  
**Machine Learning -Model:** Used linear Support Vector Machine to classify tweets.  
**Streamlit:** Used Streamlit to create simple webapp to make the model interactive.  

## Methods Used-:
* Downloaded the data from kaggle. [(data)](https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification)
* Performed some Exploratory Data Analysis to get the overview of data. [(initial_modelling.ipynb)](https://github.com/sameermankotia/Cyberbulling_twitter/blob/main/initial_modelling.ipynb)
*  Created a Word Cloud from the data.
*  Performed the necessary steps for textual analysis.
    * Removing Stopwords, puctuations, URLs, etc
    * Performed Stemming and Lemmatization.
* Automated the process of preprocessing by creating functions. Which would be helpful in predicting Custom Outputs.
* Created Illustrations for the webapp from [Canva](https://www.canva.com/).
* Deployed the webapp on streamlit.
