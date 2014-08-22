Milestone 1: Memory
====

Your task is to create a Verilog module for the memory. Call this `memory.v`. The single cycle CPU will use the memory as shown in the figure below. **Note** in the figure they show separate memory for instruction and data. This is not how modern Von Neumann processors are organized. In a Von Neumann processor (such as MIPS), instructions and data are stored in the same memory. Since we want to run actual MIPS code, we must implement a shared memory.

![Figure 4.24 from Patterson & Hennessey, 5ed](fig/single_cycle.png)

Inputs to the memory unit are:

* instruction address (32-bit)
* data address (32-bit)
* write data (1-bit)

Outputs from the memory unit are:

* instruction (32-bit)
* read data (32-bit)


Grading Rubric
----

This is a *binary* rubric. You either get full credit or you don't. 

Task | Failure (0%) | Success (100%)
---       | ---     | ---
Project created on GitLab, instructor added as a developer | Incomplete or fewer than 3 commits | Complete and more than 3 commits
Component functions as expected | Incomplete / does not function | Functions correctly
Documentation | Minimal, non-existent, or ugly looking documentation | Sufficient documentation to understand operation. Nicely formatted.




