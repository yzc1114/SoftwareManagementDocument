# Project charter

**Project Title**: 基于go的分布式端到端的轻量级key-value内存数据库----Godis

**Project Start Date**:                                             **Project Finish Date**: 

**Budget Information**:

**Project Manager**: 杨紫超

**Project Objectives**: 开发一个轻量级的端到端的key-value内存数据库产品Godis，该产品将为所需要使用web技术的公司和组织提供一个高速的、高并发的、分布式的内存缓存解决方案，可用作数据库、缓存或消息中间件。Godis是一个key-value型的内存存储数据库，数据按照键值对的形式进行组织、索引和存储，数据的存储及数据库的运行均在内存中，Godis应对其存储模型不断地优化以节省内存空间。Godis将支持多种数据结构类型，如字符串（string）、散列（hash）、列表（list）、集合（set）、有序集合（sorted set）与范围查询、索引查询等，同时，Godis也支持事务（transaction）和不同级别的磁盘持久化机制，并提供类似Redis哨兵机制等监控控件和分区来提高可用性。Godis将会持续结合吸纳现有的缓存技术的优点，并持续配套开发与各类web框架的集成能力，形成更强的竞争力，最终完成一个高性能的商业数据库。

**Main Project Success Criteria**:Godis数据库能在技术上相比同类产品有自己的竞争力，并在先期能占据一定的市场份额，之后逐步扩大到同类产品领先的位置。

**Approach**:

* 调查市场现有的相关开源产品使用的技术优点，选择性的吸收或采用更新的技术替代以形成更强的竞争力。
* 审查市场上各相关产品的用户手册，了解其提供的功能，以对Godis进行功能补充并确定需要重点开发拓展的功能领域。
* 整合现有技术优势，尝试性的开发更高效的内存存储结构。
* 使用迭代的方式开发整个项目的所有功能点，以便及时补缺或进行优化。
* 确定一个指标来衡量开发成本和预期收入，并以此为依据进行项目开发的投入。

​                                                  **Roles and Responsibility**

|  Name  |            Role             |  Position  | Contact Informatica |
| :----: | :-------------------------: | :--------: | :-----------------: |
| 斯邦斯 |      出资人（Sponsor）      |    CEO     |     xxx@163.com     |
| 杨紫超 | 项目经理（Project Manager） | 高级程序员 |                     |
| 王笑天 |   团队成员（Team Member）   |   程序员   |                     |
| 周宇东 |   团队成员（Team Member）   |   程序员   |                     |





