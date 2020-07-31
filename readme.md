```
a maven plugin to generate rest crud api

- 自带全局异常处理
- hibernate validation
- 跨域处理
- 数据访问层分为读操作写操作, 方便实施读写分离
- 自带分页
- 使用 ThreadLocal 从 controller 中剥离了业务无关的参数

代码生成用到了 velocity 模板

如何使用?

git clone https://github.com/xiaoyureed/rest-api-maven-plugin.git
cd rest-api-maven-plugin
mvn clean install

```