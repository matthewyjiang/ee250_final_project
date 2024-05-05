# EE250 Final Project

## Group Members:
- Matthew Jiang <jiangmy@usc.edu>
- Max Chow <mtchow@usc.edu>

## Running Instructions

On the laptop:
```python3 detect.py```
On the raspberry pi:
```python3 imagetaker.py```

To see visualization, go to 127.0.0.1:5000 in your browser.

If there is a permission error go to your browser settings [(Chrome Settings)](chrome://settings/) and clear cookies. (this fixes it and I don't know why)

## Dependencies
- [opencv](https://opencv.org/)
- [yolov3 trained weights and configuration file](https://pjreddie.com/darknet/yolo/)
- flask
- mosquitto mqtt
- coco names and labels
