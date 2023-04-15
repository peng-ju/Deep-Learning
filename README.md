# Deep Learning
This repository contains the course projects from [ECE601 Deep Learning](https://engineering.purdue.edu/DeepLearn/) taught by [Prof. Avinash Kak](https://engineering.purdue.edu/kak/) and [Prof. Charles A. Bouman](https://engineering.purdue.edu/~bouman/). I highly recommend this course to Purdue students who want to have a hands-on experience with deep learning. 

These projects implements the key components of the deep learning.

### OOP Object Oriented Programming [[code]](https://github.com/peng-ju/Deep-Learning/blob/main/OOP_Object_Oriented_Programming.ipynb)
> - A practice program for Objective Oriented Programming. Created a calllable class for Fibonacci sequence and Prime number.

### DataLoader with Image Augmentation [[code]](https://github.com/peng-ju/Deep-Learning/blob/main/DataLoader_ImageAugmentation.ipynb)
> - Created a customized Dataloader class with torch.utils.data.Dataset. Applied normalization and image augmentation. Practice with Torchvision.

### A Simple Neural Network [[code]](https://github.com/peng-ju/Deep-Learning/blob/main/Simple_Neural_Network.ipynb)
> - Constructed a two-layer neural network with Adam, SGD+ optimizer. Compared the result with Torch.nn.

### Image classification with a two-layer CNN for COCO dataset [[code]](https://github.com/peng-ju/Deep-Learning/blob/main/Image_classification_for_MS-COCO_Dataset.ipynb)
> - Loaded 5 categories of 10000 images from the [COCO dataset](https://cocodataset.org/#download).   
> - Created a dataloader with image augmentation.   
> - Built a classifier with a simple two-layer CNN and achieved a classification accuracy of 0.65. (Reasonable result for 64x64 images and simple CNN)   

### Predict label and bbox with ResBlock [[code]](https://github.com/peng-ju/Deep-Learning/blob/main/ResBlock_Label_and_Bbox.ipynb)
> - Loaded 3 categories of 6k images from the [COCO dataset](https://cocodataset.org/#download). The data also include the bboxes of the objects in images.   
> - Created a dataloader with image augmentation.
> - Build a deep (58 layer) NN with convolutional layer, BatchNormalizaion layer, Downsampling layer, Resblock, classification head to predict the label and regression head to predic the bbox.
> - Classification accuracy is 0.86, Mean IoU value is 0.55. 

### YOLO: multi-object detection


### GAN (Generative Adverserial Network) [[code]](https://github.com/peng-ju/Deep-Learning/blob/main/GAN.ipynb)
> - Loaded 8k pizza images with the size of 64x64.
> - Built GAN based on the generator and descriminator. The Generator is based on Transpose convolutions, while the descriminator is based on BCELoss of a CNN classifier.
> - Evaluated the generated images with FID (Frechet Inception Distance), and get a FID score of 173 between 1000 'fake' and 'real' pizza images. 

### Setiment Analysis with GRU (Gated Recurrent Unit)
