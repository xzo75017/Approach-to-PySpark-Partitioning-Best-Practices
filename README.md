
# I Partition  
Partitioning is nothing but dividing data structure into parts. In a distributed system like Apache Spark, it can be defined as a division of a dataset stored as multiple parts across the cluster  

    
# II Pyspark  
PySpark is an interface for Apache Spark in Python. It not only allows you to write Spark applications using Python APIs, but also provides the PySpark shell for interactively analyzing your data in a distributed environment.  

## 1 Need of partition  

Applying partitioning we can reduce the number of I/O operations rapidly  
### 1Shuffling  
- Shuffle is a mechanism for redistributing or re-partitioning data so that the data is grouped differently across partitions  
 
### 2 Types of Transformation  

- wide transformation  
- narrow transformation  


### 3 Discuss Approach  

- Approach - 1  
- Approach - 2  



### 4 Business Overview Of Airlines Industry  

- https://openflights.org/  
- https://developer.ibm.com/exchanges/data/all/airline/  
- https://www.bts.dot.gov/topics/airlines-and-airports/quick-links-popular-air-carrier-statistics  

### 5 S3 link for dataset  

- s3://airlines555/airline/data.zip  
 
### 6 Code Description   
    File Name : partition.ipynb , and partition.py   
    DataSets : data.zip  
    File Description : Implement partition techniques  

    
### 7  Steps to Run  
There are two ways to execute the end to end flow.  
- Command Prompt => python script  
- spark_path spark-submit file_path  
- spark_path => <path_to_spark>>  
- file_path => <path_to_file>  
- Data file path is same as script file path  
 
eg. <C:\Users\admin\Desktop\spark\bin>spark-submit C:\Users\admin\Desktop\partition\partition.py>  


- IPython  

### Modular code  
- Create virtualenv  
- Install requirements `pip install -r requirements.txt`  
- Run Code `python partition.py`  
- Check output for all the visualization  
### IPython  
Follow the instructions in the notebook `partition.ipynb`  
