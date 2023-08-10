# deep-learning-challenge

## Analysis Overview:

The purpose of this analysis is to develop a binary classification model using deep learning techniques to predict whether organizations funded by Alphabet Soup will be successful based on various features provided in the dataset. The goal is to achieve a predictive accuracy of at least 75% by optimizing the model through preprocessing, architecture design, and hyperparameter tuning.

## Results:

### Data Preprocessing:

- Target Variable: The target variable for the model is `IS_SUCCESSFUL`, which indicates whether an organization was successful in their funding.
- Features: The features for the model include various columns from the dataset, after preprocessing and encoding. These features are used to make predictions.
- Removed Variables: The variables `EIN` and `NAME` were removed from the input data as they were not relevant to the prediction task.

### Compiling, Training, and Evaluating the Model:

- Neural Network Model:
  - Number of Hidden Layers: Three hidden layers were used.
  - Number of Neurons in Hidden Layers: The first hidden layer had 128 neurons, the second had 64, and the third had 32.
  - Activation Functions: Rectified Linear Unit (ReLU) activation function was used for all hidden layers to introduce non-linearity.
  - Output Layer Activation: Sigmoid activation function was used in the output layer for binary classification.

- Achieving Target Performance: Despite multiple optimization attempts, the model achieved an accuracy of around 72%, which is below the target of 75%.

- Steps for Increasing Model Performance:
  - Applied binning and encoding to categorical variables for feature representation.
  - Designed a deep neural network architecture with multiple hidden layers and appropriate activation functions.
  - Explored different hyperparameters, such as learning rates and batch sizes, during training.
  - Experimented with various combinations of preprocessing steps to improve data representation.

## Summary:

The analysis aimed to develop a deep learning model for predicting the success of Alphabet Soup-funded organizations. Despite optimization efforts, the model fell short of achieving the target accuracy of 75%. This indicates that the current model and preprocessing techniques may have limitations in capturing the complex relationships within the data.

In conclusion, while the current model's performance has room for improvement, it provides a foundation for further experimentation and refinement. The choice of model and preprocessing strategies should be guided by a thorough understanding of the data and the specific problem at hand.