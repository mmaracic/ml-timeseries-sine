# README

## LSTM

Building LSTM deep learning model to predict sine curve.

Code is based on:  
https://towardsdatascience.com/pytorch-lstms-for-time-series-data-cd16190929d7/

Related blog explaining LSTM:  
https://colah.github.io/posts/2015-08-Understanding-LSTMs/

### Experiments

### 1 Experiment with sine wave length
* LBFGS optimizer
* When sine wave is 80 points long the test loss after 5 epochs is around 1e5 and the test curve (next 1000 points) looks like a sine.
* When sine wave is 160 points long the test loss after 5 epochs is around 1e3 and the test curve (next 1000 points) does not look like a sine, more like a flat line.
* Seems in line with LSTM having problem with sequences over 100 points


