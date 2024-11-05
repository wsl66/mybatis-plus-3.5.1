# 一、配置阶段

> 1. 注册单DataSource

> 2. 注册MybatisSqlSessionFactoryBean，仅设置DataSource

> 3. @MapperScan基于BaseMapper和package


# 二、编写Model与Mapper/Service

> 1. Modle中使用@TableName/@TableId/@TableFidld注解

> 2. Mapper继承BaseMapper

> 3. 业务Service接口继承IService,实现ServiceImpl


# 三、直接使用

直接注入业务Service,直接使用各类Wrapper或BaseMapper的API