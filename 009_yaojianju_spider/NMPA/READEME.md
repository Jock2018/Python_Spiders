# 基于Scrapy+MySQL爬取国家药监局100w+数据
## 1. 声明
本爬虫仅用于技术学习和科研需要，切勿用于商业用途！！！否则，后果自负。
## 2. 爬虫的使用
### 2.1 环境配置
推荐：Anaconda + Pycharm + MySQL + Scrapy 1.7(1.6之前的都不行)
### 2.2 运行爬虫
1. 安装好环境之后，记得修改setting中的msyql配置文件，连接上自己的mysql数据库,同时用sql语句建表。
2. 直接运行run即可。
## 3. 其他
本爬虫只抓取了国产药品库、进口药品库、国产器械库、进口器械库、国产化妆品库、进口化妆品库、执业药师库、网上药店库。
如果你需要其他的数据，可以直接找到table_id,添加Item即可。