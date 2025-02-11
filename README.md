# Bert-Based-Anime-Eec-System
## 文件说明
DataAcquire.ipynb：爬取排名前50的动漫以及对应的标签与长评论

Cutting.ipynb：对长评论进行分词并结合固有标签处理为one-hot向量

train.ipynb：随机森林模型训练

train_bert.py：bert模型微调
## 运行说明
在Anaconda(或其他已配置好的环境)中进入项目文件夹

cd RecommendSystem

然后运行项目

python manage.py runserver

## 参考链接
https://github.com/WilliamPockey/Pal_Classify

https://blog.csdn.net/qq_48764574/article/details/126068667
