# Forest-Cover-Type-Classification-NN

## Abstract:

I trained a deep neural network to classify 1.2 million cartographic datapoints into 7 different classes. On the test data, I achieved an average recall score of 90.4%. The neural network, which has 8,072 parameters and 190 neurons, consists of a single hidden layer (128 neurons) connected to a final 8-way softmax. To make the training faster, I used premium GPU allocation units provided by the Google Colaboratory platform. At $9.99, the computing units provided were more than enough for the task.

The specific contributions of this project are as follows:

1. How I addressed the skewed class distribution problem in the dataset using the Synthetic Minority Over-sampling Technique (SMOTE).
2. How I applied the Keras ModelCheckpoint callback during training to capture the best optimized model on the basis validation loss.
3. How I handled some of the reproducibility issues inherent in the use of neural networks by applying Central Limit Theorem.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyYakuza/Forest-Cover-Type-Classification-NN/blob/main/forest_covertype_nn.ipynb)
