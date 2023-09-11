# Large Efficient Flexible and Trusty (LEFT) File Sharing Program

This program is a Python Socket-based P2P file sharing tool. It allows for efficient, flexible, and reliable file sharing between two virtual machines. 

## Key points
+ Implemented event locking to resolve race conditions in a multi-end file synchronization project, ensuring exclusive directory access for one thread and preventing data location conflicts during transmission
+ Split transferred file into several blocks and sent blocks in parallel to enhance efficiency, so a 500MB file could be transferred within 10 seconds


<img width="844" alt="Screenshot 2023-09-11 at 17 33 38" src="https://github.com/sophiefeifeifeiya/file-sharing/assets/75290925/56c264fc-5e30-4dce-b4a1-7be4d1cfdfa1">
