# Movie-Recommendation-System

Steps to go on with the code:

1.) Compiling the code: javac -classpath $HADOOP_HOME/share/hadoop/common/hadoop-common-3.2.3.jar:$HADOOP_HOME/share/hadoop/mapreduce/hadoop-mapreduce-client-core-3.2.3.jar:$HADOOP_HOME/share/hadoop/common/lib/commons-cli-1.2.jar -d <file_path> FinalContent.java

2.) Making jar out of the compiled files: jar -cvf <any-file-name>.jar . (lets take it as recom.jar)

3.) Running jar file over the dataset for analysis: hadoop jar recom.jar org.myorg.FinalContent /4horsemen/dataset/input1 /4horsemen/dataset/input2
