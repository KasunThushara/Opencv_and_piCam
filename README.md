# Opencv_and_piCam
This is for bullseye OS . How Opencv and Picam working 

First, clone this Git repo onto your Raspberry Pi like this:
```sh
git clone https://github.com/KasunThushara/Opencv_and_piCam
```
### captureimage.py is for test the picam with video stream.
### saveimage.py is for save a still picture by pressing 's'.
### facedetection_pi.py is for detect a face.
## To perform object detection follow this.

Then use our script to install a couple Python packages, and download the EfficientDet-Lite model:

```sh
cd https://github.com/KasunThushara/Opencv_and_piCam/ObjectDetection
```
### The script install the required dependencies and download the TFLite models.

```sh
sh setup.sh
```
### run the model

```sh
python3 detect_mod.py
```



