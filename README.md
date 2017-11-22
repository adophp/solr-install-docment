http://lucene.apache.org/solr/guide/7_1/solr-tutorial.html

#wget https://mirrors.cnnic.cn/apache/lucene/solr/7.1.0/solr-7.1.0.zip
#unzip -q solr-7.1.0.zip
#cd solr-7.1.0/

//启动solr
# ./bin/solr start
//启动所有
#./bin/solr start -all
//停止
#./bin/solr stop -all

//查看solr端口
# ./bin/solr start -force
//查看状态
#./bin/solr status

//Create a Core
#./bin/solr create -c test -force