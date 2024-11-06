# 方式1: 开箱即可(无xml)。

> 1. 引入mybatisplus-springboot包

> 2. 保证容器里仅有一个DataSource实例。

> 3. 通过MybatisPlusProperties指定mapperXml(可选)

> 4. 用@Mapper标注Mapper


# 方式2: 结合@MapperScan使用(无xml)

> 1. 引入mybatis-springboot包

> 2. 保证容器里仅有一个DataSource实例。

> 3. 通过MybatisPlusProperties指定mapperXml(可选)

> 4. 用@MapperScan指定具体mapper包的packge(并基于BaseMapper)

> 5. 是否用@Mapper标注Mapper都没关系，因为条件不生效不会重复注册
