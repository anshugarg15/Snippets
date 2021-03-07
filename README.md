# CSE-241: AI Course Spring 2021 Assignment and Lab Task Submission

## Layout of The Task:

* It contains a root folder named - **19075011-Anshu-Garg** which contains 4 subfolders and readme file -
    * Chunking
        * RNN
            * Chunking_RNN.ipynb
            * Chunking_RNN.pb
        * bi-LSTM
            * Chunking_BiLSTM.ipynb
            * Chunking_biLSTM.pb
    * NER
        * RNN
            * NER_RNN.ipynb
            * NER_RNN.pb
        * bi-LSTM
            * NER_BiLSTM.ipynb
            * NER_biLSTM.pb
        * ner_dataset_final.csv
    * POS-Tagging
        * RNN
            * POS_RNN.ipynb
            * POS_RNN.pb
        * bi-LSTM
            * POS_bi-LSTM.pb
            * POS_biLSTM.ipynb

Here, we tried to implement Chunking, POS Tagging and NER(Named Entity Recognition) using **RNN**(Recurrent Neural netwrork) and **Bi-LSTM** (Bi-directional LSTM).

## RNN:

* Recurrent neural networks (RNN) are a class of neural networks that are helpful in modeling sequence data. Derived from feedforward networks, RNNs exhibit similar behavior to how human brains function. Recurrent neural networks produce predictive results in sequential data that other algorithms can't.

### Advantages 

* The principal advantage of RNN is that RNN can model a collection of records (i.e. time collection) so that each pattern can be assumed to be dependent on previous ones.

* Recurrent neural networks are even used with convolutional layers to extend the powerful pixel neighbourhood.

## Bi-LSTM:

* Bidirectional recurrent neural networks(RNN) are just putting two independent RNNs together. This structure allows the networks to have both backward and forward information about the sequence at every time step. A bidirectional LSTM (BiLSTM) layer learns bidirectional long-term dependencies between time steps of time series or sequence data. These dependencies can be useful when you want the network to learn from the complete time series at each time step.

### Advantages

* It solves the problem of fixed sequence to sequence prediction.

## Chunking:

**Chunking** is a process of extracting phrases from unstructured text, which means analyzing a sentence to identify the constituents(Noun Groups, Verbs, verb groups, etc.)

### Implementation : 

* First we splitted the whole dataset into training, testing and validation sets.

* Then we implemented the RNN and biLSTM models using python inbuilt libraries and then plotted the models to visualize and compare the results.

### Result : 
* Using RNN we got **98.37%** accuracy and using Bi-LSTM we got **98.62%** accuracy.

## POS Tagging:

POS Tagging is the process of classifying words into their part of speech and label their tags accrodingly is called **POS tagging**.

### Implementation : 

* First we splitted the whole dataset into training, testing and validation sets.

* Then we implemented the RNN and biLSTM models using python inbuilt libraries and then plotted the models to visualize and compare the results.

### Result:

* POS Tagging using RNN we got **99.26%** accuracy and using Bi-LSTM we get **99.37%** accuracy.

## NER

**Named Entity Recognition (NER)** is the process of identifying and categorizing named entities in a given text. Examples of categories are organizations, locations, time, names, money, and rate.

### Implementation : 

* First we splitted the whole dataset into training, testing and validation sets.

* Then we implemented the RNN and biLSTM models using python inbuilt libraries and then plotted the models to visualize and compare the results.

### Result : 

* Using RNN we got **99.54%** accuracy and using Bi-lstm we got **97.11%** accuracy.

## Conclusion: 

* In all three of the above, i.e. POS Tagging, Chunking, NER, we got very high accuracy using Bi-LSTM and RNN when compared with CRF++ implementation. 

Using CRF++, we got the accuracies as follows:

* **Chunking** : 94-96%

* **NER** : 84-85%

* **POS_Tagging** : 93-94% 

**Hence our present accuracies using RNN and biLSTM are much better than those obtained using CRF++ Tool.**
