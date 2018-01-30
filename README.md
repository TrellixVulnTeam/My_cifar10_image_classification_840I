# My_cifar10_image_classification
本项目对 CIFAR-10 数据集进行图像分类，该数据集包含飞机，狗，猫等类型的图片。  
首先对数据集进行预处理，然后用卷积神经网络对所有样本进行训练，训练前先将图像归一化（normalize），对标签进行独热编码（one-hot encode the labels），然后建立卷积层、最大池化层和全连接层。最后可以看到该模型对样本图像作出的预测结果
