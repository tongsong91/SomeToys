## 简介
### caffe models prototxt about multimodal
* 关于batchNormalization在caffe中的实现，分为两部分：BatchNorm和Scale两部分,使用时将将conv或Innerproduct中
bias置于Scale中，BatchNorm对无偏置权重乘积进行norm，在Scale中进行放缩并加入bias的学习。  

* BN的作用很明显，未加入之前loss下降较为缓慢，波动较大；加入之后，audio_loss开始大幅度下降，对最终网络的学习
贡献度更大。

### theano 版本　Non-negative Matrix factorize
* 利用theano可gpu加速的原理，提升速度

### mnist手写数字识别：CNN+RNN
* 利用keras实现CNN与RNN的对接，其中使用了`Lambda`函数

### python和matlab版本DCA
* 利用python灵活性，可将其用于深度学习的训练过程中

### scrapy tutorial
* 学习scrapy框架

### porn images classify
* 利用vgg分类性感图片和非性感图片

### txt2xml
* 将txt格式文件转换为voc xml

### pycaffe
* 利用pycaffe实现lenet，prototxt  

### tf_learn  
* 利用tensorflow实现cnn, rnn  

### to_lmdb  
* 自定义lmdb,包括proto编写编译
