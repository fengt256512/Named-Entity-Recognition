# Named-Entity-Recognition


The code is mainly divided into four parts, including data preprocessing, Input embedding, NER model establishment and comparative evaluation.

In the preprocessing stage, it is mainly to remove the text that does not conform to the format.

Four methods are used in the input embedding stage, including POS, Parse tree, Word2Vec and Bert.

Two models are established, a basic BIi-LSTM model and different attention mechanism added to the basic model.
 
![image](https://user-images.githubusercontent.com/93305654/158726896-46483ffb-1cf9-4740-90a7-27606e79a251.png)

                                       Figure 1: Bi-LSTM CRF model with the attention



In the evaluation, the accuracy rates under different input embedding and different attention mechanisms were compared respectively.
