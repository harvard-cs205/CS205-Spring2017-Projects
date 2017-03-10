# CS205: Projects in Parallel Data Science at SCALE
spring 2017

![alt text](https://github.com/harvard-cs205/CS205-Spring2017-Projects/edit/master/images/projectsimg.png "Parallel Data Science")


# About
Extreme scale data science at the convergence of big data and massively parallel computing is enabling simulation, modelling and real-time analysis of complex natural and social phenomena at unprecedented scales. The aim of the project is to gain practical experience into this interplay by applying parallel computation principles in solving a compute and data-intensive problem. 
Applying interdisciplinary principles and skills of parallel computation and data science from CS205 and other courses  the goal is to construct a novel parallel software solution for an open-ended data science application that requires orders of magnitude compute scaling using Harvard’s supercomputer: Odyssey. Additionally, the project provides an opportunity to apply novel concepts and technologies to create niche applications and research outputs.

# Requirements
As a project team (**4 to 5 members**) you will identify a data science problem,  analyse its compute scaling requirement, collect the data, design and implement a parallel software, and demonstrate  scaled performance of an end-to-end application.

## The parallel software solution
- should be implemented on a heterogenous  distributed memory architecture with either a many-core or a multi-core compute node and  evaluated on 8 compute nodes (note: each compute node on Odyssey is a multi-core with 32 (or 64) cores or with a manycore GPU with hundreds of cores). 
- as a  hybrid parallel program in either i) MPI+OpenMP or ii) MPI+OpenAcc (or CUDA ) or iii) Spark+?
- and  its performance evaluated  on large data sets to  demonstrate both weak and strong scaling using appropriate metrics (throughput, efficiency, iso-efficiency).
- and should solve a problem for a  non-trivial computation graph and with hierarchical parallelism. 

# Project Deliverables
1. Web site
...+ Introduction 
..+ End-to-end application 
..+ Description of parallel software solution with links to code repository
..+ scaling plots (weak and strong scaling)
2. Software with evaluation data sets (on Github repo)
3. Presentation to the class and staff
