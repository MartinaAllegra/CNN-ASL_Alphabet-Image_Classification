<p align="center">
  <img src= "https://user-images.githubusercontent.com/80890783/115367755-c4115980-a1c6-11eb-8f61-c50077775701.png" width="400">
</p>

# <div align="center">ASL Alphabet - Image Classification</div>
**<div align="center">1° project work of Knowledge Discovery course</div>**
----

## Task
The homework was done by Martina Allegra and Susanna Saitta (@SusannaSaitta), as a project work for Knowledge Discovery course of Master degree in Data Science for Management (Unict). 
The task was to solve a classification problem using Convolutional Neural Network. 

## Dataset & Info
The dataset contains images of alphabets from the American Sign Language. It is taken from https://www.kaggle.com/grassknoted/asl-alphabet. Specifically, 87,000 images are provided in 29 separate folders representing classes: 26 of which for the letters A-Z and 3 classes for Space, Delete and Nothing. 

*Do you want to be able to run the code?*
1. Go to your Kaggle account, scroll to *API* section and click on *Create New API Token*. It will download *kaggle.json* file.
2. Go to the notebook on Google Colab.  
3. Run the first two cells.
4. In *file_update()* select your .json file.

Both .ipynb notebooks and direct links on Colab are provided. 

## CNNs architecture
8 Convolutional Neural Networks have been trained, validated and tested:
* 1°+ 2°+ 3° Conv layer + 1° FC layer + Classifier:


https://colab.research.google.com/drive/1Ruecj4ob3eU8A-eCVtOdd0SYR3url6Gt?usp=sharing
* 1°+ 2°+ 3° Conv layer + 1°+ 2° FC layer + Classifier:


https://colab.research.google.com/drive/1yjBlPK3JYBgnPfEmoADF-Y9VJbOxbK-M?usp=sharing
* 1°+ 2°+ 3°+ 4° Conv layer + 1° FC layer + Classifier:

 
  https://colab.research.google.com/drive/1kcPJ6JqNp0ISlefonXXl9-3CTNqX32Si?usp=sharing
* 1°+ 2°+ 3°+ 4° Conv layer + 1°+ 2° FC layer + Classifier: 


  https://colab.research.google.com/drive/1eTIeqZJ4t96Wgm39e-_Pe3yzWsBmd5H8?usp=sharing
* 1°+ 2°+ 3°+ 4°+ 5° Conv layer + 1° FC layer + Classifier: 


  https://colab.research.google.com/drive/1TRYt8j_CY-RKyqlO4Ld62wS3RC4GY8vK?usp=sharing
* 1°+ 2°+ 3°+ 4°+ 5° Conv layer + 1°+ 2° FC layer + Classifier: 


  https://colab.research.google.com/drive/12OWa-QMeBP2RSXOXxZsKYcdk71pvQMBl?usp=sharing
* 1°+ 2°+ 3°+ 4°+ 5°+ 6° Conv layer + 1° FC layer + Classifier:


https://colab.research.google.com/drive/1i2N4EZrlJQqxut6liUgEx8yceHhoaOP4?usp=sharing
* 1°+ 2°+ 3°+ 4°+ 5°+ 6° Conv layer + 1°+ 2° FC layer + Classifier:


https://colab.research.google.com/drive/1L7XlW3kxzl0Yt2zqJpp1QOaMYY0ezADH?usp=sharing

According the validation accuracy, the best among the trained CNNs has **5** convolutional layers and **1** fully connected layer:
![Immagine2](https://user-images.githubusercontent.com/80890783/115155095-a20cbf80-a07e-11eb-90dd-2e3a01852e7b.png)


## Details
For more information, see notebooks and report.


