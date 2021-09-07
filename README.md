# Weather-Forcasting-using-LSTMs-with-multiple-look-back-deviation-analysis

  Weather forecasting is a vital application in
present times. We can use the predictions to minimize the
weather related loss. Use of machine learning and deep
learning algorithms for forecasting, can eliminate or reduce
the necessity of big data and high computation dependent
process of parameterization. Long Short-Term Memory
(LSTM) is a widely used deep learning architecture for
time series forecasting. In this paper, we aim to predict
one day ahead average temperature using a 2-layer neural
network consisting of one layer of LSTM and one layer of
1D convolution. The input is pre-processed using a smoothing
technique and output is raw (un-smooth) next day
average temperature. The smoothing technique improves
the performance of LSTM substantially and meanwhile
1D convolution helps unsmooth the output of LSTM to
obtain the raw answers. All the models are for particular
locations only. The study shows significant improvement
in the forecasting with use of smoothing technique. Our
method outperforms other model in terms of MSE and
MAE.


Data set:
https://www.kaggle.com/juliansimon/weather_madrid_lemd_1997_2015.csv

![GitHub Logo](/Images/Capture.PNG)

![GitHub Logo](/Images/Capture_RF.PNG)

