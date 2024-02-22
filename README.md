# emotiondetection-using-FER2013
An emotion recognition system based on the Facial expressions and able to detect both from an video and  open camera feed

###packages to be installed 
- pip install numpy
- pip install opencv-python
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow

- pip install requirements.txt

# To download dataset
- https://www.kaggle.com/msambare/fer2013

# To Train the model 
- python TrainEmotionDetector.py

It will take several hours depends on your processor. 
After Training , you will find the trained model structure and weights in the directory but in this project it is speicified

# To run emotion detection file
- python TestEmotionDetector.py
