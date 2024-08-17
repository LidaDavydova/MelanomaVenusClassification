# MelanomaVenusClassification

The purpose of work is to research different implementatons of **melanoma/nevus** recognition and classification on the picture.
Moreover, in the end we should have trained model on our dataset.

Dataset was created by compilation [https://doi.org/10.7910/DVN/DBW86T] and [https://challenge2020.isic-archive.com/] sourses.

## Try it

In file testModel.ipynb you can check model on your images

### Web site:
http://89.169.135.79:5000/

### Telegram Bot:
https://t.me/AntiMelonomabot

## About models

Different neural network architectures are considered for the tasks of image classification and classification of parameterized data from these images

## Image classification models

The first model kerasSimple.h5 in dataset.ipynb has accuracy on test images ~ 0.75

**kerasSimple.h5** in folder _models/_

It consist of 3 layers of convolution

### Statistic of training and validation for model:

![image](https://github.com/user-attachments/assets/3fb66287-40b0-4775-854b-e7f84037a2b0)

The second model model_keras_2_1.keras in dataset.ipynb has accuracy on test images ~ 0.82

**model_keras_2_1.keras** in folder _models/_

It consist of 3 layers of convolution

### Statistic of training and validation for model:

![Screenshot from 2024-08-17 20-52-02](https://github.com/user-attachments/assets/c351b612-8a96-4482-84cb-f28148ebe60c)


## Parameterized data from images classification models

The model model_sklearn_1_0.pkl has accuracy on test images ~ 0.87

It depends of quality of the **image classification model**

**model_sklearn_1_0.pkl** in folder _models/_

### Statistic of trained model:
![Screenshot from 2024-08-17 21-20-51](https://github.com/user-attachments/assets/761bfe4e-0872-41f8-b2e4-1467974547d9)


## Try it

In file testModel.ipynb you can check model on your images

### Web site:
http://89.169.135.79:5000/

### Telegram Bot:
https://t.me/AntiMelonomabot
