# Dress-Recognition
Given an image of person, aim is to recognize the dress of the person.

The images are classified into four categories based on the dress categories : Tshirts, Formal Shirts, Sarees, Kurtas.
The link for the dataset is as below: https://www.kaggle.com/paramaggarwal/fashion-product-images-small

From the dataset the images belonging to category of Shirt, Tshirt, Saree and Kurta are extracted for training and testing purpose.
The pretrained ResNet-50 backbone model from Keras is used with their Imagenet weights.
