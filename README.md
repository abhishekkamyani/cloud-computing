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

---
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


---
# Chapter 03

## 1. Asynchronous vs. Synchronous Computation & Communication

- **Synchronous Communication:** This involves real-time interactions where tasks or communications happen simultaneously. For example, a live video call where all participants are present at the same time.
- **Asynchronous Communication:** This happens independently of real-time interaction. Participants can respond at their convenience, like email communication.
- **Synchronous Execution:** In programming, tasks are executed one after another. A task must complete before the next one starts.
- **Asynchronous Execution:** Tasks can run in parallel. A new task can start without waiting for the previous one to finish, improving efficiency and resource utilization.

### Key Differences

| Feature         | Synchronous | Asynchronous |
|----------------|------------|--------------|
| Execution      | One task must finish before the next starts. | Multiple tasks can run at the same time. |
| Waiting Time   | Tasks must wait for others to complete. | No waiting, tasks run simultaneously. |
| Example (Daily Life) | Phone call, video call (real-time communication). | Email, WhatsApp messages (no need to respond immediately). |
| Example (Computing)  | Database query that waits for a response before proceeding. | Downloading a file while browsing the internet. |

### Easy Way to Remember:
- **Synchronous =** Waiting in a queue to buy tickets (you must wait for your turn).
- **Asynchronous =** Ordering online (your order is processed while you do other things).

## 2. Concurrency Control

### Definition
- **Concurrency control** is a technique used to manage multiple tasks that try to access and modify the same resource/data simultaneously, ensuring data consistency and avoiding errors.

### Why is Concurrency Control Needed?
If multiple users or processes access shared data at the same time, it can cause data inconsistency or incorrect results.

#### Example (Bank ATMs):
- Imagine two people trying to withdraw ₹5000 at the same time from different ATMs.
- If there is no Concurrency Control, both transactions might process simultaneously, causing incorrect balance updates.
- **Concurrency Control** ensures that one transaction is completed before another modifies the same data.

### Concurrency Control Techniques:
1. **Locking Mechanism** – Prevents multiple processes from accessing the same resource at the same time.
2. **Timestamp Ordering** – Ensures tasks execute in the correct order based on timestamps.
3. **Optimistic Concurrency Control** – Allows tasks to proceed without locks but verifies data before committing changes.

### Easy Way to Remember:
- **Concurrency control is like traffic lights** – It prevents cars (processes) from crashing into each other at intersections.

## 3. Fault Tolerance

### Definition
- **Fault tolerance** is the ability of a system to continue functioning even when some of its components fail.

### Why is Fault Tolerance Important?
- Prevents system crashes and data loss in case of hardware/software failures.
- Ensures high availability and reliability in critical applications.

### Examples of Fault Tolerance:
✔ **Cloud Computing:** If one server fails, another takes over (e.g., AWS, Google Cloud).

✔ **Airplane Systems:** If one engine fails, the plane can still fly with the remaining engines.

✔ **RAID Storage (Redundant Array of Independent Disks):** Data is copied to multiple disks, so if one fails, the data remains safe.

✔ **Self-Driving Cars:** If one sensor fails, the system still uses other sensors to make driving decisions.

### Easy Way to Remember:
- **Fault tolerance is like a backup generator** – If the power goes out, the generator keeps things running.

---

# Chapter 04

## 1. GPU Architecture and Programming

### Definition
- **CPU (Central Processing Unit)**: Designed to handle a wide range of tasks quickly but is limited in the number of tasks it can handle concurrently.
- **GPU (Graphics Processing Unit)**: A specialized processor designed to handle multiple tasks simultaneously, especially tasks related to graphics, video processing, and parallel computing.
- Unlike a CPU, which is optimized for general-purpose tasks, a GPU is designed for high-speed parallel processing.
- **GPU Concepts**: GPUs use similar concepts to CPUs, such as ALUs (Arithmetic Logic Units), L1 and L2 caches, and pipelined designs. They also handle threads, but on a much larger scale compared to CPUs.

### CPU vs. GPU Architecture

| Feature | CPU (Central Processing Unit) | GPU (Graphics Processing Unit) |
|---------|-----------------------------|-----------------------------|
| Designed For | General-purpose computing | Graphics rendering, parallel tasks |
| Processing Cores | Fewer, but powerful cores | Thousands of smaller cores |
| Concurrency | Limited (executes fewer tasks at a time) | High (executes many tasks simultaneously) |
| Examples | Running an operating system, web browsing | Gaming, video editing, AI, deep learning |

### Where is GPU Used?
✔ Gaming & Graphics Rendering (NVIDIA, AMD GPUs).  
✔ AI & Machine Learning (Training deep learning models).  
✔ Cryptocurrency Mining (Processing blockchain transactions).  
✔ Scientific Computing (Weather simulations, protein folding).  

#### Easy Way to Remember:
- **CPU** = "Brain" of the computer (handles general tasks).
- **GPU** = "Muscles" of the computer (does heavy processing in parallel).

## 2. Heterogeneity

### Definition
- **Heterogeneous Computing System**: A system that includes different types of computational units, such as multicore CPUs, GPUs, DSPs (Digital Signal Processors), and FPGAs (Field-Programmable Gate Arrays).

### Key Aspects:
- **Transparency**: Users should not need to be aware of the underlying complexity.
- **Openness**: Systems should be open to different types of hardware and software.
- **Concurrency**: Ability to handle multiple tasks simultaneously.
- **Security**: Ensuring data and processes are secure.
- **Scalability**: Ability to scale resources up or down based on demand.
- **Failure Handling**: Systems should be able to handle failures gracefully.

### Example:
A self-driving car uses heterogeneous computing:  
- **CPU** for decision-making.  
- **GPU** for image recognition.  
- **DSPs** for signal processing from sensors.  

## 3. Introduction to OpenCL

- **OpenCL (Open Computing Language)**: A framework for writing programs that execute across heterogeneous platforms, including CPUs, GPUs, DSPs, and FPGAs.
- **Purpose**: OpenCL allows developers to write applications that can use multiple types of devices for processing, making it a versatile tool for parallel computing.
- **Cross-Platform Support**: OpenCL is an open standard that supports data parallel compute on both CPUs and GPUs, enabling efficient use of hardware resources.

## 4. Message Passing Interface (MPI)

- **MPI (Message Passing Interface)**: A standardized system for message passing in distributed and parallel computing environments.
- **Purpose**: MPI provides a portable and efficient standard for message passing, allowing different processes to communicate with each other.
- **Two-Sided Operation**:
  - **Sending Process**: Describes the data to be sent.
  - **Receiving Process**: Describes how to receive the message.
- **Language Support**: MPI is implemented in various programming languages such as Fortran, C, C++, and Java, making it widely used in parallel computing.

## Summary
✔ **GPU vs. CPU**: GPU has many small cores for parallel processing; CPU has fewer, powerful cores for general tasks.  
✔ **Heterogeneous Computing**: Uses different processors (CPU, GPU, DSP) to improve performance.  
✔ **OpenCL**: Allows programs to run on multiple hardware types (CPUs, GPUs, FPGAs).  
✔ **MPI**: A system for message-based communication between multiple processors.  
