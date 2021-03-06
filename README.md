### 邵松

-----

#### 教育与工作经历

-----

- 2008.09-2012.06 山东大学，计算机科学与技术专业，学士
- 2012.09-2015.07 中国科学院，计算技术研究所，普适计算中心，计算机应用技术 (计算机视觉，模式识别)，硕士
- 2015.07-2016.10 阿里巴巴搜索事业部，搜索产品技术团队，搜索研发工程师

#### 科研与项目

--------

- ##### 实验室

  - **场景自适应的行人检测技术研究**

    - 目的：从特征描述、样本迁移和检测器迭代优化等方面进行改进，提出一个场景自适应的行人检测框架
    - 工作：提出融合上下文局部关联特征的行人目标描述方法；提出基于分块加权距离的样本迁移策略；提出权重差异化调整的检测器迭代优化算法；深入挖掘场景信息，建立行人空间分布的关系映射模型；优化滑动窗口检测策略，形成一种更为快速高效的检测定位机制
    - 成果：使用matlab和c++完成了从训练到检测的整套行人检测框架，显著提高了现有的检测性能，发表论文（Local Associated Features for Pedestrian Detection, ACCV Robust Local Descriptors for Computer Vision Workshop, 2014）
  - **迁移学习在行人检测中的应用研究**
    - 目的：对迁移学习在行人检测中的应用现状进行梳理、分析和总结，给出未来的研究方向
    - 工作：查找和阅读大量文献资料，了解迁移学习的概念、分类和步骤等；对目前提出的各种算法进行了对比分析：指出现有方法的不足和未来值得研究的方向
    - 成果：发表论文（基于迁移学习的行人检测研究进展，计算机工程与应用，Vol.50 No.24，2014）
  - 其他
    - 参加与相关部门合作的视频监控调研活动、搭建智能视频监控演示系统	


- ##### 阿里

    - AliExpress、1688、淘宝的知识产权和假货业务部分需求的开发和维护
      - 基于安全部的风控系统（RCP）和规则系统（MTEE），开发业务代码，维护系统，解答运营在使用审核系统时遇到的问题
    - 搜索、导航、下拉推荐、评价等快速干预工具相关需求的开发和维护（主要负责人）
      - 满足产品和运营对搜索各模块进行干预的各种工具，将页面填写的配置数据传给算法。包括前端页面和后台逻辑的开发
    - **反作弊系统（虫洞）相关需求开发**（两人协作）
      - 基于idrill和parquet，统计和展示成交、物流、异常卖家和商品等数据的图表，并提供行业、类目，卖家等多维度的分析功能（能够支持对两个月近50亿订单的快速分析）
      - 基于引擎和idrill，实时展示全网作弊订单变化情况
      - 基于规则引擎和mapreduce，对算法识别的作弊订单进行处理，包括ETL数据加工任务、识别规则配置、决策规则配置，流量控制，效果评估等模块（支持几千万订单的全量处理）
    - **搜索商品卖家处罚系统（魔戒）开发**（两人协作）
      - 魔戒是搜索的关键性处罚系统，可以对淘宝和天猫的卖家和商品进行降权等流量控制
      - 由我和另外一个同事从其他团队接手整个系统的日常维护
      - 原有系统涉及后台脚本，odps任务，实时计算，前端页面，hbase存储，名单权限管理等很多子系统和上下游，由于开发历史久，有很多遗留问题和性能不足，我们在熟悉旧系统基础上，重新设计和开发了新魔戒系统进行代替。通过设置优先级队列调控数据量，将原有系统的离线和实时部分合并，简化了系统架构并提升了性能（qps>4000）
    - **算法实时反作弊系统开发**（主要负责人）
      - odps系统上运行的一些识别作弊订单的算法模型，只能达到小时级别的准实时，在双11等大促时无法满足需求，因此基于istream和blink等流式计算引擎，将已有算法改为流式计算，达到实时识别的效果
      - 负责将各种作弊订单识别模型转换为支持流式计算，并在底层的istream基础上封装一套框架，便于添加扩展各种识别模型
      - 从成交日志解析，模型识别，命中数据进订单引擎，对接后续处理系统的整个链路开发测试
    - 假货、滥发治理平台相关需求开发
      - 基于大数据的智能分析调控：不同流量桶中的商品采用了不同的治理策略，系统将收集到的数据灌入durid，然后前端支持从多个维度对比分析不同桶的治理效果。主要负责整个分析页面的开发
      - 其他日常需求与数据加工

- ##### 个人

    - 文本分类系统
    - 图片搜索系统
    - 汽车智能问答系统

#### 专业技能

--------

- 语言：c++ java javascript html/css python sql matlab 
- 了解机器学习常用算法和图像特征：HOG LBP SVM LR AdaBoost GBDT CNN
- 工具：vim git linux/osx
- 了解使用过大数据处理相关系统：drill parquet hbase mapreduce stream flink odps 

#### 兴趣爱好

------

推理、科幻小说，编程，动漫，游戏，美剧

#### 联系方式

---------

- Email：shaosongly@gmail.com
