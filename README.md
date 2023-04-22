# SC1015 MiniProject

This project aims to develop a model that can accurately classify different types of vegetables based on their images.
The images used is found in Kaggle https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset?resource=download

![Data Visualisation](https://user-images.githubusercontent.com/130839755/233574154-a8d1f6d3-1253-4ea3-a320-d2176fc14816.PNG)

## Group members
- Apurv - Data visualisation and Augmentation
- Bryan - Data preparation and Neural Network Model

## Problem Definition
Vegetable is one of the most common produce in farms and usually the farm would produce more than 1 types of vegetables. These vegetable would be sorted manually in the warehouse. By accurately classifying vegetable images, we can automate the process of sorting and grading vegetables, reducing the need for manual labor and increasing efficiency. This is especially important for large-scale vegetable production, where accurate classification is necessary to meet the market's demand and ensure profitability. Hence our goal is to accurately identify the vegetable images using CNN(Convolutional Neural Network)


## Conclusion
- The CNN model is not able to predict vegetable accurately using the grayscale images as there are similarly shaped vegetable such as radish and carrots.
- By using only resized images with retaining the colour, the model is able to predict very accurately.
- Model can be improve by adding a few layers of dropout to increase accuracy and reduce validation loss.

## Learning Points
- Image augmentation
- Convolutional Neural Network
- Precision, Recall
- Confusion Matrix for multiclass classification

## References
https://www.kaggle.com/code/ronakparmar99/vegetable-predication-model
https://www.kaggle.com/code/itsmegood/vegetableclassification
https://www.analyticsvidhya.com/blog/2020/09/overfitting-in-cnn-show-to-treat-overfitting-in-convolutional-neural-networks/
https://medium.com/mlearning-ai/confusion-matrix-for-multiclass-classification-f25ed7173e66
https://www.youtube.com/watch?v=2osIZ-dSPGE&ab_channel=codebasics

