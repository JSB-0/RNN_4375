# Apple Stock Price Prediction with Recurrent Neural Networks
## Time-Series Forecasting
### Overview
This project aimed to predict Apple stock prices using recurrent neural networks (RNNs). There are two main implementations:

1. **Custom RNN**: Manually implemented with NumPy for linear algebra operations used in methods such as forward_pass, backpropagation, and training the model.

2. **Keras RNN**: Leveraging the Keras library, this implementation uses a high-level interface for building neural networks. Here, a similar recurrent neural network architecture to the Custom RNN was constructed for comparison purposes.

### Technologies 
- Python 3.10
- NumPy
- pandas
- scikit-learn
- Matplotlib
- Keras

### Results
Model evaluation was done using mean-squared error. The Keras model had moderately more predictive power compared to the custom RNN.


![image](https://github.com/JSB-0/RNN_4375/assets/18308535/94ff253a-a486-4330-8082-58cce734fbbd)

*RMSE: 2.0848*


![image](https://github.com/JSB-0/RNN_4375/assets/18308535/21a8a65f-3adf-4e52-886a-232f3f5db2ff)

*RMSE: 0.02507*

