## Inter Process Communication(IPC) 

communication between two or more processes.

(01)shared memory

(02)message passing

## (01). Shared Memory (Synchronization)

What it is: Multiple processes use a common memory space to read and write data.
How it works: You need to synchronize the access (like using locks) to prevent two processes from messing up the data.
Example: Two programs can share a file’s contents in memory, but they must wait their turn to read/write to it.

## (02). Message Passing (Asynchronization)

What it is: Processes send messages to each other, usually through a queue.
How it works: The processes don’t need to wait for each other. One can send a message and keep working, and the other can read it later.
Example: One program sends a message to another asking for data, and the second program replies later.

## Key Difference:
Shared Memory: Both processes use the same memory, so you need to sync them to avoid issues.
Message Passing: Processes send messages, and they don’t have to wait for each other (asynchronous).

## Message Passing output:

![1](https://github.com/user-attachments/assets/fc6f7e05-3872-46fa-9dd7-324f90635053)


