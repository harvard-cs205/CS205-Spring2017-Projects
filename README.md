# CS205: Projects in Parallel Data Science at SCALE
Spring 2017

![]
(https://github.com/harvard-cs205/CS205-Spring2017-Projects/blob/master/about.png)


## About
Extreme scale data science at the convergence of big data and massively parallel computing is enabling simulation, modelling and real-time analysis of complex natural and social phenomena at unprecedented scales. The aim of the project is to gain practical experience into this interplay by applying parallel computation principles in solving a compute and data-intensive problem. 
Applying interdisciplinary principles and skills of parallel computation and data science from CS205 and other courses  the goal is to construct a novel parallel software solution for an open-ended data science application that requires orders of magnitude compute scaling using Harvard’s supercomputer: Odyssey. Additionally, the project provides an opportunity to apply novel concepts and technologies to create niche applications and research outputs.

## Requirements
As a project team (**4 to 5 members**) you will identify a data science problem,  analyse its compute scaling requirement, collect the data, design and implement a parallel software, and demonstrate  scaled performance of an end-to-end application.

### The parallel software solution
- should be implemented on a heterogenous  distributed memory architecture with either a many-core or a multi-core compute node and  evaluated on 8 compute nodes (note: each compute node on Odyssey is a multi-core with 32 (or 64) cores or with a manycore GPU with hundreds of cores). 
- as a  hybrid parallel program in either 
  * MPI+OpenMP 
  * MPI+OpenAcc (or CUDA ) 
  * PGAS + X 
  * Spark (with GPU acceleration)
- its performance evaluated  on large data sets to  demonstrate both weak and strong scaling using appropriate metrics (throughput, efficiency, iso-efficiency).
- and should solve a problem for a  non-trivial computation graph and with hierarchical parallelism. 

## Advanced concepts and technologies
To create novel parallel software solutions, or to undertake a research oriented outcome,  you can make use of advanced concepts and technology that was explored in the course. Implementations in the form of libraries and open source software  are available to build niche applications on top of it:
- ‘Cutting edge’ P100 GPU architecture at 10 TeraFlops throughput from National resource (https://www.xsede.org/). Create an account in the XSEDE portal https://portal.xsede.org/ if you wish to go down the MPI+ OpenAcc path in the project. 
- Communication avoiding algorithms  to achieve strong scaling (to be installed on Odyssey).
- Polyhedral model software to synthesise tiled parallel programs (OpenMP). https://sourceforge.net/projects/pocc/
- Parallel algorithm formulation in the semi-ring (libraries).


## Project Deliverables
1. Web site (max. 2 pages in poster format)
   * Introduction which should include comparison with existing work on the problem.
   * Background of end-to-end application with data sets used for evaluation.
   * Technical description of parallel software solution with links to code repository and test cases. 
   * Application scaling plots (weak and strong scaling).
2. Software with evaluation data sets (on Github repo)
3. Presentation to the class and staff

### Project Milestones
The milestones for your final project will be graded individually. It is important to adhere to the deadlines as the late date submission policy does not apply to projects. 

| Milestones    | Deadline  | 
| :------------- |:-------------| 
| Project Team announcement (sign up document deposited in Git repo)     | 22nd March 2017 | 
| Project Proposal (1 page web site)       | 24th March 2017      |
| Interim progress report (website populated with preliminary results) | 15th April      | 
| Project deliverables (web site, code, README)| 29th April      | 
| Project presentation to class (10 mins. + Qs)      | 2nd May 2017      | 
| Weekly meetings with project supervisors | 20th March to 25th April |

## Project submissions: Github and Piazza
- All submissions are per group. Make your own respository on Github with a link to your project web page.
- All project deliverables, including milestones related,  should be deposited in GitHub repos for peer evaluation.
- All project related correspondence should be posted on Piazza. 
- Project related emails (meeting schedules) to: cs205-2017projects@github.com, general queries to Piazza. Only critical (or personal) nature emails to project supervisors email. 

## Project Supervisors
1. Manju
2. Charles 
3. Rafael
4. WeiWeiPan

## Project choices and programming environments
- You can choose any data/computational science problem that you have already worked on in any other course: AC 209a, AC 209b, AM205, AM207, AC297R.
- Alternatively, your own research work with advanced concepts as above would be suitable to generate research output. 
- Supervisors may offer projects  based on their research interests. 
- You can re-use any code from the CS205 homework set and build your application software on top of it. But the code should be augmented with additional parallel code with  the requirements as specified above to gain further credit.
- You can implement the solution in any programming language of your choice (discuss with supervisors). 
- In the interdisciplinary spirit of the subject area, and the cs205 course, projects and project teams should have multiple disciplines.


## Research output (optional)
Optionally, the project may take the path of research and generate a research paper as output.  In this case the project requirements are:

1. To implement a parallel algorithm as above but to support the research problem being addressed.
2. To generate as  final output a technical paper of journal quality comparable in depth to  papers published  in leading journals in computational/data science or parallel computing.
3. To choose a parallel solution which could range from  a novel parallel graph algorithm  to optimising a scientific application  on odyssey with new insights,  and anything inbetween these two bounds of theory and experimentation.

## Project Grade
Project will be graded on the depth of work undertaken, communication (web site, presentation) and participation. 
- 10%: Project review (Peer and Supervisor meetings).
- 40%: Project software, README, overall quality (base line).
- 30%: Advanced features.
- 10%: Project web site.
- 10%: Presentation to class.

## Resources 
- Harvard Computational and Data Science: references in courses listed above in project choices
- NERSC data science projects: http://www.nersc.gov/science/science-highlights-presentations/
- Exascale Computing Project: https://exascaleproject.org/researchareas
- Previous years projects: http://iacs-courses.seas.harvard.edu/courses/cs205/projects.html


