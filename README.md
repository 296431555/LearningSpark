# The _LearningSpark_ Project

# NOTE: This code now uses Spark 2.0.0 and beyond -- if you are still using an earlier version of Spark you may want to work off the before_spark2.0.0 branch.

This project contains snippets of Scala code for illustrating various
Apache Spark concepts. It is
intended to help you _get started_ with learning Apache Spark (as a _Scala_ programmer) by providing a super easy on-ramp that _doesn't_ involve Unix, cluster configuration, building from sources or
installing Hadoop. Many of these activities will be necessary later in your
learning experience, after you've used these examples to achieve basic familiarity.

It is intended to accompany a number of posts on the blog
[A River of Bytes](http://www.river-of-bytes.com).

## Dependencies

The project was created with IntelliJ Idea 14 Community Edition,
JDK 1.7, Scala 2.11.2 and Spark 2.0.0 on Ubuntu Linux.

Versions of these examples for other configurations (older versions of Scala and Spark) can be found in various branches.

## Java Examples

These are much less developed than the Scala examples below.
Note that they use Java 7 and Spark 2.0.0 only -- if you go back to the before_spark2.0.0 branch
you won't find any Java examples at all. I'm adding these partly out of curiosity (because I like Java
almost as much as Scala) and partly because of a realization that lots of Spark programmers use Java.
There are a number of things it's important to realize I'm *not* promising to do:
* Rush to catch up with the Scala examples
* Keep the two sets of examples perfectly matched
* Keep working on the Java examples
* Add Python and R as well (this is _really_ unlikely)

| Package | What's Illustrated    |
|---------|-----------------------|
| [rdd](src/main/java/rdd) | The JavaRDD: core Spark data structure -- see the local README.md in that directory for details. |
| [dataset](src/main/java/dataset) | A range of Dataset examples (queryable collection that is statically typed) -- see the local README.md in that directory for details. |
| [dataframe](src/main/java/dataframe) | A range of DataFrame/Dataset<Row> examples (queryable collection that is dynamically typed) -- see the local README.md in that directory for details. |


## Scala Examples

The examples can be found under src/main/scala. The best way to use them is to start by reading the code and its comments. Then, since each file contains an object definition with a main method, run it and consider the output. Relevant blog posts and StackOverflow answers are listed in the various package README.md files.

| Package or File                  | What's Illustrated    |
|---------------------------------|-----------------------|
|          Ex1_SimpleRDD         | How to execute your first, very simple, Spark Job. See also [An easy way to start learning Spark](http://www.river-of-bytes.com/2014/11/an-easy-way-to-start-learning-spark.html).
|          Ex2_Computations      | How RDDs work in more complex computations. See also [Spark computations](http://www.river-of-bytes.com/2014/11/spark-computations.html). |
|          Ex3_CombiningRDDs     | Operations on multiple RDDs |
|          Ex4_MoreOperationsOnRDDs | More complex operations on individual RDDs |
|          Ex5_Partitions        | Explicit control of partitioning for performance and scalability. |
|          Ex6_Accumulators | How to use Spark accumulators to efficiently gather the results of distributed computations. |
| [hiveql](src/main/scala/hiveql)  | Using HiveQL features in a HiveContext. See the local README.md in that directory for details. |
| [special](src/main/scala/special) | Special/adbanced RDD examples -- see the local README.md in that directory for details. |
| [dataset](src/main/scala/dataset) | A range of Dataset examples (queryable collection that is statically typed) -- see the local README.md in that directory for details. |
| [dataframe](src/main/scala/dataframe) | A range of DataFrame examples (queryable collection that is dynamically -- and weakly -- typed)-- see the local README.md in that directory for details. |
| [sql](src/main/scala/sql) | A range of SQL examples -- see the local README.md in that directory for details.  |
| [streaming](src/main/scala/streaming) | Streaming examples -- see the local README.md in that directory for details.  |
| [graphx](src/main/scala/graphx) | A range of GraphX examples -- see the local README.md in that directory for details. |


Additional Scala code is "work in progress". 
