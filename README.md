# sentiment-analysis-of-movie-reviews

For this project, we want to classify sentiment values of movie reviews. This  is a multiclass clasification because the sentiment consist of 5 different values. To perform this classification, we need to preprocess the data by:
1. Cleaning data 
2. Upsampled sampling to balancing the data
3. One Hot Encoding
4. Tokenizing
5. Sequencing
6. Padding

Finally, after several preparation, the data is modeled by two deep learning model combination:
1. CNN - BiLSTM
2. CNN - LSTM

In conclusion, CNN - BiLSTM performs better with higher validation accuracy 86.416% than CNN -LSTM with accuracy 86.17%
