#apache-tomcat-8.5.6-src

##编译
```bash
ant clean
ant
```

##启动
```bash
java -cp ./output/classes -Dcatalina.home=./output/build org.apache.catalina.startup.Bootstrap
```