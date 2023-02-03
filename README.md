# ObjectRecognization-in-Image-data-using-ResNet50



**About the CIFAR-10 dataset:**


-----> The CIFAR-10 data consists of 60,000 32x32 color images in 10 classes, with 6000 images per class. 
There are 50,000 training images and 10,000 test images in the official data.
This dataset consists of 10 classes with 32*32 dimsenion images. 



We can find the dataset in kaggle site https://www.kaggle.com/
First download the kaggle.json file fromm your kaggle account and load the dataset i.e CIFAR-10 dataset using the api in your google colab directory.



**Operations carried out:**


1.Importing the necessary depencies(library).
2. Load the dataset in the google colab directory and extract the file using py7zr.
3. Image label processing.
4. Image data analysis and image processing.
5. Cross Validation.
6. Building the neral network using tensorflow and keras library.
7. Then use ResNet50 (i.e pre-trained CNN) as transfer learning.
8. Model Evaluation to check accuracy and loss on test data and also if there is any overfitting pr not.
9. Analyse the validation accuracy and loss by plotting graphs using matplotlib library. 
