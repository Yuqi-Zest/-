##构建高效的肝脏超声造影连续勾画软件和迁移模型 

#摘要

人工智能正在取代计算科学和工程学中的标准算法，超声造影已经在欧洲和亚洲用于心脏和腹部成像数十年，应用前景光明。基于这两个事实，深度学习在超声造影数据分析领域将大有可为。本研究围绕着超声造影视频数据的深度学习方法应用，在数据集清洗和视频学习框架两个话题上展开，详细研究了半自动追踪软件的开发设计和多种卓越的视频网络在超声造影数据上的迁移性能。文章主体分为四个章节：第一章介绍超声造影和超声影像组学的概念，系统回顾了基于机器学习的超声造影定量化分析和研究成果，说明了研究数据清洗和迁移学习的必要性；第二章围绕自主研发的基于点跟踪算法的半自动病灶连续勾画软件，介绍了造影视频的运动校正方法，比较不同特征点提取算法的性能，简要介绍软件的构建过程和使用；第3章围绕迁移学习和视频分类模型展开，在区分肝细胞癌和胆管细胞癌的分类任务下，纵向分析比较了4大类、16个视频分类模型的迁移效果，并纵向比较了采样帧数、采样方法、数据清洗和全局特征对迁移效果的影响，本章节希望帮助初学者了解如何对超声造影数据集进行清洗、如何选择模型和训练参数，并在较短的时间内达到良好的分类性能；第四章总结了研究的不足，并展望了未来深度学习在超声造影和其他医学影像的的发展。虽然这些方法只在局灶性肝脏病变数据集上测试优化，但方法本身并不涉及肝脏器官图像表征的先验知识，原则上感兴趣的连续跟踪和深度学习框架可以应用到其他器官的造影序列的处理和分析中。

#关键字

肝脏超声造影，图像序列处理，迁移学习，视频深度学习网络，图形界面编程，点跟踪, 数据清洗

#Abstract

Artificial intelligence is replacing standard algorithms in computational science and engineering. Contrast-enhanced ultrasound(CEUS) has been used for cardiac and abdominal imaging in Europe and Asia for decades with promising future. Based on these two facts, deep learning has great potential in the field of CEUS vedio dataset analysis. This study revolves around the application of deep learning methods for CEUS video data, focusing on dataset cleaning and video learning framework choosing while introduces the development and design of semi-automatic tracking software and the transfer performance of multiple superior video networks. The main body of the article is divided into four chapters: the first chapter introduces the concepts of CEUS and radiomics, systematically reviews machine learning-based quantitative analysis researches in CEUS; illustrates the need for more research on data cleaning and  transfer learning. Chapter 2 revolves around independent development point-based tracking algorithm for semi-automatic continuous outlining of liver focal lesions, introduces motion correction methods for imaging videos, and compares the performance of different feature points-based methods, briefly explains the process of constructing the software and its user manual. Chapter 3 is built around transfer learning and video classification models. We analysis and compare 4 major categories and 16 video classification models under the classification task of differentiating between hepatocellular carcinoma and cholangiocellular carcinoma, as well as compare the effects of the number of sample frames, sampling methods, data cleaning, and global features on transfer learning. This section hopes to help beginners understand how to clean CEUS dataset and know to use which model is better in CEUS. Chapter 4 summarizes the research deficiencies and looks at the future of deep learning in CEUS and other medical imaging. Although these methods only apply to focal liver lesion dataset, the methods themselves does not use any prior knowledge of the liver organ, in principle they can work for other medical problems.

#KeyWords

Liver Ultrasound Imaging Analysis,  Image Sequence Processing, Transfer learning, Video DNN Model, Graph Guided Programming, Point-based Tracking, Data Cleaning
