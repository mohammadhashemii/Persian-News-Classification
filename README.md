# Dogs Breed Classification on Stanford Dogs Image Dataset using VGG-16
This project was the third assignment of the Computational Intelligence course at Shahid Beheshti University. The aim of the project was to deal with large image datasets and use both pretrained and non-pretrained vision models to do the classification. So let's dive into it!


# Dataset

![](https://github.com/mohammadhashemii/Dogs-Breed-Classification/blob/master/sample-data.png)

The dataset has been obtained from [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/).It contains images of **120** breeds of dogs from around the world. This dataset has been built using images and annotation from [ImageNet](http://www.image-net.org) for the task of fine-grained image categorization. Contents of this dataset:

1. Number of categories: 120
2. Number of images: 20,580
3. Annotations: Class labels, Bounding boxes

There is no need to download the dataset into your local computer. It's just a huge amount of data! In the `DogsBreedClassification.ipynb` file you can see the documentation to how to fetch the dataset into your colab env directly.
  

# Model : VGG-16

The ImageNet Large Scale Visual Recognition Challenge (ILSVRC) is an annual computer vision competition. Each year, teams compete on two tasks. The first is to detect objects within an image coming from 200 classes, which is called object localization. The second is to classify images, each labeled with one of 1000 categories, which is called image classification. VGG 16 was proposed by Karen Simonyan and Andrew Zisserman of the Visual Geometry Group Lab of Oxford University in 2014 in the paper “**VERY DEEP CONVOLUTIONAL NETWORKS FOR LARGE-SCALE IMAGE RECOGNITION**”. This model won the **1st  and 2nd** place on the above categories in 2014 ILSVRC challenge.

Both training a model from scratch and using a pretrained model have been used in this project. The pretrained model can be obtained from [here](https://github.com/fchollet/deep-learning-models/releases/download/v0.1/vgg16_weights_tf_dim_ordering_tf_kernels.h5)(It is not neccessary to download it into your local computer or yourg-drive).

