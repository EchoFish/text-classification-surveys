# Text Classification papers/surveys（文本分类资料综述总结）更新中...

This repository contains resources for Natural Language Processing (NLP) with a focus on the task of Text Classification. The content is mainly from paper 《A Survey on Text Classification: From Shallow to Deep Learning》

该repository主要总结自然语言处理（NLP）中文本分类任务的资料。内容主要来自文本分类综述论文《A Survey on Text Classification: From Shallow to Deep Learning》。

# Table of Contents

<details>

<summary><b>Expand Table of Contents</b></summary><blockquote><p align="justify">

- [Surveys](#Surveys)
- [Shallow Learning Models](#Shallow-Learning-Models)
- [Deep Learning Models](#Deep-Learning-Models)
- [Datasets](#Datasets)
- [Tools and Repos](#tools-and-repos)
</p></blockquote></details>

---



*<b>Expand Table of Contents</b></summary><blockquote><p align="justify">

- [Surveys](#Surveys)
- [Shallow Learning Models](#Shallow-Learning-Models)
- [Deep Learning Models](#Deep-Learning-Models)
- [Datasets](#Datasets)
- [Tools and Repos](#tools-and-repos)
</p></blockquote></details>

---



## Surveys(综述论文)


### 2020

* <a href="https://arxiv.org/pdf/2008.00364.pdf">A Survey on Text Classification: From Shallow to Deep Learning（文本分类综述：从浅层模型到深度模型）</a> by<i> Qian Li, Hao Peng, Jianxin Li, Congying Xia, Renyu Yang, Lichao Sun, Philip S. Yu, Lifang He
</a></summary><blockquote><p align="justify">
Text classification is the most fundamental and essential task in natural language processing. The last decade has seen a surge of research in this area due to the unprecedented success of deep learning. Numerous methods, datasets, and evaluation metrics have been proposed in the literature, raising the need for a comprehensive and updated survey. This paper fills the gap by reviewing the state of the art approaches from 1961 to 2020, focusing on models from shallow to deep learning. We create a taxonomy for text classification according to the text involved and the models used for feature extraction and classification. We then discuss each of these categories in detail, dealing with both the technical developments and benchmark datasets that support tests of predictions. A comprehensive comparison between different techniques, as well as identifying the pros and cons of various evaluation metrics are also provided in this survey. Finally, we conclude by summarizing key implications, future research directions, and the challenges facing the research area.
  文本分类是自然语言处理中最基本的任务。由于深度学习的空前成功，过去十年中该领域的研究激增。已有的文献提出了许多方法，数据集和评估指标，从而需要对这些内容进行全面的总结。本文回顾1961年至2020年的文本分类方法，重点是从浅层学习到深度学习的模型。根据所涉及的文本以及用于特征提取和分类的模型创建用于文本分类的分类法。然后，详细讨论这些类别中的每一个类别，涉及支持预测测试的技术发展和基准数据集。并提供了不同技术之间的全面比较，确定了各种评估指标的优缺点。最后，通过总结关键含义，未来的研究方向以及研究领域面临的挑战进行总结。
</p></blockquote></details>


## Shallow Learning Models
[:arrow_up:](#table-of-contents)

### 1961 

<details>
<summary>1. <a href="https://dl.acm.org/doi/10.1145/321075.321084">Naïve Bayes (NB)</a> (<a href="https://github.com/Gunjitbedi/Text-Classification">{Github}</a>) </summary><blockquote><p align="justify">
</p></blockquote></details>


## Deep Learning Models
[:arrow_up:](#table-of-contents)

### 2014



<details>
<summary>1. <a href="https://www.aclweb.org/anthology/D14-1181.pdf">Convolutional Neural Networks for Sentence Classification</a> TextCNN (<a href="https://github.com/alexander-rakhlin/CNN-for-Sentence-Classification-in-Keras">Github</a>)</summary><blockquote><p align="justify">
We report on a series of experiments with convolutional neural networks (CNN) trained on top of pre-trained word vectors for sentence-level classification tasks. We show that a simple CNN with little hyperparameter tuning and static vectors achieves excellent results on multiple benchmarks. Learning task-specific vectors through fine-tuning offers further gains in performance. We additionally propose a simple modification to the architecture to allow for the use of both task-specific and static vectors. The CNN models discussed herein improve upon the state of the art on 4 out of 7 tasks, which include sentiment analysis and question classification.
</p></blockquote></details>



## Data
[:arrow_up:](#table-of-contents)

### Sentiment Analysis (SA)
SA is the process of analyzing and reasoning the subjective text withinemotional color. It is crucial to get information on whether it supports a particular point of view fromthe text that is distinct from the traditional text classification that analyzes the objective content ofthe text. SA can be binary or multi-class. Binary SA is to divide the text into two categories, includingpositive and negative. Multi-class SA classifies text to multi-level or fine-grained labels. 

情感分析是对带有情感色彩的主观文本进行分析和推理的过程。从文本中获取是否支持特定观点的信息是至关重要的，而传统的文本分类是分析文本的客观内容。情感分析可以是二进制的或多类的。二元情感分类是将文本分为正反两类。多类情感分类将文本分类为多层或细粒度的标签。

* <a href="http://www.cs.cornell.edu/people/pabo/movie-review-data/">Movie Review (MR) 电影评论数据集</a></summary><blockquote><p align="justify">
The MR is a movie review dataset, each of which correspondsto a sentence. The corpus has 5,331 positive data and 5,331 negative data. 10-fold cross-validationby random splitting is commonly used to test MR. MR是一个影评数据集，每个影评是一个句子。该语料库有正样本和负样本各5331个。十折交叉验证常用来测试MR。
</p></blockquote></details>

* <a href="http://www.cs.uic.edu/∼liub/FBS/sentiment-analysis.html">Stanford Sentiment Treebank (SST) 斯坦福情感库</a></summary><blockquote><p align="justify">
The SST [175] is an extension of MR. It has two cate-gories. SST-1 with fine-grained labels with five classes. It has 8,544 training texts and 2,210 testtexts, respectively. Furthermore, SST-2 has 9,613 texts with binary labels being partitioned into6,920 training texts, 872 development texts, and 1,821 testing texts.
 SST是MR的扩展版本，一共有两种类型。SST-1有五个类别标签，有8,544个训练文本和2,210个测试文本。SST-2有两个类别，共9,613个文本，被划分为6,920个训练文本、872个开发文本和1,821个测试文本。
</p></blockquote></details>

* <a href="http://www.cs.pitt.edu/mpqa/">The Multi-Perspective Question Answering (MPQA)多视角问答数据集</a></summary><blockquote><p align="justify">
The MPQA is an opinion dataset. It has two class labels and also an MPQA dataset of opinion polarity detection sub-tasks.MPQA includes 10,606 sentences extracted from news articles from various news sources. It shouldbe noted that it contains 3,311 positive texts and 7,293 negative texts without labels of each text.
 MPQA是一个观点数据集。它有两个类标签和一个MPQA数据集的观点极性检测子任务。MPQA包含了10,606个句子，这些句子是从各种新闻来源的新闻文章中提取的。应当指出的是，其中有3311个正样本和7293个负样本，每个文本没有标签。
</p></blockquote></details>

* <a href="https://dblp.org/rec/bib/conf/kdd/DiaoQWSJW14">IMDB reviews IMDB评论</a></summary><blockquote><p align="justify">
The IMDB review is developed for binary sentiment classification of filmreviews with the same amount in each class. It can be separated into training and test groups onaverage, by 25,000 comments per group.
 IMDB影评是对每类影评进行相同数量的二元情感分类。它平均可以被分成训练组和测试组，每组有25000条评论。
</p></blockquote></details>

* <a href="https://dblp.org/rec/bib/conf/emnlp/TangQL15">Yelp reviews Yelp评论</a></summary><blockquote><p align="justify">
The Yelp review is summarized from the Yelp Dataset Challenges in 2013,2014, and 2015. This dataset has two categories. Yelp-2 of these were used for negative and positiveemotion classification tasks, including 560,000 training texts and 38,000 test texts. Yelp-5 is used todetect fine-grained affective labels with 650,000 training and 50,000 test texts in all classes.
 Yelp评论数据来自于2013年、2014年和2015年的Yelp数据集挑战。这个数据集有两个类别。其中的Yelp-2被用于消极和积极情绪分类任务，包括560,000篇训练文本和38,000篇测试文本。使用Yelp-5对65万篇训练文本和5万篇测试文本进行精细的情感标签检测。
</p></blockquote></details>

* <a href="https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products">Amazon Reviews (AM) 亚马逊评论数据集</a></summary><blockquote><p align="justify">
The AM is a popular corpus formed by collecting Amazon websiteproduct reviews [190]. This dataset has two categories. The Amazon-2 with two classes includes 3,600,000 training sets and 400,000 testing sets. Amazon-5, with five classes, includes 3,000,000 and650,000 comments for training and testing.
 AM是一个收集亚马逊网站产品评论的流行语料库。这个数据集有两个类别。带有两个类的Amazon-2包括360万个训练集和40万个测试集。Amazon-5有五个类，包含300万条和65万条培训和测试评论。
</p></blockquote></details>


### News Classification (NC) 新闻分类数据集
News content is one of the most crucial information sources which hasa critical influence on people. The NC system facilitates users to get vital knowledge in real-time.News classification applications mainly encompass: recognizing news topics and recommendingrelated news according to user interest. The news classification datasets include 20NG, AG, R8, R52,Sogou, and so on. Here we detail several of the primary datasets.

新闻内容是影响人们生活的最重要的信息来源之一。数控系统便于用户实时获取重要知识。新闻分类应用主要包括:识别新闻话题，根据用户兴趣推荐相关新闻。新闻分类数据集包括20NG、AG、R8、R52、Sogou等。这里我们详细介绍了几个主要数据集。

* <a href="http://ana.cachopo.org/datasets-for-single-label-text-categorization">20 Newsgroups (20NG)</a></summary><blockquote><p align="justify">
 The 20NG is a newsgroup text dataset. It has 20 categories withthe same number of each category and includes 18,846 texts.
 20NG是一个新闻组文本数据集。它有20个类别，每个类别的数目相同，包括18,846个文本。
</p></blockquote></details>

* <a href="http://www.di.unipi.it/~gulli/AG_corpus_of_news_articles.html">AG News (AG)</a></summary><blockquote><p align="justify">
The AG News is a search engine for news from academia, choosingthe four largest classes. It uses the title and description fields of each news. AG contains 120,000texts for training and 7,600 texts for testing.
 AG新闻是一个搜索来自学术界的新闻的引擎，选择了四个最大的类别。它使用每个新闻的标题和描述字段。AG包含120,000篇训练文本和7,600篇测试文本。
</p></blockquote></details>

* <a href="https://www.cs.umb.edu/~smimarog/textmining/datasets/">R8 and R52</a></summary><blockquote><p align="justify">
R8 and R52 are two subsets which are the subset of Reuters. R8 has 8categories, divided into 2,189 test files and 5,485 training courses. R52 has 52 categories, split into6,532 training files and 2,568 test files.
 R8和R52是两个子集，它们是Reuters的子集。R8有8个类别，分为2189个测试文件和5485个训练文件。R52有52个类别，分为6,532个训练文件和2,568个测试文件。
</p></blockquote></details>

* <a href="https://dblp.org/rec/conf/cncl/SunQXH19.bib">Sogou News (Sogou) 搜狗新闻</a></summary><blockquote><p align="justify">
The Sogou News combines two datasets, including SogouCA andSogouCS news sets. The label of each text is the domain names in the URL.
 搜狗新闻结合了两个数据集，包括SogouCA和sogoucs新闻集。每个文本的标签是URL中的域名。
</p></blockquote></details>

### Topic Labeling (TL) 话题标签
The topic analysis attempts to get the meaning of the text by defining thesophisticated text theme. The topic labeling is one of the essential components of the topic analysistechnique, intending to assign one or more subjects for each document to simplify the topic analysis.

主题分析试图通过对文本主题的界定来获得文本的意义。话题标签是主题分析技术的重要组成部分之一，用于为每个文档分配一个或多个主题，以简化主题分析。

* <a href="https://dblp.org/rec/journals/semweb/LehmannIJJKMHMK15.bib">DBpedia</a></summary><blockquote><p align="justify">
The DBpedia is a large-scale multi-lingual knowledge base generated usingWikipedia’s most ordinarily used infoboxes. It publishes DBpedia each month, adding or deletingclasses and properties in every version. DBpedia’s most prevalent version has 14 classes and isdivided into 560,000 training data and 70,000 test data. 
 DBpedia是使用wikipedia最常用的信息框生成的大型多语言知识库。它每月发布DBpedia，在每个版本中添加或删除类和属性。DBpedia最流行的版本有14个类，分为560,000个训练数据和70,000个测试数据。
</p></blockquote></details>

* <a href="http://davis.wpi.edu/xmdv/datasets/ohsumed.html">Ohsumed</a></summary><blockquote><p align="justify">
The Ohsumed belongs to the MEDLINE database. It includes 7,400 texts andhas 23 cardiovascular disease categories. All texts are medical abstracts and are labeled into one ormore classes.
 Ohsumed属于MEDLINE数据库。它包括7400个文本，有23个心血管疾病类别。所有文本都是医学摘要，并被标记为一个或多个类。
</p></blockquote></details>

* <a href="https://dblp.org/rec/bib/conf/nips/ZhangZL15">Yahoo answers (YahooA) 雅虎问答</a></summary><blockquote><p align="justify">
The YahooA is a topic labeling task with 10 classes. It includes140,000 training data and 5,000 test data. All text contains three elements, being question titles,question contexts, and best answers, respectively.
 YahooA是一个包含10个类的主题标记任务。它包括140,000个训练数据和5,000个测试数据。所有文本包含三个元素，分别是问题标题、问题上下文和最佳答案。
</p></blockquote></details>



## Tools and Repos



<details>
<summary><a href="https://github.com/Tencent/NeuralNLP-NeuralClassifier">NeuralClassifier</a></summary><blockquote><p align="justify">
腾讯的开源NLP项目
</p></blockquote></details>


<details>
<summary><a href="https://github.com/nocater/baidu_nlp_project2">baidu_nlp_project2</a></summary><blockquote><p align="justify">
百度NLP项目
</p></blockquote></details>



<details>
<summary><a href="https://github.com/TianWuYuJiangHenShou/textClassifier">Multi-label</a></summary><blockquote><p align="justify">
多标签文本分类项目
</p></blockquote></details>
