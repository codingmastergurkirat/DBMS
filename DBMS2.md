## File System vs DBMS


| Features | File System | DBMS |
| -------- | -------- | -------- |
| Redundancy | There is more chances of redundancy | redundancy has very few chances |
| Concurrency| There is no protocols for concurrency so if there is more people access files and write it at same time then it may introduce inconsistency in the data| There is proper protocols for concurrency so there is very few chances of data inconsistency |
| File recieving| For searching 1 kb of data in a given file whole data must be opened and read which make operation slow | only 1 kb of data can be directly accessed through indexing which makes the operation fast |
| Location | We need a particular metadata of the file that we want to search | we can search the file using sql quries |
| Securyity | In file system there is no security means once the file system be open then anyone can do any operation | In DBMS there is proper roles so user can perform operations only that is permissible for that user role |
