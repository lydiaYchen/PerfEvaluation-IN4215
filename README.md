<img src="img/wordcloud.jpg" width="300px" align="middle">

# IN4215 <!-- omit in toc -->

This repository contains the materials of the **IN4215: MSc Quantitative Methods of Performance Evaluation for Computing systems** course running in 20119/20 at TU Delft (Q1). The project setup is suitable for up to 100 students.

## Table of contents <!-- omit in toc -->
- [Important links](#Important-links)
- [Course description](#Course-description)
- [Textbooks](#Textbooks)
- [Course team](#Course-team)
- [ECs](#ECs)
- [Learning objectives](#Learning-objectives)
- [:dart: Grading policy](#dart-Grading-policy)
  - [Homework](#Homework)
  - [Group projects](#Group-projects)
- [Detailed schedule](#Detailed-schedule)
- [Collaboration v.s. cheating](#Collaboration-vs-cheating)
- [Relevant references](#Relevant-references)
  - [Online lecture notes](#Online-lecture-notes)
  - [Books on performance modeling](#Books-on-performance-modeling)
  - [Books on statistical experiments and learning](#Books-on-statistical-experiments-and-learning)



## Important links

- [Lectures notes](lecture.md)
- [Project description](project.md)
- [Homework assignments](homework.md)


## Course description

<img style="float:right;" src="img/library.png" width="200px">


Todays computing systems become ever complex, due to the rapid development of hardware and software technology.  It is challenging to design and run computing systems that guarantee users’ performance requirements in a resource efficient way. Various quantitative methods are applied to capture such complex system dynamics and predict metrics of interests, from the designing phase of the systems to the runtime performance, e.g., job response times and system anomaly.  To optimize the performance of computing systems, a deep understanding on those methods and their applications on the system design are essential. Having practical hand-on experience on designing experiments, deriving models, and validating results with benchmark systems will prepare students to tackle challenges of real systems. 

Course topics include
- Design of experiments and statistical tests (week 1)
- Operational laws and queueing methods for modeling computing systems (week 2 and 3)
- Scheduling and load balancing  (week 4 )
- Machine learning methods for modeling computing systems (week 5)
- System security and scalability analysis (week 6)
- Optimization and resource management (week 7)


## Textbooks
-  Performance Modeling and Design of Computer Systems: Queuing Theory in Action by Mor. Harchol-Balter 
-  [The Art of Computer Systems Performance Analysis](https://www.cse.wustl.edu/~jain/books/perfbook.htm) by Raj Jain
-  [The Elements of Statistical Learning: Data Mining, Inference, and Prediction](https://web.stanford.edu/~hastie/ElemStatLearn/), Springer Series in Statistics



## Course team

This course will be mainly taught by [Associate Prof. Lydia Y Chen](https://lydiaychen.com/) and partially by [Assistant Prof. Mitra Nasri] and [Assistant Prof. Stefanie Roos]. The course team is composed of a number of PhDs (all from the [Distributed System group](http://www.ds.ewi.tudelft.nl/)) who support the course through guest lectures and project supervision and a TA who focuses on the grading of homework. The TA office hour will be one hour right after each lecture. TA will answer your questions about homework in their office (Building 28 3E050) 


-  [Taraneh Younesian](T.Younesian@tudelft.nl) (PhD student)
-  [Masoud Ghassi](S.ghiassi@tudelft.nl) (PhD student)


Lydia is the responsible instructors of this course and can jointly be reached at **y.chen-10@tudelft.nl**.


## ECs

This is a **5 EC course**, with **140 hours** of course work in total. We expect you to spread the load evenly across the 9 course weeks.

## Learning objectives

- Apply queueing and machine-learning models to analyze performance of modern computing systems, e.g., web servers, cloud systems, machine learning clusters, and datacenters.
- Derive models to predict the performance of selected computing system designs, e.g., the average latency, failure, energy consumption, and scalability
- Design experiments to profile applications and their workloads, extracting key inputs for the derived queueing and machine-learning models
- Develop resource provisioning policies and validate them on real computing systems


## :dart: Grading policy

This course has no final exam, instead the grade is largely determined through three components: 

1. Homework (50%): 2 individual homework due in week 4 (September 27 Friday 8 am) and 7 (October 18 Friday 8 am). Each homework accounts 25% of the grade and cover 3 weeks material. Homework will be given in week 1 and 4. Students have three weeks time to complete them. 

Late submission will result into 10% point reduction per day. 

2. Group project (50%): group project report (40%) and presentation (10%). There will be topics of modeling response times, configuring, dependability, scheduling dessign. There will be an initial proposal in week 3, interim discussion with each team in week 6. The final report will be due in week 9, and 20 minutes presentation in week 9 as well.


**All assessment items (homework, and projects reports) have to be submitted via Brightspace.**


### Homework
- Homework 1: due in week 4 (September 27, 8 AM)
- Homework 2: due in week 7 (October 18, 8 AM)

### Group projects
<!-- 7 predefined project topics: evaluating the systems of 
-->
There are different aspects of performance  on modeling and optimizing the executions of deep neural network jobs. In this project, you will play with benchmarks that emulate the training jobs of deep neural networks on top of Spark platform - one of the most popular platform. You can build a model to predict the performance such jobs, to optimize their response times through resource allocations and scheduling, and to test the dependability of such a cluster against malicious attacks. You will do this project in a group with 1-2 other peers.

- Group size: 2-3 students
- Schedule: initial proposal (week 3), interim meeting (week 6), report due (week 9), and presentation/interview (week 9)

At the end of each project phase we will conduct a short interview (20 minutes per group) about the group project and its connection to the course content. Based on the project report and the interview, each member of the group receives a grade. 



In order to pass this course, you need to fullfil **all** of the following:
1. Receive an overall grade of 5.8 or higher (in alignment with TU Delft's exam regulations). 
2. Each homework and project at least a grade of 5.0.


## Detailed schedule
- Week1: Design of experiments 1 (September 2nd ) and Design of experiments II (September 5th)
- Week2: Operation laws (September 9th) and probability/Statistics review (September 12)
- Week3: DTMC/CTMC (September 16) and queueing theory (September 19)
- Week 4: scheduling policies
- Week5:  clustering and tree algorithms (September 30) and kernal and deep models (October 3)
- Week6: network dependability
- Week7: optimization (October 14) and simulation (October 17)


## Collaboration v.s. cheating


You will receive one homework every few weeks. These are meant to reinforce the material that we are learning during that time, so please start immediately. Please do not search the web for help on the homework problems. It is difficult to develop good homework problems, and thus you may come across similar problems if you search the web for help. 

Each pearson must write up the final solutions individually. If you discussion with classmates, please make sure you still work on your homework individually without copying solutions.




## Relevant references 

### Online lecture notes

 - [Design of Experiments](https://newonlinecourses.science.psu.edu/stat503/node/5/), Penn State University
 - [Computer System Performance Evaluation](http://www.cse.cuhk.edu.hk/~cslui/csc5420.html) , John C.S. Lui at CUHK
- [Data Mining](http://personal.psu.edu/jol2/course/stat557/), Jia Li at Penn State University
-  [Introduction to Machine learning](http://www.cs.cmu.edu/~epxing/Class/10701/), Eric Xing at Carnagie Mellon University



### Books on performance modeling
- Introduction to Probability Models by S. M. Ross, 
- Quantitative System Performance by E. Lazowska, J. Zahorjan, S. Graham, and K. Sevcik.
- Capacity Planning and Performance Modeling by D. Menasce, V. Almeida, and L. Dowdy 


### Books on statistical experiments and learning
- [Design and Analysis of Experiments] (http://faculty.business.utsa.edu/manderso/STA4723/readings/Douglas-C.-Montgomery-Design-and-Analysis-of-Experiments-Wiley-2012.pdf) by Douglas Montgomery
- [Dive into Deep Learning](https://www.d2l.ai/) by Alex Smola et. al.
- [Pattern Recognition and Machine Learning]() by Christopher Bishop 




