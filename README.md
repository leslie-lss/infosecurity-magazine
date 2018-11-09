# 概述

爬取infosecurity-magazine的所有文章内容，进行分词预处理，并且存入mongodb中

# 网址分析

https://www.infosecurity-magazine.com/news/page-1396/   1396页，每页12篇

https://www.infosecurity-magazine.com/news/veracode-ca-broadcom-thoma-bravo/

# 数据存储结构

>key | 意义
>-------- | --------
>url | 文章的地址
>article | 文章正文内容
>article_no_url | 过滤掉正文中的链接
>article_chi | 文章中的中文字符
>article_chi_final | 文章中的中文字符的分词结果
>article_eng | 文章中的英文字符
>article_eng_final | 文章中的英文字符的分词结果
