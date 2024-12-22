# concurrency-vs-parallelism
Concurrency and parallelism are fundamental concepts in computer science and software development, especially in areas like multi-threading, distributed systems, and performance optimization.

A comprehensive list of topics and subtopics in concurrency and parallelism:

---

### Core Concepts of Concurrency and Parallelism:
1. **Concurrency vs. Parallelism**
   - Definition and differences
   - Examples of use cases in quant development

2. **Processes and Threads**
   - Processes vs. threads
   - Thread lifecycle
   - Thread scheduling and priorities

3. **Parallel Programming Models**
   - Shared memory
   - Distributed memory (Message Passing)
   - Hybrid models

---

### Language-Specific Implementations:
1. **C++**
   - Threading with `<thread>` library
   - Mutexes and locks (`std::mutex`, `std::lock_guard`)
   - Condition variables
   - Atomic operations and memory order (`std::atomic`)
   - Thread pools
   - Parallel algorithms in C++17/20 (`std::execution`)

2. **Java**
   - Java `Thread` class and `Runnable` interface
   - `synchronized` blocks and methods
   - Locks (`ReentrantLock`, `ReadWriteLock`)
   - Java Concurrency Framework (Executor Services, Fork/Join framework)
   - Completable Futures and asynchronous programming
   - Java Streams and parallel processing

---

### Advanced Concurrency Topics:
1. **Synchronization Techniques**
   - Mutexes, Semaphores, and Monitors
   - Deadlock, livelock, and starvation
   - Avoidance and detection of deadlocks

2. **Concurrent Data Structures**
   - Queues (BlockingQueue, ConcurrentLinkedQueue)
   - Hash maps (ConcurrentHashMap, synchronized maps)
   - Thread-safe lists and arrays

3. **Memory Models and Visibility**
   - Cache coherence
   - Happens-before relationship
   - Volatile variables
   - Memory barriers and fences

4. **Lock-Free and Wait-Free Programming**
   - Compare-and-Swap (CAS) operations
   - Spinlocks
   - Lock-free queues and stacks

5. **Task Parallelism**
   - Work stealing
   - Task schedulers
   - Dependency graphs for tasks

---

### Tools and Frameworks:
1. **Distributed Computing Frameworks**
   - MPI (Message Passing Interface)
   - Apache Spark for parallel computation
   - Grid computing libraries

2. **GPU and Hardware Acceleration**
   - OpenMP and OpenACC
   - CUDA programming for GPUs
   - SIMD instructions

3. **Testing and Debugging Tools**
   - Debugging race conditions and deadlocks
   - Tools: Valgrind, Intel Inspector, Thread Sanitizer

---

### Quantitative Development Specific Applications:
1. **High-Performance Computing (HPC)**
   - Numerical optimization techniques
   - Monte Carlo simulations in parallel
   - Matrix computations and parallel linear algebra

2. **Event-Driven Programming**
   - Reactors and proactors
   - Asynchronous I/O models

3. **Real-Time Systems**
   - Low-latency programming
   - Deterministic execution and deadline scheduling

4. **Market Data and Order Handling**
   - Multithreaded market data feed handlers
   - Concurrent order matching engines
   - Risk calculation and parallel processing

5. **Algorithmic Trading Systems**
   - Tick-by-tick data processing
   - Portfolio optimization in parallel
   - Execution engines with concurrency

---

### Theoretical Foundations:
1. **Mathematical Models**
   - Queuing theory
   - Lamport clocks and logical timestamps
   - Petri nets for concurrency modeling

2. **Formal Methods**
   - Proof of correctness in concurrent algorithms
   - Verification of safety and liveness properties

3. **Parallel Algorithm Design**
   - Divide-and-conquer
   - Parallel sorting and searching
   - Graph algorithms in parallel

---
