                                                              **Face Recognition Using FaceNet**
                                                                
This repository implements a face recognition system using the FaceNet model, leveraging pre-trained weights for efficient facial embedding generation. It combines face recognition with liveness detection, suitable for real-time applications such as access control and security systems.

**Features**
Pre-Trained Model: Uses a pre-trained FaceNet model to avoid computationally expensive training from scratch.
Face Embeddings: Converts facial images into embeddings to compare and identify individuals.
Real-Time Recognition: Implements live face recognition using a webcam feed.
Face Detection: Employs Haar Cascade for face detection in images and videos.
Extensibility: The modular design allows easy addition of new faces to the database.

**Setup and Dependencies**

Prerequisites
Python 3.7 or above
The following Python libraries:
1. tensorflow2.
2. keras
3. numpy
4. opencv-python
5. matplotlib
6. pandas
