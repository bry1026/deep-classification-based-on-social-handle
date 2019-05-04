# deep-name-gender
This recurrent neural network classifies a given first name as either male or female. 

This model will use a 2-layer LSTM model with a dense-activation layer and dropout regularization. This decision was through multiple trials with 1-3 layer LSTM models using various dropout rates and batch sizing. 

The configuration of batch_size = 32 was found to be the most efficient while being as accurate as possible. The model converges in less than 6 epochs and is able to achieve 89% accuracy.
