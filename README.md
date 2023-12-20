# Recepku-ML
The repository contains a model with 12 image classification implemented 
using Conv2D, MaxPooling2D, and Dense layer.
the result we received that if we combined with that 3 layer from tensorflow library
we got 81% accuracy on the validation dataset.


# Table of Contents
- Introduction
- Datasets
- Model Architecture
- Training
- Further Work

# Introduction
Conv2D conducts convolution operations by sliding a filter over the input, producing a feature map matrix that highlights specific image features. 
The filter, acting as a weight matrix, is convolved with the input image to identify and extract these features. and the 
MaxPooling2D is utilized to reduce the spatial dimensions of an image representation by extracting the maximum value from a specific area within the image.
This process aids in reducing computations and model parameters while mitigating the risk of overfitting. so thats why we combined that 2 layer with Flatten
And Dense layer to get the highest accuracy which is 81 % on the validation set.

# Datasets
for the dataset we do web scrapping from 2 different search engine:
1. Bing
2. Kali on linux

and we dont stop there we used beutifulsoup library from the python to scrap the image from website that have access to scrap their website.

you can download the dataset here:

[Our Dataset](https://drive.google.com/drive/folders/1RbygN80QWnJcJtUYC8B2zAEg_1hskkfO?usp=sharing)

in the dataset we have 12 labels, they are:
1. Bakso
2. Bika Ambon
3. Dadar Gulung
4. Kue Cubit
5. Nasi Goreng
6. Pepes Ikan
7. Putu Ayu
8. Rendang
9. Sate
10. Telur Balado
11. Tempe Bacem

# Model Architecture

for the model architecture we use Conv2D and MaxPooling2D, and we combined it with Flatten and Dense layer, with that model architecture we got good accuracy on trainig and validation set.

# Training

in our model we do some 50 epochs of training with a callback on 80% accuracy so we dont train 50 epochs on raw, we training until the validation accuracy reach 80%.

# further work

for our further work we as mechine learning team we will make a new model so the user can scan the spices and ingridients and the model can know what the ingridients is that and can know
what the recipes fits to the ingridients on the scanned ingridients.


