# Project Title

SSTF DISK SCHEDULER

A disk Scheduler that uses Shortest Seek Time First(SSTF) algorithm on all the requests

## Description

Implement I/O  scheduler in the current kernel that enables the scheduler to dispatch different tasks. There are different algorithms that can be used such as FIFO, LIFO but this project is supposed to find the task that has the shortest distance from where the head of the I/O scheduler is pointed. So the nearest sector would be dispatched before the next read call was executed.

