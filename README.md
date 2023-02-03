# OpenMMLabAI--1
OpenMMLabAI实战营作业1

[📘 Documentation](https://mmclassification.readthedocs.io/en/latest/)

实验基于ImageNet-1k作为pretrained进行finetuned
[预训练权值下载]（https://github.com/open-mmlab/mmclassification）
## 基础实验
使用mmclassification对5种花进行分类

## 实验设备
NVIDIA GeForce GTX 1080 Ti

##  flower 数据集

#### 数据集介绍

flower 数据集包含 5 种类别的花卉图像：雏菊 daisy 588张，蒲公英 dandelion 556张，玫瑰 rose 583张，向日葵 sunflower 536张，郁金香 tulip 585张。

数据集下载链接：

- 国际网：https://www.dropbox.com/s/snom6v4zfky0flx/flower_dataset.zip?dl=0
- 国内网：https://pan.baidu.com/s/1RJmAoxCD_aNPyTRX6w97xQ 提取码: 9x5u


### flower

|        Model        |  Top-1 (%) | Top-5 (%) | 
| :-----------------: |  :-------: | :-------: |
| MobileNetV2 |   95.2797   |   100.00   | 
| ResNet50 |   93.8811   |   100.00   | 


## 进阶实验
使用mmclassification对CIFAR-10进行分类

## CIFAR-10数据集
🚥图像分类数据集：CIFAR-10：https://opendatalab.com/CIFAR-10 562M

### CIFAR-10
|        Model        |  Top-1 (%) | Top-5 (%) | 
| :-----------------: |  :-------: | :-------: |
| MobileNetV2 |   84.4500   |   99.4400   | 
| ResNet50 |   82.6700   |   99.2400  | 

所有的实验都提供了权值以供复现
CIFAR-10 ResNet50权值
链接：https://pan.baidu.com/s/1inUEZJaVAoPAZ0qI-ZlfTQ 
提取码：qs06 

