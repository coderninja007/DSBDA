# Semester-6
SPPU Computer TE-Sem 2 Assignments
Steps for WordCount Execution program

/* 

run daemons
$ start-all.sh
$ start-dfs.sh

Pass@123
*/

$ mkdir words

$ javac -classpath hadoop-core-1.2.1.jar words/WordCount.java

$ jar -cvf words.jar -C words/ .

$ hadoop fs -mkdir /words

$ hadoop fs -put fruits.txt /words

$ hadoop jar words.jar WordCount /words /output

~$ hadoop fs -ls /output

~$ hadoop fs -cat /output/part-r-00000

//replace output with any name

//Assignments name //

A1 = Data wrangling - 1 (1. Locate open source data ...) \
A2 = Data Wrangling -2  (1. scan all variables ....) \
A3 = Descriptive Statistics - Measures of central Tendency and Variability (1. Provide summary statistics (means,mediam ..) \
A4 = Data Analytics -1 (Create a linear Regression Model ...) \
A5 = Data Analytics- 2 (1. Implement logistics regression ...) \
A6 = Data Analytics -3 (1. Implement Simple Naive Bayes ...) \
A8 = Data Visualization -1 (1. Use the inbuilt dataset 'titanic' contain 891 rows...) \
A9 = Data Visualization -2 (1. Use the inbuilt dataset 'titanic' as used in above problem. ...) \
A10 = Data Visualization -3 (1. List down the features ...(iris)) \
A11 = Aim : Write a code in java for a simple WordCount  \
A12 = Aim : Design a distributed application using MapReduce ...  \

