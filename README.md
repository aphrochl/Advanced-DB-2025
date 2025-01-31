# Advanced-DB-2025

## [Local Notebook](./Local/AdvancedDataBase.ipynb):

How to run the notebook locally:

## Windows 10/11:

### Requirements:
---------------------
1. Python 3
2. Pyspark
3. Apache Hadoop
4. Apache Sedonna

### Set up:
-------------------
1. Download and install [Python](https://www.python.org/downloads/release/python-3119/). We will be using Python 3.11.9 for compatibility purposes.
Make sure to add python to Path.

2. Open command prompt and install pyspark with pip:

```
pip install pyspark
```

3. Download [Apache Hadoop](https://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-3.3.6/hadoop-3.3.6.tar.gz) and extract its files to your prefered path (we use version 3.3.6)
In the __System Environment Variables__ make the following additions:
    
    - Add __path\to\hadoop\bin__ to __Path__
    - Create a variable __HADOOP_HOME__ with value __path\to\hadoop__

4.