# WebServerBestPractice

## 参考文章

##### [基于spring mvc 移动终端后台开发](http://blog.csdn.net/andyliulin/article/details/46544715)
##### [Rest框架搭建实践（包含服务端、客户端、demo）](http://www.eoeandroid.com/thread-333818-1-1.html?_dsign=9afacd84)


##### [<Building a RESTful Web Service>](http://spring.io/guides/gs/rest-service/#initial)
    "Caused by: java.lang.IllegalStateException: Tomcat connector in failed state"
    
    fixed: $java -jar target/gs-rest-service-0.1.0.jar --server.port=8181
