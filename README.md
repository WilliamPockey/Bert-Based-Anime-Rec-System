# Bert-Based-Anime-Eec-System

## 运行说明
下载并解压RecommendSystem.zip并解压项目

打开Index和display目录下的view.py，分别修改anime_tag和records处的代码，使之读取根目录下的tag.txt

并修改display目录的view.py中的绝对路径，将其更改为自己电脑上的路径

在Anaconda(或其他已配置好的环境)中进入项目文件夹

`cd RecommendSystem`

然后运行项目(因为项目前端是在Pal_Classify的Django框架基础上改的，所以名字显示为pal_classify)

`python manage.py runserver`

## 文件说明
RecommendSystem.zip：项目主体(其他文件均为项目前期准备时用的文件)

DataAcquire.ipynb：爬取排名前50的动漫以及对应的标签与长评论

Cutting.ipynb：对长评论进行分词并结合固有标签处理为one-hot向量

train.ipynb：随机森林模型训练

train_bert.py：bert模型微调


## 参考链接
https://blog.csdn.net/m0_62890769/article/details/145569584?spm=1001.2014.3001.5501

https://github.com/WilliamPockey/Pal_Classify

https://blog.csdn.net/qq_48764574/article/details/126068667
