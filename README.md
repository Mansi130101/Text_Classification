# Text_Classification

Binary Text classification using TensorFlow using 1D-CNN architecture on IMDB movie review sentiment classification with a test accuracy of 87.01%. The models are saved in .h5 file format and can be used later.

## Dataset:

## Model Architecture & Summary:
1D Convolution Neural Network is used as a model architecture, which is then implemented on TensorFlow.

<img width= 350, src="https://github.com/Mansi130101/Text_Classification/blob/6731d09f65b069a0129f2eb98c8f8ab43c69c144/model%20architecture.png" alt="Model Architecture" /> <img width= 350, src="https://github.com/Mansi130101/Text_Classification/blob/e23c671c5bccddc63120224b726367bba50c55b4/model_summary.png" alt="Model Summary" />

## Learning Curves:
During the training of the model, the train and validation split is in the ratio of 0.8 : 0.2 of the whole training dataset to avoid overfitting to the training dataset. Loss and Accuracy curves for train and validation datasets:

<img width= 350, src="https://github.com/Mansi130101/Text_Classification/blob/f22e5ed3925a98dad7cf83061c0a8535f9372c0f/Loss.png" alt="Loss" /> <img width= 350, src="https://github.com/Mansi130101/Text_Classification/blob/f22e5ed3925a98dad7cf83061c0a8535f9372c0f/Accuracy.png" alt="Accuracy" />

## Future Scope:
Further hypertuning can be done to improve results:

1. model architecture
2. optimizer
3. learning rate
4. batchsize
5. metrics
