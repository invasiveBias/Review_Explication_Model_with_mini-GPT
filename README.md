# Review_Explication_Model_with_mini-GPT
Code to build a mini Generative Pretrained Transformer to explicate (give broader explanations) on online product reviews. The model is built by combining a positional embedding,with an encoder-type transformer and then feeds the output through a final linear layer.
The project is grouped into data analysis,pre-processing & model training & evaluation
The model was built with keras and notable sub-modules include Layers and Callbacks,Data analysis libraries include pandas, numpy,TextVectorization from keras.layers etc
The dataset used for the training and evaluation of the model contains 180,000 text data grouped into either psoitive,negative or neutral,each text in the data is mostly divided into a shortersummary of the reiview & then a longer and more detailed part that expands on the summary. After training the model is expected to only recieve the shorter summary & output the more detailed reviews.
The project was run on GPU powered google colab notebook.
