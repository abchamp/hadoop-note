# hadoop-note

# Courses 1
The Ultimate Hands-On Hadoop: Tame your Big Data!

- Download grouplen.org => older datasets MovieLens 100K Dataset

*The Ultimate Hands-On Hadoop: Tame your Big Data!

Section 2: Using Hadoop's Core: HDFS and MapReduce
```
hadoop fs -ls
hadoop fs -mkdir ml-100k
wget http://media.sundog-soft.com/hadoop/ml-100k/u.data
hadoop fs -copyFromLocal u.data ml-100k/u.data
hadoop fs -rm ml-100k/u.data
hadoop fs -rmdir ml-100k/u.data
```

# Courses 2
Data Anaytics with Hadoop - An Introduction for Data Scientists.
[Wait]