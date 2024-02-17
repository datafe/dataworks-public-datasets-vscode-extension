# DataWorks Public Datasets

Aliyun (阿里云) DataWorks 公共数据集支持 MaxCompute/Hologres/EMR Spark 等引擎，并提供多样的数据集以及有趣的使用示例，部份数据集内容定期更新，开通 [Dataworks](https://www.aliyun.com/product/bigdata/ide/) 查看更多的数据集加速大数据开发与分析效率。

## 插件地址

### VS Code
[公共数据集 VS Code 插件安装地址](https://marketplace.visualstudio.com/items?itemName=dataworks.public-dataset)


### Chrome
[公共数据集 Chrome 插件安装地址](https://chromewebstore.google.com/detail/%E9%98%BF%E9%87%8C%E4%BA%91-dataworks-%E5%85%AC%E5%85%B1%E6%95%B0%E6%8D%AE%E9%9B%86/dhddjlgoniabgogocminjceggkleeclk?hl=en)

## 如何使用

- DataWorks 公共数据集提供 SQL 示例与建表、查表语句，语句支持 MaxCompute/Hologres/EMR Spark 等引擎。
- 在本地 VS Code 若要运行语句，可透过 [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) 与 [PostgreSQL](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools-driver-pg) 插件运行 Hologres 数据源。
- 使用 MaxCompute/EMR Spark/Hologres 引擎对数据进阶分析，请至 [DataWorks 数据分析](https://da-cn-shanghai.data.aliyun.com/) 上参考 [大数据AI公共数据集分析](https://help.aliyun.com/zh/dataworks/getting-started/use-big-data-and-ai-to-analyze-public-datasets) 的操作。
- 若要基于数据集内容建立线上 API，请至 [DataWorks 数据服务](https://ds-cn-shanghai.data.aliyun.com/) 上使用。

### 相关资源介绍

点击下方链接查看:

- [DataWorks](https://www.aliyun.com/product/bigdata/ide/)
- [DataWorks 数据分析](https://da-cn-shanghai.data.aliyun.com/)
- [DataWorks 数据服务](https://ds-cn-shanghai.data.aliyun.com/)
- [MaxCompute](https://www.aliyun.com/product/odps/)
- [Hologres](https://www.aliyun.com/product/bigdata/hologram/)
- [EMR Spark](https://www.aliyun.com/product/bigdata/emapreduce/)

### 数据集列表

此插件挑选出部份数据集，可查阅建表、查表 SQL 与示例 SQL。

- [阿里电商数据集](https://dataworks.console.aliyun.com/publicDatasets/701)
- [淘宝广告数据集](https://dataworks.console.aliyun.com/publicDatasets/703)
- [淘宝购物数据集](https://dataworks.console.aliyun.com/publicDatasets/702)
- [杭州各区县旅游数据统计](https://dataworks.console.aliyun.com/publicDatasets/1002)
- [阿里音乐数据集](https://dataworks.console.aliyun.com/publicDatasets/705)
- [全球电动汽车数据集](https://dataworks.console.aliyun.com/publicDatasets/1004)
- [飞猪推荐数据集](https://dataworks.console.aliyun.com/publicDatasets/704)
- [中国大陆各地区生产总值数据集](https://dataworks.console.aliyun.com/publicDatasets/1003)
- [Github 事件数据集](https://dataworks.console.aliyun.com/publicDatasets/706)
- [QS 世界大学排名](https://dataworks.console.aliyun.com/publicDatasets/1001)
- [亚运会奖牌数据集](https://dataworks.console.aliyun.com/publicDatasets/1005)
- [中国大陆专利申请和授权数据集](https://dataworks.console.aliyun.com/publicDatasets/1006)

![public-datasets](https://img.alicdn.com/imgextra/i4/O1CN01daFKhK28m96ZDOTP7_!!6000000007974-2-tps-1360-1370.png)


### SQL 示例使用方式

由左方树结构点选数据集示例 (Example)，跳出下方选单，选取引擎种类添加对应的 SQL 文档:

![select-engine-type](https://img.alicdn.com/imgextra/i2/O1CN01m14OJB1NFpDHsjWiq_!!6000000001541-2-tps-1718-564.png)

动图:

![example-sql](https://img.alicdn.com/imgextra/i2/O1CN01lS5Jpp1YLHi1VUa3c_!!6000000003042-1-tps-2878-1748.gif)

### 建表与查表使用方式

由左方树结构点选数据表，跳出下方选单，选取引擎种类添加对应的 SQL 文档:

![select-engine-type](https://img.alicdn.com/imgextra/i2/O1CN01m14OJB1NFpDHsjWiq_!!6000000001541-2-tps-1718-564.png)

动图:

![table-sql](https://img.alicdn.com/imgextra/i2/O1CN01ihAUsX29Ls04vs3NE_!!6000000008052-1-tps-2878-1742.gif)

### 透过 SQLTools 运行建表、查表与示例SQL

目前仅支持透过 [PostgreSQL](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools-driver-pg) 插件运行 Hologres 数据源。

1. 安装 [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) 与 [PostgreSQL](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools-driver-pg) 插件
2. 透过 [Hologres 管控台](https://hologram.console.aliyun.com/) 开启公网，并至 [HoloWeb](https://holoweb-cn-shanghai.data.aliyun.com/) 建立数据库与建立连线帐密

![sqltools-connection](https://img.alicdn.com/imgextra/i3/O1CN01jvB9Y021rSOBia4jG_!!6000000007038-2-tps-2880-1388.png)

3. 运行
- 运行建表、查表

![run-ddl](https://img.alicdn.com/imgextra/i3/O1CN01r0D4pB1JlBsOwJF3g_!!6000000001068-1-tps-2878-1748.gif)

- 示例 SQL (拷贝示例至 SQL 档运行)

![run-example](https://img.alicdn.com/imgextra/i2/O1CN014KNRLv1ql56PwePSJ_!!6000000005535-1-tps-2878-1742.gif)

### 支持 SQL 文档高亮与代码补全

- 选择 public-dataset-sql 语言进行语法高亮
![sql-lang](https://img.alicdn.com/imgextra/i3/O1CN01Uwdpff1pZLKwgEd4g_!!6000000005374-2-tps-1000-607.png)

- 支持 SQL 语法高亮与代码补全
![sql-autocomplete](https://img.alicdn.com/imgextra/i3/O1CN01fmkVei1j3qP4xzcwA_!!6000000004493-2-tps-1000-578.png)

- 动图:
![sql-autocomplete-gif](https://img.alicdn.com/imgextra/i4/O1CN01l8W9UF27nEQjkPEb4_!!6000000007841-1-tps-2878-1660.gif)


### 维护者

云胧 寞然 风樵 簌篱 晨曦 继风
