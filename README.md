# Redis-Cluster

3-Master and 3-Slave Redis Distributed Cache. The topology is as below:

![](https://github.com/xxu10/Redis-Cluster/blob/master/images/Screen%20Shot%202018-10-18%20at%206.09.34%20PM.png)

First we need to build the cluster, instead of using redis-trib.rb, I used Lettuce(https://lettuce.io/) to do that. I opened 6 Redis instances to simulate 6 nodes in this cluster.
