# Performance Evaluation in Computer Systems and Networks Project

A project focused on performance evaluation, queueing behavior, and system analysis through a game-inspired service model.

## Overview

This repository contains a project for **Performance Evaluation in Computer Systems and Networks**.

The core scenario models a videogame-like system called **punch’em**, where an avatar fights two classes of opponents:

- **minions**
- **bosses**

The system can fight only one opponent at a time. If a boss arrives while a minion is being fought, the current minion fight is interrupted and the boss is served immediately. This creates a queueing and priority-based service model that can be analyzed from a performance evaluation perspective. :contentReference[oaicite:1]{index=1}

## Problem Description

According to the repository README, the game follows these rules:

- fights against both minions and bosses take time
- opponents arrive with interarrival times
- only one opponent can be fought at a time
- bosses preempt minions
- when a minion fight is interrupted by a boss arrival, the minion recovers health while the boss is being fought
- recovery happens at a rate equal to **x%** of the rate at which the minion’s health is depleted
- opponents of the same class are handled in **FIFO** order
- defeated opponents leave the game :contentReference[oaicite:2]{index=2}

This setup makes the project suitable for studying:

- preemptive priority systems
- queueing behavior
- service interruption and recovery effects
- response time and performance analysis

## Repository Structure

The repository currently contains the following main components:

```text
.
├── Analysis/
├── Documentation/
├── punchem/
├── Project7.pdf
└── README.md
```

These files and folders indicate that the project includes:

- analytical work
- documentation
- a `punchem` implementation or model
- a supporting PDF report or project handout :contentReference[oaicite:3]{index=3}

## Main Topics

This project is related to the following topics:

- Performance Evaluation
- Queueing Systems
- Priority Scheduling
- Preemptive Service Disciplines
- Computer Systems and Networks
- Analytical Modeling
- System Behavior under Interruptions

## Methodology

Based on the repository structure and problem statement, the project appears to combine:

- formal system modeling
- analytical or numerical performance analysis
- implementation or simulation through the `punchem` component
- supporting documentation and project reporting :contentReference[oaicite:4]{index=4}

## Key Modeling Concepts

The described scenario naturally maps to performance evaluation concepts such as:

- multi-class arrivals
- service-time modeling
- priority queues
- preemptive interruption
- FIFO service discipline within each class
- workload recovery / degradation effects
- comparison of service dynamics for different customer classes

## Possible Evaluation Goals

Typical goals in this kind of project may include:

- estimating waiting time for minions and bosses
- analyzing the effect of boss priority on minion completion time
- evaluating the impact of health recovery parameter `x`
- measuring queue growth under different arrival/service conditions
- comparing analytical and implementation-based results

## Documentation

The repository includes documentation-oriented material such as:

- `Documentation/`
- `Project7.pdf`

These likely support the theoretical description, project report, and analysis workflow. 

## Notes

This repository represents a performance evaluation project built around a game-inspired priority service model. Its structure suggests a combination of analysis, implementation, and documentation, centered on preemptive queueing behavior and opponent handling policies. :contentReference[oaicite:6]{index=6}


## License

This project is licensed under the MIT License.
