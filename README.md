# awesome_computer_science
A detailed syllabus of computer science. Roadmap computer science degree.

If you have pull requests, please do in [This repository](https://github.com/apeman/awesome_computer_science_)

*This syllabus is structured in __Top Down approach for maximum productivity.__ You can start seeing the results of your learning as you progress through the course by building small programs and steadily learning the advanced details.*

If you want the bottom up approach (College format), please visit [This repository](https://github.com/apeman/awesome_computer_science_)


## Programming

- [ ] **Learn C**
    - [ ] Character constants, escape sequences, string constants
    - [ ] Data types and Type conversion
    - [ ] Precedence and associativity of operators
    - [ ] Functions
    - [ ] storage class and variable scope
    - [ ] if, for, while, switch_case
    - [ ] break, continue, goto
    - [ ] Arrays, Strings, Pointers
    - [ ] Structs, Union, enum, typedef
    - [ ] Header files, #MACROS
    - [ ] malloc, calloc, realloc, argc argv
    - [ ] file iO, streams
    - [ ] <Math.h>

## Data Structures

- [ ] **[Linked Lists](https://www.cs.cmu.edu/~adamchik/15-121/lectures/Linked%20Lists/linked%20lists.html)**
- [ ] **[Skip Lists](https://www.cs.cmu.edu/~ckingsf/bioinfo-lectures/skiplists.pdf)**<sup>PDF</sup>
- [ ] **stack** and **queues** and **sets**
- [ ] **Hash Tables**
- [ ] **Trees** and **Tries**
    - [ ] Self Balancing Trees
    - [ ] n-ary Trees
    - [ ] 2-3 Trees
- [ ] **Graphs**
    - [ ] Adjacency matrix vs Adjacency list

## [Algorithms](https://xlinux.nist.gov/dads/)

- [ ] **Searching**
    - [ ] Breadth First Search
    - [ ] Depth First Search
- [ ] **[Sorting](https://en.wikipedia.org/wiki/Sorting_algorithm)**
    - [ ] Merge Sort
    - [ ] Quick Sort
    - [ ] Insertion Sort
    - [ ] Selection Sort
- [ ] **Graph Traversal**
    - [ ] Minimum Spanning Trees
    - [ ] Shortest Paths
- [ ] **space-time Complexity** 

## Compiler Design

- [ ] **Compiler Design**
   - [ ] Lexical analysis
   - [ ] Syntax analysis
   - [ ] Type Checking
   - [ ] Intermediate code generation
   - [ ] Machine code generation
   - [ ] Assembly and linking
   - [ ] Analysis and optimisation
   - [ ] Memory management
   - [ ] Interpreters

## Computer Organization and Architecture

- [ ] **Computer Organization**
   - [ ] Address Bus, Data Bus
   - [ ] ROM, EPROM, RAM
   - [ ] Memory Hierarchy, Cache Memory, Virtual Memory
   - [ ] Secondary Storage
   - [ ] Programmable Logic Devices and Controllers
   - [ ] Input - Output Devices

- [ ] **Computer Architecture**
   - [ ] Stack
   - [ ] Registers
   - [ ] Endian_ness
   - [ ] Floating Point Numbers
   - [ ] Addressing Modes
   - [ ] Pipelining
   - [ ] Interrupts
   - [ ] RISC - CISC
   - [ ] aarch64, Intel_x86 / AMD64, MIPS / RISC-V (learn the differences)
   - [ ] [Assembly Language](https://stackoverflow.com/questions/1933801/x86-assembly-reference-sheet) (basic instructions)

    
## [Operating Systems](http://pages.cs.wisc.edu/~remzi/OSTEP/)
   - [ ] The Boot Process
- [ ] **Processes and Threads**
  - [ ] Process Control Block
  - [ ] Dispatcher and Scheduler
- [ ] **Inter Process Communication**
  - [ ] Mesage Passing
  - [ ] Shared Memory 
- [ ] **Scheduling Algorithms**
  - [ ] Round Robin.
  - [ ] Shortest Remaining Time First.
  - [ ] Least Recently Used.  
- [ ] **Deadlocks**
  - [ ] MutEx and Locks
  - [ ] Semaphores
  - [ ] Banker's Algorithm
- [ ] **Memory Management**
  - [ ] Paging and Page tables
  - [ ] Segmentation
  - [ ] First Fit, Next Fit, Best Fit
  - [ ] Non-continuous Allocation
- [ ] **Virtual memory**
  - [ ] Page Faults
  - [ ] Page Replacement Algorithms
  - [ ] Belady’s Anomaly
- [ ] **File Systems**
  - [ ] File Allocation Tables.
  - [ ] Disk Scheduling Algorithms

## Computer Networks

- [ ] **Layers of TCP and OSI**
    - [ ] Application.
    - [ ] Presentation.
    - [ ] Session.
    - [ ] Transport.
    - [ ] Network.
    - [ ] Data.
    - [ ] Physical.

- [ ] **Flow Control**
    - [ ] Flow Control
    - [ ] Congestion Control
    - [ ] Error Control
    
- [ ] **Routers and Routing Algorithms**
    - [ ] DHCP and static routing
    - [ ] Round Robin and others
    - [ ] DHCP | ICMP
    
- [ ] **UDP and Sockets**

- [ ] **IPv4 | IPv6**
    
- [ ] **Application Layer Protocols**
    - [ ] HTTP | FTP
    - [ ] DNS | SMTP
    - [ ] Email MIME Types | POP | IMAP

## Cryptography

- [ ] **Encryption Algorithms**
    - DES, AES, Whirlpool, One Time Pad
- [ ] **Hashing Algorithms**
    - SHA family
- [ ] **Key Distribution**
    - RSA, Kerberos
- [ ] **Digital Signatures**
    - Message Digest    
 - [ ] **Compression**
    - [History](https://www.hanshq.net/zip.html#huffman).
    
## Web Development
> You can study Web Development from [Mozilla Developer Network Website](https://developer.mozilla.org/en-US/docs/Web/Tutorials).

- [MDN Getting Started Guide](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)
- [ ] **Front-End**
    - [HTML5](https://developer.mozilla.org/en-US/docs/Learn/HTML)
    - [CSS3](https://developer.mozilla.org/en-US/docs/Learn/CSS)
    - [JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
    - [Web Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms) 
    - [Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility) 
    - [Tools and Testing](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing)
    - [DNS and Domain Names](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name)
    - [JSON and other formats](https://www.zionandzion.com/json-vs-xml-vs-toml-vs-cson-vs-yaml/) and [YAML](https://yaml.org/)


## SQL and DBMS and Redis

- [ ] **[SQL](https://www.javatpoint.com/sql-tutorial)**
    - [ ] **Data Definition Language**
     - [ ] CREATE
     - [ ] DROP
     - [ ] ALTER
     - [ ] TRUNCATE
    - [ ] **Data Query Language**
     - [ ] SELECT
    - [ ] **Data Manipulation Language**
     - [ ] INSERT
     - [ ] UPDATE
     - [ ] DELETE
    - [ ] **Data Control Language**
     - [ ] GRANT
     - [ ] REVOKE
    - [ ] **Transction Control Language**
     - [ ] COMMIT
     - [ ] ROLLBACK
     - [ ] SAVEPOINT
    - [ ] **JOINS**
     - [ ] FULL OUTER JOIN
     - [ ] LEFT JOIN
     - [ ] RIGHT JOIN
     - [ ] NATURAL JOIN
     - [ ] LEFT OUTER JOIN
     - [ ] RIGHT OUTER JOIN

- **[DataBase Management Systems](https://www.javatpoint.com/dbms-tutorial)**
    - Entity-Relationship model.
    - [ ] **Integrity Constraints**
     - [ ] Primary Key and Foreign key
     - [ ] Composite keys
     - [ ] All other types of keys
    - [ ] Normal Forms : 1NF to 4 NF
    - [ ] File Organization.
    - [ ] Indexing (B- Trees and B+ Trees)
    - [ ] **Transactions and Concurrency Control**
    - [ ] Conflict Serializability
    - [ ] Locking
    - [ ] ACID | BASE
- **[ ] Redis**
 
 
After you are done with all this and want to make projects, check out [Projects you can make](https://github.com/apeman/awesome_computer_science/blob/master/what-should-i-code.md)

## LICENSE

[Mozilla-Public-License](./LICENSE.txt)
