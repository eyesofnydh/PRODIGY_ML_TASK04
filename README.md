
---

# Gesture Recognition

Recognizing "Hand Gestures" using OpenCV and Python.

## Libraries needed

* `cv2`
* `imutils`
* `numpy`
* `sklearn`

## Usage

### 1. `segment.py`

This script captures real-time video from your webcam, segments the hand region from the background, and displays the thresholded (binary) image. It's useful for visualizing how the hand is being segmented and fine-tuning the segmentation process.

To run the script:

```sh
python segment.py
```

### 2. `recognize.py`

This script captures real-time video from your webcam, segments the hand region, and then uses a pre-trained machine learning model to recognize and classify the gesture. The recognized gesture is displayed on the video feed.

To run the script:

```sh
python recognize.py
```

### 3. `recognize-image.py`

This script takes an image file as input, segments the hand region, and uses a pre-trained machine learning model to recognize and classify the gesture in the image. The result is displayed on the image.

To run the script:

```sh
python recognize-image.py <image-path>
```

Replace `<image-path>` with the path to the image file you want to use for gesture recognition.

---
