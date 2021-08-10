# Text_Classification

Binary Text classification using TensorFlow using 1D-CNN architecture on IMDB movie review sentiment classification with a test accuracy of 87.01%. The models are saved in .h5 file format and can be used later.

## Dataset:
The dataset considered for the project is IMDB movie review, which is publically available for anyone to use and experiment their ideas on the same.

## Model Architecture & Summary:
1D Convolution Neural Network is used as a model architecture, which is then implemented on TensorFlow.

<img width= 350, src="https://github.com/Mansi130101/Text_Classification/blob/a7f604b46edddd7722d252d99e99ca4fa4872b15/Images/1D_CNN/Model%20architecture.png" alt="Model Architecture" /> <img width= 350, src="https://github.com/Mansi130101/Text_Classification/blob/a7f604b46edddd7722d252d99e99ca4fa4872b15/Images/1D_CNN/Model_summary.png" alt="Model Summary" />

## Learning Curves:
During the training of the model, the train and validation split is in the ratio of 0.8 : 0.2 of the whole training dataset to avoid overfitting to the training dataset. Loss and Accuracy curves for train and validation datasets:

<img width= 350, src="https://github.com/Mansi130101/Text_Classification/blob/a7f604b46edddd7722d252d99e99ca4fa4872b15/Images/1D_CNN/Loss.png" alt="Loss" /> <img width= 350, src="https://github.com/Mansi130101/Text_Classification/blob/a7f604b46edddd7722d252d99e99ca4fa4872b15/Images/1D_CNN/Accuracy.png" alt="Accuracy" />

## Future Scope:
Further hypertuning can be done to improve results:

1. model architecture
2. optimizer
3. learning rate
4. batchsize
5. metrics
