# 深度学习之自然语言处理斯坦福大学CS224n课程集训营

## 课程资料
1. [课程主页](https://web.stanford.edu/class/cs224n/)  
2. [中文笔记](http://www.hankcs.com/nlp/cs224n-introduction-to-nlp-and-deep-learning.html)  
3. [课程视频](https://www.bilibili.com/video/av9595652/)  
4.  实验环境推荐使用Linux或者Mac系统，以下环境搭建方法皆适用:  
    [Docker环境配置](https://github.com/ufoym/deepo)  
    [本地环境配置](https://github.com/learning511/cs224n-learning-camp/blob/master/environment.md)
5. [作业链接](https://github.com/learning511/cs224n-learning-camp/blob/master/Assignmnet.md) 


#### 重要🔥🔥一些的资源：
1. [深度学习斯坦福教程](http://deeplearning.stanford.edu/wiki/index.php/UFLDL%E6%95%99%E7%A8%8B)
2. [廖雪峰python3教程](https://www.liaoxuefeng.com/article/001432619295115c918a094d8954bd493037b03d27bf9a9000)
3. [github教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
4. [莫烦机器学习教程](https://morvanzhou.github.io/tutorials)
5. [深度学习经典论文](https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap.git)
6. [斯坦福cs229代码(机器学习算法python徒手实现)](https://github.com/nsoojin/coursera-ml-py.git)  
7. [本人博客](https://blog.csdn.net/dukuku5038/article/details/82253966)


## 前言
自然语言是人类智慧的结晶，自然语言处理是人工智能中最为困难的问题之一，而对自然语言处理的研究也是充满魅力和挑战的。
通过经典的斯坦福cs224n教程，让我们一起和自然语言处理共舞！也希望大家能够在NLP领域有所成就！

## 知识要求(学习的过程中可以遇到问题后再复习）  
- 了解python基础知识
- 了解高等数学、概率论、线性代数知识
- 了解基础机器学习算法：梯度下降、线性回归、逻辑回归、Softmax、SVM、PAC（先修课程斯坦福cs229 或者周志华西瓜书）
- 具有英语4级水平（深度学习学习材料、论文基本都是英文，**一定要阅读英文原文，进步和提高的速度会加快！！！！**）

## 知识工具
为了让大家逐渐适应英文阅读，复习材料我们有中英两个版本，**但是推荐大家读英文**
### 数学工具
**斯坦福资料：**  
1.[线性代数](http://web.stanford.edu/class/cs224n/readings/cs229-linalg.pdf)  
2.[概率论](http://web.stanford.edu/class/cs224n/readings/cs229-prob.pdf)  
3.[凸函数优化](http://web.stanford.edu/class/cs224n/readings/cs229-cvxopt.pdf)  
4.[随机梯度下降算法](http://cs231n.github.io/optimization-1/)  
**中文资料：**  
[机器学习中的数学基本知识](https://www.cnblogs.com/steven-yang/p/6348112.html)  
[统计学习方法](http://vdisk.weibo.com/s/vfFpMc1YgPOr)  
**大学课本**  

### 编程工具 
**斯坦福资料：**  
[Python复习](http://web.stanford.edu/class/cs224n/lectures/python-review.pdf)  
**中文资料：**  
[莫烦python教程](https://morvanzhou.github.io/tutorials/python-basic/basic/)  
[廖雪峰python3教程](https://www.liaoxuefeng.com/article/001432619295115c918a094d8954bd493037b03d27bf9a9000)  

## 学习安排
每周具体时间划分:  
     - 1部分安排周一到周二  
     - 2部分安排在周四到周五  
     - 3部分安排在周日  
     - 4部分作业是本周任何时候空余时间    
     - 周日晚上提交作业运行截图  
     - 周三、周六休息^_^     
### Week1
1. 自然语言处理和深度学习简介  
- **课件:** [lecture01]()
- [观看视频1](https://www.bilibili.com/video/av30326868/?spm_id_from=333.788.videocard.0)
- **学习笔记**：[自然语言处理与深度学习简介](http://www.hankcs.com/nlp/cs224n-introduction-to-nlp-and-deep-learning.html)

2. 词的向量表示1：
- **课件:** [lecture02]() 
- [观看视频2](https://www.bilibili.com/video/av30326868/?p=2)
- **学习笔记**：[wordvecotor](http://www.hankcs.com/nlp/word-vector-representations-word2vec.html)

3. 论文导读：一个简单但很难超越的Sentence Embedding基线方法
- **课件:** [paper1]() 
- **论文笔记**：[Sentence Embedding](http://www.hankcs.com/nlp/cs224n-sentence-embeddings.html)
4. 作业：Assignment 1.1-1.2  
- 1.1 Softmax 算法
- 1.2 Neural Network Basics 基础实现
### Week2
1.  高级词向量表示：word2vec 2
- **课件:** [lecture03]()
- [观看视频3](https://www.bilibili.com/video/av30326868/?p=3)
- **学习笔记**： [word2vec-2](http://www.hankcs.com/nlp/cs224n-advanced-word-vector-representations.html)

2. Word Window分类与神经网络
- **课件:** [lecture04]() 
- [观看视频4](https://www.bilibili.com/video/av30326868/?p=4)
- **学习笔记**：[Word Window分类与神经网络](http://www.hankcs.com/nlp/cs224n-word-window-classification-and-neural-networks.html)

3. 论文导读：词语义项的线性代数结构与词义消歧
- **课件:** [paper2]()  
- **论文笔记：**[词语义项的线性代数结构与词义消歧](http://www.hankcs.com/nlp/cs224n-word-senses.html)
4. 作业：Assignment 1.3-1.4 
- 1.3 word2vec 实现
- 1.4 Sentiment Analysis 情绪分析  
### Week3
1. 反向传播与项目指导：Backpropagation and Project Advice
- **课件:** [lecture05]()
- [观看视频5](https://www.bilibili.com/video/av30326868/?p=5)
- **学习笔记:** [反向传播与项目指导](http://www.hankcs.com/nlp/cs224n-backpropagation-and-project-advice.html)

2. 依赖解析：Dependency Parsing 
- **课件:** lecture06
- [观看视频6](https://www.bilibili.com/video/av30326868/?p=6)
- **学习笔记:** [句法分析和依赖解析](http://www.hankcs.com/nlp/cs224n-dependency-parsing.html)

3. 论文导读：高效文本分类
- **课件:** [paper]
- **论文笔记：**[高效文本分类](http://www.hankcs.com/nlp/cs224n-bag-of-tricks-for-efficient-text-classification.html)
4. **作业** Assignment 2.2
- 2.2 Neural Transition-Based Dependency Parsing 基于神经网络的依赖分析

### Week4
1. TensorFlow入门
- **课件:** lecture07
- [观看视频](https://www.bilibili.com/video/av30326868/?p=7)
- **学习笔记**：[TensorFlow](http://www.hankcs.com/nlp/cs224n-tensorflow.html)

2. RNN和语言模型
- **课件:** lecture08
- [观看视频](https://www.bilibili.com/video/av30326868/?p=8)
- **学习笔记**：[RNN和语言模型](http://www.hankcs.com/nlp/cs224n-rnn-and-language-models.html)

3. 论文导读：词嵌入对传统方法的启发
- **课件:** [paper]
-  **论文笔记：**[词嵌入对传统方法的启发](http://www.hankcs.com/nlp/cs224n-improve-word-embeddings.html)
4. 作业：Assignment 2.1  
- 2.1 Tensorflow Softmax 基于TensorFlow的softmax分类

### Week5
1.  高级LSTM及GRU：LSTM and GRU
- **课件:** [lecture09]()
- [观看视频](https://www.bilibili.com/video/av30326868/?p=9)
- **学习笔记**： [高级LSTM及GRU](http://www.hankcs.com/nlp/cs224n-mt-lstm-gru.html)

2. 期中复习
- **课件:** [lecture-mid]()
- [观看视频](https://www.youtube.com/watch?v=2DYxT4OMAmw&list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6&index=10)

3. 论文导读：基于转移的神经网络句法分析的结构化训练
- **课件:** [paper]
-  **论文笔记：**[基于转移的神经网络句法分析的结构化训练](http://www.hankcs.com/nlp/cs224n-syntaxnet.html)
4. 作业：Assignment 2.3
- 2.3 Recurrent Neural Networks: Language Modeling 循环神经网络语言建模

### Week6
1.  机器翻译、序列到序列、注意力模型：Machine Translation, Seq2Seq and Attention 
- **课件:** lecture10
- [观看视频](https://www.bilibili.com/video/av30326868/?p=10)
- **学习笔记**： [机器翻译、序列到序列、注意力模型]http://www.hankcs.com/nlp/cs224n-9-nmt-models-with-attention.html)

2. GRU和NMT的进阶
- **课件:** lecture11
- [观看视频](https://www.bilibili.com/video/av30326868/?p=11)
- **学习笔记**：[GRU和NMT的进阶](http://www.hankcs.com/nlp/cs224n-gru-nmt.html)

3. 论文导读：谷歌的多语种神经网络翻译系统
- **课件:** [paper]
-  **论文笔记：**[谷歌的多语种神经网络翻译系统](http://www.hankcs.com/nlp/cs224n-google-nmt.html)
4. 作业：Assignment 3.1
- 3.1  A window into NER

### Week7
1.  语音识别的end-to-end模型
- **课件:** lecture12
- [观看视频](https://www.bilibili.com/video/av30326868/?p=12)
- **学习笔记**： [语音识别的end-to-end模型](http://www.hankcs.com/nlp/cs224n-end-to-end-asr.html)

2. 卷积神经网络:CNN
- **课件:** lecture13
- [观看视频](https://www.bilibili.com/video/av30326868/?p=13)
- **学习笔记**：[卷积神经网络](http://www.hankcs.com/nlp/cs224n-convolutional-neural-networks.html)

3. 论文导读：谷歌的多语种神经网络翻译系统
- **课件:** [paper]
-  **论文笔记：**[读唇术](http://www.hankcs.com/nlp/cs224n-lip-reading.html)
4. 作业：Assignment 3.2
- 3.2  Recurrent neural nets for NER


### Week8
1.  Tree RNN与短语句法分析
- **课件:** lecture14
- [观看视频](https://www.bilibili.com/video/av30326868/?p=14)
- ****学习笔记****： [Tree RNN与短语句法分析](http://www.hankcs.com/nlp/cs224n-tree-recursive-neural-networks-and-constituency-parsing.html)

2. 指代消解
- **课件:** lecture15
- [观看视频](https://www.bilibili.com/video/av30326868/?p=15)
- ****学习笔记****：[指代消解](http://www.hankcs.com/nlp/cs224n-coreference-resolution.html)

3. 论文导读：谷歌的多语种神经网络翻译系统
- **课件:** [paper]
-  **论文笔记：**[Character-Aware神经网络语言模型](http://www.hankcs.com/nlp/cs224n-character-aware-neural-language-models.html)
4. **作业**：Assignment 3.3
- 3.3  Grooving with GRUs

### Week9
1.   DMN与问答系统
- **课件:** lecture16
- [观看视频](https://www.bilibili.com/video/av30326868/?p=16)
- ****学习笔记****： [DMN与问答系统](http://www.hankcs.com/nlp/cs224n-dmn-question-answering.html)

2.  NLP存在的问题与未来的架构
- **课件:** lecture17
- [观看视频](https://www.bilibili.com/video/av30326868/?p=17)
- ****学习笔记****：[指代消解](http://www.hankcs.com/nlp/cs224n-nlp-issues-architectures.html)

3. **论文导读**：神经网络自动代码摘要
- **课件:** [paper]
-  **论文笔记：**[神经网络自动代码摘要](http://www.hankcs.com/nlp/cs224n-summarizing-source-code.html)
6. 比赛（待定）

### Week10 
1.   DMN与问答系统
- **课件:** lecture16
- [观看视频](https://www.bilibili.com/video/av30326868/?p=16)
- ****学习笔记****： [DMN与问答系统](http://www.hankcs.com/nlp/cs224n-dmn-question-answering.html)

2. **论文导读**：neural-turing-machines
- **课件:** [paper]
-  **论文笔记：**[neural-turing-machines](http://www.hankcs.com/nlp/cs224n-neural-turing-machines.html)

3 **论文导读**： 深度强化学习用于对话生成
- **课件:** [paper]
-  **论文笔记：**[深度强化学习用于对话生成](http://www.hankcs.com/nlp/cs224n-deep-reinforcement-learning-for-dialogue-generation.html)

 ### Week11
 1. **论文导读**：图像对话
- **课件:** [paper]
- **论文笔记：**[图像对话](http://www.hankcs.com/nlp/cs224n-visual-dialog.html)
 2. 比赛复盘  
 3. 期末总结  
