LoginAndRegister
JavaWeb实现登录注册功能，有数据库

需要的知识以及项目环境
1.客户端：HTML CSS JS （JQuery）
2.服务器：JAVA  JSP   Servlet  JDBC  Tomcat
3.数据库：MySQL
4.本地数据库名为login,表为user
5.需要导入的jar包：
    
    1.commons-dbutils-1.7.jar
    2.druid-1.1.12.jar
    3.mysql-connector-java-8.0.13.jar
    4.servlet-api.jar

项目结构
1.数据库：MySQL实现数据存储
2.服务器：
  
   1.DAO层，负责数据库操作，CRUD
   2.Service层，处理业务逻辑，通过调用DAO层保存到数据库
   3.Web层，用Servlet实现，获取请求参数封装成Bean对象，调用Service处理业务，并将相应数据发送给客户段请求转发
   
3.客户端：最终将结果响应到浏览器上
   
