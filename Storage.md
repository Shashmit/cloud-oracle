###Storage
- Understand Storage
  - Persisten Storage & Non Persistent Storage.
  - What types of Storage.
- Performance
  - Capacity
  - IOPS
  - Throughput
- Durability
  - How many copies.
- Connectivity
  - Local Storage
  - Network Storage
  - How to access data
- Protocol
  - Block
  - File
  - HTTP
- And Many More
  
----
`Local NVME`
- High Speed NVME Storage, Higher IOPS

`Block Volume`
  - High persistent, Fixed Sized Block, Partition of Disk

`File Storage`
 - Storage is shared more like one handles in files and directory

`Object Storage`
  - Simple Storage<PUT, GET> like Photos and all.

###OCI Object Storage ----
- Internet-scale, high performance storage platform.
- Data Managed as Object
- Ideal for Unstructured data
- Multiple Storage tiers
- Regional and Public Service
  >Uses : Content Repository, Big Data/Spark/ Data Analytics, Archive/Backup
  - Object is [Key,Value] pair in a `Bucket`.
  - It is based on a flat Hierachy and a namespace.
  - Thats how you access the file from anywhere.

####Tiers
>- Standard Storage Tier
>- Infrequent Access
>- Archive Storage Tier
>Auto Tiering: Which can manipulate as per your need and change in pattern
>Life cycle Management: To switch data from one tier to other if not utilised.
>Version: As the name suggest information can be changed so you can have multiple versions of same file.

###Block Volume
- One can connect to the block volume throught the compute instance.
- Creater and attach disk -> detach disk ->keep data even after you delete the instance.
- Persistent: Safe storage, Durable.
  `Tiers`
  - Lower Cost
  - Balanced
  - Higher Performance
  - Ultra High Performance
  - Auto Tune Performance
- Encrypted by the Oracle syatem
- Read/Write Shareable to multiple Instance.
- Resizing of Block Volume
- Replication of Block Volume
- Volume Groups : TO group multiple group volume.


