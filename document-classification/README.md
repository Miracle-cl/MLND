# 文档分类

## 描述
*对20类新闻包实现精准分类*

## 开发文档说明：
* text_classification_sklearn.ipynb：包含tf-idf和LDA文本表示算法，以及sklearn库中常用的机器学习分类算法，运行时间大约在2小时左右。
* text_rnn_tf.ipynb：包括文本预处理以及使用tensorflow建模，运行时间大约在2小时左右。
* text_classification_keras.ipynb：包括3中keras建模以及结果可视化处理，运行时间大约也是2-3小时。
* pretrained_glove_keras.ipynb：采用预训练的glove词向量，然后使用CNN，RNN以及RCNN算法进行分类，运行时间较长，具体见文档。
* text_han_keras.ipynb：采用预训练的glove词向量，然后使用层次注意力模型进行分类，keras后端为theano。

## 使用的数据集为：
* [20Newsgroups](http://qwone.com/~jason/20Newsgroups/), 直接从[sklearn](http://scikit-learn.org/stable/datasets/twenty_newsgroups.html)中导入
* [glove.6B.100d.txt](https://nlp.stanford.edu/projects/glove/)

## 使用的软件和库包括：
* python 3.6.1
* numpy 1.12.1
* sklearn 0.19.1
* matplotlib 2.0.2
* tensorflow 1.1
* theano 1.0.1
* keras 2.1.2
* nltk 3.2.5
* gensim 3.0.1
