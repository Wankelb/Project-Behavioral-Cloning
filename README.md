# Behavioral Cloning Project

by Batuhan Alkan submitted on May 2021 as part of Udacity Self Driving Car Engineer

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

Overview
---

![](/gif1.gif)



(Vehicle driving autonomously)


The goals / steps of this project are the following:
* Use the simulator to collect data of good driving behavior
* Build, a convolution neural network in Keras that predicts steering angles from images
* Train and validate the model with a training and validation set
* Test that the model successfully drives around track one without leaving the road
* Summarize the results with a written report

Required Files
---
To meet specifications, the project will require submitting five files: 
* [model.py](model.py) containing the script to create and train the model
* [drive.py](drive.py) (script to drive the car - it's the original provided by the course)
* [model.h5](model.h5) (trained Keras model)
* writeup_report.md summarizing the results
* [video.mp4](video.mp4) for recording of autonomous mode using model.h5 for 1 lap around Track1
weights.h5 containing the weights of model.h5 in order to fine tune the model like transfer learning.

functional code
---
The model provided caon be used to successfully operate the simulation. With the simulator provided by Udacity and my drive.py file, the car can be driven autonomously over the route by executing it

```sh
python drive.py model.h5
```
The Pipeline
---
1. Loading the raw data
2. Dataset summary and visual exploration
3. Data set consists of 1081 camera images
4. Data Augmentation
Here the image is reduced and only reduced
No further image processing was used because the result of the architecture was, as expected, good
5. the CNN Architecture with Keras
 ![](/NVIDIA.jpg)


