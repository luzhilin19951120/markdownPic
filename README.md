# 写在前面

这里汇总了2018年9月以来的Weekly Arxiv推送，如无意外每周至少有2篇。推送中整理了分类、检测、模型压缩等方向的最新文章，写明了【标题、Arxiv链接、研究机构、文章代码链接】等文章基本信息，并对文章进行了简介归纳、关键技术梳理、结果总结和创新亮点分析。

__为了格式考虑，建议下载html文件后用浏览器打开查看__

# 推送列表

|Index|  Time   |    Key Focus    |     Title and Highlight   |     Link    |
|:-----:|:----------:|:--------:|:----------:|:-------------|
|  001  |  2018.9.6  |  人脸匹配 |  _Deep Multi-Center Learning for Face Alignment_ <br>本文通过多轮廓估计层（shape prediction layer, SPL）更好地在遮挡、多相外观等复杂数据条件下解决了face alignment问题。| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/001) |
|  002  |  2018.9.14  | 物体检测 | _Acquisition of Localization Confidence for Accurate Object Detection_ <br>利用IoU-Net提升NMS选框的性能，并利用新的方法微调选出的bbox最终提高检测性能。| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/002) |
|  003  |  2018.9.23  | 模型压缩 | _Soft Filter Pruning for Accelerating Deep Convolutional Neural Networks_ <br>通过channel wise的网络软剪枝保留更多网络描述能力，从而在同样的pruning rate下取得更高的performance!| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/003) |
|  004  |  2018.9.27  | 模型压缩 | _AMC: AutoML for Model Compression and Acceleration on Mobile Devices_ <br>Song Han组新工作，利用网络自动搜索技术进行网络压缩，并取得超过手动压缩的性能。| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/004) |
|  005  |  2018.10.11  | 模型研究 | _Reconciling Feature-reuse and Overfitting in DenseNet with Specialized Dropout_ <br>运用在DenseNet架构中的全新Dropout。| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/005) |
|  006  |  2018.10.15  | 模型研究 | _Elastic Neural Networks for Classification_ <br>通过弹性网络架构压制梯度消失来提升部分backbone的性能，同时赋予网络快速inference的能力。| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/006) |
|  007  |  2018.10.20  | 人脸数据 | _Consensus-Driven Propagation in Massive Unlabeled Data for Face Recognition_ <br>利用半监督学习和主动学习的思想，依托已有的标注数据，将海量无标注数据自动标注后引入训练，提升训练效果。| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/008) |
|  008  |  2018.10.25  | 压缩综述 | _Rethinking the Value of Network Pruning_ <br>对网络压缩技术的探究性工作，指出了几个旧有的错误印象，得出了新的指导性结论，能够辅助优化网络压缩过程。| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/008) |
|  009  |  2018.11.23  | 模型研究 | _GPipe: Efficient Training of Giant Neural Networks using Pipeline Parallelism_ <br>本文利用流水线搭建超大规模网络提升点数，同时引出对up-to-date的数据增强策略和AmoebaNet网络介绍。| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/009) |
|  010  |  2018.11.23  | 模型研究 | _Regularized Evolution for Image Classifier Architecture Search_ <br>提出AmoebaNet，最近的ImageNet Backbone，达到83.9%/96.6%的t1/t5 acc。| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/010) |
|  011  |  2018.11.23  | 模型研究 | _AutoAugment: Learning Augmentation Policies from Data_ <br>自动数据增强(Auto Augment)算法，利用更高级的数据增强涨点。| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/011) |
|  012  |  2018.12.20  | 模型研究 | 本文综述了一系列利用正则化和增强，在cifar/imagenet上对抗overfitting的技术，其中state-of-the-art的部分对一些backbone的涨点较有实用价值。| [URL](https://github.com/luzhilin19951120/paperReadingMails/tree/master/2018/012) |
