# master-data-centric-algorithms
Master data-centric algorithms, regarding: storage, streaming, and compression

## ✅ Setup Env
- Create Python environment\
`conda create -n env_name python=3.10`\
`conda activate env_name`
- Create Python environment\
`pip install -r .\path_to_requirements\requirements.txt`


## ✅ Data-centric algorithms
- Data classification
  - Volume
  - Velocity
  - Variety
- Data storage algorithm
  - CAP theorem for distributed storage system
    - Consistency (C)
    - Availability (A)
    - Partition tolerance(P)
  - Sub-CAP
    - CA system, ex. Oracle, MySQL
    - AP system, ex. Cassandra
    - CP system, ex. MongoDB
- Data streaming algorithm
  - Types 
    - Batch process --> bounded data / data at rest
    - Streaming process --> unbounded data / data in transit
  - Application of streaming
    - Fraud detection 
    - System monitoring 
    - Smart order routing 
    - Live dashboards 
    - Traffic sensors along highways
    - Credit card transactions 
    - User moves in multi-user online gaming
- Data compress algorithm
  - Reduce the size of data
  - Lossless compression algorithms
    - To compress documents 
    - To compress and package source code and executable files 
    - To convert a large number of small files into a small number of large files