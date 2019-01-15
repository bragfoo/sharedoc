# sys infra’s road

- 6.824
  - LEC
    - Intro
    - RPC,Threads,crawler,K/V
    - GFS
    - Primary-Backup Replication
    - Fault Tolerance:Raft
    - Spinnaker
    - Zookeeper
    - Distributed Transactions
    - Optimistic Concurrency Control
    - Big Data: Spark
    - Big Data: Naiad
    - Distributed Machine Learning: Parameter Server
    - Cache Consistency: Memcached at Facebook
    - Disconnected Operation,Eventual Consistency
    - Peer-to-peer,DHTs
    - Dynamo
    - Peer-to-peer: Bitcoin

  - LAB
    - mapreduce
    - raft
    - kvraft
    - shardmaster

## Modern Operating Systems

- concepts
  - Processes
  - Address Spaces
  - Files
  - Input / Output
  - Protection

- Processes And Threads
  - Scheduling
  - Processes
    - Creation
    - Hierarchies
    - States
    - Termination

  - Threads

    - Thread Usage
    - POSIX Threads
    - Scheduler
    - Thread Implements
      - Kernel Space
      - User Space
      - Hybird

  - Interprocess Communication
    - Race Conditions
    - Critical Regions
    - Read Copy Update
    - Mutual Exclusion with Busy Waiting
    - Sleep and Wakeup
    - Semaphores
    - Mutexes
    - Monitors
    - Barriers

- Memory Management
  - Address Spaces
  - Virtual Memory
  - Page Replacement Algorithms
  - Design Issues For Paging Systems
  - Segmentation

- File Systems
  - Files
    - Naming
    - Structure
    - Types
    - Access
    - Attributes
    - Operations

  - Directories
    - Single-Level Directory System
    - Hierarchical Directory Systems
    - Path Names
    - Directory Operations

## Machine Learning

- Neural Networks And Deep Learning
  - 感知机
    - 感知机实现
    - 感知机的局限性
    - 多层感知机

  - 神经网络
    - 感知机与神经网络
    - 多位数组运算
    - 激活函数
    - 实现三层神经网络
    - 输出层设计
    - 损失函数
    - 梯度
    - 数值微分

  - 误差反向传播法
    - 计算图
    - 链式法则
    - 反向传播
  - CNN
  - 深度学习

## DB&DBMS

- K/V
  - Redis
    - data structure
      - 简单动态字符串
      - 链表
      - 字典
      - 跳跃表
      - 压缩列表
      - 对象
    - Single Node Database
    - Multi Node Cluster
- TSDB
  - Prom
  - InfluxDB
- Relational
  - Mysql
    - Engine
      - InnoDB
        - Structure
          - Checkpoint
          - Master Thread
          - Write Buffer
          - doublewrite
          - Adaptive Hash Index
          - AIO
          - Flush Meighbor Page
        - File
          - Config File
            - my.cnf
          - Log File
            - Error Log
            - Binlog
            - Slow query log
            - log(查询日志)
          - Socket FIle
          - Pid File
          - Table File
        - Tables
          - tablespace
          - segment
          - extent
          - page/block
          - B-tree Node
          - undo Log Page
          - System Page
          - Transaction system Page
          - Insert Buffer Bitmap
          - Insert Buffer Free List
          - Uncompressed BLOB Page
          - compressed BLOB Page
        - Storage Engine
          - Index
            - B+
            - 全文索引
            - 哈希索引
      - MyISAM
- Management

## Network
