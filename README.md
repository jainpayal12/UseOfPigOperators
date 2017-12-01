# UseOfPigOperators
The project illustrates use of different pig operators to perform data operations on large datasets. This is a simple userguide for beginners to get started with pig. It describes examples for commonly used operators with syntax description and understandable output.

### Pre-Requisites
In the use cases illustrated, we will work with PIG in map_reduce mode and interactively(use grunt shell). Hence we make sure that we have all hadoop daemons up and running.
1. Make sure hadoop is configured in the system
2. All hadoop daemons are up and running(start-all.sh)
3. Pig is configured
4. Pig is launched in map_reduce mode. (pig) (Pig by default is launched in map_reduce mode)
5. We have dataset to be worked on, loaded in HDFS.
I:e  grunt > fs -put </path/of/datasetFile/from/LFS>  </path/in/HDFS/To store/Dataset>;

OR 

You can use the cloudera to perform the same where all you have hadoop and pig preconfigured for you. 





