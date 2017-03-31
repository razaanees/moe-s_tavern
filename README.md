# moe-s_tavern

This is a LSTM RNN trained on scenes from Moe's Tavern in the Simpson's TV show. Each sentence of the script is converted to integers and vectorized using an embedding layer in the neural network. The targets are set as the next word in the sentence in order to train the network to predict the word that should follow. After training the RNN, a sample script is generated to test the RNN out. At the moment, the sample script is non-sensical; however, it requires more data input and iteration in order to make useful sentences.

References:
Udacity Deep Learning Nanodegree
Udacity forums
stackoverflow
