# Style-Transfer-with-Deep-Neural-Networks

Recreating a style transfer method that is outlined in the paper, Image Style Transfer Using Convolutional Neural Networks, by Gatys in PyTorch.

In this paper, style transfer uses the features found in the 19-layer VGG Network, which is comprised of a series of convolutional and pooling layers, and a few fully-connected layers. In the image below, the convolutional layers are named by stack and their order in the stack. Conv_1_1 is the first convolutional layer that an image is passed through, in the first stack. Conv_2_1 is the first convolutional layer in the second stack. The deepest convolutional layer in the network is conv_5_4.
<img width="528" alt="vgg19_convlayers" src="https://user-images.githubusercontent.com/30608533/49687071-afa8f680-fb0e-11e8-8ef1-39ca4b486c09.png">

Google Colab is used for training our Deep Learning model with GPU support.
