# object_detection
# Tensorflow

This directory contains all of the necessary files to construct your very own Tensorflow Object Detection model.

Please follow the steps :

Step 1: Formatting the data
The Open Images dataset is separated into a number of components:

    the image index file
    the bounding box annotations file
    class descriptions
    trainable classes files.

Step 2: Setting up the environment
#download all the required packages and don't forget to install TENSORFLOW.
obtain the models git repository which can be found here git clone https://github.com/tensorflow/models.git

Then configure the model using the faster_rcnn object detection template.

Step 3: Training and Production

Please go through train.py and eval.py available here https://github.com/tensorflow/models/research/object_detection
