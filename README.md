# Time-series-Analysis-using-LSTM-RNN-and-GRU
## Time series Analysis using LSTM, RNN, and GRU with PyTorch

Here I am implementing some of the RNN structures, such as RNN, LSTM, and GRU to build an understanding of deep learning models for time-series forecasting. I have worked on some of the feature engineering techniques that are widely applied in time-series forecasting, such as one-hot encoding, lagging, and cyclical time features. The libraries used are Scikit-learn, Pandas, and PyTorch, an open-source machine learning library. I have followed this great article you can find more details over here [link](https://towardsdatascience.com/building-rnn-lstm-and-gru-for-time-series-using-pytorch-a46e5b094e7b). It will give you extensive detail about this.
Time Series Dataset I am using is from [PJM’s Hourly Energy Consumption data](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption), a univariate time-series dataset of 10+ years of hourly observations collected from different US regions. From all files, I am working with the PJM East region data, which originally has the hourly energy consumption data from 2001 to 2018, but you can use any dataset.

### Data Distribution:
![DataGraph](https://user-images.githubusercontent.com/32578887/183041408-699c45de-3230-46f0-abfd-e652c9a0fb22.PNG)

### RNN Results:

![RNN](https://user-images.githubusercontent.com/32578887/183041504-ba90ca6c-85d6-4b38-be64-0fa84a17cc29.PNG)

### LSTM Results:

![LSTM](https://user-images.githubusercontent.com/32578887/183041462-be429e25-8160-4893-a086-004e44d1f523.PNG)

### GRU Results:

![GRU](https://user-images.githubusercontent.com/32578887/183041489-3ddfc7c9-f610-4cd0-b22e-66ddbdaa6aeb.PNG)



