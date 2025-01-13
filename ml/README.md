# Teachable Machine

## 
**tm.html**
Runs a tensorFlow.js model which has been exported from Teachable Machine.
Configuration is required:
```
const URL = '{{URL}}';
```
URL is supplied when uploading model hosted service, similar to https://teachablemachine.withgoogle.com/models/{TOKEN}


## Demo
**demo.py**
Runs a TensorFlow model which has been exported from Teachable Machine.
Required files are keras_model.h5 and labels.txt.

Runs in virtual environments based on python 3.11/3.12.
There is currently no TensorFlow version compatible with 3.13.

## Contributions

**Teachable Machine Community**
https://github.com/googlecreativelab/teachablemachine-community/blob/master/snippets/markdown/image/tensorflow/opencv-keras.md

**Stack Overflow**
https://stackoverflow.com/a/79118565

Hack to avoid 
```
ValueError: Unrecognized keyword arguments passed to DepthwiseConv2D: {'groups': 1}
```
