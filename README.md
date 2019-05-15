<img src="img/wordcloud.jpg" width="300px" align="middle">

# IN4325 <!-- omit in toc -->

This repository contains the materials of the **MSc Information Retrieval** course running in 2018/19 at TU Delft (Q3). The project setup is suitable for up to 100 students.

## Table of contents <!-- omit in toc -->
- [Important links](#important-links)
- [Course description](#course-description)
- [Text books](#textbooks)
- [Course team](#course-team)
- [ECs](#ecs)
- [Learning objectives](#learning-objectives)
- [:dart: Grading policy](#dart-grading-policy)
  - [Homework](#homework)
  - [Group projects](#group-projects)
- [Schedule](#schedule)
- [Collaboration v.s. cheating](#collaboration-cheating)
- [Relevent references](#relevant-references)




## Important links

- [Lectures notes](lecture.md)
- [Project descrition](project.md)
- Signing up on Slack: [https://join.slack.com/t/in43252019/signup](https://join.slack.com/t/in43252019/signup)
- Signing up for support and the group interview: [https://queue.ewi.tudelft.nl/](https://queue.ewi.tudelft.nl/)

## Course description

<img style="float:right;" src="img/library.png" width="200px">

Performance Evalution

**But how do search engines actually work?** This is what this course is about. In the **first module** of the course, we focus on **core IR** techniques such as indexing, retrieval models, evaluation metrics and so on. 

In the **second module** of the course we cover natural language processing (NLP) and natural language generation (NLG). While for many years, IR and NLP researchers stayed far away from each other, in recent years the two fields have moved closer together, with search engines using many NLP techniques to enhance the search experience--e.g. by providing automatically generated explanations of search result rankings and by enabling a _dialogue_ to take place between the search engine and user.

The split (core IR / applied NLP) will be made halfway through the course: the first eight lectures cover core IR techniques, the remaining eight lectures cover applied NLP techniques with applications to search in mind. 

## Textbooks

## Course team

This distribution also fits the lecturer team of this course: [Associate Prof. Lydia Y Chen](https://lydiaychen.com//) teaches the core IR lecture. The course team is composed of a number of PhDs (all from the [Distributed System group](http://www.ds.ewi.tudelft.nl/)) who support the course through guest lectures and project supervision and a TA who focuses on the grading of the paper reviews:


-  (PhD student)
-  (PhD student)


Lydia is the responsible instructors of this course and can jointly be reached at **y.chen-10@tudelft.nl**.

The whole course team can also be found on a dedicated [Slack channel](https://join.slack.com/t/in43252019/signup) - join it to get quick feedback on questions/issues. You have to use your `@student.tudelft.nl` email address to join!

## ECs

This is a **5 EC course**, with **140 hours** of course work in total. We expect you to spread the load evenly across the 9 course weeks.

## Learning objectives

- Apply queueing and machine-learning models to analyze performance of modern computing systems, e.g., web servers, cloud systems, machine learning clusters, and datacenters.
- Derive models to predict the performance of selected computing system designs, e.g., the average latency, failure, energy consumption, and scalability
- Design experiments to profile applications and their workloads, extracting key inputs for the derived queueing and machine-learning models
- Develop resource provisioning policies and validate them on real computing systems

- **Evaluate** natural language processing applications in different task contexts.
- Illustrate suitable application scenarios for advanced natural language processing topics such as **natural language queries** and **summarization**.

## :dart: Grading policy

This course has no final exam, instead the grade is largely determined through three components: 

1. Two Homework assigmnets (50%)
2. Group projects (40% )
3. Presentation (10%).

**All assessment items (reviews, projects reports) have to be submitted via Brightspace.**


### Homework

Most lectures are accompanied by **one required reading**, which is usually a scientific paper. For every required reading you are asked to write a *review*. These review activities are individual work.

Each review is graded as either *excellent*, *sufficient* or *insufficient*. In order to pass the course, 9 of the 14 offered review opportunities have to be passed with at least *sufficient*. Use the provided [review template](reviewForm.md) and follow its instructions. Reviews are submitted via Brightspace.

### Group projects

The group projects follow each other. During the first 5 course weeks, the group tackles the [core IR project](projectCoreIR.md) (reproducing a research paper essentially), during the second 5 weeks of the course the group tackles the [applied NLP project](projectAppliedNLP.md).

Group size:
- 2-3 students.


At the end of each project phase we will conduct a short interview (20 minutes per group) about the group project and its connection to the course content. Based on the project report and the interview, each member of the group receives a grade. We have two project phases (core IR and applied NLP), so each group will have one interview in week 5 and week 9 (*tentatively*).



In order to pass this course, you need to fullfil **all** of the following:
1. Receive an overall grade of 5.8 or higher (in alignment with TU Delft's exam regulations). 
2. Complete both project phases with at least a grade of 5.0.
3. Receive a *sufficient* for at least 9 of the 14 reviews.

## Schecule

## Collaboration v.s. cheating


You will receive one homework every few weeks. These are meant to reinforce the material that we are learning during that time, so please start immediately. Please do not search the web for help on the homework problems. It is difficult to develop good homework problems, and thus you may come across similar problems if you search the web for help. 

You are strongly encouraged to collaborate with your classmates on these problems, but each person must write up the final solutions individually. You should note on your homework specifically which problems were a collaborative effort and with whom.


## Relevant references 

### Online lecture notes

 - Caltech
 - CUHK, [Computer System Performance Evaluation](http://www.cse.cuhk.edu.hk/~cslui/csc5420.html]Computer) , John C.S. Lui
 - Columbia, [ Stochastic Models](http://www.columbia.edu/~ww2040/6711F08/IEOR6711F08.html), Ward Whitt
 - TuE [Queueing Theor](http://www.win.tue.nl/~iadan/queueing.pdf), Ivo Adan
- Columbia,[Performance Modeling and Evaluatio](http://www.ee.columbia.edu/~egc/e6180a.html), Ed Coffman
- UMASS Amherst,[Performance Evaluation](http://www-net.cs.umass.edu/pe2002/notes.html), Don Towsley


### Books on stochastic process
- S. M. Ross,  Introduction to Probability Models
- S. M. Ross,  Stochastic Processes
- R. W. Wolff,  Stochastic Modeling and the Theory of Queues
- L. Kleinrock,  Queueing Systems, Vol. I: Theory
- L. Kleinrock,  Queueing Systems, Vol. II: Computer Applications
- S. Karlin and H. M. Taylor,  A First Course in Stochastic Processes
- S. I. Resnick,  Adventures in Stochastic Processes
- W. Whitt, Stochastic Process Limits


### Books on performance modeling

- H. Kobayashi and B. L. Mark, System Modeling and Analysis
- E. Lazowska, J. Zahorjan, S. Graham, K. Sevcik,  Quantitative System Performance
- D. Menasce, V. Almeida, and L. Dowdy,  Capacity Planning and Performance Modeling
- R. Jain,  The Art of Computer Systems Performance Analysis: Techniques for Experimental Design, Measurement, Simulation, and Modeling

test
