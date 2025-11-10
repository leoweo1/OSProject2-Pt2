# BENSCHILLIBOWL Restaurant Simulation

**Daniel Onwuka**  
**Fall 2025**  
**Operating Systems Project Part 2**

## Description
A multi-threaded restaurant simulation implementing the producer-consumer pattern using pthreads and synchronization primitives. Customers produce orders while cooks consume and fulfill them.

## Features
- Producer-Consumer pattern with pthreads
- Mutual exclusion using mutex locks
- Condition variables for efficient waiting
- Linked list order queue
- Resource management and memory safety

## Compilation
```bash
cd BENSCHILLIBOWL
gcc -o restaurant main.c BENSCHILLIBOWL.c -lpthread
```

## Usage
```bash
./restaurant
```
