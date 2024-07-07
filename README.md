# Sentimental Analysis using Imdb
## Developed a Sentimental Analyzer using Recurrent Neural Network(RNN) with Imdb Dataset. 
### IMDB dataset having 50K movie reviews for natural language processing or Text analytics. This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. It provides a set of 25,000 highly polar movie reviews for training and 25,000 for testing.

![image](https://github.com/twishackaul/Sentimental-Analysis_Imdb/assets/107127632/a5bd8e3d-390d-4537-915f-6d8f0ba26cb4)

## How to use model:

- Importing libraries: Import necessary libraries such as:-
  * Numpy
  * imdb
  * pad_sequences
  * Sequential
  * Embedding
  * LSTM
  * Dense
  * Tokenizer
  * Dropout

- Loading Data: Then load the data using the already present imdb dataset in tensorflow. Use the syntax => imdb.load_data()

- Training the model: You can train the model using Recurrent Neural Network. Add the required loss and activation functions, performance metrics along with the optimizers. One can also apply an regularization technique to further optimize the model, such as using Drop Regularization, etc.

- Testing model: Test the model using unseen data and calculate the testing accuracy. Change the string data into integer form using Integer Encoding (if string data is used).

***A colab file showing Integer Encoding is also attached to show ho wto convert textual/string data into integer data for analysis***
***The reviews for testing the model were obtained from https://text2data.com/Demo website***


