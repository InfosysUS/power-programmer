# Mesos

![](https://files.slack.com/files-pri/T5ZCCM18S-FBYKT2FUG/infosys_pp_github_infographic-02.png)
Apache Mesos is an open source cluster manager that we Power Programmers use to simplify running applications on scalable server clusters.

Originally developed at the University of California at Berkeley, Mesos sits between the application layer and the operating system and makes it easier to deploy and manage applications in large-scale clustered environments more efficiently. It can run many applications on a dynamically shared pool of nodes. Alongside Infosys, other prominent users of Mesos are Twitter, Airbnb, MediaCrossing, Xogito and Categorize.

Mesos leverages features of the modern kernel—"cgroups" in Linux, "zones" in Solaris—to provide isolation for CPU, memory, I/O, file system, rack locality, etc. The big idea is to make a large collection of heterogeneous resources. Mesos introduces a distributed two-level scheduling mechanism called resource offers. Mesos decides how many resources to offer each framework, while frameworks decide which resources to accept and which computations to run on them. It is a thin resource sharing layer that enables fine-grained sharing across diverse cluster computing frameworks, by giving frameworks a common interface for accessing cluster resources.The idea is to deploy multiple distributed systems to a shared pool of nodes in order to increase resource utilization. A lot of modern workloads and frameworks can run on Mesos, including Hadoop, Memecached, Ruby on Rails, Storm, JBoss Data Grid, MPI, Spark and Node.js, as well as various web servers, databases and application servers.

Why we use it:

* Scalability to over 10,000 nodes
* Resource isolation for tasks through Linux Containers
* Efficient CPU and memory-aware resource scheduling
* Highly-available master through Apache ZooKeeper
* Web UI for monitoring cluster state

[You can see all of the Power Programmer’s key technology areas here.](https://github.com/InfosysUS/power-programmer/blob/master/Key%20Technology%20Areas.md)
