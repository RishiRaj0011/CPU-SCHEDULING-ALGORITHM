# CPU-Scheduling-Simulator

## Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem_statement)
- [Features](#features)
- [Files and Directories](#files-and-directories)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Example](#example)
- [Contributing](#contributing)
- [YouTube Video](#youtube_video)

## Overview

This repository contains a Java-based simulator for CPU scheduling algorithms. CPU scheduling is a fundamental aspect of operating systems, where the CPU decides the order in which processes are executed. This simulator allows users to visualize and analyze different scheduling algorithms such as First-Come, First-Served (FCFS), Shortest Job Next (SJN), Round Robin (RR), and more. 

## Problem Statement
Different CPU scheduling algorithms have unique properties, and choosing the right one for a particular situation depends on various criteria used to compare their performance. These criteria are referred to as CPU scheduling criteria. For instance, in some cases, maximizing response time may be prioritized over throughput, while in others, minimizing average waiting time might be more important, even if it means sacrificing response time. Sometimes, a balance between multiple criteria is required. The challenge lies in determining which scheduling algorithm is best suited for a given situation. This project aims to address that challenge. The CPU Scheduling Simulator provides an environment where users can experimentally test and compare the performance of different scheduling algorithms through simulation. At the start, users can select any CPU scheduling algorithm they wish to evaluate. They then input the number of processes and relevant details for each process, such as CPU burst time, process ID, priority (if a priority scheduling policy is chosen), arrival time, and more. The simulator visually demonstrates the execution of processes, showing the remaining wait and burst times, as well as the processes waiting in the ready queue. One of the key features of this project is its Graphical User Interface, making it user-friendly and easy to operate.

## Features

- **Multiple Scheduling Algorithms**: Simulates various CPU scheduling algorithms such as FCFS, SJN, RR, and more.
- **User Interface**: Provides a graphical user interface (GUI) for easy interaction and visualization.
- **Detailed Output**: Displays the order of process execution, waiting time, turnaround time, and other performance metrics.
- **Custom Data Structures**: Tailored data structures for managing processes and scheduling tasks.


## Files and Directories
- `sources/`: Directory for additional source files.
- `src/main/`: Main source code directory where the implementation of CPU scheduling algorithms resides.
- `target/`: Directory for compiled classes and build artifacts.
- `pom.xml`: Maven project file for managing dependencies and build configurations.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher.
- Apache Maven (optional, for building the project).
- A Java IDE (e.g., IntelliJ IDEA, Eclipse) or any text editor with Java support.

### Installation

1. Clone the repository to your local machine using:
   ```bash
   git clone https://github.com/ammarlodhi255/cpu-scheduling-simulator.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd cpu-scheduling-simulator
   ```

3. Open the project in your preferred Java IDE.

### Usage

1. **Compile the project**: Ensure all `.java` files are compiled. Most IDEs handle this automatically.
2. **Run the Simulator**:
   - Execute the main class in `src/main/` to launch the simulator's user interface.
   - Choose the desired CPU scheduling algorithm and input the process data.
3. **View Results**:
   - The simulator will display the sequence of process execution and calculate important metrics like waiting time, turnaround time, and CPU utilization.

### Example

- **Simulating Round Robin Scheduling**:
  1. Open the simulator.
  2. Select "Round Robin" from the list of algorithms.
  3. Input the number of process.
  4. Click "Start" to see the order of execution and performance metrics.


