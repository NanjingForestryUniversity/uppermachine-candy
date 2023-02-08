# 上位机
糖果分选机的上位机基于Qt4开发，主要功能包括控制Hikvison工业相机、参数配置、人机交互、下位机通信、Python识别进程通信等功能。上位机硬件环境为Nvidia Jetson Xaviar，包括1个网口，2个usb接口、1个hdmi接口。软件环境为Ubuntu18.04。具体环境配置过程可参考`v1.0-beta1`这个版本中release的文件教程。

经过多次本地修改，目前上位机代码对应下位机版本为[b01-d0.2-h1.1-p1.0-s1.0-a1.1](https://github.com/NanjingForestryUniversity/lowermachine/tree/b01-d0.2-h1.1-p1.0-s1.0-a1.1)

文件说明：
- deploy.pdf：上位机环境搭建及程序部署说明，包括相机如何安装和配置
- grap-image.pdf：采集糖果的图像到U盘，用于建立数据集
- change-model.pdf：通过u盘导入模型，用于更新或更换糖果分选机分选的糖果种类等
- deploy-res.zip：deploy.pdf文档中所需的文件，包括yolov5环境文件夹，海康威视相机SDK安装包

程序具体工作原理三言两语介绍不完，有问题或者有兴趣的可以提问。
# 作者
丁坤

无情的补丁修复机器：程磊
