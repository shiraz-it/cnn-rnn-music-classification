# CNN RNN Music Classification 

This project using classic neural networks to classify music genres. We used data-sets of classified songs- pre-processing them first into mel-spectrograms, and used this representation of music as a pictures. We focused on different architectures of neural networks- CNN, RNN, and CRNN. After training over more than 6000 instances, we tested over validation and plotted the accuracy and loss. We examined the graphs and discussed insights.

In the first step, as we treat a spectrogram of a song as an image, we implemented different CNNs. Later on, as our data embodies a time dimension, we put a RNN into use. RNNs might be able to aid identifying the short and long term temporal features in the song. The last step was to combine the two into a CRNN attempting to take advantage of local feature extraction of CNNs with temporal summarization of a RNN. In all our models we used soft-max classifier. Also, we used L2 regularization to reduce over-fit.

This is the final project for Deep Learning course at IDC Herzeliya.

FMA (Free Music Archive)- a dataset for music analysis:

https://github.com/mdeff/fma

After pre-processing:

https://drive.google.com/drive/u/0/folders/1-PTQBiz6E53uUa9LebHjds_ZQesRHEqx

Deeper insights can be found at the included paper. Enjoy!
