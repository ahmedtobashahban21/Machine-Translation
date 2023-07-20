# Machine-Translation
- loading data from here ( https://www.kaggle.com/datasets/alincijov/bilingual-sentence-pairs )
# review 
- seq2seq model has wide variance applications in NLP such as Machine Translation task
# let's talk about the notebook 
- first you will load your dataset and split it into lines each line has a tow different languages
- so let's split data and store it in a list to do some operations
- clean data by 1. removing punctuation 2. doing lowercase
- in the NLP task you need to transfer your text into numerical data so you need first to tokenize it and encode it
# model 
- by TensorFlow, we use LSTM which is the update of RNN, it's resolved the vanishing gradient problem so it's good to deal with text.
- build a model and save it by using checkpoint
- then load it in any time you want then make predictions 
