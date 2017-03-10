# CS205: Projects in Parallel Data Science at SCALE
spring 2017

![alt text](https://github.com/harvard-cs205/CS205-Spring2017-Projects/edit/master/images/projectsimg.png "Parallel Data Science")


# About
Extreme scale data science at the convergence of big data and massively parallel computing is enabling simulation, modelling and real-time analysis of complex natural and social phenomena at unprecedented scales. The aim of the project is to gain practical experience into this interplay by applying parallel computation principles in solving a compute and data-intensive problem. 
Applying interdisciplinary principles and skills of parallel computation and data science from CS205 and other courses  the goal is to construct a novel parallel software solution for an open-ended data science application that requires orders of magnitude compute scaling using Harvard’s supercomputer: Odyssey. Additionally, the project provides an opportunity to apply novel concepts and technologies to create niche applications and research outputs.

## Requirements
As a project team (**4 to 5 members**) you will identify a data science problem,  analyse its compute scaling requirement, collect the data, design and implement a parallel software, and demonstrate  scaled performance of an end-to-end application.

### The parallel software solution
- should be implemented on a heterogenous  distributed memory architecture with either a many-core or a multi-core compute node and  evaluated on 8 compute nodes (note: each compute node on Odyssey is a multi-core with 32 (or 64) cores or with a manycore GPU with hundreds of cores). 
- as a  hybrid parallel program in either i) MPI+OpenMP or ii) MPI+OpenAcc (or CUDA ) or iii) Spark+?
- and  its performance evaluated  on large data sets to  demonstrate both weak and strong scaling using appropriate metrics (throughput, efficiency, iso-efficiency).
- and should solve a problem for a  non-trivial computation graph and with hierarchical parallelism. 

### Project Deliverables
1. Web site
-  Introduction 
..* End-to-end application 
..+ Description of parallel software solution with links to code repository
..+ Application scaling plots (weak and strong scaling)
2. Software with evaluation data sets (on Github repo)
3. Presentation to the class and staff

### Project Milestones

| Milestones    | Deadline  | 
| :------------- |:-------------| 
| Project Team announcement (sign up document deposited in Git repo)     | 22nd March 2017 | 
| Project Proposal (2 pages max.)       | 24th March 2017      |  
| Project presentation to class (10 mins. + Qs)      | 25th April 2017      |  
| Project deliverables (web site, code, README)| 29th April      | 
| Weekly meetings with project supervisors | 20th March to 25th April |

## Project submissions: Github and Piazza
- All project deliverables, including milestones related,  should be deposited in GitHub repos for peer evaluation.
- All project related correspondence should be posted on Piazza. 
- Project related emails (meeting schedules) to: cs205-2017projects@github.com, general queries to Piazza. Only critical (or personal) nature emails to project supervisors email. 

## Project Supervisors
1. Manju
2. Charles 
3. Rafael
4. WeiWeiPan

## Project choices and programming environments
- You can choose any data/computational science problem that you have already worked on in any other course: eg., 109a, 109b, AM207, AC297R (Capstone) or your own research work. 
- Supervisors may offer projects  based on their research interests. 
- You can re-use any code from the CS205 homework set and build your application software on top of it. But the code should be augmented with additional parallel code with  the requirements as specified above to gain further credit.
- You can implement the solution in any programming language of your choice (discuss with supervisors). 
- In the interdisciplinary spirit of the subject area, and the cs205course, projects and project teams should have multiple disciplines.

## Advanced concepts and technologies
To create novel parallel software solutions the project can make use of advanced concepts and technology that was explored in the course. Implementations in the form of libraries and open source software  are available to build niche applications on top of it:
- Communication avoiding algorithms  to achieve strong scaling (to be installed on Odyssey).
- Parallel algorithm formulation in the semi-ring.
- Polyhedral model software to synthesise tiled parallel programs (OpenMP). https://sourceforge.net/projects/pocc/
- ‘Cutting edge’ P100 GPU architecture at 10 TeraFlops throughput from National resource (https://www.xsede.org/). (to be organised). 

## Research output (optional)
Optionally, the project may take the path of research and generate a research paper as output.  In this case the project requirements are:
1. To implement a parallel algorithm as above but to support the research problem being addressed.
2. The problem could be from generating a novel parallel graph algorithm  to optimise a scientific application  on odyssey with new insight and anything inbetween these two bounds of theory and experimentation.  
3. The final output is a technical paper of journal quality comparable in depth to  papers published  in leading journals in computational/data science  or parallel computing.

## Resources
- previous year project proposals
- Harvard Computational and Data Science
- NERSC data science projects.
- Exascale Computing Project 
