# neo4j-demo
Neo4j简单Demo,方便学习者可以随意下载学习新的图形数据库的理解。
Neo4j是一个开源的NoSQL图形数据库。它是一个完全事务性数据库（ACID），用于存储结构化为由节点组成的图形的数据，这些节点通过关系连接。受现实世界结构的启发，它可以在复杂数据上实现高查询性能，同时为开发人员保持直观和简单。
官方文档如下：

[neo4j文档](https://neo4j.com/docs/)
[spring Data Neo4j](https://docs.spring.io/spring-data/neo4j/docs/5.1.4.RELEASE/reference/html/#preface.spring-data)

## 环境配置
安装图形数据库，选择社区版本，社区版本只支持单机。

下载地址：https://neo4j.com/download-center/


## 访问登录
- 在neo4j的conf中修改neo4j.conf，将如下注释#去掉
    ```shell
    #dbms.connectors.default_listener_address=0.0.0.0
    ```
- 启动服务
    ```shell
    ./ne04j start 
    //出现以下的字样
    Started neo4j (pid 1466). It is available at http://0.0.0.0:7474/
    ```
- 浏览器访问
    http://localhost:7474/
    首次登录账户密码都是neo4j，首次提示修改密码为123456

## 创建节点



