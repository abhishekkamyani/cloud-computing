# Computer Vision

## Chapter 1: Introduction to Computer Vision

### Part 1: Introduction to Cloud Computing

#### 1. What is Cloud Computing?
Cloud computing is a technology that allows users to access computing resources (like servers, storage, databases, networking, software) over the internet instead of relying on a personal computer or a local server. It enables users to store data and run applications remotely without needing high-end hardware.

**Example:**
Think of cloud computing like Google Drive or Dropbox, where you can store files online and access them from any device.

---

#### 2. Operations in Cloud Computing
Cloud computing consists of different operations that help manage and utilize cloud services efficiently. These include:

1. **Computing Power:** Running applications on virtual machines instead of local computers.
2. **Storage Management:** Storing data on cloud-based servers rather than on local hard drives.
3. **Networking:** Connecting users and applications globally through the internet.
4. **Security Management:** Protecting data through encryption, authentication, and firewalls.
5. **Resource Allocation:** Distributing computing resources as per demand to ensure efficiency.

---

#### 3. Why Cloud Computing?
Cloud computing is widely used because of several benefits, such as:

- **Cost Savings:** No need to buy expensive hardware or software.
- **Scalability:** You can increase or decrease resources as per your needs.
- **Accessibility:** Access data from anywhere in the world with an internet connection.
- **Automatic Updates:** Cloud service providers handle software and security updates.
- **Data Backup & Recovery:** Data is stored safely and can be recovered if lost.

---

#### 4. Characteristics of Cloud Computing
- **Agility** – Fast deployment of resources.
- **High Availability & Reliability** – Ensures services run without interruptions.
- **Scalability** – Resources can be increased or decreased as needed.
- **Multi-Sharing** – Many users can use the same cloud infrastructure.
- **Device & Location Independence** – Access services from any device, anywhere.
- **Maintenance** – Cloud providers handle system updates and repairs.
- **Low Cost** – Pay only for what you use, reducing IT costs.
- **Pay-Per-Use Model** – Users are charged based on their resource consumption.

---

#### 5. Advantages of Cloud Computing
1. **Reduced IT Costs:** No need for expensive infrastructure.
2. **Flexibility & Scalability:** Easily scale resources up or down.
3. **Accessibility:** Work from anywhere with an internet connection.
4. **Automatic Updates:** Cloud providers handle maintenance and updates.
5. **Better Collaboration:** Teams can work together in real-time using shared files.

---

#### 6. Disadvantages of Cloud Computing
1. **Internet Dependency:** Needs a reliable internet connection.
2. **Security Risks:** Data stored on cloud servers can be targeted by hackers.
3. **Limited Control:** Users rely on cloud providers for maintenance and updates.
4. **Downtime Issues:** Cloud services may face outages, affecting accessibility.
5. **Hidden Costs:** Some cloud services may have additional charges.

---

### Types of Cloud Computing  

#### A. Based on Deployment Model  
1. **Public Cloud** – Owned by third-party providers, accessible to anyone (e.g., AWS, Google Cloud).  
2. **Private Cloud** – Dedicated to a single organization for security (e.g., bank data centers).  
3. **Hybrid Cloud** – Combination of public & private clouds (e.g., sensitive data on private cloud, applications on public cloud).  

#### B. Based on Service Model  

1. **Infrastructure as a Service (IaaS)**  
   - Provides virtualized computing resources (servers, storage, networking) over the internet.  
   - Replaces physical hardware, allowing businesses to rent IT infrastructure.  
   - **Examples:** AWS EC2, Microsoft Azure Virtual Machines, Google Compute Engine, IBM Cloud Infrastructure.  

2. **Platform as a Service (PaaS)**  
   - Offers a development environment with tools, libraries, and infrastructure for building, testing, and deploying applications.  
   - Developers don’t need to manage servers or networking.  
   - **Examples:** Google App Engine, Microsoft Azure App Services, AWS Elastic Beanstalk, Heroku.  

3. **Software as a Service (SaaS)**  
   - Delivers ready-to-use software applications over the internet.  
   - No installation or maintenance required—access via a web browser.  
   - **Examples:** Google Drive, Gmail, Google Docs, Microsoft Office 365, Dropbox, Netflix.  

---

#### 8. Conclusion
Cloud computing is an essential technology that offers flexibility, scalability, and cost savings. However, it also has some security and internet dependency concerns. Despite these drawbacks, it remains one of the most widely used technologies for businesses and individuals.

---

### Part 2: Parallel & Distributed Computing

#### Introduction
Computing is any task that involves using computers, from software development to data processing. It has applications in science, engineering, and daily life.

#### History of Computing
Computing has evolved through different generations:
1. **Vacuum Tubes (1940s-1950s)** – Bulky and slow.
2. **Transistors (1950s-1960s)** – Smaller, faster, and more reliable.
3. **Integrated Circuits (ICs) (1960s-1970s)** – Allowed multiple transistors on a single chip.
4. **Silicon Chips (1970s-present)** – Enabled the modern microprocessor.
5. **Artificial Intelligence (AI)** – Advanced computing with machine learning and automation.

#### Moore’s Law
- Predicts that the number of transistors on a chip doubles every two years while costs decrease.
- This means computers get faster and cheaper over time.

---

#### Fundamentals of Parallel & Distributed Computing

##### Difference Between Parallel and Distributed Computing
Parallel and distributed computing are both used to enhance computational power, but they differ in how tasks are executed and resources are managed.

**Key Differences:**

| Feature           | Parallel Computing  | Distributed Computing |
|------------------|-------------------|----------------------|
| Definition       | Multiple processors work on a problem simultaneously within a single system. | Multiple computers (nodes) communicate over a network to solve a problem. |
| Memory          | Shared memory (single system) | Distributed memory (separate machines) |
| Processing      | Tasks are divided among multiple processors within one machine. | Tasks are divided among multiple computers connected via a network. |
| Communication   | Processors communicate via shared memory. | Computers communicate over a network. |
| Examples       | Multi-core processors, GPUs, supercomputers. | Cloud computing, web applications, blockchain. |
| Pros           | Faster than serial computing. Efficient for large-scale calculations. | Scalable and cost-effective. Can handle large amounts of data. |
| Cons           | Requires complex programming techniques. Expensive due to specialized hardware. | Network delays can slow down performance. Requires efficient coordination between systems. |

---

#### ILLIAC IV – First Massively Parallel Computer
- Built in the 1960s by the University of Illinois.
- Had 64 processing units, making it a major advancement in parallel computing.

---

#### Parallel vs. Serial Computing
- **Serial Computing:** One task is completed at a time (e.g., a single queue for movie tickets).
- **Parallel Computing:** Multiple tasks are processed at the same time (e.g., multiple counters at a bank).

| Feature         | Serial Computing    | Parallel Computing    |
|---------------|-------------------|---------------------|
| Processing    | One instruction at a time | Multiple instructions at the same time |
| Speed        | Slower             | Faster             |
| Cost         | Lower              | Higher             |
| Data Transfer | Bit by bit         | Byte by byte (8 bits) |

---

#### Types of Computing
1. **Traditional Computing** – Uses physical data centers.
2. **Cloud Computing** – Uses internet-based servers.
3. **Grid Computing** – Uses multiple computers to solve a problem.
4. **Personal Computing** – Single-user systems like laptops.
5. **Time-Sharing Computing** – Multiple users share computing resources.
6. **Client-Server Computing** – Clients request data from a central server.
7. **Peer-to-Peer (P2P) Computing** – No dedicated servers, all devices are equal.
8. **Mobile Computing** – Computing on portable devices.
9. **Cluster Computing** – Multiple computers act as one system.

---

#### Pros & Cons of Parallel & Distributed Computing
**Advantages:**

✔ Faster processing for big data tasks.

✔ Can solve complex problems efficiently.

✔ Ideal for AI, simulations, and real-time applications.

**Disadvantages:**

❌ More expensive due to advanced hardware.

❌ Requires more power and cooling.

❌ Programming for parallel architecture is complex.


# Chapter 02

## 1. Flynn’s Taxonomy
**Definition:** Flynn’s taxonomy is a classification system for computer architecture proposed by Michael J. Flynn in 1966 and extended in 1972. It categorizes computers based on how they handle instructions and data streams in parallel computing.

### Flynn’s Four Types of Computer Architectures:
| Type  | Description  | Example  |
|---|---|---|
| SISD (Single Instruction, Single Data) | One processor executes one instruction at a time on a single data set. | Single-core CPU. |
| SIMD (Single Instruction, Multiple Data) | Executes the same instruction on multiple data points simultaneously. | GPU image processing. |
| MISD (Multiple Instruction, Single Data) | Multiple instructions operate on a single data stream. This is rare and mostly theoretical. | Fault-tolerant systems. |
| MIMD (Multiple Instruction, Multiple Data) | Multiple processors execute different instructions on different data streams. | Multi-core processors. |

## 2. Introduction to Multithreading
### What is Multithreading?
- Multithreading is a technique where a program is divided into multiple "threads", which run simultaneously.
- A thread is a lightweight unit of a process that can execute independently.
- **Concurrency:** Threads can run independently but share process resources like memory.

### How It Works?
- In a **single-threaded** program, tasks execute one after another.
- In a **multi-threaded** program, tasks run concurrently, improving efficiency.

### Examples of Multithreading:
- Web browsers (Multiple tabs open at once).
- Video games (Game physics, AI, rendering handled separately).
- Operating systems (Handling multiple applications at the same time).

**Key Point:** Multithreading improves performance by running multiple tasks in parallel.

## 3. Parallel Algorithms & Architectures
### What are Parallel Algorithms?
A parallel algorithm performs multiple operations at the same time instead of executing them sequentially like traditional algorithms.

### Examples of Parallel Algorithms:
- Newton’s method (used in AI and machine learning).
- Parallel sorting algorithms (e.g., parallel merge sort).
- Simulations (weather forecasting, physics calculations).

### Parallel Architectures:
Multiple processors working together to solve the same problem.
- **Shared Memory:** Multiple processors share one memory space.
- **Distributed Memory:** Each processor has its own memory, and they communicate via a network.

**Key Point:** Parallel algorithms reduce execution time by splitting tasks among multiple processors.

## 4. Parallel I/O (Input/Output)
### What is Parallel I/O?
- Instead of processing I/O operations one at a time (serially), parallel I/O handles multiple I/O operations simultaneously.
- Used in supercomputers, cloud storage, and large databases.

### Example:
- A high-speed database system handling thousands of user queries at the same time.
- Writing multiple files to storage devices simultaneously.

**Key Point:** Parallel I/O speeds up data storage and retrieval, making computers more efficient.

## 5. Parallel Programming Models
A parallel programming model defines how parallel tasks interact with each other and how resources are shared.

| Model  | Description  | Example  |
|---|---|---|
| Data Parallelism | Executes the same task on multiple data sets at the same time. | Processing large datasets on multiple cores. |
| Task Parallelism | Executes different tasks on different processors at the same time. | Running multiple programs at once. |
| Bit-Level Parallelism | Increases processor word size to process more data at once. | Modern CPUs processing 64-bit instructions. |
| Instruction-Level Parallelism | Executes multiple instructions simultaneously. | Pipelined processors in modern computers. |

## 6. Memory Models: Shared vs. Distributed Memory
### Shared Memory Model:
- All processors share a common memory.
- Fast communication between processors.
- **Example:** Multi-core processors in modern computers.

### Distributed Memory Model:
- Each processor has its own private memory.
- Processors communicate via messages over a network.
- **Example:** Cloud computing, supercomputers.

## 7. Process-Centric Architecture (PCA)
### What is PCA?
- A process-centric architecture moves the abstraction level higher by organizing tasks based on process logic rather than hardware.

### Why is PCA Important?
- Improves efficiency in distributed computing.
- Reduces complexity by focusing on task execution instead of low-level system management.

**Key Point:** PCA helps in managing complex systems by focusing on high-level process execution.

## 8. Distributed Shared Memory (DSM)
### What is DSM?
- DSM allows multiple processors to access a shared memory space, even though they are physically distributed.
- This makes distributed computing feel like a single shared memory system.

### Advantages of DSM:

✔ Simplifies programming for distributed systems.

✔ Reduces data transfer costs.

**Key Point:** DSM makes it easier to manage memory in distributed computing systems.

## Conclusion (Quick Revision for Exams)

📌 **Flynn’s Taxonomy:** Classifies architectures into SISD, SIMD, MISD, MIMD.

📌 **Multithreading:** Allows multiple tasks to run simultaneously in one process.

📌 **Parallel Algorithms:** Solve problems faster using multiple processors.

📌 **Parallel I/O:** Reads/writes data to storage simultaneously.

📌 **Parallel Programming Models:** Includes bit-level, instruction-level, data, and task parallelism.

📌 **Shared vs. Distributed Memory:** Shared → Fast, limited scalability. Distributed → Scalable, slower.

📌 **Process-Centric Architecture:** Focuses on high-level process execution.

📌 **Distributed Shared Memory:** Makes distributed computing feel like shared memory.

