
## dubbo + spring mvc + mybatis + mysql 简单实例


## 作者 ddr2@foxmail.com   (大头)

## 项目主要用的技术及版本
	Dubbo 2.5.3
	Spring 4.2.5
	Mybatis 3.4.0
	Mysql 5.5
	
## 项目运行环境

Jdk 1.7.0_67 
Tomcat 7.0.69 


## zk配置文件位置及mysql配置文件位置

+ 1 test-dubbo-web-provider 项目中的 resources/context/dubbo-pro.xml 
+ 2 test-dubbo-web-consumer 项目中的 resources/context/dubbo-cm.xml
+ 3 test-dubbo-web-provider 项目中的 resources/context/datasource.xml



## 运行地址

	http://localhost:8080/test-dubbo-web-consumer/
	
	provider中的controller主要用来查看本地调用service与consumer中调用service时间上的差距！

	http://localhost:8080/test-dubbo-web-provider/
	
	两个项目可以做任意分开部署，注意一下本地测试时端口
	






