该数据库在etcd的基础上，实现了http 服务、命令行交互、支持string值类型、wal快照储存，是一个多副本、高可用、高容忍度的分布式kv数据库
该项目划分为三部分，http服务、存储服务和raft服务，各服务间通过信道交互
目前已成功在局域网部署
