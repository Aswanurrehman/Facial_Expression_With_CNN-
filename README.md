# Facial Expressions With_CNN

![Emotion_detection](emoition_detection.png)

### Packages need to be installed
- pip install numpy
- pip install opencv-python
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow


### Train Emotion detector
- with all face expression images in the FER2013 Dataset
- command --> python TrainEmotionDetector.py

It will take several hours depends on your processor. (On RYZEN3 processor with 16 GB RAM it took me around 4 hours)
after Training , you will find the trained model structure and weights are stored in your project directory.
emotion_model.json
emotion_model.h5

copy these two files create model folder in your project directory and paste it.

### run your emotion detection test file
python TestEmotionDetector.py


**Model Accuracy & Loss**

<br><br>
<img src="Model Accuracy & Loss.png">
<br><br>
    


**some output pic**

<br><br>
<img src="Output1.png">
<br><br>


<br><br>
<img src="Output2.png">
<br><br>
    

<br><br>
<img src="Output3.png">
<br><br>

<br><br>
<img src="Output4.png">
<br><br>
    

<br><br>
<img src="Output5.png">
<br><br>