
**Self-Driving Cars** 

**Goals**

The goals / steps of this project are the following:
* Use the udacity self driving car simulator to collect data of good driving behavior.
* Build, a convolution neural network in Pytorch that predicts steering angles from images.
* Train and validate the model with a training and validation set.
* Test that the model successfully drives around the track in autonomous mode.

### Overview

#### 1. Project contents:
The project includes the following files:
* self_driving_car.py containing the script to create and train the model.
* Self_Driving_Car.ipynb containing the notebook code to create and train the model.
* model.py as a helper function for loading the required model in drive.py.
* drive.py for driving the car in autonomous mode.
* model.h5 containing a trained convolution neural network.
* Note: This project uses python 3 version.

#### Running the model
Using the Udacity provided simulator and the drive.py file, the car can be driven autonomously around the track by executing 
```sh
python drive.py model.h5
```

### Model Architecture

The project is based on the research by Nvidia. The paper is available [here](https://arxiv.org/pdf/1604.07316v1.pdf). The network is a CNN which maps raw pixel inputs along with steering data from a log file and clones the behaviour of the steering in autonomous mode. For more in depth explanation, please refer to the tutorial.