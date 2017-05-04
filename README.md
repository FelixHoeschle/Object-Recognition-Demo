## Deep Learning Demo:
### Object Recognition 

#### Summary
This demo utilizes a deep convolutional neural network for object recognition. The objects that are to be classified are filmed from all sides. The neural network is fed by extracting pictures from the video.

#### Motivation
- Create deep learning demo that doesn't use MNIST, CIFAR-10 etc.
- End-to-End demo that deals with everything from data creation to consumption
- Outline real life application

#### Real life application
The concept can be used to replace barcode scanners. The current version is trained on a sample of supermarket items that do not have barcodes.

#### How the demo works
- Videos of items that should be classified are in the folder 'input_videos'
- Running the iPython notebook extracts pictures from the videos and stores them in the folder 'create classes'
- CNN is trained on the extracted pictures

#### Further plans
- Apply Mask R-CNN to do checkout with one snapshot
- Reproduce Keras code in TensorFlow

