# Anomaly-Detection-for-Packaging-Machines-Using-Machine-Learning
I wanted to create a repo for my Master thesis so that I don't by any chance lose it. It is also quite nice to have it easily accessible.

I will add the python files also, just have to find the correct files and clean up the code first :S

## Summary:
Tronrud engineering’s packaging machines have occurrences of lost products that exceed the
expectations of their customers, and there is currently no optimal way to detect it. The
goal of this thesis is to use computer vision to solve this problem by developing two different
computer vision models. Where Model 1 will use image comparison to evaluate the similarity
between an input image and a target image to detect product loss. Model 2 are using a
convolutional neural network to extract features from an image. The features extracted in
the network are then used to distinguish if there are any errors or anomalies in the product
in the image. The implementation includes data collection and methods to preprocess the
data such as grayscaling, thresholding, cropping, and rotating before the models use this
data. With the data collected, both Model 1 and Model 2 were able to get 100% prediction
accuracy on the output from the test data. However, for Model 2, the data collected was
limited and the model should be trained and tested on a bigger dataset. Deployment of
the models connected to live data from the machines was a shortcoming in this thesis, but
suggested solutions for deployment and implementation are given for further work.
