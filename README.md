# COVID19_Project
关于新型冠状病毒感染的肺炎的研究，研究学者已经发出了大量论文，由kaggle提供的COVID-19的数据集被认为是搜集最全的相关论文。该数据集提供了论文网站和论文摘要。

本项目爬取了网页版的COVID-19论文集（未爬取只提供pdf的），COVID-19论文，但是爬到1千多篇时本机IP被封。在分析处理时依然采用题目和摘要进行分析。

metadata.csv 由Kaggle提供的数据，包括论文题目，论文摘要，论文网站等信息
stopwords.txt jieba分词后去掉的停用词数据
medical_words jieba分词后提取的医学单词数据
original_data 爬取的论文（1千多篇）数据
count_words 统计所有摘要和题目的医学词频数据
order_count_words 对词频进行排序的数据



本项目代码地址在博客https://blog.csdn.net/qq_31089125/article/details/105588962中
包括爬虫 正则化 jieba分词 及spark技术的对数据进行处理分析并统计词频。
