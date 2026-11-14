# Operating Systems Lab

C programs for my Operating Systems lab, covering process management, inter-process communication (IPC), CPU scheduling and page replacement.

## Programs

### Process Management
| Program | Description |
|---|---|
| `q2_parent_child.c` | Demonstrates the `fork()` system call |
| `odd_even_sum_fork.c` | Parent sums odd numbers and child sums even numbers using `fork()` |
| `q3_wait.c` | Demonstrates the `wait()` system call |
| `orphan_process_demo.c` | Demonstrates an orphan process |
| `zombie_process_demo.c` | Demonstrates a zombie process |

### Inter-Process Communication
| Program | Description |
|---|---|
| `pipe.c` | Communication between processes using a pipe |
| `fifo_writer.c` | Writes data to a FIFO (named pipe) |
| `fifo_reader.c` | Reads data from a FIFO (named pipe) |
| `message_receiver.c` | Receives messages from a message queue |
| `shared_writer.c` | Writes data to shared memory |
| `shared_reader.c` | Reads data from shared memory |

### CPU Scheduling
| Program | Description |
|---|---|
| `fcfs.c` | First Come First Served (FCFS) |
| `sjf.c` | Shortest Job First (SJF) |
| `priority.c` | Priority scheduling |

### Page Replacement
| Program | Description |
|---|---|
| `fifo_page.c` | FIFO page replacement algorithm |
| `lru_page.c` | Least Recently Used (LRU) page replacement algorithm |

## How to Compile and Run

These programs use Linux system calls, so run them on Linux, WSL or a Linux virtual machine.

```bash
gcc filename.c -o output
./output
```

Example:
```bash
gcc fcfs.c -o fcfs
./fcfs
```

The IPC programs come in pairs (writer/reader, sender/receiver). Run the writer in one terminal and the reader in another.

## Topics Covered
- Process creation and synchronization (`fork`, `wait`)
- Orphan and zombie processes
- Pipes, FIFOs, message queues and shared memory
- CPU scheduling algorithms
- Page replacement algorithms

## Author
Aanya
