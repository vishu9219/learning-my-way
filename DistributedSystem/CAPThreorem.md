# CAP Theorem

### Consistency
Every read receives the most recent write or an error.

### Avilability
Every request receives a (non-error) response, without the guarantee that it contains the most recent write.

### Partition
The system continues to operate despite an arbitrary number of messages being dropped (or delayed) by the network between nodes.

## What is CAP
1. Competing requirements in a distributed system with replication.
2. Two Trade off to focus while designing the distrubuted system.

## References
1. https://en.wikipedia.org/wiki/CAP_theorem
2. https://www.geeksforgeeks.org/the-cap-theorem-in-dbms/