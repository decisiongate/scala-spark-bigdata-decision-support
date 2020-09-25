# Scala application using Spark for Big Data driven decision support

## Table of contents
* [General info](#general-info)
* [Technology stack](#technologies)
* [Setup](#setup)
* [Usage](#usage)

## <a id="general-info" />General info
Building applications for summary statistics for decision support using Apache Spark and Scala.
	
## <a id="technologies" />Technology stack
The project is created with:
* Scala: 2.12.12
* Apache Spark: 3.0.0 
* Maven Scala Plugin: 2.15.2
* IntelliJ IDEA (Ultimate Edition)
* OpenJDK, Java 1.8.0
* SBT 1.2.1
* Windows binaries for Hadoop versions: winutils
* Apache Hive Configuration Properties (providing data query and analysis, a SQL-like interface to query data stored in various databases and file systems that integrate with Hadoop).
	
## <a id="setup" />Setup
To run this project, install it on Linux (Debian 9.7 x64) using the scripts:

```
$ install-Apache-Spark.sh
$ install-Scala.sh
$ install-SBT.sh
$ install-Python-packages-tools.sh
$ install-Apache-Hadoop-in-Stand-Alone-Mode.sh
```

Download libraries from Maven Repository ( mvnrepository.com ):

```
org.apache.spark:spark-core_2.12:3.0.0
org.apache.spark:spark-sql_2.12:3.0.0
org.apache.spark:spark-mllib_2.12:3.0.0
```

## <a id="usage" />Usage
```
...
```
