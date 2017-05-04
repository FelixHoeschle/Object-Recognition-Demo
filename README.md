#Deep Learning Use Case:
##Super market check out with Object Recognition

**Motivation:** There is many tutorials for object recognition with deep learning. Many use of-the-shelf data sets like MNIST or CIFAR.

I wanted to create a use case that works with fresh data and solves a real life problem.

**Use Case:** Most supermarkets sell bakery goods piece by piece. The customer takes a bag and fills it with items. Since the items are not in a standardized package, there is no bar codes.
The cashier then types the code for each item before checking out. The cashier either needs to know all the codes, or look each item up in a booklet. The same is true for vegetables or fruits.

A powerful object recognition algorithm could make this unnecessary.

**Idea:** Taking a video of every item. The video covers all sides of the item. Extracting a large amount of pictures from every item. Every type of item represents one class. Train deep convolutional network to predict class of item.

Implementation: Train model in cloud. Whenever there is a new item, it is sufficient to take one more video. Put it in the right folder. Retrain the model. Since the model lies in the cloud it is available at every cashiers desk.

The model is very accurate, because there is no background noise in the training picture. The cashier can take a picture of the item against a simple piece of paper. There is not background noise then neither.

This could reduce waiting time in the line.

**Possible update:** Segment picture first. This would allow to take a picture of the whole basket instead of scanning single items.

