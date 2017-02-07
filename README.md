# BigData

How to run a word count example of map reduce framework in hadoop cluster.:--

create a project "WordCount" in eclipse IDE.
Export jar of this project to your Desktop.
Make a HDFS directory: hadoop fs -mkdir -p /user/local/hadoop/Input
Copy input text file from local to hdfs:hadoop fs -copyFromLocal /home/hduser/Desktop/test/input.txt /user/local/hadoop/Input
hadoop jar /home/hduser/Desktop/wordcount2.jar PackageDemo.WordCount /user/local/hadoop/Input/input.txt /user/local/hadoop/Output


