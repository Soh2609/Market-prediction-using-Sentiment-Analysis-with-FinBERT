# Market-prediction-using-Sentiment-Analysis-with-FinBERT
Programming with torch is becoming fun day by day. And with that finetuning a LLM is becoming interesting too! I have fine tuned FinBERT LLM an opensource finance transformer model to give stock market prediction based on the news headlines or financial articles with the help of sentiment analysis on the text input.
# The model roughly works in following way 
1 -> Taking input from the user(any financial news headline or article)
2 -> Tokenizing the sentences and assinging the sentiments score/labels
3 -> Showing the output with confidence score
For Example
text=$SAP Q1 disappoints as #software licenses down. Real problem? #Cloud growth trails $MSFT $ORCL $GOOG $CRM"
output = Predicted Sentiment: Negative (Confidence: 0.98)


# As the finbert model size is around 400mbs+ I have shared google drive link to access the model for bulding more better predictive system or stock forecasting system.
link = https://drive.google.com/file/d/1uHbJexJ1xNMVarMWW0FQT4d78gFQlFmW/view?usp=drive_link

# The dataset i have used is also shared in the repo. 
#AS I WILL BE UPDATING THE MODEL FREQUENTLY WITH DIFFERENT LOSS FUNCTIONS AND TRAINING IT TO REDUCE TRAIN LOSS AND VAL LOSS (ps: cuurently it is trainloss=0.173400 and valloss=0.156230 which i think is huge number )SO WILL WORK ON TO PROVIDE BETTER RESULTS.

THANK YOU . STUDY HARD ,SCORE WELL , KEEP CODING.
