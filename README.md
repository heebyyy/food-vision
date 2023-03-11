# food-vision
Tring to beat the DeepFood, a 2016 paper which used a Convolutional Neural Network trained for 2-3 days to achieve 77.4% top-1 accuracy.

I used tensorflow and tranfer learning to train an efficientnetB0 to claasify the food into 101 claaes

I trained a feature extraction model for three epochs and got an accuracy of 72.80%

I then fine tuned the model unfreezing the last 20 layers and making them trainable, i reduced my learning rate (divided by 10), recompiled my model and fit  to my daa fo 3 epochs.

With this fine tuning, I got an accuracy of 75.79%

I leveraged the tesla t4 GPU n colab and this took me a couple of minutes 
