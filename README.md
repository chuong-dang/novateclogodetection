# novateclogodetection
Novatec Logo Detection on Edge Device with Tensorflow Object Detection API and OpenVINO

This repository is part of this blogpost from Novatecs Blog.
I used TensorFlow's Object Detection API to train a Novatec Logo Detector. The model was converted to Intel OpenVINO to perform the detections on an Edge Device.


Files:
``` 
- openvinomodel: contains the converted model in OpenVINOs format
- tf-frozen-model: contains the frozen model which was trained with TensorFlow's Object Detection API
- LiveOD.py: the Python file to perform live detection on an Edge Device
- a few files used for the model training
