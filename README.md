# Transfer Learning For Multiclass Classification

This notebook is an implementation of transfer learning approach by using multi-class weather dataset for image classification task.

The dataset consists of a total of 1125 images which are maually labeled as cloudy, sunrise, rainy and sun shine. I will use pre-trained models which are ResNet and InceptionV3 available from Keras.

With transfer learning, instead of starting the learning process from scratch, we start from patterns that have been learned when solving a new related problem. So we reuse initial and middle layers of our pre-trained model to re-train only final layers for our new task. A pre-trained model denotes a model that was trained on a large benchmark dataset to solve a problem similar to the one that we want to solve.

### Dataset 

Ajayi, Gbeminiyi (2018), “Multi-class Weather Dataset for Image Classification”, Mendeley Data, V1, doi: 10.17632/4drtyfjtfy.1

- Can be downloaded from here -> [https://data.mendeley.com/datasets/4drtyfjtfy/1](https://data.mendeley.com/datasets/4drtyfjtfy/1)