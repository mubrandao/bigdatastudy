#
## The four major components of the Spark platform are as follows:

* Spark Core and RDDs      : is a fundamental data structure of Spark, It is an immutable distributed collection of objects. Each dataset 
                                in RDD is divided into logical partitions, which may be computed on different nodes of the cluster

* Spark SQL		 : A clearing language for Spark

* Spark Streaming		 : Allows you to feed in real-time streaming data

* MLlib (machine learning) : The machine learning library for Spark

* GraphX (graph)		 : The graphing library for Spark
##

#
## Core concepts in Spark and PySpark

* SparkSession       : Since Spark 2.0, SparkSession has become an entry point to Spark to work with RDD, DataFrame, and Dataset

* SparkConf          : SparkConf allows us to configure a Spark application

* Spark shell        : Spark is now available to us as a spark variable

* SparkContext 	   : SparkContext is available since Spark 1.x (JavaSparkContext for Java) and it used to be an entry point to Spark and PySpark before 
                introducing SparkSession in 2.0. Creating SparkContext is the first step to use RDD and connect to Spark Cluster

* Spark applications : Run as independent sets of processes on a cluster and are coordinated by the SparkContext object in the driver program

* Cluster managers   : Supported cluster managers are Standalone, Apache Mesos, and Hadoop YARN
#
## Spark's Toolkit
Low-level  APIs : RDD
Structured APIs : Dataset, Dataframe, SQL
#
## PySpark
#
*What is PySpark?*

PySpark is a Spark library written in Python to run Python applications using Apache Spark capabilities.
Spark basically written in Scala and later on due to its industry adaptation it’s API PySpark released for Python using Py4J. 
Py4J is a Java library that is integrated within PySpark and allows python to dynamically interface with JVM objects, hence 
to run PySpark you also need Java to be installed along with Python, and Apache Spark
#
*PySpark Modules & Packages:*

* PySpark RDD (pyspark.RDD)
* PySpark DataFrame and SQL (pyspark.sql)
* PySpark Streaming (pyspark.streaming)\
* PySpark MLib (pyspark.ml, pyspark.mllib)
* PySpark GraphFrames (GraphFrames)
* PySpark Resource (pyspark.resource) It’s new in PySpark 3.0