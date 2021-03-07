# CSE-241: AI Course Spring 2021 Assignment and Lab Task Submission

## Layout of The Task:

* It contains a root folder named - **19075011-Anshu-Garg** which contains 4 subfolders and readme file -
    * Chunking -   
        * RNN
            * Chunking_RNN.ipynb

## POS Tagging:

POS tagging is the process of classifying words into their part of speech and labelling them accrodingly is called POS tagging.
Here, we have tried to implement it using RNN (Recurrent Neural netwrork) and Bi-lstm (Bi directional Lstm)

### Procedure:

First, we import all necessary libraries and download conll2000 dataset:

* Step 1: Preprocess data and divide the data into words (x) and tags(y).

* Step 2: We vectorize X and Y using tokenizer function from keras library.

* Step 3: Make sure that each sequence of input and ouput are of same length.

* Step 4: Pad the sequence and then implement word embeddings and then do one hot encoding for output sequences(Y).

* Step 5: Split data into training , testing , validation sets.

* Step 6: Implement RNN model using libraries and fit the model.

* Step 7: Visualise using graphs and compile the model and get summary of model.

* Step 8: Just Implement the Bi Lstm model, fit the model to embeddings created , visualise , compile and get summary of Bi Lstm Model.

## Chunking:
Chunking refers to the process of taking individual pieces of information and grouping them into larger units.

### Procedure

First, we import all necessary libraries and download conll2000 dataset:

* Step 1: Preprocess data and divide the data into words (x) and tags(y)

* Step 2: We vectorize X and Y using tokenizer function from keras library

* Step 3: Make sure that each sequence of input and ouput are of same length

* Step 4: Pad the sequence and then implement word embeddings and then do one hot encoding for output sequences(Y)

* Step 5: Split data into training , testing , validation sets

* Step 6: Implement RNN model using libraries and fit the model

* Step 7: Visualise using graphs and compile the model and get summary of model.

* Step 8: Just Implement the Bi Lstm model, fit the model to embeddings created , visualise , compile and get summary of Bi Lstm Model.


## NER

NER (Named Entity recognition) is a task of information extraction that seeks to locate and classify named enitties mentioned in unstructured texts into pre-defined categories such as name of a person, locations , quantities , measurments etc.

Here, we have tried to implement it using RNN (Recurrent Neural netwrork) and Bi-lstm (Bi directional Lstm).

### Procedure:

First, we import all necessary libraries and download conll2003 dataset:

* Step 1: Load the dataset.

* Step 2: Extract mappings required for neural network.

* Step 3: Transform columns to extract sequential data.

* Step 4: Split the dataset into train and test after padding.

* Step 5: Build the model architecture which will have 4 layers as embedding layer , Bidirectional Lstm, Lstm layer, Time distributed layer.

* Step 6: Fit the model visualise them and get summary and results of the model.
