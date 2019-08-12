# Faster R-CNN for Signature and Annotation detection using Keras
## Introduction
The original code of Keras version of Faster R-CNN I used was written by yhenon (resource link: GitHub .) He used the PASCAL VOC 2007, 2012, and MS COCO datasets. I applied configs different from his work to fit my dataset and I removed unuseful code.

## Project Structure
Use the sign_detection_train_vgg.ipynb file to train on any dataset of your choice. Define the annotaion and bounding box coordinates in the annotaion.txt file. It uses a VGG 16 model. For future scope You can add RESNET and other models. Use the sign_detection_test_vgg.ipynb file to test your images. During Training we keep updating and saving the weights, incase of any system failure or power cut, our trained data would still be saved to the nearest epoch.

## Requirements
1) python 3.6+ Link to download and install (https://www.python.org/downloads/)
2) You will need jupyter notebook to open the .ipynb files. (On command line type pip install jupyter)
3) Tensorflow(if you have gpu the you could use a tensorflow-gpu version). (On command line type pip install tensorflow or tensorflow-gpu)
4) Keras (On command line type pip install keras)
5) Numpy (On command line type pip install numpy)
6) Pandas (On command line type pip install pandas)

You Can use this model and make it learn the classes you define. 
