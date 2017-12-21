HDFS Commands
-----------

List directory : `hadoop fs -ls [DIRECTORY_PATH]`

Remove directory : `hadoop fs -rm -r [DIRECTORY_PATH]`

Create directory : `hadoop fs -mkdir [DIRECTORY_PATH]`

Remove file : `hadoop fs -rm [FILE_PATH]`

Head file : `hadoop fs -cat [FILE_PATH] | head`

Copy file from local : `hadoop fs -copyFromLocal [LOCAL_FILE_PATH] [HDFS_FILE_PATH]`

Copy file to local : `hadoop fs -copyToLocal [HDFS_FILE_PATH] [LOCAL_FILE_PATH]`

Copy file hdfs to hdfs : `hadoop fs -cp [HDFS_SOURCE_FILE_PATH] [HDFS_DESTINATION_FILE_PATH]`

Move file hdfs to hdfs : `hadoop fs -mv [HDFS_SOURCE_FILE_PATH] [HDFS_DESTINATION_FILE_PATH]`

Spark shell command
-----------

spark-shell --master yarn-client --jars /home/hilabs/downloads/mysql-connector-java-5.1.39-bin.jar,/home/hilabs/downloads/spark-core-0.0.1-SNAPSHOT-jar-with-dependencies.jar
