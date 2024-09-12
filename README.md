# BlockChaining
Title : Blockchain-based File Integrity Checker in Python

Project Description:
This project implements a basic file integrity checking system using blockchain technology. It hashes file contents and records these hashes in a blockchain. This ensures that any tampering with the file can be detected by verifying the integrity of the blockchain.

Explanation:
Block Class:

Defines the structure of a block in the blockchain with properties for index, timestamp, file hash, previous hash, proof, and the block's hash.
FileIntegrityBlockchain Class:

Initialization: Starts with creating the Genesis Block.
Add File: Allows adding files to the blockchain by hashing their contents and creating a new block.
Hash File: Computes the SHA-256 hash of the file's contents.
Proof of Work: Ensures each block is valid through a computational process.
Chain Validation: Verifies the integrity of the blockchain to detect any tampering.
Display Chain: Shows the details of each block in the chain.
Example Usage:

Adds files to the blockchain (you need to create example_file_1.txt and example_file_2.txt or modify the file paths accordingly).
Checks the validity of the blockchain.
Displays the entire blockchain.
Usage:
Add Files: Modify the add_file calls to add different files to the blockchain.
Validate and Display: Check the integrity and visualize the blockchain to ensure the records are accurate.
This application can be used for file integrity verification in various scenarios, such as software distribution or data archival
