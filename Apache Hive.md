# Apache Hive

Apache Hive is an open-source data warehouse system that we use to query and analyze large datasets stored in Hadoop files.

It supports queries expressed in a language called HiveQL, which automatically translates SQL-like queries into MapReduce jobs executed on Hadoop. In addition, HiveQL supports custom MapReduce scripts to be plugged into queries. Hive also enables data serialization/deserialization and increases flexibility in schema design by including a system catalog called Hive-Metastore.

According to the Apache Hive wiki, "Hive is not designed for OLTP workloads and does not offer real-time queries or row-level updates. It is best used for batch jobs over large sets of append-only data (like web logs)." 

Hive supports text files (also called flat files), SequenceFiles (flat files consisting of binary key/value pairs) and RCFiles (Record Columnar Files which store columns of a table in a columnar database way.)

Hive adds extensions to provide better performance in the context of Hadoop and to integrate with custom extensions and external programs. It is well suited for batch processing data like: log processing, text mining, document indexing, customer-facing business intelligence, predictive modeling and hypothesis testing.

[You can see all of the Power Programmer’s key technology areas here.](https://github.com/InfosysUS/power-programmer/blob/master/Key%20Technology%20Areas.md)
