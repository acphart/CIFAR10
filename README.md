# CIFAR10
- CIFAR10图片分类
- 数据集下载地址：[cifar-10-python.tar.gz](http://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz)
## 文件说明
- 目前包含4个训练文件，均是 Jupyter notebook 文件，使用 `Keras` 框架。
- 可在下面点击相应的文件名，跳转到`nbviewer`直接查看对应内容，若需要在本地运行，请下载相应文件:)
- 从一个基础CNN架构开始，再通过图像增强，优化模型结构（增加滤波器的数量，使用`Dropout`和`atchNormal`），以及使用更深的网络架构（`ResNet20`-已做，`Inceptionv1-4`-在做，`vgg`-未做，`ResNet50-101-152-1k`-未做），目前准确率已从`0.7065`提升到`0.9118`。
- `img`文件夹里面是4个文件的可视化训练过程图
