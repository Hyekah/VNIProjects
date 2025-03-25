# VNIProjects
This study focuses on forecasting the volatility of Vietnam’s Stock Index (VN-Index) by comparing the
effectiveness of deep learning models—namely Deep Neural Networks (DNN) and Long Short-Term
Memory (LSTM)—with traditional econometric models such as ARMA-GARCH. The dataset comprises
daily closing prices of Vietnam’s Stock Index from 2000 to 2024, totaling 5,867 trading days. Two
approaches are employed to evaluate the deep learning models: one uses a distance-based loss function
(Mean Squared Error, MSE), and the other employs a likelihood-based loss function. The findings reveal
that LSTM with the likelihood-based loss function delivers the most accurate forecasts, achieving the
highest log-likelihood value on the test set (1663.98), outperforming all other models, including DNN
and ARMA-GARCH. Although DNN demonstrates strong performance, it still lags behind LSTM in
most cases. Meanwhile, the traditional ARMA-GARCH model exhibits significant weaknesses,
particularly in handling nonlinear and highly volatile data. Furthermore, the study illustrates the capacity
of deep learning models to forecast long-term volatility and their robustness when applied to various data
samples. Visual comparisons further affirm the superior predictive accuracy of LSTM over the other
approaches.
