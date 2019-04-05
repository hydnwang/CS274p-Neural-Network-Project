# cs274p-Neural-Network-Project
Stock prediction has always been a trending financial topic, but the prediction performance varies depending on the techniques people used. In this project, we aim to apply neural network knowledge based on what we’ve learned in class to this problem. We focus on predicting the following index: 
- `Taiwan Semiconductor Manufacturing Company Limited (TSM)` 

with the help of dependent indices: 
- `iShares PHLX Semiconductor ETF (SOXX)` 
- `VanEck Vectors Semiconductor ETF (SMH)` 

As for our model, we decide to use `RNN` as our base architecture, and we implement it with `LSTM` and `GRU`, to further increase the performance on predicting our target. Finally, we introduce hyperparameter to our model for hidden unit optimization.


## Brach Description

-  `master`: code base (source: )
-  `develop`: branch after testing with `feature/weather_predict` and `feature/dep_oil_price`.
-  `feature/stock_predict`: integegrated 5 more stock indices
-  `feature/weather_predict`: project inspiration
-  `feature/dep_oil_price`: integrated stock ETF index: `QQQ` with weights by using daily oil prices: `Cushing_OK_WTI_Spot_Price_FOB.csv` (source: [https://github.com/datasets/oil-prices](https://github.com/datasets/oil-prices))


## Tool and Framework Versions

- **Python**: `3.6.8`
- **Numpy**: `1.15.4`
- **Pandas**: `0.24.1`
- **Tensorflow**: `1.12.0`
- **Keras**: `2.2.4`


## Contributors
* [**Hayden Wang**](https://github.com/hydnwang)
* [**Kuo-Wei Chiao**](https://github.com/kwchiao)
* [**Alex Chu**](https://github.com/alchucam)
* [**Pin-Ying Wu**](https://github.com/pinyingiriswu)
* [**Zoe Chao**](https://github.com/tzuyuc)

## References

- [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
- [How LSTM networks solve the problem of vanishing gradients](https://medium.com/datadriveninvestor/how-do-lstm-networks-solve-the-problem-of-vanishing-gradients-a6784971a577)
- [Understanding GRU Networks](https://towardsdatascience.com/understanding-gru-networks-2ef37df6c9be)
- [How Recurrent Neural Networks Work](https://towardsdatascience.com/learn-how-recurrent-neural-networks-work-84e975feaaf7)
- [Illustrated Guide to LSTM’s and GRU’s: A step by step explanation](https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21)
- [Tips for Training Recurrent Neural Networks](https://danijar.com/tips-for-training-recurrent-neural-networks/)
- [Time-Series Prediction (Hvass-Labs)](https://github.com/Hvass-Labs/TensorFlow-Tutorials/blob/master/23_Time-Series-Prediction.ipynb)
- [SHERPA: A Python Hyperparameter Optimization Library](https://github.com/sherpa-ai/sherpa)