## Deep Learning Demo:
### Object Recognition for supermarket checkout

#### Summary
This demo applies a deep convolutional neural network for object recognition.
It could be used to speed up supermarket checkouts or replace barcode scanners.

#### The Idea
When buying fruits or bakery goods in supermarkets checkout can be rather inefficient.
Items of this kind are often sold by the piece and its not possible to print bar codes on them.
The cashier has to search for the code that fits the item in a booklet which takes time.

#### This Demo
To solve the problem with deep learning requires a dataset that contains images of every product, photographed from every angle. For this demo I bought three items in the local supermarket. I took a video of each item with my mobile phone. 

The iPython notebook contained in this demo conducts the following steps:
- Extract pictures from the videos
- Store the pictures in folders that are named after the videos
- Train deep convolutional network for object recognition

#### How this could work in real life
The demo includes several advantages:
- Easy to train:
 Make a video of each product. Give it a name. Run the iPython notebook.
 Result: Trained model, ready to classify each Prodcut

- Scaleabilty:
 The model can be trained once for all stores. The model can reside in the cloud.

- Flexibility:
 This exact model can be used for everything from bakery goods to fruits, candy or screws
 
#### Why this works
The video clip can be shot infront of a controlled environment. The cashier can take the picture the same way.
This makes the object recognition method very reliable.

#### How well it is working so far

The version that is currently uploaded here is trained on 3 different bakery items that look very similar.
It achieves 100% accuracy. The reason is that environment is very controlled, compared to most object recognition implementations.

#### Next steps
Add image segmentation: If object segmentation is added to the code, it would be possible to do checkout by simply taking a picture of the entire shopping basket.
