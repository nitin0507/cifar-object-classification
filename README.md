# cifar-object-classification


# problem statement---
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
For Cifar10 database -
You are given:
1. Readme file has Template file to download cifar10 dataset (it has training and test dataset). You have to download dataset using this.
Your task is to:
1. Predict correct class for every image in the test dataset.
Read Instructions carefully -
1. Submit a csv file with only predictions for X test data. File should not have any headers and should only have one column i.e. predictions.
2. Predictions should be class names and not numbers.
3. Your score is based on number of accurate predictions.

#These are the classes in the dataset:

airplane,
automobile,
bird,
cat,
deer,
dog,
frog,
horse,
ship,
truck

#Approach
Imported dataset
Analysed data
Applied PCA
Prediction using Random Forest
Prediction using KNN
Prediction using Logistic Regression
Prediction using SVM
Comparison between various classifier


#Conclusion
Best accuracy comes from Support vector classifier. Although, It can be further improved by using neural networks (which i will be deploying in other repository.)
