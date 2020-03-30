gene_classification.py:主要是用参考基因组序列来预测确实基因组序列，为多个序列对一个序列

transformer_stack.py:主要是针对transformer进行堆栈式多个序列对一个序列进行预测的

transformer_encoder.py:主要采用多个transformer编码器来进行下采样编码，然后通过上采样来进行解码

unet.py:主要是采用全卷积自动编码模式来对序列进行图形化处理，最终对图像的噪声规律来进行模型学习

unet_parts.py:为下采样模型和上采样模型的有用代码，能够很好得进行上采样和下采样等操作

train.py:为训练模型的通用函数

predict.py:模型预测用的通用函数，包含多个函数，可以预测单个数据集数据缺失，也可以预测多个数据集缺失。

preprocess.py:用来对数据预处理，得到想要的数据




