# Stock Prices Prediction & Sentiment Analysis
The model was created to predict the changes in stock prices based on news, which were determined by two datasets. 
- Gathered polarity data (Subjectivity, Compound, Positive, Negative, Neutral) to predict stock prices. 
- Achieved 84% accuracy score using LDA

## Resources Used
**Programming language:** Python 3.7

**Packages:** pandas, numpy, vaderSentiment, textblob, scikit-learn, re

## Dataset
The datasets are from the Dow Jones Industrial dataset (2008-2016), containing daily news and stock prices. 

- Data points:-
  - Date (date/time) 
  - Label (boolean)
  - Top1, Top2....V25 (character)

## Exploratory Data Analysis
<img src="https://github.com/PannaD8ta/StockPrices_Prediction_Sentiment_Analysis/blob/main/lda_classification_report.png" alt="Confusion Matrix" width="300" height="150" />
