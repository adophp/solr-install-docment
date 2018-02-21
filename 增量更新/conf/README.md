1、将jar包上传到solr目录下的/server/lib
2、将conf文件夹上传到/server/solr
3、修改server/solr-webapp/webapp/WEB-INF/web.xml
  在servlet标签前添加：
  <listener>  
    <listener-class>org.apache.solr.handler.dataimport.scheduler.ApplicationListener</listener-class>  
  </listener>

注意solr默认的是UTC时区，需要修改成Asia/Shanghai