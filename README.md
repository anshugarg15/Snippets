# Lab Task-4: Part-of-Speech (POS) Tagging, Chunking and Named Entity Recognition (NER) using RNN and Bi-LSTM.

## The Lab-project consists of a main folder named as 
19074045-Megha-Agarwal which consists of three sub-folders –

   * **Chunking**
        * Chunking_RNN – 
            * Chunking_RNN.ipynb
            * Chunking_RNN_model.pb
        * Chunking_Bi-LSTM –
            * Chunking_Bi-LSTM.ipynb
            * Chunking_Bi-LSTM_model.pb

   * **NER** –
        * NER_RNN – 
            * NER_RNN.ipynb
            * NER_RNN_model.pb
        * NER_Bi-LSTM – 
            * NER_Bi-LSTM.ipynb
            * NER_Bi-LSTM_model.pb
            
   * **POS** – 
        * POS_RNN – 
            * POS_RNN.ipynb
            * POS_RNN_model.pb
        * POS_Bi-LSTM –
            * POS_Bi-LSTM.ipynb
            * POS_Bi-LSTM_model.pb
    
   * Google-Colab notebook (.ipynb) – It consists of the whole code which trains and test the data.
   * Model trained (.pb) – It consists of the model trained i.e., RNN or Bi-LSTM.

## RNN -

Recurrent neural network (RNN) is a neural network that is suitable for modeling sequential information. Although theoretically it is able to capture longdistance dependencies, in practice it suffers from the gradient vanishing/exploding problems. RNN recalls the past and its selections are motivated with the aid of what it has learned from the past.

A recurrent neural network appears very just like feedforward neural networks, except it also has connections pointing backwards.
At each time step t (additionally called a frame), the RNN’s gets the inputs x(t) in addition to its personal output from the preceding time step, y(t–1). In view that there is no previous output at the primary time step, it’s far usually set to 0.
    
### Advantages: 

* The principal advantage of RNN is that RNN can model a collection of records (i.e. time collection) so that each pattern can be assumed to be dependent on previous ones.

* Recurrent neural networks are even used with convolutional layers to extend the powerful pixel neighbourhood.

## Bi- LSTM -

Bidirectional recurrent neural networks(RNN) are really just putting two independent RNNs together. 

This structure allows the networks to have both backward and forward information about the sequence at every time step.

Using bidirectional will run our inputs in two ways, one from past to future and one from future to past and what differs this approach from unidirectional is that in the LSTM that runs backward, we preserve information from the future and using the two hidden states combined you are able in any point in time to preserve information from both past and future.
    
### Advantages:

* It solves the problem of fixed sequence to sequence prediction.


## POS Tagging:

Part-of-Speech (PoS) tagging, then it may be defined as the process of assigning one of the parts of speech to the given word. It is generally called POS tagging. In simple words, we can say that POS tagging is a task of labelling each word in a sentence with its appropriate part of speech. We already know that parts of speech include nouns, verb, adverbs, adjectives, pronouns, conjunction and their sub-categories.
    
Here, we have tried to implement it using RNN (Recurrent Neural netwrork) and Bi-lstm (Bi directional Lstm)

### Implementation

First, we import all necessary libraries and download conll2000 dataset:

* Step 1: Process the dataset and categorise the data into words (x) and tags(y) and splitted the data into training , testing , validation sets.

* Step 2: Implemented both the RNN and Bi-LSTM models using libraries and plotted their results and finally we visualized and compared individual models.

### Result:

POS tagging using RNN we get 99.26 accuracy and using Bi-lstm we get 99.37% accuracy.

## Chunking:

Chunking refers to the process of taking individual pieces of information and grouping them into larger units.

### Implementation

First, we import all necessary libraries and download conll2000 dataset:

* Step 1: Process the dataset and categorise the data into words (x) and tags(y) and splitted the data into training , testing , validation sets.

* Step 2: Implemented both the RNN and Bi-LSTM models using libraries and plotted their results and finally we visualized and compared individual models.

### Result:

Chunking, using RNN gave 98.37% accuracy and using Bi-lstm 98.62% accuracy.

## NER:

NER (Named Entity recognition) is a task of information extraction that seeks to locate and classify named enitties mentioned in unstructured texts into pre-defined categories such as name of a person, locations , quantities , measurments etc.

Here, we have tried to implement it using RNN (Recurrent Neural netwrork) and Bi-lstm (Bi directional Lstm).

### Implementation:

First, we import all necessary libraries and download conll2003 dataset:

* Step 1: Load the dataset and extract mappings required for neural network. Split dataset into test and train after padding.

* Step 2: Build the model architecture which will have 4 layers as embedding layer , Bidirectional Lstm, Lstm layer, Time distributed layer. Fit the model          visualise them and get summary and results of the model. 

### Result:

NER, using RNN got 99.54% accuracy and using Bi-lstm got 97.11% accuracy.

## Conclusion: 

 In all three of the above, i.e. POS Tagging, Chunking, NER, we got very high accuracy using Bi-LSTM and RNN when compared with CRF++ implementation. 

 Using CRF++, we got the accuracies as follows:

  - Chunking : 94-96%

  - NER : 73-84%

  - POS : 93-94% 

 Our present accuracies using Bi-LSTM and RNN are far better than the ones using CRF++.
