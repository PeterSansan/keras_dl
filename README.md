# Keras 编程实践
---

-  1.[线性回归](./notes/01_linear_regression.ipynb)

-  2.[逻辑回归-MNIST](./notes/02_logistic_regression.ipynb)

-  3.[简单多层感知器-MNIST](./notes/03_net.ipynb)

-  4.[高级多层感知器-MNIST](./notes/04_modern_net.ipynb)：加入了dropout层

-  5.[卷积神经网络-MNIST](./notes/05_convolutional_net.ipynb)

-  6.[自编码器-MNIST重构](./notes/06_autoencoder.ipynb)

-  7.[lstm-imbd情感分类](./notes/07_lstm.ipynb)

-  8.[Bi-lstm-imbd情感分类](./notes/08_bilstm.ipynb)

-  9.[Tensorboard使用](./notes/09_tensorboard.ipynb)

-  10.[模型的保存与加载](./notes/10_save_restore_net.ipynb)

-  11.[CNN-imdb情感二分类](./notes/11_cnn_imdb.ipynb)

-  12.[CNN-lstm-imdb情感二分类](./notes/12_cnn_bilstm.ipynb)

-  13.[lstm不同计算模型比较](./notes/13_batch_batchmark.ipynb)

-  14.[lstm文本生成(字母级)](./notes/14_lstm_generation.ipynb)

 - 15.[使用预训练词向量-CNN文本分类](./notes/15_pretrained_word_embeddings.ipynb)
 
 - 16.[stateful-lstm信号预测](./notes/16_stateful_lstm.ipynb)
 
 - 17.[K折交叉验证](./notes/17_tkfcv.ipynb)
 
 - 18.[实用函数](./notes/util_function.ipynb)
 
本学习库代码与资料参考多修改自官网例子和网上资料，感谢他们的分享：

- https://github.com/leriomaggio/deep-learning-keras-tensorflow
- https://github.com/tgjeon/Keras-Tutorials
- http://keras-cn.readthedocs.io/en/latest/

附加：
- 1、单单从常见例子来看，相比`TensorFlow`，`Keras`的代码的确简单了许多，函数也不会太复杂，但是用久了，确定会不清楚里面的实现细节，所以能有时间与精力写好`TF`，尽量用`TF`好一点。不过'TensorFlow'与'Keras'可以互相嵌套使用，两个联合学是最好的。另外一个框架PyTorch也赞誉不错，也是可以可以选择的框架之一。
- 2、里面使用的数据没有的话会自动下载，无法下载请各自下载数据。
- 3.最新版1.4加入了CudnnLSTM与CudnnGRU,速度比原来的LSTM与GRU快了3~4倍，这个库中的代码并没有更新这一部分。