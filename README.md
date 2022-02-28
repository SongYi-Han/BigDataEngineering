# BigDataEngineering
this is an pilot project to analyze data generated from smart car : 1) collect log file from diverse devices in smart car and inspect the status 2) collect live streamed log of diriver's driving information and anlyze the driving pattern.
  
In this project, we restrict the number of car to 100 and use log simulator. 
  

**Software Architecture** 
1. Data Sources 
- Flume, Storm, Esper 
  
  
  
2. Data Storage
- HDFS : Hadoop
- NoSQL : HBase
- in-memory db: Redies
- message middleware: kafka 
  
  
  
3. Data Processing 
- Hue, Hive, SparkSQL, Oozie
  
  
4. Data Analysis
- Impala, Zeppelin, Mahout, R, Tensorflow, Sqoop

  
  
**Hardware Architecutre** 
- server01 : Hadoop Management nodes, Hadoop dataNodes, HBase Management, HBase Region server, PostgreSQL 
- server02 : Hadoop DataNode, HBase region, OOzie, Flume, Redies, Hive/Spark, Storm, Hue, Zeppelin, Kafka, zookeepe
- server03 : Hadoop DataNode, HBase region, Cloudera Management, Impala, Sqoop
