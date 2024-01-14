# ObjectRecognization-in-Image-data-using-ResNet50



## **About the CIFAR-10 dataset:**


-----> The CIFAR-10 data consists of 60,000 32x32 color images in 10 classes, with 6000 images per class. 
There are 50,000 training images and 10,000 test images in the official data.
This dataset consists of 10 classes with 32*32 dimension images. 



We can find the dataset on the Kaggle site https://www.kaggle.com/
First, download the kaggle.json file from your Kaggle account and load the dataset i.e. CIFAR-10 dataset using the API in your Google colab directory.



## **Operations carried out:**


1. Importing the necessary dependencies (libraries).
2. Load the dataset in the Google Colab directory and extract the file using py7zr.
3. Image label processing.
4. Image data analysis and image processing.
5. Cross Validation.
6. Building the neural network using Tensorflow and Keras library.
7. Then use ResNet50 (i.e. pre-trained CNN) as transfer learning.
8. Model Evaluation to check accuracy and loss on test data and also if there is any overfitting or not.
9. Analyse the validation accuracy and loss by plotting graphs using matplotlib library. 
