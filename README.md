# DnCNN
Date:2021/12/27

本项目为做毕设之前学习pytorch进行图像去噪处理的复现练习

DnCNN为经典图像去噪算法，论文地址为：https://ieeexplore.ieee.org/abstract/document/8554135

其网络结构如下：
![dncnn](https://user-images.githubusercontent.com/53635655/184607227-32878cb1-a5c4-4d84-86a4-0e4f3dd59d28.png)

复现的材料和数据集下载地址见ipynb文件中有详细描述与说明。
训练使用pytorch，平台采用谷歌colab进行训练。


Date：2022/3/15

在后续实验过程中发现DnCNN在红外图像非均匀性校正上只能做到对图像的PSNR等图像质量上的提升但无法对于图像非均匀性上有所作用
