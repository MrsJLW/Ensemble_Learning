# Ensemble_Learning

一．题目要求
使用5-6个模型（可以是knn svm 贝叶斯等等）用投票的方式做一个集成学习对MNIST数据集进行分类。
二．题目分析
本实验中我才用的模型有线性SVM，非线性（多项式）SVM，KNN算法，朴素贝叶斯估计和神经网络5个模型，根据五个模型的分类结果进行投票，票数多的为最终分类，若票数均一样，则任取一个模型的分类结果。
三.文档
首先运行Bayes.py,KNN.py,Neural_Network.py,SVM.py生成五组模型训练结果，根据训练模型对测试集进行测试，最后运行Ensemble_Learning用投票方式决定最后结果