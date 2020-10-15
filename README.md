# Text-Processing-with-MapReduce
The goal of this project is to gain experience with the MapReduce programming model, text processing, and index development. 

**Programming Language**

You can use either Java or Python. Python is strongly recommended.

**Part 0: VM Setup**

I have used Cloudera for thid project. Cloudera is a company that provides Apache Hadoop.I was provided with a virtual machine (VM) that is hosted on the cluster.

**Part 1: Determining the number of Starbucks in a City**

There is a dataset consisting of information about each Starbucks location. I used MapReduce to provide for each city the number of Starbucks located in that city.  The input is a csv file, starbucks-locations.csv, and the output is be a file, cityInformation, where each line represents a city and the number of Starbucks located in that city. 

This part's solution can be found in Part1.zip. When unzipped there are three files: mapper.py, reducer.py, and query.py.  

**Part 2: Inverted Index**

I built an inverted index that supports queries for movies based on movie genres. A query can take one of the following forms:

- A single movie genre  e.g., Drama, Comedy.

- Boolean search queries with either only AND or only OR.  For example, “Drama OR Comedy” or “Drama AND Comedy”. It supports the use of one Boolean operator and the user can assume that this program is case agnostic.

Some of the movies are not associated with a genre. I have an entry, “ None”, for those movies.

This part's solution can be found in Part2.zip. When unzipped there are two files: indexer.py and query.py which represents the query code.

**Part 3: Inverted Index**

I built an inverted index using MapReduce with the same functionality as in Part 2.

This part's solution can be found in Part3.zip. When unzipped there are three files: mapper.py,  reducer.py and query.py.

**Part 4: Some Questions**

- Describe the design you used for Part 1 and 3.  This should include the keys and values you used.

- What else would you have done in the inverted index implementation, given more time, energy, resources, etc.?

- How difficult was it to implement the inverted index? How difficult would it be to implement another task, given this experience?

- What would be straightforward? What would take more time?

The answers to these questions can be found in Answers.pdf.


**Resources**

1) Michael G. Noll, Writing an Hadoop MapReduce Program in Python

2) J. Dean  and S. Ghemawat. “MapReduce: Simplified Data Processing on Large Clusters”, in Proceedings of the 6th Conference on Operating Systems Design & Implementation." Berkeley, CA, USA: USENIX Association (2004): 10-10.

3) Hadoop  shell commands to manage HDFS: HDFS File System Commands

4) Wikipedia entry for Makefile
