# -gender-identification-using-voice-datasets
It is a project using deep learning to identify gender by given voice based datasets.
# problem statement 
The aim of the project, is to perform binary classification (the algorithm or model is trained on a labeled dataset, where each data point is associated with a class label, either 0 or 1. The two classes are often represented as positive (1) and negative (0) or as "yes" and "no.") on a voice dataset using two different tensor flow neural network architectures: a Dense Neural Network and a 2D Convolutional Neural Network (CNN). The dataset contains voice-related features, and the goal is to classify whether a given voice belongs to one of two classes (encoded as 0 and 1) represented by the 'label' column in the 'voice.csv' dataset.
# data set for voice
https://www.kaggle.com/datasets/primaryobjects/voicegender
# conclusion
Comparing the two models, Model 1 achieved higher accuracy (98.11%) and a slightly higher AUC (0.9972) compared to Model 2, which had an accuracy of 95.58% and an AUC of 0.9926. This indicates that Model 1 performed better overall in terms of accuracy and discrimination ability. However, it's important to note that the choice of the best model depends on the specific requirements of the task and the trade-off between different evaluation metrics. While Model 1 had higher accuracy and AUC, Model 2, being a 2D CNN, might provide additional advantages in terms of interpretability and capturing spatial patterns in the data.


