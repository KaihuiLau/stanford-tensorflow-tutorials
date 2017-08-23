# tf-stanford-tutorials
This repository contains code examples for the course CS 20SI: TensorFlow for Deep Learning Research. <br>
It will be updated as the class progresses. <br>
Detailed syllabus and lecture notes can be found here http://cs20si.stanford.edu 

这里是斯坦福大学2017年课程，CS 20SI《深度学习研究中的 TensorFlow》所有示例和作业的代码。<br>
课程大纲、课堂笔记和PPT可以在 https://web.stanford.edu/class/cs20si/syllabus.html 找到。<br>

## Quickstart 
1. Install Python and Jupyter notebooks
2. Install TensorFlow
3. [Clone the repository](https://github.com/jiagengliu/stanford-tensorflow-tutorials/archive/master.zip)
4. Find and open examples folder with Jupyter notebook
5. Start with jupyter_02_feed_dict.ipynb

开始学习
1. 安装 Python 和 Jupyter notebooks
2. 安装 TensorFlow
3. [克隆这个项目](https://github.com/jiagengliu/stanford-tensorflow-tutorials/archive/master.zip)
4. 在 Jupyter notebook 中找到 examples 文件夹
5. 打开 jupyter_02_feed_dict.ipynb 开始学习

## Jupyter Notebooks
We are adding Jupyter notebooks for examples and assignments, with names "jupyter\_blah_blah.ipynb" under /assignments and /examples. You can now open up the notebook and execute and debug your TensorFlow code line by line! The converted notebooks are labelled with checks below.<br>
We also added the inline TensorBoard code, a useful tool for visualizing and debugging your graph. See [show_tf_graph.py](https://github.com/jiagengliu/stanford-tensorflow-tutorials/blob/master/examples/show_tf_graph.py) for instructions.
The conversion is still in progress, and we welcome any pull requests!

为了方便学习，我们正在把代码改写为 Jupyter notebooks ，它们位于 assignments 和 examples 文件夹下。通过 Jupyter notebooks，我们可以一行行地实现和调试 TensorFlow 的代码。已经改写的代码会在下面的代码列表中标识。<br>
此外，Jupyter notebook 还支持实时查看 TensorBoard，详情参考 [show_tf_graph.py](https://github.com/jiagengliu/stanford-tensorflow-tutorials/blob/master/examples/show_tf_graph.py)<br>
项目正在进行，欢迎提交pull request！<br> 

## Install TensorFlow 安装 TensorFlow
Windows users often have trouble installing TensorFlow with GPU support on Windows. I have found a useful step-by-step installation. <br>
Windows 用户在安装支持GPU的TensorFlow过程中经常遇到问题，下面这个链接给出了逐步的安装教程：<br>
https://nitishmutha.github.io/tensorflow/2017/01/22/TensorFlow-with-gpu-for-windows.html

## Models include: <br>
Code with checks indicate Jupyter notebooks. 
### In the folder "examples": <br>
- [x] Linear Regression with Chicago's Fire-Theft dataset, 线性回归
- [x] Logistic Regression with MNIST, 逻辑回归
- [x] Word2vec skip-gram model with NCE loss, word2vec语言模型
- [x] Convnets with MNIST, 卷积网络
- [ ] Autoencoder (by Nishith Khandwala), 自编码机
- [ ] Deepdream (by Jon Shlens), 风格迁移
- [ ] Character-level language modeling, 生成语言模型
### In the folder "assignments":
- [ ] Style Transfer, 风格迁移
- [ ] Chatbot using sequence to sequence with attention, 基于seq2seq与注意力机制的聊天机器人
### Misc<br>
- [ ] Examples on how to use data readers, TFRecord
- [ ] Embedding visualization with TensorBoard
- [x] Usage of summary ops
- [ ] Exercises to be familiar with other special TensorFlow ops
- [x] Demonstration of the danger of lazy loading 
- [ ] Convolutional GRU (CRGU) (by Lukasz Kaiser)

### Note (as of July 11, 2017)
I've updated the code to TensorFlow 1.2 and Python3, except the code for chatbot. I will update the code for chatbot soon.
