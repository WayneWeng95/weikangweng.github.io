---
layout: default
---

# 翁维康

## Phd candidate in Leiden University

## Organizations
  - [Leiden University (Universiteit Leiden)](https://www.universiteitleiden.nl/en)

## Social network links
### Profiles:
  - Email: w.weng@liacs.leidenuniv.nl
  - University webpage: [(https://www.universiteitleiden.nl/en/staffmembers/weikang-weng#tab-1)](https://www.universiteitleiden.nl/en/staffmembers/weikang-weng#tab-1)
  - GitHub: [(https://github.com/WayneWeng95)](https://github.com/WayneWeng95)
  - Llinkedin: [https://www.linkedin.com/in/weikang-weng95/](https://www.linkedin.com/in/weikang-weng95/)

## Education:
### PhD Computer Engineering - LIACS Leiden University, Leiden, The Netherlands
#### Promotor: Dr.Rob van Nieuwpoort  
#### Daily Supervisor: Dr.Alexandru Uta
#### PHD topic: Modernizing the OS to efficiently run serverless workloads.

Serverless computing is a novel cloud computing paradigm where users describe computation via fine-grained functions. This entails hiding much of the complexity regarding resource management storage, scheduling behind the platform built by the cloud providers. Under those platforms runs the traditional operating system which is designed for general-purpose computing. This situation brings many challenges in various aspects such as memory, scheduling, and opens up novel research problems on how we can re-design parts of The OS to efficiently handle modern workloads such as serverless. In this project, we aim to tackle OS problems related to serverless computing.

### Msc Embedded System - TU Delft, Delft, The Netherlands
#### Mentor: Dr. Jan S. Rellermeyer
#### Thesis project: An adaptive memory allocator for better reallocation performance

This project aims to achieve a nearly zero copy reallocation scheme for reallocations, especially with large memory objects. We want to replace the sequence of malloc new blocks, copy the content and free the old block with other options, so we save the performance losses during the copy. We combine several approaches and build a novel adaptive memory allocator to achieve efficient memory reallocation for modern big data workloads. 


### Bsc Electrical Engineering and Logical Control - HZ University of applied science, Vlissingen, The Netherlands & Shanghai Maritime University, Shanghai, China

## Service
### Teaching Assistance - LIACS, Leiden University
- Computer Architecture - 2024-2025 Q1
- Cloud Computing - 2023-2024 Q2
- Operating System - 2023-2024 Q2
- Cloud Computing - 2022-2023 Q2
- Distributed Data Processing System - 2022-2023 Q1

### Researcher - De Zeeuse Huiskamer and Amels Holland, Vlissingen, The Netherland 
- Find wearable solutions which meet the functional requirements and are suitable to control the living room for both clients on the yacht. Enhancing the overall user experience to use voice commands.  
- Research and test solutions for improvements in the home automation system powered by ZigBee, Bluetooth LTE, and microphone arrays. 

## Skills:
- C / C++
- Rust

## Language:
- English
- Chinese
- Nederlands (A2)

## Publications:
### Brug: An Adaptive Memory (Re-)Allocator. W Weng, A Uta, JS Rellermeyer - CCGRID 2024
Designed Brug, an adaptive memory allocator that leverages the strengths of existing allocators while addressing their limitations. Brug dynamically selects suitable allocators for applications or individual data structures and includes an auto-tuner to simplify developer decisions, optimizing memory allocation for complex workloads.

### In Serverless, OS Scheduler Choice Costs Money: A Hybrid Scheduling Approach for Cheaper FaaS. Y Zhao, W Weng, R van Nieuwpoort, A Uta - Middleware 2024
Developed a hybrid OS-level scheduler for Function-as-a-Service (FaaS) workloads to address inefficiencies of Linux's Completely Fair Scheduler (CFS) in highly concurrent environments. The proposed two-level scheduler executes short-lived functions in FIFO order and longer ones with CFS, reducing serverless workload costs by up to 10X without adding provider overhead. This approach enhances affordability and efficiency in serverless computing.

### Serverless Snapshot-Resume Performance in the Real-World. W Weng, Y Zhao, R van Nieuwpoort, A Uta - UCC 2024
Analyzed snapshot-resume techniques for reducing serverless cold start delays, incorporating real-world assumptions. Demonstrated that academic optimizations like memory prefetching and dirty page tracking conflict with real-world practices such as encryption and data chunking, causing up to 10X overhead. Highlighted the need to align academic solutions with practical system designs to maximize their effectiveness.
