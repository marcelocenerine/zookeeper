# zookeeper

https://zookeeper.apache.org/


```
docker run -d \
-e MYID=1 \
-e SERVERS=node-1,node-2,node-3 \
-p 2181:2181 -p 2888:2888 -p 3888
--name=zookeeper --net=host --restart=always marcelocenerine/zookeeper:3.4.6

```

