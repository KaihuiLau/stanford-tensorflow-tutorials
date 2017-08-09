# tf-stanford-tutorials
This repository contains code examples for the course CS 20SI: TensorFlow for Deep Learning Research. <br>
It will be updated as the class progresses. <br>
Detailed syllabus and lecture notes can be found here http://cs20si.stanford.edu <br>
这里是斯坦福大学2017年课程， CS 20SI: 深度学习研究中的 TensorFlow 的所有例子和作业的代码。<br>
课程大纲和课堂笔记可以在 http://cs20si.stanford.edu 找到。<br>

# Jupyter Notebooks
We are adding Jupyter notebooks for examples and assignments, with names "jupyter\_blah_blah.ipynb" under /assignments and /examples. You can now open up the notebook and execute and debug your TensorFlow code line by line! <br>
We also added the inline TensorBoard code, a useful tool for visualizing and debugging your graph. See [show_tf_graph.py](https://github.com/jiagengliu/stanford-tensorflow-tutorials/blob/master/examples/show_tf_graph.py) for instructions.
The conversion is still in progress, and we welcome any pull requests!<br>
为了方便学习，我们正在把代码转换为 Jupyter notebooks ，它们位于 assignments 和 examples 文件夹下。通过 Jupyter notebooks 可以一行行地实现和调试 TensorFlow 的代码。<br>
此外，Jupyter notebook 还支持实时查看 TensorBoard，详情请看 [show_tf_graph.py](https://github.com/jiagengliu/stanford-tensorflow-tutorials/blob/master/examples/show_tf_graph.py)<br>
项目依然在进行中，欢迎提交pull request！<br>

# Note (as of July 11, 2017)
I've updated the code to TensorFlow 1.2 and Python3, except the code for chatbot. I will update the code for chatbot soon.

## Models include: <br>
### In the folder "examples": <br>
Linear Regression with Chicago's Fire-Theft dataset<br>
Logistic Regression with MNIST<br>
Word2vec skip-gram model with NCE loss<br>
Convnets with MNIST<br>
Autoencoder (by Nishith Khandwala)<br>
Deepdream (by Jon Shlens)<br>
Character-level language modeling <br>
<br>
### In the folder "assignments":<br>
Style Transfer<br>
Chatbot using sequence to sequence with attention<br>
<br>
## Misc<br>
Examples on how to use data readers, TFRecord<br>
Embedding visualization with TensorBoard<br>
Usage of summary ops<br>
Exercises to be familiar with other special TensorFlow ops<br>
Demonstration of the danger of lazy loading <br>
Convolutional GRU (CRGU) (by Lukasz Kaiser)



