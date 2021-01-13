# Face_Detection_Methods

The aim of this project is to detect faces irrespective of whether they are wearing a mask or not.
Initially, several in-built face detection algorithms are tested on images containing both masked and unmasked faces. The output should detect all the human faces present in the image. But I observed that most of the in-built detectors failed to detect faces wearing a mask.

# 1) Haar Cascade Classifier
The input image used is:-

![haar](https://user-images.githubusercontent.com/41821013/104417995-44a73500-559c-11eb-9272-52bea9186179.JPG)

The output we got:-

![haar1](https://user-images.githubusercontent.com/41821013/104418351-c8f9b800-559c-11eb-8001-2503f8cab66b.JPG)

# 2) dlib library HOG based face detector
Input is:-

![dlib](https://user-images.githubusercontent.com/41821013/104418484-f8102980-559c-11eb-9673-9a51ac924ad1.JPG)

This library was not able to detect any face in the provided image.

# 3) dlib library CNN based face detector
The output of CNN based face detector of dlib library:-

![dlib1](https://user-images.githubusercontent.com/41821013/104418674-4fae9500-559d-11eb-8f9c-64c15884f3a5.JPG)

# 4) MTCNN face detector
![mtcnn](https://user-images.githubusercontent.com/41821013/104418910-ae740e80-559d-11eb-9cec-eba553c57d2b.JPG)

# 5) CNN based face classifier
This face classification was built using few layers of CNN and maxpooling. The final result classified whether a given image has a face or not.

# 6) Face Detection with VGG16 model
This model is built using VGG16's few pre-trained layers and the last layer was replaced to get the coordinate values of the bounding box.

![my](https://user-images.githubusercontent.com/41821013/104420235-93a29980-559f-11eb-9b73-48a49af94304.JPG)
