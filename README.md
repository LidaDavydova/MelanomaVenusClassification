# MelanomaVenusClassification

The purpose of work is to research different implementatons of **melanoma/nevus** recognition and classification on the picture.
Moreover, in the end we should have trained model on our dataset.

Dataset was created by compilation [https://doi.org/10.7910/DVN/DBW86T] and [https://challenge2020.isic-archive.com/] sourses.


## About models

Different neural network architectures are considered for the tasks of image classification and classification of parameterized data from these images

## Image classification models

The first model kerasSimple.h5 in dataset.ipynb has accuracy on test images ~ 0.75

**kerasSimple.h5** in folder _models/_

It consist of 3 layers of convolution

### Statistic of training and validation for model:
![Screenshot from 2024-02-13 19-28-26](https://github.com/LidaDavydova/MelanomaVenusClassification/assets/79317010/0aa3660f-adec-4b01-9412-bec9179bba24)

The second model model_keras_2_1.keras in dataset.ipynb has accuracy on test images ~ 0.82

**model_keras_2_1.keras** in folder _models/_

It consist of 3 layers of convolution

### Statistic of training and validation for model:
![Screenshot from 2024-08-17 20-52-02](https://github.com/user-attachments/assets/c5c58433-b7a0-4287-b016-9061e2207aad)


## Parameterized data from images classification models

The model model_sklearn_1_0.pkl has accuracy on test images ~ 0.87

It depends of quality of the **image classification model**

**model_sklearn_1_0.pkl** in folder _models/_

### Statistic of trained model:
![Screenshot from 2024-08-17 21-20-51](https://github.com/user-attachments/assets/2d36204b-520d-4182-a896-232db1369804)


## In file testModel.ipynb you can check model on your images
