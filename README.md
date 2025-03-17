# LSM-Based Storage Engine

This project implements a simplified LSM-based storage engine in C++. It includes support for compaction and efficient range queries.

## Features
- **MemTable**: In-memory structure for recent writes.
- **SSTable**: On-disk structure for storing sorted key-value pairs.
- **Compaction**: Merges smaller SSTables into larger ones to improve read performance.
- **Range Queries**: Efficiently retrieves all keys within a specified range.

## How to Run
1. Compile the code:
   ```bash
   g++ lsm_storage.cpp -o lsm_storage
   
2. Run the executable:
   ```bash
   ./lsm_storage
