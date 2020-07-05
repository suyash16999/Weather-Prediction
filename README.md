# Weather Prediction System using LSTM

A simple weather monitoring and prediction system using Deep Learning(LSTM)

Several weather parameters like temperature,pressure,humidity,PM(Particulate Matter),etc can be collected by IOT sensors and single-board computer-Raspberry Pi 3B. This data is published over the web using MQTT.

The MQTT broker(Mosquito) is running on Raspberry Pi.

The monitoring room can subscribe to this data for performing further analytics. 

For obtaining future weather conditions, a LSTM(Long Short Term Memory) network-special kind of recurrent neural network(RNN) is involved. The framework used for developing the model is Keras.

If extreme conditions are predicted, i.e. parameters cross a certain threshold, automated e-mails can be sent to the authorities concerned. E-mails are sent using SMTP(Simple Mail Transfer Protocol)

## References

https://machinelearningmastery.com/multivariate-time-series-forecasting-lstms-keras/
