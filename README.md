# autoencoder

Purpose of this project is:
    Understand, describe and implement the concepts of novelty detection using autoencoders. Apply it to the detection of handwritten digits.
    We have previously developed a computer vision application to recognize handwritten numbers. However, external disturbances on the captured image degrade the performance of our application. The goal of this brief is to use anomaly detection to improve the handwritten digit recognition performance of our application.

​

NB You should not use a Denoising Autoencoder and even less a Variational Autoencoder.

To make test dataset balanced 50/50 normal/anomal, I have to take 10000 image in form of 28*28 and greyscale.