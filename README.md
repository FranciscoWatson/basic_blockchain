# basic_blockchain
## **What This Project (will do) Does**

This project implements a simple blockchain in **Rust** with the following features:

1. **Block Structure**: 
   - Each block contains an index, timestamp, data, previous hash, and current hash.
   - The hash is generated using the SHA-256 algorithm to ensure integrity.

2. **Blockchain Implementation**:
   - A linked chain of blocks where each block references the hash of the previous block.
   - Includes a genesis block (the first block in the chain).

3. **Proof of Work (PoW)**:
   - Implements a basic mining mechanism to add new blocks by solving a computational puzzle.

4. **Chain Validation**:
   - Verifies the integrity of the blockchain by checking hashes and links between blocks.

5. **Command-Line Interaction**:
   - Add new blocks with custom data.
   - View the current state of the blockchain.

6. **Data Persistence**:
   - Store the blockchain locally using JSON or another storage format.

7. **Networking**:
   - Create a basic peer-to-peer network to share and validate blocks between nodes.

8. **Transactions**:
   - Introduce a system for adding and validating transactions within blocks.

This project is intended as a learning tool to explore the fundamentals of blockchain technology and Rust programming.

