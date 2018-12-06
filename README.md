Analyzing Reddit Data with MapReduce

This program takes text files as input and runs Hadoop MapReduce on them to calculate the impact of an image given as
the sum of all interactions (upvotes, downvotes, comments), and presents them in sorted order outputs

Main class is redditHadoop.ImageImpact

Export project as JAR and put JAR and input file on HDFS

To run:

$hadoop <jar> <main class> <input file> <output location (MUST BE UNIQUE(>

