# Face Detection with OpenCV

This script uses the OpenCV library to detect faces in real-time video captured by a webcam.

## Installation

To use this script, you need to install the following libraries:
- OpenCV
- Logging
- Datetime

You can install these libraries using pip:

```
pip install opencv-python
pip install logging
pip install datetime
```

You also need to download the Haar Cascade classifier XML file for frontal faces from [here](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml) and save it in the same directory as the script.

## Usage

To run the script, simply run the following command:

```
python face_detection.py
```

This will open a window with the video feed from your webcam and rectangles around any detected faces. The script will also log the number of faces detected in each frame in a `webcam.log` file.

To exit the script, press the 'd' key.

## Contributions

Contributions are welcome! If you find any bugs or want to add new features, feel free to submit a pull request or open an issue.
