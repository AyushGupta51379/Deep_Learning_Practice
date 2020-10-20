# Deep_Learning_Practice
Practicing my Deep learning skills - and improving them

# MNIST - Computer Vision - handwritten digit recognition

# Dogs vs Cats - Computer Vision - Image classification

# MNIST -
- Simple experiments on training model and testing on the popular MNIST data set. 
- Computer Vision for handwritten digit classification, single digits: 0 to 9.
- Currently used a simple CNN - Convolutional Neural Network.

## 1st attempt
I have uploaded my Python notebook in 1, MNIST_1.ipynb. Note that you might need to click on reload a few times for github to properly display it, due to some issues of Github.
### Simple CNN
#### Train on 50% data and test on 50% data
I understand that we could train on 80% data and test on 20% data. However, I want to see the robustness of my current CNN architecture - by training on less data than general and testing on more data than general. Thus, the 50-50 split. Later, we can use 80% train and 20% test split.
#### Accuracy 
##### 95.5% accuracy and 0.95 cohen kappa score
Error Analysis using classification report and Confusion matrix: f1-score is low for case of digits: 8 and 9.

- Digit 8: precision: 0.76, recall: 0.99, f1-score: 0.86. Low Precision, High recall - We incorrectly classified most of the 8 digits (0.76 precision). Out of the digits we predicted as 8, most of those classifications were correct (0.99 recall)

- Digit 9: precision: 0.99, recall: 0.85, f1-score: 0.91. High Precision, Low recall - We correctly classified most of the 9 digits (0.99 precision). Out of the digits we predicted as 8, most of those classifications were incorrect (0.85 recall) 

### To do:

#### Try training on 80% data and testing on 20% data.
#### Try different CNN model, by varying the architecture.
#### Try other models.


# Dogs vs Cats -
- Simple experiments on training model and testing on the popular Dogs vs Cats data set from Kaggle. 
- Computer Vision for image classification, category - dogs, cats.
- Currently used a simple 2D CNN - Convolutional Neural Network.

## 1st attempt
I have uploaded my Python notebook in 1, with name Dogs_vs_Cats_Classifier.ipynb. Note that you might need to click on reload a few times for github to properly display it, due to some issues of Github.
## 2nd attempt
I have uploaded my Python notebook in 2, with name Dogs_vs_Cats_Classifier.ipynb. Note that you might need to click on reload a few times for github to properly display it, due to some issues of Github.

### Simple CNN
#### Train on 50% data and test on 50% data
I understand that we could train on 80% data and test on 20% data. However, I want to see the robustness of my current CNN architecture - by training on less data than general and testing on more data than general. Thus, the 50-50 split. Later, we can use 80% train and 20% test split.
#### Accuracy 
##### 88.8% accuracy and 0.776 cohen kappa score
Error Analysis using classification report and Confusion matrix..

Confusion matrix:
array([

[5675,  646],
       
[ 752, 5427]])

Classification Report:
               
               precision    recall  f1-score   support

         Cat       0.88      0.90      0.89      6321
         
         Dog       0.89      0.88      0.89      617
### To do:

#### Try training on 80% data and testing on 20% data.
#### Try different CNN model, by varying the architecture.
#### Try other models.
