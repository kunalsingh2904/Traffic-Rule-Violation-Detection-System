# Traffic Rule Violation Detection System (Smart Traffic)

This project tries to detect a car whenever it crosses a Red Light or overspeeds.
It uses tensorflow with an ssd object detection model to detect cars and from the detections in each frame each vehicle can be tracked across a video and can be checked if it crossed a redlight and speed of that vehicle can be calculated.

## Getting Started

The project is made by using tensorflow so you must be familiar with tensorflow and basic object detection and you must also know basic maths for understanding the tracking algorithm. You must be also familiar with linux OS as We have made this on Ubuntu and didn't test on other platforms.

### Demo

https://youtu.be/HuwTrCYU_Ek


### Prerequisites

Python packages to be installed

```
* Tensorflow (Tensorflow-gpu if you have Nvidia GPU)
* openCV
* imutils
* Pillow
* numpy
* scipy
* tkinter
* urllib
* openALPR api
* matplotlib
```
Make account on openalpr and get api secret key from [OpenALPR](https://www.openalpr.com/)

## Installing

* Clone the repo
* Create and accont on https://cloud.openalpr.com/account/register
* Paste your secret key in [VehicleMoniter.py](https://github.com/luckynirania/devhack_victor/blob/master/VehicleMoniter.py) file on line 144.
* Initiate virtual environment
* Install api ```python3 openalpr/setup.py install```
* Install pip packages ```pip3 install -r requirements.txt```
* run the project by the command ```python3 VehicleMoniter.py```
* You can edit the video name at line 348 of [VehicleMonitor.py]

## Built With

* [Tensorflow](https://www.tensorflow.org/) - ML library
* [OpenALPR](https://www.openalpr.com/) - For detecting license plate and extracting license plate number

## Screenshots
we gave added screenshots in "Screenshots" folder
