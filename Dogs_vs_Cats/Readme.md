# Deep_Learning_Practice
Practicing my Deep learning skills - and improving them

# Dogs vs Cats
- Simple experiments on training model and testing on the popular Dogs vs Cats data set from Kaggle. 
- Computer Vision for image classification, category - dogs, cats.
- Currently used a simple 2D CNN - Convolutional Neural Network.

## 1st attempt
I have uploaded my Python notebook in CNN/1, with name Dogs_vs_Cats_Classifier.ipynb. Note that you might need to click on reload a few times for github to properly display it, due to some issues of Github.
## 2nd attempt
I have uploaded my Python notebook in CNN/2, with name Dogs_vs_Cats_Classifier.ipynb. Note that you might need to click on reload a few times for github to properly display it, due to some issues of Github.

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
