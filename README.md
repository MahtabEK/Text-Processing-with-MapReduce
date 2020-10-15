# Text-Processing-with-MapReduce
The goal of this project is to gain experience with the MapReduce programming model, text processing, and index development. 

**Programming Language**

You can use either Java or Python. Python is strongly recommended.

**Part 0: VM Setup**

I have used Cloudera for thid project. Cloudera is a company that provides Apache Hadoop.I was provided with a virtual machine (VM) that is hosted on the cluster.

**Part 1: Determining the number of Starbucks in a City**

There is a dataset consisting of information about each Starbucks location. I used MapReduce to provide for each city the number of Starbucks located in that city.  The input is a csv file, starbucks-locations.csv, and the output is be a file, cityInformation, where each line represents a city and the number of Starbucks located in that city. 

**Part 2: Inverted Index**

I built an inverted index that supports queries for movies based on movie genres. A query can take one of the following forms:

- A single movie genre  e.g., Drama, Comedy.

- Boolean search queries with either only AND or only OR.  For example, “Drama OR Comedy” or “Drama AND Comedy”. It supports the use of one Boolean operator and the user can assume that this program is case agnostic.

Some of the movies are not associated with a genre. I have an entry, “ None”, for those movies.

**Part 3: Inverted Index**
