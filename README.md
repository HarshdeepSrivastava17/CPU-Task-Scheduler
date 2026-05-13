# CPU-Task-Scheduler
Python-based CPU Task Scheduler using OOP concepts implementing FCFS, Round Robin, and Priority Scheduling algorithms with task execution timing simulation.

## Features

* Take user input for multiple tasks/processes
* Store task details like:

  * Task Name
  * Burst Time
  * Priority
* Implemented CPU Scheduling Algorithms:

  * First-Come, First-Serve (FCFS)
  * Round Robin (RR)
  * Priority Scheduling (Non-Preemptive)
* Displays:

  * Start Time
  * Finish Time
  * Execution Order
* Round Robin scheduling supports custom Time Quantum input
* Built using Python and `deque` for efficient queue handling

## Concepts Used

* Object-Oriented Programming (Classes & Objects)
* Queue Data Structure
* CPU Scheduling Algorithms
* Process Management Simulation
* User Input Handling
* Time Calculation Logic

## Technologies Used

* Python 3
* collections.deque

## Learning Outcome

Through this project, I learned:

* How CPU scheduling works in Operating Systems
* Real-world implementation of scheduling algorithms
* Process execution and time management
* Practical use of OOP in Python

## Sample Algorithms Included

### FCFS

Processes execute in the order they arrive.

### Round Robin

Each process gets a fixed time quantum in cyclic order.

### Priority Scheduling

Processes with higher priority (lower priority number) execute first.

## Project Source

This project was completed as part of the CPU Task Scheduler module on [CodeChef](https://www.codechef.com?utm_source=chatgpt.com).
