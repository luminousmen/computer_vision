Computer vision
---

Set of task and solution on some of the Computer Vision problems. Hope it helps somebody.

## Panchromatic sharpening 

Panchromatic sharpening uses a higher-resolution panchromatic image to fuse with a lower-resolution multiband raster dataset. Simply put:

High-res grayscale band + Low-res color bands = high-res color image

To pansharpen I tried browley, FIHS and PCA. To align to images we need to find key-points using ORB, BRISK or FREAK algorithms. Mostly using OpenCV.


[Notebook](https://github.com/luminousmen/computer_vision/blob/master/Pan-sharpening.ipynb)
[Nbviewer](https://nbviewer.jupyter.org/github/luminousmen/computer_vision/blob/master/Pan-sharpening.ipynb)


## Cifar classification with classical methods

Putting together a simple image classification pipeline, based on the k-Nearest Neighbor, SVM classifiers and Softmax. Using PCA for visualization, HOG for features.


[Notebook](https://github.com/luminousmen/computer_vision/blob/master/Cifar10-classical.ipynb)
[Nbviewer](https://nbviewer.jupyter.org/github/luminousmen/computer_vision/blob/master/Cifar10-classical.ipynb)


## Cifar classification using CNN

Fast.ai based cifar classification using simple CNN based on Resnet-34. Nothing special.

[Notebook](https://github.com/luminousmen/computer_vision/blob/master/Cifar10-classification.ipynb)
[Nbviewer](https://nbviewer.jupyter.org/github/luminousmen/computer_vision/blob/master/Cifar10-classification.ipynb)



## Sign detection

Detecting signes on the roads using fucking [tf-garden model](https://github.com/tensorflow/models). Model `ssd_inception_v2_coco_2017_11_17`.

[Notebook](https://github.com/luminousmen/computer_vision/blob/master/Sign-Detection-tfgarden.ipynb)
[Nbviewer](https://nbviewer.jupyter.org/github/luminousmen/computer_vision/blob/master/Sign-Detection-tfgarden.ipynb)


## Segmentation with Blob detection

The task here is to count the iron bars. The solution use U-net with MAPE custom metrics for segmentation, blob detection for actual counting of segmented bars. Custom fast.ai v2 implementation.

[Notebook](https://github.com/luminousmen/computer_vision/blob/master/Segmentation.ipynb)
[Nbviewer](https://nbviewer.jupyter.org/github/luminousmen/computer_vision/blob/master/Segmentation.ipynb)
