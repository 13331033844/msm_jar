# msm_jar
msm_jar相关jar包

MSM介绍
传统tomcat集群，会话复制随着结点数增多，扩展性成为瓶颈。Msm使用memcached完成统一管理tomcat会话，避免tomcat结点间过多会话复制。MSM会话分为sticky与no-ticky模式。

MSM依赖包
spymemcached-2.11.1.jar

reflectasm-1.01.jar

msm-kryo-serializer-1.8.3.jar

msm-javolution-serializer-1.8.3.jar

msm-flexjson-serializer-1.8.3.jar

minlog-1.2.jar

memcached-session-manager-tc8-1.8.3.jar      --tc8为tomcat的版本号。不同版本号tomcat，对应的包不同。此处为tomcat8的jar包

memcached-session-manager-1.8.3.jar

kryo-serializers-0.11.jar

kryo-1.04.jar

asm-3.2.jar

 放到tomcat/lib下
