# msm_jar
msm_jar相关jar包

MSM介绍
传统tomcat集群，会话复制随着结点数增多，扩展性成为瓶颈。Msm使用memcached完成统一管理tomcat会话，避免tomcat结点间过多会话复制。MSM会话分为sticky与no-ticky模式。

MSM依赖包
spymemcached-2.12.3.jar
reflectasm-1.11.7.jar
objenesis-3.0.1.jar
msm-kryo-serializer-2.3.2.jar
minlog-1.3.0.jar
memcached-session-manager-tc9-2.3.2.jar --tc9为tomcat的版本号。不同版本号tomcat，对应的包不同。此处为tomcat9的jar包
memcached-session-manager-2.3.2.jar
kryo-serializers-0.42.jar
kryo-4.0.2.jar
asm-7.0.jar

 放到tomcat/lib下
