# Performance modeling group project

There are different aspects of performance on modelling and optimizing the executions of deep neural network jobs. In this project, you will play with benchmarks that emulate the training jobs of deep neural networks on top of Kubernetes - one of the most popular platforms for distributed computing. You can build models to predict the performance such jobs, to optimize their response times through resource allocations and scheduling, and to test the dependability of such a cluster against malicious attacks. You will do this project in a group with 1-2 other peers.

## There are three expected milestones:

1. **Project proposal** (mandatory, but ungraded - you will receive feedback): due on week 5
2. **Intermediate project meeting** (mandatory, but ungraded - you will receive feedback): due on week 9
3. **Final project report** (mandatory, graded): due on week 13
4. **20 min project presentation** (mandatory, graded): due on week 13

**Group projects are conducted in groups of 2-3 students. Please enroll together with your team members in group on ILISA ! !**

## Grading breakdown
- Final report: 65%
- 15 min project presentation: 15 %
- Individual contribution: 20%

## Google testbed platform for (Kubernetes ) FLTK

Each team will be given a Google Cloud Platform coupon to set up their project and run their experiments. To request the Google coupon, you will need to follow the link below and provide your UNINE email address and name. Then, an email will be sent to you to confirm these details before a coupon is sent to you.

Details about the coupon:

Link: Student Coupon Retrieval link&nbsp;
Validation of coupon: now to 
You can only request ONE code per unique email address.

## Evaluation criteria
- The novelty of the proposed project.
- The rigorous of applying quantitative methods. The more methods applied, the higher the score.
- The performance improvement of the proposed solutions, compared to the based line performance (defined by you).
- The scale of the experiments, i.e., the number of servers, the number of data sets, the number of training algorithms.
- The completeness of the report.
- To get the passing grades, you need to execute and analyze at least two types of ML workloads on three different system configuration, using at least one modelling method.



## Choosing topics

There are different aspects of performance  on modeling and optimizing the executions of training deep neural network jobs, e.g., job response times, job accuracies, cluster utilization/energy, and dependability. In this project, you will play with benchmarks that emulate the training jobs of deep neural networks on top of Spark platform - one of the most popular big data processing platform. You will build models to predict the performance such jobs, to optimize their response times through resource allocations and scheduling, and to evaluate/test the dependability of such a cluster against malicious attacks or careless configurations/set-up.

Important rule: **collaborations across groups are not allowed** - every group has to work independently. 

### Executing applications on testbed

he benchmark you will fiddle with is (Kubernetes) FLTK, which is a deep learning benchmark suite built by our group. Your project based on this benchmark will provide some performance insights on how to best tune modern AI jobs in a centralized or distributed way. We (the TA) will offer an additional tutorial session on how to set up such a benchmark in the second week of the course and provide a set of inputs used in the project.

Note that we will provide a VM, which packages all the software needed to run (Kubernetes) FLTK and a workload generator that can emulate the users for such systems. The benchmark and installation manual can be found here (Performance_Evaluation_Project).

You set up (Kubernetes) FLTK benchmarks on a computing platform, being your laptops or any cluster of machines (eg., on the google cloud). You need to analyze their performance using quantitative techniques learned in the class. The aim is to analyze, discover and improve the performance issues of such an application, which is yet to be explored by the related work. To complete this project, you can perform (some of) following tasks:

Before you start, you need to decide (i) the metrics of interests, e.g., latency, throughput or security vulnerability, (ii) workload inputs, e.g, how often jobs are generated, and what job inputs to use, and (iii) the computing platforms, e.g., your laptop, Delft clusters, or Google.

Design experiments to build a performance profiling of such an application, e.g., identify performance bottlenecks and optimal configuration. You need to rigorously design experiments, collect the measurements, summarizes the results with appropriate statistical tests and graphic presentations.

Derive a white or black model for such an application in the scenario where jobs arrive stochastic fashion. You need to collect statistics that are essential to building predictive models. You are welcome to try all the models and have a light-weight optimization section. You can also study how such benchmarks can withstand different imperfect conditions, such as node failures (e.g., neural network layer nodes or spark nodes) or data packet drops.

Optimize the application performance via designing new application algorithms, configurations of the applications, and resource provisioning. You must choose an approach that can improve the metrics of your interests. For example, you can design a resource scaling algorithm such that the run time of a training job is constant for any given input by scaling the number of computing nodes. Or you can design scheduling algorithms. Or you may even design a communication algorithm for the distributed version of such an application, which can run on distributed nodes in a cloud or edge like fashion.




#### List of papers that can inspire you how to do performance evaluation
- Prediction-Based Power Oversubscription in Cloud Platforms. https://www.usenix.org/conference/atc21/presentation/kumbhare

- Habitat: A Runtime-Based Computational Performance Predictor for Deep Neural Network Training. https://www.usenix.org/conference/atc21/presentation/yu

- INFaaS: Automated Model-less Inference Serving. https://www.usenix.org/conference/atc21/presentation/romero

- Heterogeneity-Aware Cluster Scheduling Policies for Deep Learning Workloads. https://www.usenix.org/conference/osdi20/presentation/narayanan-deepak

- Elastic Parameter Server Load Distribution in Deep Learning Clusters. https://dl.acm.org/doi/10.1145/3419111.3421307

- InferLine: Latency-Aware Provisioning and Scaling for Prediction Serving Pipeline. https://arxiv.org/abs/1812.01776

- AlloX: compute allocation in hybrid clusters This paper is published at Eurosys19. Modern deep learning frameworks support a variety of hardware, including CPU, GPU, and other accelerators, to perform computation. This paper study how to schedule jobs over such interchangeable resources - each with a different rate of computation - to optimize performance while providing fairness among users in a shared cluster.

- HetPipe: Enabling Large DNN Training on(Whimpy) Heterogeneous GPU Clusters This paper is published at ATC20. It is inevitable to use heterogeneous GPU to train deep neural network due to the short release cycle of new GPU architectures. This paper investigates how to enable training of large DNN models on a heterogeneous GPU cluster.

## Report formats

### Project proposal

The proposal should contain between 300 and 400 words. Your proposal should address the following points:

1. Problem description: which performance problem of which application will you tackle and what is novel about the problem?  
2. Experiment setup: what workloads, and testbeds will you use?
2. Exploration of experiments: what parameters and configurations do you plan to explore?
3. Predictive analysis: what analytical methods will you apply and what predictive models will derive?
5. Optimization and validation: how will you evaluate your algorithm/approach and what type of resource and algorithmic suggestions will explore?
6. Background readings: list at least 5 related papers that you will read to add context to your research

**Submission**: every group uploads their proposal on ILIAS. The proposal should be in PDF format and should contain the group name and the list of group members (name, student IDs).

**Feedback**: the course team will provide feedback on the project proposal within a few days.

### Final project report

[UPDATE] We change the requirement. You just need to submit ppt slides, which summarize the results. If you submit a report, you will be getting bosnus point.

The **final** group project report should be **6-7 pages** long in the [IEEE conference proceedings format](https://www.overleaf.com/latex/templates/ieee-conference-template-example/nsncsyjfmpxy) (available as LaTeX and Word templates) - even if the paper you originally chose to reproduce is 2 or 4 pages long, we still expect your report to adhere to the 6-7 page limit (think about the related work, implementation issues, analyses of results, etc. that are often underdeveloped in short papers). 
 <!---The **intermediate** project report is likely to be shorter (it is due a week before the final deadline), that is fine, submit whatever you have by then.)
 -->

We suggest the following final report structure:

- Title, authors
- Abstract
- Introduction: problem statement, motivation for the problem, and the overview how
- Background: what important works does this project build on
- Experiments: describe your setup and present the baseline results
- Predictive models: describe your analytical approach for performance prediction
- Optimization strategy: describe your optimization algorithms/strategies that can improve the performance 
- Conclusions: what can be the future direction
- References 

The final report should also contain a link to a repository (or several) that contain the software you created, the scripts you used to analyze your data, etc.

Submission: every group uploads their intermediate presentation and final group project reports on ILIAS. The reports should be in PDF format. Note that after submission a plagiarism check is executed by Turnitin - please make sure to follow the academic rules of writing ([you can read them up here one more time](https://www.tudelft.nl/library/actuele-themas/copyright/c/plagiarism/)).

In addition, your report must also include a figure that graphically depicts a major component of your project (e.g., your approach and how it relates to the application, etc.). Such a summary figure makes your paper much more accessible by providing a visual counterpart to the text. Developing such a concise and clear figure can actually be quite time-consuming; I often go through around ten versions before I end up with a good final version.

The final project report is graded in combination with the project interview. The interview will be an academic discussion about the executed project.

## Interviews

The 20 minute interviews per group will be scheduled on the last week of the course. 
