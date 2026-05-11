
1.开启事务
在业务逻辑层接口上添加@transactional，非接口的实现类


2.添加事务管理器
在配置类里添加platformtransactionmanager，交给spring管理
通过DATa source platform transactionmanager实现类，还要传递datasource数据源对象（mybatis 框架使用的JDBC事务）


3.开启注解式事务驱动
在spring配置类中添加@EnableTranscationManager注解