# Semantic Segmentation
### Introduction
In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)

You may also need [Python Image Library (PIL)](https://pillow.readthedocs.io/) for SciPy's `imresize` function.

##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

#### Model
The neural network is contained in the jupyter notebook file `Semantic Segmentation.ipynb`. It is based on Encoder-Decoder architecture which is commonly used in the Semantic Segmentation tasks. VGG-16 is used for encoder and we use techniques such as Deconvolutions, 1x1 Convolutions and SKip connection on the decoder side to classify each pixes in the image as "Road" or "No Road". See below for network visuals. 
![Semantic-Segmentation-Model](https://github.com/abhisheksreesaila/CarND-Semantic-Segmentation/raw/master/FCN-8%20Network.png)

#### Inference Samples


