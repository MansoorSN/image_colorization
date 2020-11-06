# image_colorization
In this project we will colorize b&amp;w images using Autoencoders

Two models are trained to colorize black and white images. The first models is simple autoencoder and the second model is based on [Deep Koalarization: Image Colorization using CNNs and Inception-ResNet-v2](https://arxiv.org/abs/1712.03400), in this the bottleneck layer of autoencoder is concatenated with the ResNets output layer before the softmax layer. The information provided by fusion of the Resnet helps in the decoder to colorize the images better.In this project, unlike the paper, I have used densenet architecture instead of Resnet.
The paper trains the models on the images in L*a*b image space, but in this project i have used images in the RGB colorspace.Each of these models takes 224x224x1 B&W image as input and outputs a RGB image of 224x224x3.





1.![image1](https://github.com/MansoorSN/image_colorization/blob/main/color1.png)
2.![image2](https://github.com/MansoorSN/image_colorization/blob/main/color2.png)
3.![image3](https://github.com/MansoorSN/image_colorization/blob/main/color3.png)
4.![image4](https://github.com/MansoorSN/image_colorization/blob/main/color4.png)
5.![image5](https://github.com/MansoorSN/image_colorization/blob/main/color5.png)
6.![image6](https://github.com/MansoorSN/image_colorization/blob/main/color6.png)
7.![image7](https://github.com/MansoorSN/image_colorization/blob/main/color7.png)
8.![image8](https://github.com/MansoorSN/image_colorization/blob/main/color8.png)
