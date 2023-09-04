# Fine-Tuning-and-Accuracy-Improvement-for-LSTM-model-to-predict-the-stock-price
Built an LSTM model in Python to predict stock prices for major companies including GOOG, GOOGL, JNJ, and BRK.B based on trend, momentum, volume, and volatility factors; 
fine-tuned hyperparameters such as epochs, time steps, and neurons per layer with Bayesian optimization techniques; achieved 92% out-of-sample accuracy 

Algorithm: Currently there are 3 algorithms (LSTM, CNN, BiLSTM), and we use LSTM as the default model to train and predict stock price.

Training data size: The default is 2000 previous data points, that is, stock prices in previous 2000 trading days. 

