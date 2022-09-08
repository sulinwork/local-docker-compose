## 可能启动失败
- 启动后 可能出现把./broker/conf/broker.conf 这个文件当做了目录
- 可以先把这个目录删除 然后新建一个broker.conf文件
```
brokerClusterName = DefaultCluster
brokerName = broker-a
brokerId = 0
deleteWhen = 04
fileReservedTime = 48
brokerRole = ASYNC_MASTER
flushDiskType = ASYNC_FLUSH
# 如果是公网的机器部署 比如:阿里云  这里需要加上
# brokerIP1=公网IP
```