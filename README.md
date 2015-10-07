# A Generate-Test-Aggregate Automatic Parallelization Programming library for MapReduce (on Spark)

This library is an implementation of Yu Liu's academic paper:

  Yu Liu, Kento Emoto, Zhenjiang Hu, A Generate-Test-Aggregate Parallel Programming Library for Systematic Parallel Programming,  Parallel Computing, Available online 10 December 2013, ISSN 0167-8191, Elsevier.

It provides a high performance scalable parallel programming DSL so-called Generate-Test-Aggregate.
The source code is under the GNU GPL v2.0 license

#High Level Parallel Programming
This GTA library provides a domain-specific-language style programming environment, and users
can write GTA programs in a sequential manner, which will be transformed to efficient MapReduce
programs.

This library is implemented in Scala and using the generic programming technique. All components
of this library are well typed and can be easily extended.

This library is designed on a high abstraction level, so that is can be easily ported to various of
parallel computation environments including multi-core/multi-threads, GPU, and distributed cluster.

#Working with Apache Spark(TM) and Hadoop
GTA library can work with either Spark or Hadoop or any other framework that has API of MAP and REDUCE. Current version only contains Spark version. If you need Hadoop version, please contact me.

# Build from source
1.  $ git clone https://bitbucket.org/inii/gtalib.git
2.  $ cd gtalib
3.  $ sbt compile

# The auther's home page 
http://www.prg.nii.ac.jp/members/yuliu/index.html
