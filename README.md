# SSD Storage System with Flash Translation Layer (FTL)

## Overview
This project implements a simplified SSD simulator that models the internal behavior of flash storage systems. The system focuses on Flash Translation Layer (FTL) mechanisms such as logical-to-physical address mapping, wear leveling, and garbage collection to manage flash memory constraints.

## Features
- Logical-to-Physical Address Mapping
- Wear Leveling Algorithm
- Garbage Collection for Block Reclamation
- NAND Flash Memory Behavior Simulation
- Storage Performance Evaluation

## Performance Analysis
The simulator evaluates storage behavior using Linux-based workloads. Key metrics analyzed include:

- IOPS (Input/Output Operations Per Second)
- Latency
- Write Amplification
- Flash endurance under erase cycles

## Tools & Technologies
- C++
- Linux
- fio
- blktrace
- perf
- Git

## Future Improvements
- Implement advanced FTL mapping strategies
- Add multi-channel SSD simulation
- Introduce workload-aware garbage collection
