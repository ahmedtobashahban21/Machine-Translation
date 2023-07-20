# Machine-Translation
- loading data from here ( https://www.kaggle.com/datasets/alincijov/bilingual-sentence-pairs )
# review 
- seq2seq model has wide variance application in NLP such as Machine Translation task
# let's talk about notebook 
- first you will load your dataset and split it into lines each line has a tow different languages
- so let's split data and store it in a list to do some operations
- clean data by 1.remove punctuation 2. do lower case
- in NLP task you need to transform you text into numerical data so you need first to tokenize it
- and encode it
# model 
- by tensorflow we using LSTM which is the update of RNN, it's resolved vanishing gradient problem so it's good to dealing with text.
- build model and save it by using checkpoint
- then load it in any time you want then make prediciton 
