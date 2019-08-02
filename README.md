# CIFAR10
- CIFAR10图片分类
- 数据集下载地址：[cifar-10-python.tar.gz](http://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz)
## 文件说明
- 目前包含4个训练文件，均是 Jupyter notebook 文件，使用 `Keras` 框架。
- 可在下面点击相应的文件名，跳转到`nbviewer`直接查看对应内容，若需要在本地运行，请下载相应文件:)
- 从一个基础CNN架构开始，再通过图像增强，优化模型结构（增加滤波器的数量，使用`Dropout`和`atchNormal`），以及使用更深的网络架构（`ResNet20`-已做，`Inception v1-4`-在做，`vgg`-未做，`ResNet50-101-152-1k`-未做），目前准确率已从`0.7065`提升到`0.9118`。
### 训练文件
1. [Keras_CIFAR10_CNN_simple.7065.ipynb](https://nbviewer.jupyter.org/github/acphart/CIFAR10/blob/master/Keras_CIFAR10_CNN_simple.7065.ipynb)
2. [Keras_CIFAR10_CNN_Dropout_BN.7885.ipynb](https://nbviewer.jupyter.org/github/acphart/CIFAR10/blob/master/Keras_CIFAR10_CNN_Dropout_BN.7885.ipynb)
3. [Keras_CIFAR10_CNN_DA_lr.8436.ipynb](https://nbviewer.jupyter.org/github/acphart/CIFAR10/blob/master/Keras_CIFAR10_CNN_DA_lr.8436.ipynb)
4. [Keras_CIFAR10_ResNet20.9118.ipynb](https://nbviewer.jupyter.org/github/acphart/CIFAR10/blob/master/Keras_CIFAR10_ResNet20.9118.ipynb)
