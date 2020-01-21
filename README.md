# StereoVision-DepthEstimation-3DReconstruction

## 3D Reconstruction


## Neural Network - Stereo Images
### Unsupervised Monocular Depth Estimation with Left-Right Consistency
This algorithm enables a convolutional neural network to learn to perform single image depth estimation, despite the absence of ground truth depth data.

#### monodepth
[Paper](https://arxiv.org/abs/1609.03677) -- [Original code](https://github.com/mrharicot/monodepth) -- [Unofficial code - pytorch](https://github.com/OniroAI/MonoDepth-PyTorch)


#### monodepth2
[Paper](https://arxiv.org/abs/1806.01260) -- [Original code](https://github.com/nianticlabs/monodepth2) 


### Anytime Stereo Image Depth Estimation on Mobile Devices
[Paper](https://arxiv.org/abs/1810.11408) -- [Original code](https://arxiv.org/abs/1810.11408)

### StereoGAN
It is a cGAN network that takes stereo image as input and generate depth image.

[code](https://github.com/zhenkaiwang/StereoGAN)

### Learning Monocular Depth by Distilling Cross-domain Stereo Networks
propose to use the stereo matching network as a proxy to learn depth from synthetic data and use predicted stereo disparity maps for supervising the monocular depth estimation network. Cross-domain synthetic data could be fully utilized in this novel framework.

[code](https://github.com/xy-guo/Learning-Monocular-Depth-by-Stereo) -- The code is implemented with **Python 2.7** (Anaconda) (Python 3.x will cause bugs) and **PyTorch 0.4.1**.
## Calibration
### StereoPi tutorial scripts
This repo has code and video link -- [repo](https://github.com/realizator/stereopi-tutorial) 

### StereoVision: Library and utilities for 3d reconstruction from stereo cameras
StereoVision is a package for working with stereo cameras, especially with the intent of using them to produce 3D point clouds. The focus is on performance, ease of usability, and the ability to construct 3D imaging setups cheaply. It relies heavily on OpenCV.

[Repo](https://github.com/erget/StereoVision)

To Install 

``pip install StereoVision'``

## Building stereo
[Building and calibrating a stereo camera with OpenCV (<50€)](https://erget.wordpress.com/2014/02/01/calibrating-a-stereo-camera-with-opencv/)

## Benchmark
[Middlebury Stereo Evaluation - Version 3](http://vision.middlebury.edu/stereo/eval3/)

## Dataset
[Middlebury Stereo Datasets](http://vision.middlebury.edu/stereo/data/)

[Structured3D](https://github.com/bertjiazheng/Structured3D)

A Large Photo-realistic Dataset for Structured 3D Modeling [project-page](https://structured3d-dataset.org)

## Courses

[Computer Vision Basics - Video Lectures](https://www.youtube.com/watch?v=_mOG_lpPnpY&list=PLgnQpQtFTOGRsi5vzy9PiQpNWHjq-bKN1)
--- By Cyrill Stachniss