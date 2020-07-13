# snowflake-spark-connector

In this example, the code uses snowflake-spark-connector and snowflake-jdbc driver to connect to a snowflake database from spark and perform some processing.

## Create an EMR cluster
Version used: 5.30.0 with Spark 2.4.5 and Scala 2.11.12

## Download the latest snowflake-spark-connector and snowflake-jdbc drivers
For this example, I downloaded the latest snowflake-spark-connector and snowflake-jdbc driver jars on to the EMR cluster.
We could also refer to the corresponding packages from the maven repository

## Spark Command line interface for development
For this example, I used the Spark command line interface with Scala, by issuing 
    spark-shell --jars snowflake-jdbc-3.12.8.jar,spark-snowflake_2.11-2.8.0-spark_2.4.jar


