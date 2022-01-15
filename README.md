# Facial Recognition with Keras, FaceNet and Inception model using Siamese Networks and transfer learning. 

This repo contains one notebook, where I use Keras and customize a pretrained Inception model which I then use for building a Siamese Network that performs face recognition.

Facial recognition is the task of looking at an image showing the face of a person and being able to identify that person from a collectiong of images already present in our database.

    - the system has a database of n persons (images for each of them, most often just 1)
    - the system receives as input a new, unseen, image of a person
    - and should be able to recognize if this is any of the n persons already present in the database.

To build such a system, I'm using:

    - Siamese Networks
    - the Triplet loss function, described in the FaceNet article by Schroff et al 2015
    - Transfer learning, to save training time by making use of pretrained convolutional neural networks.
    - Keras interface for the TensorFlow library and Keras Applications pretrained models.


<b>How to use this repo:</b>
Open the Jupyter Notebook in this folder. You can clone it, download it or just read it here. 
There is also a link at the top of the Notebook which takes you to the same Notebook on Kaggle.
