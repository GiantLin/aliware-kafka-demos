## Run Demo

demo的目的仅仅是把应用跑起来作为参考，很多参数请参考文档设置以保证客户端的稳定和性能。

1. 安装软件：确保安装了 JDK 8+ 和 Maven 3.2.5+
2. 编写配置：修改application.properties XXX 替换为实际值
3. 发收消息：sh run_demo.sh 

## 配置参数
1. 修改application.properties中的
kafka.bootstrap-servers=XXX
kafka.consumer.group=XXX
kafka.topic.name=XXX

2. 可根据需求修改相应的source和sink

## 文档
参考 https://docs.spring.io/spring-cloud-stream/docs/current/reference/htmlsingle/

	


