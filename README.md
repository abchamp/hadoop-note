# HADOOP MY NOTE

# Courses 1

## The Ultimate Hands-On Hadoop: Tame your Big Data!

- Download grouplen.org => older datasets MovieLens 100K Dataset

### Section 2: Using Hadoop's Core: HDFS and MapReduce

```
hadoop fs -ls
hadoop fs -mkdir ml-100k
wget http://media.sundog-soft.com/hadoop/ml-100k/u.data
hadoop fs -copyFromLocal u.data ml-100k/u.data
hadoop fs -rm ml-100k/u.data
hadoop fs -rmdir ml-100k/u.data
```

- MapReduce flow
- Tabular data => mapper => shuffle and sort => reducer
- write mapReduceScript with PYTHON Langauge
- map => reduce => map => reduce
- mainly sql command
- ใช้แก้ปัญหาที่เป็นสามารถแบ่งตัวได้

### Section 3: Programming Hadoop with Pig

- Ambari => Dashboard
- Pig => Pig Latin to Script (like SQL Style)
- Top of Tez (run job called a directed acyclic graph = optimi)
- UFD's user Defined function (custom function) - exension of pig
- GRUNT, Script, Ambari/Hue

# Courses 2

Data Anaytics with Hadoop - An Introduction for Data Scientists.
[Wait]
