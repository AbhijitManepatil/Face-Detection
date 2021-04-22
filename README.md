# Face-Detection
This project represent the number of people count from the image on the basis of face as a parameter.



As a result we will recive the following list from MTCNN()

    [{'box': [305, 13, 33, 44],
    'confidence': 0.9999947547912598,
    'keypoints': {'left_eye': (316, 30),
    'right_eye': (332, 32), 
    'nose': (325, 40),
    'mouth_left': (314, 45), 
    'mouth_right': (331, 46)}}]
    
Box: will gives the values of pixels.

Confidance: is about the score of face detection.

Keypoints: are the other information about the face parameters.


# requirements
* pip install opencv-python
* pip install mtcnn
* pip install tensorflow
* pip install matplotlib

> You can test and execute face detection with jupyter notebook.
> above notebook tested on ubuntu 20.0

>You can easily find the face detected and count the faceces with a 1min of code.

> You can test with your own image input and have a fun.

# Ref:
https://github.com/ipazc/mtcnn
