## P2：交通标志识别

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

## 简介

在本项目中，你会使用你所学到的深度学习知识和卷积神经网络进行交通标志识别。你会训练并验证一个可以识别[德国交通标志数据集](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset)的一个模型。训练好了以后，你还会使用网络上的德国交通标志图像来测试你的模型。

我们会在 Jupyter Notebook 上完成我们的项目，所以你需要先安装好 [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit)。

我们也需要写一个项目报告，[点此查看模板](writeup_template.md)。你可以提交 pdf 文件或者 markdown 文件。

为了通过本项目，你需要提交三个文件：

* 完整运行且无错误的 notebook 代码
* notebook 导出的 html 文件
* 一份 pdf 或者 markdown 格式的报告

## 如何编写更好的报告

一份好的报告首先应该满足每一条[审阅标准](https://review.udacity.com/#!/rubrics/481/view)，你需要详细描述你的每个步骤，必要时可以引用代码块或者外部链接。最好在报告中添加一些图片来演示你的算法能做些什么。

还有一点之前已经提到了，一定要写得简洁！我们不是在写书，所以你只需要简洁地介绍你的算法是如何满足评审要求的，并且附上相关的代码。

报告不是必须要用 markdown 来写，比如你可以用 word 来写报告。如果你想用其他方式写报告，只要你最后提交的文件是 pdf 格式的文件就行。

## 项目

项目需要完成以下几点：

* 载入数据集
* 探索、总结、可视化数据集
* 设计、训练和测试模型
* 使用模型预测新的图片
* 分析模型输出的 Softmax 后的概率
* 总结并编写报告文件

### 做项目之前

在做本项目，需要安装:

* [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit)

无人驾驶第一学期入门工具包可以帮你搭建环境。点击[这里](https://github.com/nd013/CarND-Term1-Starter-Kit/)开始安装。

### 准备数据集和项目代码

1. 首先要下载数据集，课程已经提供了数据集的链接，你可以在 Project Instructions 页面里看到。数据集已经经过了预处理，转为了 32x32 的大小，分好了训练集、验证集和测试集，并且保存成了 pickle 文件，可以被 python 直接读取。
2. 然后下载本项目，包括 notebook 代码，报告模板等文件。

下载方式如下：

```sh
git clone https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project
cd CarND-Traffic-Sign-Classifier-Project
jupyter notebook Traffic_Sign_Classifier.ipynb
```

### 提交审阅

按照 `Traffic_Sign_Classifier.ipynb` 做完了项目，并且根据报告模板 `writeup_template.md` 写好了项目报告以后，就可以提交审阅了。

* 完整运行且无错误的 notebook 代码
* notebook 导出的 html 文件
* 一份 pdf 或者 markdown 格式的报告

## 如何编写 README 文件

写好 README 可以提升你的 GitHub 项目的吸引力，如果你想学习如何更好地写 README 文件，你可以学习这个免费课程：[编写 README 文档](https://www.udacity.com/course/writing-readmes--ud777)。
