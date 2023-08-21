# Natural-Language-Processing-with-Disaster-Tweets
Twitter or X has become an important communication channel in times of emergency.

The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

However many tweets has metaphorical terms like 'sky was blaze', 'its fire!', and so on which are actually common expressions in languages. Due to this it may be difficult to identify tweets related to real emergency.

For this project, our goal is to try solving the above problem by providing a Machine Learning Model.

Dataset has been obtained from this kaggle competition: https://www.kaggle.com/competitions/nlp-getting-started/overview

Dataset contains more than 10,000 tweets which were hand classified. 7613 of the Tweets have been provided as Training dataset with labels and 3263 tweets are provided as Test Dataset with no label. Our goal is to create a Bidirectional RNN based on both LSTM and GRU and compare the result against the test data by providing submission to the Kaggle Competition which gives out the F1 score. 
