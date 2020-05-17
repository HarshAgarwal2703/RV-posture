# RV-posture

## Problem statement

To develop an application which uses object detection, classification, and identify features of the given object
To determine the action of the user (sitting/standing/sleeping) which can be used in video-based exercises.

## INTRODUCTION
Exercises such as squats, deadlifts, and shoulder presses are beneﬁcial to health and ﬁtness, but they can also be very dangerous if performed incorrectly. The heavyweights involved in these workouts can cause severe injuries to the muscles or ligaments. Many people work out and perform these exercises regularly but do not maintain the proper form (pose). This could be due to a lack of formal training through classes or a personal trainer, or could also be due to muscle fatigue or using too much weight. For our course project, we seek to aid people in performing the correct posture for exercises by building Pose Trainer, a software application that detects the user’s exercise pose and provides useful feedback on the user’s form, using a combination of the latest advances in pose estimation and machine learning. Our goal for Pose Trainer is to help prevent injuries and improve the quality of people’s workouts with just a computer and a webcam.


## TO RUN

### Install libraries: 
tensorflow=1.14.0
argparse
dill
fire
matplotlib
numba
psutil
pycocotools
requests
scikit-image
scipy
slidingwindow
tqdm

### Demo


$ python run.py --model=mobilenet_thin --image=./images/image1.jpg

Image should be added to image folder of the project. 

### Webcam 

$ python run_webcam.py --model=mobilenet_thin --camera=0















