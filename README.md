# mnist_tutorial
A tutorial for MNIST handwritten digit classification using sklearn, PyTorch and Keras.

# Code structure
* [`numpy_matplotlib_sklearn.ipynb`](numpy_matplotlib_sklearn.ipynb): for numpy, matplotlib and sklearn.
* [`pytorch.ipynb`](pytorch.ipynb): for pytorch.
* [`keras.ipynb`](keras.ipynb): for keras.
* Reference solution: (not published yet)
    * [`numpy_matplotlib_sklearn_solution.ipynb`](numpy_matplotlib_sklearn_solution.ipynb)
    * [`pytorch_solution.ipynb`](pytorch_solution.ipynb)
    * [`keras_solution.ipynb`](keras_solution.ipynb)

# Requirements
Code tested on following environments, other version should also work:
* linux system (ubuntu 16.04) 
* python 3.6.3
* numpy 1.13.3
* matplotlib 2.1.0
* sklearn 0.19.1
* pytorch 0.4.1
* keras 2.1.2

# For students from SJTU
Please read [HEAR](EE369.md).

# 实验结果

本次实验使用sklearn和pytorch框架进行。

|      | Train accuracy | Test accuracy |
| ---- | -------------- | ------------- |
| Q1   | 97.18%         | 88.00%        |
| Q2   | 81.80%         | 80.00%        |
| Q3   | 97.82%         | 85.90%        |
| Q4   | 95.25%         | 88.20%        |
| Q5   | 99.0%          | 98.6%         |

上述Q4为对SVM的正则项，最大迭代次数，是否求解对偶问题等参数进行调整后的结果。

Q5为使用pytorch搭建的CNN的实验结果，使用的数据集为整个MINST数据集（不同于前四个实验），由于模型收敛较快只训练了三个epoch。

