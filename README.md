# Operating Systems Lab

C programs for my Operating Systems lab. Run them on Linux, WSL or a Linux virtual machine.

## List of Experiments

| S.No. | Experiment | File | Description |
|---|---|---|---|
| 1 | Implementation of `fork()` system call | `q2_parent_child.c` | Creates a child process and shows the parent and child running separately |
| 2 | Sum of odd and even numbers using `fork()` | `odd_even_sum_fork.c` | Parent adds the odd numbers and the child adds the even numbers |
| 3 | Implementation of `wait()` system call | `q3_wait.c` | Parent waits for the child to finish before continuing |
| 4 | Implementation of orphan process | `orphan_process_demo.c` | Parent exits first, so the child keeps running as an orphan |
| 4 | Implementation of zombie process | `zombie_process_demo.c` | Child exits but the parent does not collect its status |
| 5 | Implementation of pipe | `pipe.c` | Two related processes exchange data through a pipe |
| 6 | Implementation of FIFO (named pipe) | `fifo_writer.c` | Writes data into the FIFO |
| 6 | Implementation of FIFO (named pipe) | `fifo_reader.c` | Reads data from the FIFO |
| 7 | Implementation of message queue | `message_receiver.c` | Receives messages from the message queue |
| 8 | Implementation of shared memory | `shared_writer.c` | Writes data into shared memory |
| 8 | Implementation of shared memory | `shared_reader.c` | Reads data from shared memory |
| 9 | Implementation of FCFS CPU scheduling | `fcfs.c` | Runs processes in the order they arrive |
| 10 | Implementation of SJF CPU scheduling | `sjf.c` | Runs the process with the shortest burst time first |
| 11 | Implementation of priority scheduling | `priority.c` | Runs processes in order of their priority |
| 12 | Implementation of FIFO page replacement | `fifo_page.c` | Replaces the oldest page in memory |
| 13 | Implementation of LRU page replacement | `lru_page.c` | Replaces the page that was used least recently |

## How to Compile and Run

```bash
gcc filename.c -o output
./output
```

For programs that come in pairs (writer/reader, sender/receiver), run each in a separate terminal.

## Author
Aanya
