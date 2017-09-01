# "A real case: Spark-assisted analysis of telecom operator Call Detail Records (CDR)"
### [Master in Data Science](http://www.masterdatascience.es/)'s Thesis, by **Miguel-Angel Monjas**

This thesis documents the whole process that has taken out in order to implement a simple analytics project. This project aimed to make sense of a large dataset which contained several months Call Detail Records (CDR) of a telecom operator, Operator X. Operator X serves a small country in Europe and is mainly interested in knowing about the incoming roamers (i.e. subscribers from abroad served by Operator X when they are in the territory served by Operator X). The process this thesis documents goes through the actual knowledge extraction but also infrastructure deployment on an Openstack cloud.

## Infrastructure deployment
The following guidelines have been generated:
1. [Setting up a Hadoop cluster](doc/hadoop-cluster-setup.md).
2. [Running a Standalone Spark cluster](doc/spark-standalone-cluster-setup.md).
   1. [Running Jupyter notebooks on a Spark Standalone cluster](./jupyter-setup.md)
   2. [Running Zeppelin notebooks on a Spark Standalone cluster](./zeppelin-setup.md)
3. [Deploying YARN on a Hadoop cluster](doc/yarn-cluster-setup.md).
4. [Running a Spark cluster on YARN](doc/spark-yarn-cluster-setup.md).

Two different types of Spark clusters are described: Standalone and YARN-based. For the first type, sections 1 ([Setting up a Hadoop cluster](doc/hadoop-cluster-setup.md)) and 2 ([Running a Standalone Spark cluster](doc/spark-standalone-cluster-setup.md)) must be read (including, if wished, the sections for running notebooks). For the second type, sections 1 ([Setting up a Hadoop cluster](doc/hadoop-cluster-setup.md)), 3 ([Deploying YARN on a Hadoop cluster](doc/yarn-cluster-setup.md)) and 4 ([Running a Spark cluster on YARN](doc/spark-yarn-cluster-setup.md)) are relevant.