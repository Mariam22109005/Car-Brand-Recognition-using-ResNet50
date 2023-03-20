# Car-Brand-Recognition-using-ResNet50
This is a recognition system that predict of car brand  

![image](https://user-images.githubusercontent.com/125149919/226267853-9895312d-7533-4f29-bf06-b241d6c60d12.png)
# RESNET50
********A convolutional neural network with 50 layers is called ResNet-50. A common neural network that serves as the foundation for many computer vision applications is called ResNet, short for Residual Networks. The main innovation with ResNet was that it enabled us to train very deep neural networks with more than 150 layers. In their 2015 computer vision research paper titled "Deep Residual Learning for Image Recognition," Kaiming He, Xiangyu Zhang, Shaoqing Ren, and Jian Sun initially presented this novel neural network.**

******The "Vanishing Gradient Issue" is a serious drawback for convolutional neural networks. Gradient value greatly reduces during backpropagation, therefore weights scarcely change at all. ResNet is employed to get around this. It uses the "SKIP CONNECTION" feature.************

# The main architecture of RESNET50

![image](https://user-images.githubusercontent.com/125149919/226268392-2b3ce060-1351-4dd8-827c-bc7c2fa40a0b.png)



# Skip Connection :— 
*Adding the original input to the output of the convolutional block*


![image](https://user-images.githubusercontent.com/125149919/226268662-597d3688-67d1-4da9-b156-f63970602d0b.png)


*All algorithms train on the output ‘Y’ but, ResNet trains on F(X). In simpler words, ResNet tries to make F(X)=0 so that Y=X.*

 source :  <a href = "https://blog.devgenius.io/resnet50-6b42934db431">read more</a>
