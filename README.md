# KGQA
使用方法
1.下载数据
因数据文件过大，所以将文件放到北大网盘：https://disk.pku.edu.cn:443/link/239AEAA9A2A27EE7134ED6EFC7F2BFCC（有效期限：2021-06-30 23:59）。
下载完成后放入到data/文件夹内即可。

2. 修改配置文件路径
修改DouBan-KGQA/json2jena/rdf2jena/apache-jena-fuseki-3.10.0.2/run/configuration/fuseki_conf.ttl中ja:rulesFrom和tdb:location路径地址。

3.启动Apache Server
进入到DouBan-KGQA/json2jena/rdf2jena/apache-jena-fuseki-3.10.0.2/路径下，启动fuseki-server。

cd DouBan-KGQA/json2jena/rdf2jena/apache-jena-fuseki-3.10.0.2/ 
./fuseki-server

4.启动query_main.py
启动query_main.py进行知识图谱问答。

python query_main.py

5.配置好公众号，可以通过python query_server.py 80开启服务，通过公众号问答。
