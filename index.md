---
layout: cv
title: Wode "Nimo" Ni
email:
  url: mailto:woden@cs.cmu.edu
  text: woden@cs.cmu.edu
homepage:
  url: http://cs.cmu.edu/~woden
  text: cs.cmu.edu/~woden
---

# 中文名 **好看**

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}
## 目标工作

-----
## 教育背景

### `2013.9— 2016.4`   **中国科学技术大学**      软件工程                   `硕士学位` <br>
```
Pittsburgh, PA
```

### `2005.9—2009.7`     **湘潭大学**             机械设计制造及其自动化     `学士学位` <br>


-----
## 编程技能

### **技术 vs 语言**    * [JavaWeb] ，[Spark] ，[MySql]，[机器学习]，Solr，[推荐系统]
                       * [Java] >[Scala]== [C] > [Python] > [C#]




----

## 项目经验

2016.10—现在  fenbusds分布式环境项目查到的的
• 软件环境: J2EE+Hibernate+MySql+SolrClouder+Zookeeper+Spark+Hbase+Tomcat
• 项目介绍: 通过关键词、脚本特征值、域名和短码进行布控，将相应布控指令发送到网综平台，网综把命中结果以 post
      包队列方式推送到分析系统，分析系统通过多种方式对结果进行解析和处理，判断域名的违法类别，寻求违法线索
– 使用脚本定时获取 360 公司推送在 ftp 服务器上的 xml 格式数据，执行 Jar 包程序将其解析并导入到项目
       模块，进行分页查看，同时按照日期(月和日)统计其类别和数量;
– 搭建 Spark on Yarn 大数据计算平台，对聚类数据进行 RemoveDup、PreJob、EdgeMaker、Fastunfolding
和 PostJob 代码流程聚类，并对聚类结果进行统计和分析;
– 实现关键词提取模块，对 post 包数据进行 TF-IDF 值计算，分析和优化提取的关键词;
– 对一些关系型数据进行分页展示，用户登录模块，日志模块和权限管理模块

2016.06—2016.10 XX 市 -智能终端取证采集分析系统 公司项目
• 软件环境: J2EE+Hibernate+MySql+Solr+Tomcat + SVN
• 项目介绍: 对智能终端数据进行采集、展示和分析。采集是将数据进行接入和管理;展示是指查看采集设备的通讯信息和
网络数据，用图表展示统计信息和发展趋势;分析采用同人、团伙和关键人等多种数据分析能力，挖掘犯罪线索及虚拟身份 特征，识别身份类型
– 通过 sql 代码对相关数据进行统计分析，服务器状态抓取，获取服务器的 cpu、硬盘和内存的使用率
– 用户登录模块，日志模块和权限管理模块，对一些代码进行优化和重写

2016.04—2016.7 XX 省 -网络传销数据分析平台 公司项目
• 软件环境: J2EE+Hibernate+MySql+SolrClouder+Zookeeper+Tomcat + SVN
• 项目介绍: 对客户提供的网络传销数据进行查询、构建网络关系图和掌控重点人员。查询，通过对海量数据进行模糊、精
确、单条件和多条件查询功能，查询结果合理化展示;网络关系图包含推荐图和安置图;重点人员，对多个案件数据的用户 身份证、银行账户、手机号和 QQ 进行关联查找
– 使用 MySQL 数据库技术进行条件查询模块实现，使用 SolrCloud 技术实现全文查询模块 – 用户登录模块，日志模块和权限管理模块，实现相关关系图导出到 excel 表格

2014.09—2015.11  基于 Spark 的电影推荐系统设计与实现 中国科学技术大学 论文相关项目

### **Carnegie Mellon University, Research碍事法师是的方法都是啥的 Experiences for Undergraduate** `2017.5 - 2017.8`

_Research Assistant_<br>
**Penrose** is a system that automatically visualizes mathematics using two domain-specific languages: **Substance** and **Style**. Co-advised by [Jonathan Aldrich](https://www.cs.cmu.edu/~./aldrich/), [Keenan Crane](https://www.cs.cmu.edu/~kmcrane/), [Joshua Sunshine](http://www.cs.cmu.edu/~jssunshi/), and [Katherine Ye](https://www.cs.cmu.edu/~kqy/), I designed and implemented the Style language, and extended the Substance language to support functions and logically quantified statements.

### **Columbia University, Computer Graphics and User Interfaces Lab** `2017.1 - 2017.5`

_Research Assistant_<br>
Worked with prof. Steven Feiner, on **Cyber Affordance Visualization in Augumented Reality** project. Developed a Microsoft Hololens application that visualizes the Columbia campus in AR environment.

### **AsiaInfo** `2015.6 - 2015.8`

_Software Engineering Intern_<br> Worked on serv web applications and
server deployment tools.
-----
## 工作经验


2016.02—现在                         XX部第 X 研究所 `数据研发工程师` <br>  
2014.07—2015.08                 中科院电子所苏州研究院 `大数据研发工程师` <br>
2012.09—2013.06                  北京航空航天大学 `移动云计算专业` <br>  
2009.06—2011.07        富士康科技集团 cnsbg事业群 `制程/机构工程师` <br>

Max Krieger (CMU, independent research & [REUSE](https://www.cmu.edu/scs/isr/reuse/)) `CMU, 2018 - Now` <br>
Courtney Miller (New College of Florida, [REUSE](https://www.cmu.edu/scs/isr/reuse/)) `CMU, 2019` <br>
Anael Kuperwajs Cohen (Macalester College, [REUSE](https://www.cmu.edu/scs/isr/reuse/)) `CMU, 2019` <br>
-------
## 素质技能
**外语水平**: 英语 CET6，考研英语 70 分，具备日常沟通和阅读专业文献能力 <br>
**个人评价**: 热爱技术，善于思考，学习能力强，沟通能力强，富有团队精神 <br>
        读研时担任班长，个人获省级优秀毕业生、校级优秀学生干部等 <br>
Teaching Assistant, **Programming Languages and Translators (COMS 4115)** `Columbia, 2017 - 2018` <br>
Teaching Assistant, **Introduction to Java II (COMP 132)** `Dickinson, 2016` <br>
Peer Tutor, **Data Structures and Problem Solving (COMP 232)** `Dickinson, 2016` <br>
Computer Lab Consultant `Dickinson, 2014 - 2016` <br>

<!-- ### Footer

Last updated: May 2013 -->
