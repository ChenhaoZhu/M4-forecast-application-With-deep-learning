# M4-forecast-application-on-machine-learning-and-time-series-models

This project includes one python code file,
for the python code files, it used some mathine learning techniques and deep learning algorithms to predict the future value of time series data.
The codes are originally provided by 'https://github.com/Mcompetitions/M4-methods', as machinelearning banchmark. 

It originally applied MLP and basic neural network such as RNN methods to predict time series data. We add some other methods like LSTM and Random forest. We do not make siginificant changes to original codes, we add our codes based on original framework to compare the performance of different algorithms for predicting time seires data. Through further learning, we added the idea of ensemble learning to combine LSTM, random forest, and lasso regression. This project somehow did not show the imporvement of ensemble learning compared to other single methods. 

It is an interesting finding that ensemble learning performs worse than single method. Our team discussed a lot and could not find a reason. In most time, the ensemble learning works better than any other method, but once an exception occurs, ensemble learning would perform an extremely high error. There may be some mistakes on the codes in ensemble learning part, with a misunderstanding of the application.
Hope anyone could point out the potential reasons. 

This project is also for learning mathine learning method(Partilly deep learning), ensemble learning for better prediction. We did not use every line of data, we used partial set of the original data to test each methods. The data we used could be downloaded by the link I mentioned previously.

