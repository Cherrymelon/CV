## 个人信息

- 张锐/男/1994
- 学历：本科-电子信息工程-湖北工业大学(2013-2017)
- 期望职位：Python开发工程师
- Github: [Cherrymelon](https://github.com/Cherrymelon)
- Email:Cherrymelon@foxmail.com
- 电话：19916948002
- Wechat:Bananaa2
- 工作经验:1年(2018.10辞职考研)

## 技能
- 熟悉Python，如文件I/O、多进程、正则表达式
- 熟悉Numpy、Pandas、Scipy
- 熟悉常用数据结构和算法
- 熟悉Linux、Shell、Git、Maven
- 熟悉MySQL，如事务、索引
- 了解Dask、Sklearn、Scrapy、Websocket、Tensorflow
- 了解Django
- 了解OOP和常用设计模式，如单例模式、工厂模式、MVC模式
- 了解Http、TCP/UDP、IP等网络协议
- 了解Restful、RPC
- 了解WEB安全问题，如XSS、CSRF、SQL注入
- 了解Java，如集合、泛型、JVM
- 了解Spring Boot
- 了解Docker、K8S、MongoDB、Neo4j、Redis 、Kafka



## 工作经历

### 武汉解语科技有限公司-NLP算法工程师（2017.7-2018.10）
负责NLP方向的开发工作，另外负责编写基于Dask的DAU、WAU、用户留存率等分布式计算和数据收集、标注、清洗

#### SNS消息多标签分类(Tensorflow)

需求：针对社群运营者对不同广告的允许类型，提供类别可选的过滤功能
负责算法选型及实现,采用了Bi-lstm+Attention+Word2vec，使用gensim训练经过清洗和预处理的语料构建词向量模型。对训练数据做广告特征的抽取，测试中正常消息label的f1 score：99%左右，广告label的f1 score：80%左右。最后使用Tensorflow-serving进行部署。

#### 基于决策树的句式判别(Sklearn)

需求：配合QA识别句式
负责算法实现和调参，使用句法依存分析+词性标注+正则+编码向量+决策树进行句式分类，测试集中f1 score：85%左右。

#### 法律判决文书分类(Tensorflow)

需求:把相似案例的判决文书推送给法官作为参考判例
负责算法选型及实现，起初尝试Doc2vec和Paragraph2vec，发现效果不理想,正则提取双方陈述部分，视为pairwise问题，使用RankNet+CNN。

## 其他项目

#### 基于 Springboot + Redis + Kafka +MySQL的秒杀系统

参照Github上的项目，实现了一个秒杀系统，组件全部部署在Docker中。使用乐观锁更新库存，Redis计数限流和缓存预热，Kafka异步消息队列,数据存放在MySQL中，利用MyBatis进行持久化管理。由于CPU性能限制，Jmeter测试TPS只从300提升到2400。

## 关于我

- 热爱编程，具有强烈的自我驱动力，对学习新技术有极大的热情
- 自学能力较强，具备独立分析解决问题的能力，能够阅读专业内英语论文
- 做事认真，有较强的责任感，乐于沟通

## 致谢

感谢您花时间阅读我的简历，期待有机会与您共事。
