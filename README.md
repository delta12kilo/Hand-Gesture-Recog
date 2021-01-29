# Hand-Gesture-Recog

## File Description

[PalmTracker.py] : Run this file to generate custom datasets. Go into the file and change the name of the directory and make other appropriate changes.

[ResizeImages.py] : Run this file after PalmTracker.py in order to resize the images so that it can be fed into the Convolution Neural Network designed using tensorflow. The network accepts 89 x 100 dimensional image.

[ModelTrainer.ipynb] : This is the model trainer file. Run this file if you want to retrain the model using your custom dataset.

[ContinuousGesturePredictor.py] : Running this file opens up your webcam and takes continuous frames of your hand image and then predicts the class of your hand gesture in realtime.


## Run in terminal: $ python3 ContinuousGesturePredictor.py
### *use python 3.7 or less.(not compatible for python 2.7)


