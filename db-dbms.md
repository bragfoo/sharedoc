## DB DBMS

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
