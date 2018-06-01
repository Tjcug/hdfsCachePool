# hdfsCachePool
Hadoop Distributed File System (HDFS) has slow serial read speed of the log stream file, it cannot meet the requirements of the stream processing system and can not fully exert the processing capability of the stream processing system, thus restricting the stream processing system. Improve performance. On the basis of HDFS, this software adopts parallel data transmission methods to fully utilize network bandwidth and effectively improve the throughput of distributed file system and meet the demand of stream processing system for data source throughput. At the same time, with respect to the highly ordered nature of the log stream, the software controls the timing of the data to ensure the timing of the log file and provides high-speed and orderly data input for the stream processing system.
