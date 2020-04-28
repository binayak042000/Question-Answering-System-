# Question-Answering-System-
Disclaimer : The model developed is not for any practical usage for any educational or commercial activities . The sole aim of this project was to explore the methods involved in creating question-answer systems as well as some of the aspects of Natural Language Processing . 

The dataset used here is a part of the SQUAD (Stanford Question Answer Dataset) . I have used Infersent , Facebook's sentence embedding model to convert sentences to 4096 dimensional vectors irrespective of the length of the sentence . 
NLP feature - dependency tree has benn explored in the notebook but not used in our final model .
The final model implements use of Random Forest , Gradient Boosting and Bidirectional LSTMs . 

Procedure : The magnitude of the 4096 dimensional vector of each sentence has been used . A separate dataframe created for context vectors where each cell contains the magnitude of vector representation of a sentence . Similar operation has been done to the questions too . The index of the sentence containing the final answer is chosen as the target output variable . In order to standardise the output variable , the index of the sentence has been divided by the number of sentences in the corresponding context .

Future Work : The model has a low accuracy thus leaving a lot of scope for improvement. I will come back to this after getting decent exposure to NLP and Deep Learning concepts .
