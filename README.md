# FaultTolerantFS

The objective is to design a file system where the loss of information is proportional to the damage. For example, if one block of a file gets corrupt, the whole file shouldn't become inaccessible even if that particular block is the inode of that file. 
