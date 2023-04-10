# Statistical-Methods-for-Machine-Learning
Open notebook directly at:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KTNlGpa_7WjzlpImmxKvZXbQnu0DKm9Y)

Convolutional Neural Networks (CNN) are usually used for image classification. CNN is a regular Neural Network (NN) with added layers before it.
Those layers are introduced to reduce the number of parameters of regular NN
and to reduce overfitting. The goal is to classify pictures of cats and dogs and
in this project, we will see different models, starting from the simplest one and
moving to the more complex models, with aim to reach high accuracy and low
loss. After choosing the best model according to the accuracy and log loss,
the model’s hyperparameters are tuned, and then the model is validated using
5-Fold cross-validation. The final model is evaluated on the testing set, and
also on 20 self-made pictures of cats and dogs.


Neural networks are algorithms (a family of algorithms) created to imitate the human
brain. They are based on interconnected neurons depending on the type of network,
and there are many types of them, but generally, can be divided into three classes:
Fully connected neural networks, Convolutional neural networks, and Recurrent neural
networks. In this project, we will use the first two types. Our goal is to do binary
classification with high accuracy, and as we will see it is not enough to use just fully
connected neural networks. It needs extensions such as convolution layers to reach more
satisfying results with image classification. Convolutional neural networks (CNN) are
subclass of neural networks that have at least one convolution layer. They are specifically
made to process pixel data and are used in processing and image recognition. We use
them to obtain local information, for instance, from a neighbor pixel in an image, and
also to reduce the complexity of the model in terms of the number of parameters. A fully
connected layer treats all features as independent from one another. A convolutional
layer treats features nearby in space as connected by clustering them into smaller groups.
In essence, they are trying to introduce information (spatial positioning) into the layer
that would not be present otherwise.
