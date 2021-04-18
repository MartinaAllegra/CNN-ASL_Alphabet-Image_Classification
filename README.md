# <div align="center">ASL Alphabet - Image Classification</div>
**<p align="center"> 1° project work of Knowledge Discovery course - UniCt </p>**
----

## Task
The homework was done by Martina Allegra and Susanna Saitta, as a project work for Knowledge Discovery course of Master degree in Data Science for Management (Unict). 
The task was to solve a classification problem using Convolutional Neural Network. 

## Dataset 
The dataset contains images of alphabets from the American Sign Language. It is taken from https://www.kaggle.com/grassknoted/asl-alphabet. Specifically, 87,000 images are provided in 29 separate folders representing classes: 26 of which for the letters A-Z and 3 classes for Space, Delete and Nothing. 

*Do you want to run the code?*
1. Go to your Kaggle account, scroll to *API* section and click on *Create New API Token*. It will download *kaggle.json* file.
2. Load the notebook on Google Colab.  
3. Run the first two lines.
4. In *file_update()* select your .json file.

## CNNs architecture
8 Convolutional Neural Networks have been trained, validated and tested:
* 1°+ 2°+ 3° Conv layer + 1° FC layer + Classifier.
* 1°+ 2°+ 3° Conv layer + 1°+ 2° FC layer + Classifier.
* 1°+ 2°+ 3°+ 4° Conv layer + 1° FC layer + Classifier.
* 1°+ 2°+ 3°+ 4° Conv layer + 1°+ 2° FC layer + Classifier.
* 1°+ 2°+ 3°+ 4°+ 5° Conv layer + 1° FC layer + Classifier. 
* 1°+ 2°+ 3°+ 4°+ 5° Conv layer + 1°+ 2° FC layer + Classifier.
* 1°+ 2°+ 3°+ 4°+ 5°+ 6° Conv layer + 1° FC layer + Classifier.
* 1°+ 2°+ 3°+ 4°+ 5°+ 6° Conv layer + 1°+ 2° FC layer + Classifier.

According the validation accuracy, the best among the trained CNNs has **5** convolutional layer and **1** fully connected layer:
![Immagine2](https://user-images.githubusercontent.com/80890783/115155095-a20cbf80-a07e-11eb-90dd-2e3a01852e7b.png)


## Datails
For more information, see notebooks and report. 


