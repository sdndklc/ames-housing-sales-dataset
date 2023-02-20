# Regression with Ames Housing Sales Dataset

- Ames Housing Sales dataset consists of 79 explanatory features and corresponding sale prices of 1379 different residential houes in Ames. This dataset contains both numerical and non-numerical features.

- Pre- processing of data includes label encoding and scaling. 

   Strings in non-numerical data should be encoded and converted to integers to be used in training. Encoding is done by using Label Encoder.

   Feature scaling can be performed to handle highly varying magnitudes and values. Scaling of the data makes it easy for a model to learn and understand the regression problem. It is done by using Standard Scaler.
   
- Neural network consist of 4 linear layers. ReLu activation function used between first three linear layers. There is no activation function after output layer since this a regression problem.

- Model evaluation is demonstrated with accuracy, train loss, and test loss graphs.



