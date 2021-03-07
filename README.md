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

Here we tried to implement Chunking, POS Tagging and NER(Named Entity Recognition) using RNN(Recurrent Neural netwrork) and Bi-lstm (Bi directional LSTM).

## Chunking:

**Chunking** is a process of extracting phrases from unstructured text, which means analyzing a sentence to identify the constituents(Noun Groups, Verbs, verb groups, etc.)

### Result : 
* Using RNN we got **98.37%** accuracy and using Bi-LSTM we got **98.62%** accuracy.

## POS Tagging:

POS Tagging is the process of classifying words into their part of speech and label their tags accrodingly is called **POS tagging**.

### Result:

* POS Tagging using RNN we got **99.26%** accuracy and using Bi-LSTM we get **99.37%** accuracy.

## NER

**Named Entity Recognition (NER)** is the process of identifying and categorizing named entities in a given text. Examples of categories are organizations, locations, time, names, money, and rate.

### Result : 

* Using RNN we got **99.54%** accuracy and using Bi-lstm we got **97.11%** accuracy.

## Conclusion: 

* In all three of the above, i.e. POS Tagging, Chunking, NER, we got very high accuracy using Bi-LSTM and RNN when compared with CRF++ implementation. 

Using CRF++, we got the accuracies as follows:

* **Chunking** : 94-96%

* **NER** : 84-85%

* **POS_Tagging** : 93-94% 

**Hence our present accuracies using RNN and biLSTM are much better than the obtained using CRF++ Tool.**
