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

Linux shell command
-----------
File system disk usage : `df -h`

Disk space for a directory : `du -sh [DIRECTORY_PATH]`

Process list : `ps -ef`

High memory consuming processes : `top`

Spark shell command
-----------

spark-shell --master yarn-client --jars [LIST_OF_COMMA_SEPARATED_JARS]

Spark submit command
-----------
 
spark-submit --class [MAIN_CLASS] --master yarn --conf [KEY]=[VALUE] --jars [LIST_OF_COMMA_SEPARATED_JARS] [JAR_TO_EXECUTE] [ARGS]
