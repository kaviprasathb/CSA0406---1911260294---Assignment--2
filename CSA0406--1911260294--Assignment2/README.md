# Operating Systems – Assignment 2

## Student Details

* **Name:** Kaviprasath B
* **Register Number:** 1911260294
* **Course:** CSA0406 – Operating Systems
* **Compiler:** GCC 15.2.0
* **Operating System:** Ubuntu Linux (WSL2)

## About the Repository

This repository contains the C programs, implementations, execution results and screenshots for Operating Systems Assignment 2.

The assignment covers process management, CPU scheduling, multithreading, inter-process communication, process synchronisation and deadlock management.

Each task folder contains its relevant source code and screenshots of compilation, execution and experimental results.

## Assignment Tasks

|Question|Topic|Description|
|-|-|-|
|Question 01|Processes and Process States|Process creation, execution and process-state observation.|
|Question 02|CPU Scheduling|Implementation and analysis of CPU scheduling algorithms.|
|Question 03|Threads|POSIX threads, thread pools and performance comparison.|
|Question 04|Inter-Process Communication|Pipe-based IPC, shared memory and data-transfer benchmarking.|
|Question 05|Synchronisation|Mutexes, semaphores, producer-consumer problem and locking benchmarks.|
|Question 06|Deadlock and Banker's Algorithm|Safety algorithm, resource allocation and performance benchmarking.|

## Software Requirements

* Ubuntu Linux (WSL2)
* GCC compiler
* Visual Studio Code
* POSIX Threads and semaphores where required

## Compiler Information

The programs were compiled and executed using:

```bash
gcc --version
```

Compiler version:

```text
GCC 15.2.0
```

## Compilation and Execution

Open the Ubuntu terminal, navigate to the relevant task folder and compile the required C source file.

### Question 03 – Threads

```bash
gcc -std=c11 -Wall -Wextra threads.c -o threads -pthread
./threads
```

### Question 04 – Inter-Process Communication

Pipe IPC:

```bash
gcc -std=c11 -Wall -Wextra pipe\_ipc.c -o pipe\_ipc
./pipe\_ipc
```

Shared Memory IPC:

```bash
gcc -std=c11 -Wall -Wextra shared\_memory\_ipc.c -o shared\_memory\_ipc -pthread -lrt
./shared\_memory\_ipc
```

IPC Benchmark:

```bash
gcc -std=c11 -Wall -Wextra ipc\_benchmark.c -o ipc\_benchmark -pthread -lrt
./ipc\_benchmark
```

### Question 05 – Synchronisation

Producer–Consumer:

```bash
gcc -std=c11 -Wall -Wextra producer\_consumer.c -o producer\_consumer -pthread
./producer\_consumer
```

Multiple Producers and Consumers:

```bash
gcc -std=c11 -Wall -Wextra producer\_consumer\_multi.c -o producer\_consumer\_multi -pthread
./producer\_consumer\_multi
```

Railway Lock Benchmark:

```bash
gcc -std=c11 -Wall -Wextra railway\_lock\_benchmark.c -o railway\_lock\_benchmark -pthread
./railway\_lock\_benchmark
```

Atomic, Spin Lock and Mutex Benchmark:

```bash
gcc -std=c11 -Wall -Wextra atomic\_spin\_mutex.c -o atomic\_spin\_mutex -pthread
./atomic\_spin\_mutex
```

### Question 06 – Deadlock and Banker's Algorithm

Banker's Algorithm:

```bash
gcc -std=c11 -Wall -Wextra bankers\_algorithm.c -o bankers\_algorithm
./bankers\_algorithm
```

Banker's Algorithm Benchmark:

```bash
gcc -std=c11 -Wall -Wextra bankers\_benchmark.c -o bankers\_benchmark
./bankers\_benchmark
```

## Experimental Results

Performance measurements were obtained by executing the programs on the local Ubuntu WSL2 environment.

Benchmark results may vary depending on the processor, system load and execution environment.

The screenshots inside each task folder provide evidence of compilation, execution and experimental results.

## Learning Outcomes

Through this assignment, the following concepts were implemented and studied:

* Process creation and process states.
* CPU scheduling and waiting-time analysis.
* Multithreading using POSIX threads.
* Inter-process communication using pipes and shared memory.
* Synchronisation using mutexes, semaphores and atomic operations.
* Deadlock avoidance using Banker's Algorithm.
* Performance measurement and algorithm complexity analysis.

## Author

**Kaviprasath B
1911260294**

B.Tech – Computer Science Engineering

