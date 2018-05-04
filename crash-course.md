Labels
A label is the thing we're predicting—the y variable in simple linear regression. The label could be the future price of wheat, the kind of animal shown in a picture, the meaning of an audio clip, or just about anything.  

标签
标签是我们预测的东西 - 简单线性回归中的y变量。标签可以是小麦的未来价格，图片中显示的动物的种类，音频剪辑的含义或任何东西

Features
A feature is an input variable—the x variable in simple linear regression. A simple machine learning project might use a single feature, while a more sophisticated machine learning project could use millions of features, specified as:
{X1,X2,X3...Xn}

特征
一个特征是一个输入变量 - 简单线性回归中的x变量。一个简单的机器学习项目可能会使用单一功能，而更复杂的机器学习项目可能会使用数百万个功能，具体如下：

在垃圾邮件检测器示例中，功能可能包括以下内容：

电子邮件中的文字
寄件人地址
发送电子邮件的时间
电子邮件包含短语“一个奇怪的把戏”。

Examples  
An example is a particular instance of data, x. (We put x in boldface to indicate that it is a vector.) We break examples into two categories:

labeled examples  
unlabeled examples

A labeled example includes both feature(s) and the label. That is:  
labeled examples: {features, label}: (x, y)  
An unlabeled example contains features but not the label. That is:  
unlabeled examples: {features, ?}: (x, ?)  
