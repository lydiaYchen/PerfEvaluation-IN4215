# Performance modeling project

## There are three expected milestones:

1. **Project proposal** (mandatory, but ungraded - you will receive feedback): due on week 3
2. **Intermediate project meeting** (mandatory, but ungraded - you will receive feedback): due on week 6
3. **Final project report** (mandatory, graded): due on week 9
4. **20 min project presentation**

**Group projects are conducted in groups of 2-3 students. Please enroll together with your team members in group on Brightspace - we have predefined XXX different groups, take your pick! !**

## Grading breakdown
- Final report: 80%
- 15 min project presenation: 20 %

## Evaluation criteria

- The novelty of project 



## Choosing topics

There are two types of performance projects: (i) executions of application and (ii) trace driven analysis and simulation study.

### Excuting applications on testbed

You choose an computer application, e.g.,  web services, streaming processing, and (deep) machine learning systems, and conduct performance evalution analysis using quantiative techniques learned in the class. The aim is to discover and improve the performance issues of such an application, which is yet to be explored by the related work. To complete this project, you can perform (some of) following tasks:

-Before you start, you need to decdie (i) the metrics of intrests, e.g., latency, throughput or security volunerability, (ii) workload inputs, e.g, how often jobs are generated, and what job inputs to use, and (iii) the computing platforms, e.g., your laptop, Delft clusters, or Google.

- Design experiments to build a performance profiling of such an application, e.g., identify performance bottlnecks and optimal configuration.  You need to rigorously design experiments, collect the measurments, summarizes the results with appropriate statistical tests and graphic presenation.

- Derive white or black model for such an application in the scenario where jobs arrive stochastic fashion. You need to collect statstics that are essential to build predictive models. 

- Optimize the application performance via designing new application algorithms, configurations of the applications, and resource provisioning. It's imporatnat you choose an approach that can improve the metrics of your interests. For example, you can desing a resource scaling algorithm such that the run time of a training job is constant for any given input by scaling the number of computing nodes. Or you can desing a scheduling algorithms.  Or you can design a communication algorithm for the distributed version of such an application, which run on distributed nodes in cloud or edge. 


We strongly encourage you to use the following benchamrk [BigDL](https://bigdl-project.github.io), which is a deep learning benchmark suite that is easy to setup, versitle configuration files, rich functionalities, and multiple examples, including text analysis and image calssification. Your project based on this benchmark will provide some performance insights on  how to best tune modern AI jobs in a centralized or distributed way. We (the TA) will offer an additional tutorial session how to set up such a benchmark on September and provide a set of input used in the project. Here is a [detailed summary](https://arxiv.org/pdf/1206.5533.pdf) on the key parameters one can change for their neural network.

Here is list of recent papers that address different performance issues and leverage performance 

 Several groups can choose the same paper to reproduce (though of course it is more interesting for us instructors if that does not happen too often). To be clear: **collaborations across groups are not allowed** - every group has to work independently. 



#### List of papers that can inspire you how to do performance evalution


- [Optimus.](https://i.cs.hku.hk/~cwu/papers/yhpeng-eurosys18.pdf) This paper first built a first-order model to capture the dynamices of neural network jobs and then design a novel cluster schedule algorithm. Extended resarch questions: how to replicate the similar idea on BigDL cluster, validation of their model for BigDL and your specific scenarios.

- [Model Driven Computational Sprinting](http://web.cse.ohio-state.edu/~stewart.962/Papers/morris2018modeldriven.pdf) This paper derived tree-based machine learning models to guid the sprinting policies

- https://www.usenix.org/conference/osdi18/presentation/lee

- https://www.usenix.org/conference/osdi18/presentation/xiao

- https://www.usenix.org/conference/atc19/presentation/zhang-chengliang

- https://www.usenix.org/conference/atc19/presentation/zhang-xu




## Report formats

### Project proposal

The proposal should contain between 300 and 400 words. Your proposal should address the following points:

1. Problem description: which problem will you tackle and what is interesting about the problem? If you reproduce a paper make sure to reference the original paper.
2. Resources: which data and tools will you be using (this includes also existing implementations of algorithms
3. Methodology: if you choose to reproduce a paper, tell us which part of the paper (if not all) you will reproduce; if you choose your own research idea, tell us what type of algorithm/approach you are proposing and what your baseline(s) will be
4. Background readings: list at least 5 related papers that you will read to add context to your research
5. Evaluation: how will you evaluate your algorithm/approach? Which evaluation metrics will you use?

**Submission**: every group uploads their proposal on Brightspace. The proposal should be in PDF format and should contain the group name and the list of group members (name, student IDs).

**Feedback**: the course team will provide feedback on the project proposal within a few days.

### Intermediate and final project report

The **final** group project report should be **6-7 pages** long in the [SIG XX proceedings format](https://sigchi.org/templates/) (available as LaTeX and Word templates) - even if the paper you originally chose to reproduce is 2 or 4 pages long, we still expect your report to adhere to the 6-7 page limit (think about the related work, implementation issues, analyses of results, etc. that are often underdeveloped in short papers). 
 <!---The **intermediate** project report is likely to be shorter (it is due a week before the final deadline), that is fine, submit whatever you have by then.)
 -->

We suggest the following final report structure:

- Title, authors
- Abstract
- Introduction: problem statement, motivation for the problem, overall plan to tackle the problem
- Background: what important works does this project build on
- Approach: what methods/algorithms did you use
- Experiments: describe your experiments, the results and discuss them
- Conclusions: describe what you learnt/found and what avenues for future work you see
- References

The final report should also contain a link to a repository (or several) that contain the software you created, the scripts you used to analyze your data, etc.

Submission: every group uploads their intermediate presentation and final group project reports on Brightspace. The reports should be in PDF format. Note that after submission a plagiarism check is executed by Turnitin - please make sure to follow the academic rules of writing ([you can read them up here one more time](https://www.tudelft.nl/library/actuele-themas/copyright/c/plagiarism/)).

In addition, your report must also include a figure that graphically depicts a major component of your project (e.g., your approach and how it relates to the application, etc.). Such a summary figure makes your paper much more accessible by providing a visual counterpart to the text. Developing such a concise and clear figure can actually be quite time-consuming; I often go through around ten versions before I end up with a good final version.

The final project report is graded in combination with the project interview. The interview will be an academic discussion about the executed project.

## Interviews

The 20 minute interviews per group will be scheduled on ** 14** and ****. 
