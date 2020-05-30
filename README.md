## 个人信息

- 张锐/男/1994
- 学历：本科-电子信息工程-湖北工业大学(2013-2017)
- 期望职位：研发工程师
- Github: [Cherrymelon](https://github.com/Cherrymelon)
- Email:Cherrymelon@foxmail.com
- 电话：19916948002
- Wechat:Bananaa2

## 技能

- 熟悉Java，如集合、泛型
- 熟悉常用数据结构和算法
- 了解常用设计模式，如单例模式、工厂模式、MVC模式
- 了解JVM，如GC、类加载机制、JVM内存分配
- 了解锁，如CAS、偏向锁
- 了解Spring Boot，DI，IOC
- 了解Http、TCP/UDP、IP等网络协议
- 了解WEB安全问题,如XSS、CSRF、SQL注入
- 熟悉Python，如GIL、GC
- 熟悉Numpy、Pandas、Scipy
- 熟悉Linux、Shell、Git、Maven
- 了解MySQL，如事务、脏读、幻读
- 了解Docker、K8S
- 了解C、MongoDB、Neo4j、Redis 、Kafka、MyBatis

## 其他项目

#### 基于 Springboot + Redis + Kafka 的秒杀系统

参照Github上的项目，实现了一个秒杀系统，组件全部部署在Docker中。使用乐观锁更新库存，Redis 计数限流和缓存预热，Kafka异步消息队列,数据存放在MySQL中,利用MyBatis进行持久化管理。由于CPU性能限制，Jmeter测试TPS只从300提升到2000。

## 工作经历

### 武汉解语科技有限公司-NLP算法工程师（2017.7-2018.10）

#### SNS消息多标签分类

需求：针对社群运营者对不同广告的允许类型，提供类别可选的过滤功能
解决方案：Bi-lstm+Attention+Word2vec，使用gensim训练经过清洗和预处理的语料，构建词向量模型。对训练数据做广告特征的抽取，测试中正常消息label的f1 score：99%左右，广告label的f1 score：80%左右。最后使用tensorflow-serving进行部署。

#### 基于决策树的句式判别

为了配合QA识别句式需要，使用句法依存分析+词性标注+正则+编码向量+决策树进行句式分类。

#### 法律判决文书分类

需求:把相似案例的判决文书推送给法官作为参考判例
解决方案：起初尝试Doc2vec和paragraph2vec，发现效果不理想。考虑正则提取双方陈述部分，视为pairwise问题，使用RankNet+CNN。

#### 基于知识图谱的简单114查号台QA

需求：根据用户的请求，查询对应的机构或单位的联系方式或信息
解决方案:语音转文本后，bilstm+crf+attention意图识别和提取关键信息如命名实体，美食景点等调用地图api，公共事务利用构建的知识图谱进行路径搜索，找到符合要求的信息，否则转接人工服务。


## 关于我

- 热爱编程，具有强烈的自我驱动力，对学习新技术有极大的热情
- 自学能力较强，具备独立分析解决问题的能力
- 做事认真，有较强的责任感，乐于沟通，能够阅读专业内英语论文

## 致谢

感谢您花时间阅读我的简历，期待有机会与您共事。