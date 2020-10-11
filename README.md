# FaceDetection using HaarCascade
## Goal 
* Basics of face detection
* Extend the same for eye detection
### Basics
1. Object Detection using Haar feature-based cascade classifiers is an effectiv object detection method proposed by Paul Viola and Michael Jones in their paper,
"Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001. 
2. It is a machine learning based approach where a cascade functions is trained from a lot of positive and negative images. 
It is then used to detect objects in other images.
### Haar-cascade Detection in OpenCV
1. OpenCV already contains many pre-trained classifiers for face, eyes, smile etc., 
2. Those XML files are stored in *opencv/data/haarcascades/* folder. 
3. Firstly we need to load the required XML classifers. Then load our image (or video) in grayscale mode.
### Resource 
https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_objdetect/py_face_detection/py_face_detection.html
