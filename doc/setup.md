# start zookeeper
sudo JMXPORT=9999 bin/zookeeper-server-start.sh -daemon config/zookeeper.properties

#start kafka
sudo JMX_PORT=9999 bin/kafka-server-start.sh -daemon config/server.properties

#JMX_HOST
JMX采集数据客户端地址

#JMX_PORT
JMX采集数据客户端JMX PORT

#JMX_EXPORTER_CONFIG_FILE
采集规则文件
