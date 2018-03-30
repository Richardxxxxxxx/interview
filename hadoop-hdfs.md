(the resources coverd reference from Prof. C.L. Wang's lecture slides)

1.X

JobTracker and TaskTracker

JobTracker is responsible for allocating resource and supervising application.

2.X

ResourceManager and Nodemanager

ResourceManager allocates resource for a application, once created a application master(AM,a container) in a node,

the AM will be responsible for supervising  other container(Map task or Redeuce takse).

adavantages:
1.mutiple applications run simultaneously(mutiple AM)

2.dynamic allocation, has containers of different size in one node

![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/hadoop-version.jpeg)

HDFS:
namenode only keep some metadata(to avoid namenode to be too busy),data transfer directly from each datanode
![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/HDFS.jpeg)

HDFS write and replicate policy:

![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/replicate-1.jpeg)
![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/replicate-2.jpeg)
![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/replicate-3.jpeg)
![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/replicate-4.jpeg)
![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/replicate-5.jpeg)
![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/replicate-6.jpeg)


HDFS read policy:

![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/hdfs-read.jpeg)

HDFS heart beat policy:

![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/hdfs-heart-beat.jpeg)

HDFS deals with missing replicas policy:

![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/hdfs-missing-replicas.jpeg)

HDFS secondary namenode policy:

![alt text](https://github.com/Richardxxxxxxx/interview/blob/master/image/secondary-namenode.jpeg)
