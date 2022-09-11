---
layout: project
title: Teaching Responsible Computing
description: Incorporating responsible computing and ethics in computing courses
tagged_people: Matthew Bolton,Varun Chandola,Kenneth Joseph,Jonathan Manes,Dalia Antonia Caraballo Muller,Atri Rudra,Mark Shepard,<a href='https://www.linkedin.com/in/kimberlyboulden' target='_blank'>Kimberly Boulden</a>,<a href = 'https://cse.buffalo.edu/~hartloff/index.html' target='_blank'>Jesse Hartloff</a>,<a href = 'https://cse.buffalo.edu/~mhertz/' target='_blank'>Matthew Hertz</a>,<a href='https://odin.cse.buffalo.edu/people/oliver_kennedy.html' target='_blank'>Oliver Kennedy</a>,<a href = 'https://nsr.cse.buffalo.edu/?page_id=272' target='_blank'>Steve Ko</a>,<a href = 'https://cse.buffalo.edu/~jwinikus/' target='_blank'>Jennifer Winikus</a>
key: Teaching Responsible Computing
---

## Project Overview
Computing is ubiquitous in our daily lives. Increasingly computing makes decisions in our lives starting from the mundane (e.g. Netflix recommending  us movies/TV shows or sensors dispensing soap), to the somewhat more relevant (e.g. algorithms deciding which ads Google shows you or a car parking itself) to the downright worrisome (e.g. automated systems deciding the risk of a person who is arrested committing a crime in the future or automated "killer drones"). 

While we have (and continue to) educate our computing students on the  technical aspects of building computing systems that are used in our daily lives, there has been relatively less focus on incorporating ethics and responsible computing in such courses. Our project aims to incorporate ethics and more generally responsible computing in a wide range of computing courses.

While most of our work in this project has been in incorporating responsible computing in our [courses](#courses), we have also created [grading rubric](#rubric) for ethical/responsible computing related assignments.

## <a name="courses">Courses</a>

We have currently targeted a mix of courses: three required courses (spanning the first year, sophomore and senior year) for the BS Computer Science degree, one popular elective and created one new elective. Here is a quick overview of the courses that we targeted:

- _Required courses_
    - First year seminar ([CSE 199](https://cse.buffalo.edu/faculty/ahunt/classes/internet/)): Module on history, society and diversity,  module on societal computing and module on making computing anti-racist were targeted. Each module is a two week long combination of lectures and in-class activities. CSE 199 is required for BS Computer Science and BS Computer Engineering programs.
    - Data structures course ([CSE 250](https://odin.cse.buffalo.edu/teaching/cse-250/2021fa/index.html)): Co-developed with <a href="https://www.garegin.info/" target="_blank">Garegin Grigoryan</a> at Alfred University (their data structures course is [CSCI 157](https://www.garegin.info/blog/17/)). Students did homework(s) on data anonymization.
    - Algorithms course ([CSE 331](http://www-student.cse.buffalo.edu/~atri/cse331/fall19/index.html)): Homework assignments and a project based on access to high-speed Internet in Western New York (WNY) were introduced. CSE 331 is required for the BS Computer Science program.
    - Capstone course ([CSE 442](https://cse.buffalo.edu/~mhertz/2019fall/cse442/)): Students review a made-up dossier of government data to identify if an individual should be added to the government’s No-Fly list. Students must then discuss biases in the data provided and, finally, how they would respond if their job assigned them to the team automating this analysis.  A second assignment asks students to document the ethical implications of the capstone project they chose. CSE 442 is the capstone course for the BS Computer Science program.
- _Existing elective_
    - Machine learning course ([CSE 474](http://www.cse.buffalo.edu/~chandola/machinelearning.html)): Students worked in a group project exploring bias in data driven criminal risk assessment
- _New course_
    - [Algorithms and Society](http://www-student.cse.buffalo.edu/~atri/algo-and-society/spr20/index.html): This course has separate sections for CSE and non-CSE majors (but seated in the same room). The goal is to give non-CSE students a non-trivial understanding of various stages of the ML pipeline and for CSE students to get a deep dive into societal implications of machine learning systems. The class is a [mix of lectures and discussions](http://www-student.cse.buffalo.edu/~atri/algo-and-society/spr20/schedule.html).

<b><a href="#materials">Interested in using any of the above material in your class?</a></b>

Next, we provide bit more details on the ethical and/or responsible computing assignments that we created as part of our existing courses:

### First year seminar (CSE 199)

The first year seminar is composed of  six two-weeks modules (consisting of four lectures and two in-class activities) and we picked two modules in the first year seminar.

#### History, Society and Diversity module

It is easy to take for granted how much computers are part of our life. This module explores how we got here and what computing means to modern day life, all with a connection to societal issues and ethics.

##### Week 1 material

This week the exploration is historical, from the beginning though modern times.

Here are all the relevant material for week 1 of the module:
* [Lecture videos for week 1](https://ub.hosted.panopto.com/Panopto/Pages/Sessions/List.aspx?folderID=53f4d538-94d9-4268-8d37-ac150015b63f)
* [Lecture slides for week 1](https://drive.google.com/drive/folders/1gHQAeoXYz9KpGJcsslGZ7bfCRuKloxI_?usp=sharing)
* [Material for week 1 activity](https://drive.google.com/drive/folders/1YXrFL2iYX9iFJx6Uv-9_aItWtkeduiJh?usp=sharing)

##### Week 2 material

This week looks at the societal issues with computing and modern trends in how computers are part of life.
Here are all the relevant material for week 2 of the module:
* [Lecture videos for week 2](https://ub.hosted.panopto.com/Panopto/Pages/Sessions/List.aspx?folderID=7a1d778a-dd02-45a4-a370-ac4000f5b298)
* [Lecture slides for week 2](https://drive.google.com/drive/folders/1--REPOxagD_dWPtzyc3AJzGW3eRgP5qx?usp=sharing)
* [Material for week 2 activity](https://drive.google.com/drive/folders/13yfQG_ukE_bOQYfCyfyqXiOITY65pL2W?usp=sharing)

#### Societal Computing 

The Societal Computing module of CSE199 introduces students to the idea of Societal Computing, which we define as computing for, in, and ideally, with, society. (We note that this is our own definition of societal computing, but it is _not_ our term. The concept originates in various places, including as the namesake of [Carnegie Mellon's Societal Computing Ph.D. program](https://sc.cs.cmu.edu/).)

##### Week 1 material

In the first week, we cover the idea of societal computing and how it can be used as a critical lens through which we can understand today's applications of machine learning technologies.


Here are all the relevant material for week 1 of the module:
* [Lecture Slides for week 1]({{ site.url | append: "assets/resources/cse199/societal-computing/week_1_slides.pdf"}})
* [Week 1 assignment]({{ site.url | append: "assets/resources/cse199/societal-computing/assignment1.pdf"}})
* [Week 1 recitation activity]({{ site.url | append: "assets/resources/cse199/societal-computing/activity1.pdf"}})

##### Week 2 material

In the second week, we turn to social media, taking another critical lens as we chart the history of social media, its benefits (e.g. as a space for [networked counterpublics](https://onlinelibrary.wiley.com/doi/abs/10.1111/jcom.12185)) and its many, many failings.

Here are all the relevant material for week 2 of the module:
* [Lecture Slides for week 2]({{ site.url | append: "assets/resources/cse199/societal-computing/week_2_slides.pdf"}})
* [Week 2 assignment]({{ site.url | append: "assets/resources/cse199/societal-computing/assignment2.pdf"}})
* [Week 2 recitation activity]({{ site.url | append: "assets/resources/cse199/societal-computing/activity2.pdf"}})

#### Making Computing Anti-Racist

This module was created using <a href="https://www.daliamuller.com/" target="_blank">Dalia Muller</a>'s <a href="https://www.daliamuller.com/impossible-project" target="_blank">Impossible project framework</a>. In CSE 199, students are asked to spend two weeks of their semester imagining what it would take to build a world in which computing could become anti-racist. Starting with the specific case of the use of predictive policing algorithms, they proposed computational and non-computational solutions to the problems exacerbated by technology in society.


For more details, please see the CSE 199 [Impossible project webpage](https://www-student.cse.buffalo.edu/cseimpossibleproject/). Below is a video that gives an overview of the module (as well as its development):

<p align="center">
<iframe title="vimeo-player" src="https://player.vimeo.com/video/741278133?h=3924918b2d" width="640" height="360" frameborder="0" allowfullscreen></iframe>
</p>

### Data Structures course (CSE 250 at UB and CSCI 157 at Alfred University)

The goal of this project was to show how simple anonymization trick of dropping sensitive information from a data set and releasing it does not guarantee any privacy if e.g. the "anonymized" dataset could be "joined" with another publicly available dataset. E.g. <a href="https://dataprivacylab.org/people/sweeney/">Latanya Sweeney</a> used this idea to [figure out the medical details of the MA governor](https://epic.org/wp-content/uploads/privacy/reidentification/Sweeney_Article.pdf). As another example, In 2007, Netflix held a competition to improve their recommendation algorithms. This required releasing a large amount of anonymous data from their customers' movie ratings and viewing histories. By combining the Netflix data set with the Internet movie database (IMDb) site data, [researchers found a way to link the identity of a Netflix user to a user's IMDb profile based on the select reviews that they published](https://ieeexplore.ieee.org/document/4531148).

A two-part homework module was co-developed at UB and Alfred University and piloted in Fall 2021 and Spring 2022 respectively.

#### CSE 250 at UB

This project was in Scala and required students to 
* Load health records and voter records (via `.csv` files)
* Compute the join of the two datasets using Hashmaps and return only the health records of voters who were uniquely identified in this join.
* Compute aggregate statistics

[This page has more details](https://github.com/UBOdin/cse250-maps-anonymization).

#### CSCI 157 at Alfred University

This project was in python and required students to
* Load voter records and survey responses
* Combine the anonymized version of survey responses (the first and last names of the responders were removed but birthday and zipcode were not removed) and voters record to figure out the survey responses of specific respondents.
* Use the method of [randomized response](https://en.wikipedia.org/wiki/Differential_privacy#Randomized_response) to anonymize the data set
* Compare the statistics generated by the randomized response dataset and the original data.

[This page has more details](https://github.com/AUCSLAB/csci157-anonymization).

### <a name="cse331">Algorithms course (CSE 331)</a>

There are multiple activities/assignments in CSE 331 that all have the common thread of accessing high speed Internet. The main reason for this choice was because this is an issue all of our students could appreciate at a personal level. COVID-19 hit _after_ we implemented/ran these activities in Fall 2019. In future iterations we plan to incorporate increased awareness of the structural inequalities when it comes to access to high speed Internet (see e.g. this [Netgain Partnership](https://www.netgainpartnership.org/)  webinar on [Broadband Access in the US](https://www.netgainpartnership.org/events/covid19/broadband-access-in-the-us)) that has been brought to the fore by the pandemic.

Below we provide an overview of four activities/assignments that we piloted in Fall 2019.

#### In class discussion on improving broadband access in WNY

The introductory lecture asks students to think about how they would improve broadband access in [Cattaraugus county](https://en.wikipedia.org/wiki/Cattaraugus_County,_New_York) (which is one county over from [Erie](https://en.wikipedia.org/wiki/Erie_County,_New_York), which is where [Buffalo](https://en.wikipedia.org/wiki/Buffalo,_New_York) resides). Students are asked to talk in small groups in the lecture to think about both technical as well as societal issues as they think about how to solve the whole problem. 

This in-class activity on improving Internet access in Cattaraugus county was an activity that was used in CSE 331 before Fall 2019 though the focus was mostly on the technical aspects. Starting in Fall 2019, students were explicitly asked to think about societal issues as well.

[This related talk]({{ site.url | append: "talks/Incorporating Societal Context in an UG Algorithms course.html" }}) provides more details on this in-class activity including some of the in-class responses.


#### Greedy algorithm problem

[Greedy algorithms](https://en.wikipedia.org/wiki/Greedy_algorithm) is perhaps the basic algorithmic technique. CSE 331 covers greedy algorithms for bit over 2 week period. One of the homework problems for greedy algorithms (which is a classical covering an interval with minimum number of fixed width intervals that can "slide" as needed) asks the students to provide high speed Internet coverage on a straight line using wireless network towers. The problem is connected to the in-class discussion on access to high speed Internet from the first lecture.

Here are [the details on the actual problem statement (with some additional notes)]({{ site.url | append: "assets/resources/cse331/greedy/problem.html"}}).

#### Dynamic programming problem

CSE 331 spends two weeks on [dynamic programming](https://en.wikipedia.org/wiki/Dynamic_programming). One of the homework problems is for students to design a dynamic programming algorithm for a problem that generalizes the weighted interval scheduling problem. The setup asks the students to design an algorithm that schedules request to access a computer with high speed Internet access in a way that serves the diversity of users in the community.

Here are [the details on the actual problem statement (with some additional notes)]({{ site.url | append: "assets/resources/cse331/dynamic-programming/problem.html"}}).

#### Coding project

This project was created from scratch. One constraint we put in early was to make sure that the underlying technical concept that was covered early in the course. Given the current course structure the best option seemed to pick something related to the [shortest path problem](https://en.wikipedia.org/wiki/Shortest_path_problem). On the other side, acknowledging that our student population is skewed towards students from WNY and New Yor State (NYS) in general), we wanted to pick a scenario that was local. During the discussion stage someone suggested we look into the [NYS Attorney General’s case against Spectrum](https://ag.ny.gov/sites/default/files/summons_and_complaint.pdf) that alleged serious unethical behavior of Spectrum towards their customer. Given the ubiquity of the Internet in what we do as computing professionals this seemed like a scenario that all of our students would relate to. The choice was finalized when we realized that we could create a programming project related to routing of packets in this context, which would tie directly to the shortest path problem that we had covered in class (and on which students have a programming assignment early in the semester). The programming project has multiple parts where most of them corresponded to potentially unethical ways of routing packets as detailed in NYS AG's complaint. The final part asked the students to route packets under a fairness constraint.

Here are [the details on the actual coding project (with some code templates)]({{ site.url | append: "assets/resources/cse331/coding-project/index.html"}}).



### <a name="cse442">Capstone course (CSE 442)</a>

Ethics is covered in bits and pieces throughout the term. In addition, there is an entire week specifically dedicated to ethics,
 which has two components: an in-class activity and the capstone project itself.

#### In-class activity

Students review a made-up dossier of government data to identify if an individual should be added to the government’s No-Fly list. Students must then discuss biases in the data provided and, finally, how they would respond if their job assigned them to the team automating this analysis. 

This activity is organized as follows. It (usually) begins with the [in-class activity]({{ site.url | append: "assets/resources/cse442/activity/No-fly-list.pdf"}}) to get them thinking about how these decisions will matter to them. This is then followed up with a [brief lecture]({{ site.url | append: "assets/resources/cse442/activity/lect1.pptx"}}), presentation of the [grading rubric](#rubric),
and then a discussion of the rubric and lecture.


#### Capstone project

Finally, we have another activity [as part of a lecture]({{ site.url | append: "assets/resources/cse442/project/lect2.pptx"}}) asking students to discuss the ethics of their project. Students answers to this latter activity are evaluated using the [rubric](#rubric). The results of this latter activity (evaluated using the rubric) are also reported as part of our ABET evaluations. 

### Machine learning course (CSE 474)

The machine learning course introduced a new coding group project exploring bias in data driven criminal risk assessment. We used the [COMPAS recidivism dataset](https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis) and data driven criminal risk assessment. There already had been [media coverage of this topic](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) and so we figured we could use the coverage to introduce the topic to the students.

The students work on a class assignment (in groups of three) in which they take one of two roles. In either role, each group takes the role of machine learning engineers who have been tasked with designing a new system for use in U.S. court systems. They are given three different ML models and must apply five postprocessing techniques onto each of them. Finally, each group must identify a single model and technique to submit, which is then measured against the rest of the class for a chance at extra credit.

#### Role 1 – Employee of a publicly traded corporation

In this role, the students approach this assignment as employees of a large publicly traded corporation. They have a fiduciary duty to their shareholders to deliver strong returns, which can only be done by consistently winning development contracts. To this end, financial considerations are very important, as the engineers want their contracts to be more appealing than your competitors. Additionally, their life relies on the paycheck provided by this job, and making decisions that lose the company money could very quickly get then fired. However, since the corporation is publicly traded, they are still subject to public scrutiny, and thus cannot completely ignore social concerns.

Here is a [link to the project description for this role]({{ site.url | append: "assets/resources/cse474/criminal-justice/PA3_Corporation.pdf"}}).

#### Role 2 - Volunteer for Non-Governmental Organization

In this role, the students approach this assignment as volunteers of a humanitarian NGO (non-governmental organization). The NGO is a non-profit, and thus the volunteers do not receive a paycheck and are not reliant on this work for money to survive. Each group’s mission revolves around advocating for the fair treatment of individuals within the U.S. criminal justice system. To this end, societal considerations and positive reform are the main concerns. However, it will be difficult to get various local and state governments to adopt the software if the financial concerns are completely disregarded.

Here is a [link to the project description for this role]({{ site.url | append: "assets/resources/cse474/criminal-justice/PA3_NGO.pdf"}}).

## <a name="rubric">Grading Rubric</a>

We created a rubric to assess ethics related assignments, which was then used in both [CSE 331](#cse331) and [CSE 442](#cse442). Somewhat interestingly, when we started assessing student work the rubric was not effective. The problem was not with the rubric or student work, but that the  assignments discussed ethical issues but did not require students perform any analysis. We first used this rubric while rewriting existing assignments and creating ones to make certain they require students respond to the ethical issues they raised. Once this was complete, in [CSE 442](#cse442), we then presented the rubric to teach students the different criteria for them to consider when evaluating the ethics of a situation and, finally, to evaluate their responses.


Here is a [link to the ethics grading rubric]({{ site.url | append: "assets/resources/cse442/Ethics-Rubric.pdf"}}).

### <a name="materials">Interested in using any of the above materials?</a>

We encourage you to use the material posted above in your classes. However, we request that you <a href="mailto:atri@buffalo.edu">let us know</a> if you have used any of the material above so that we can keep track (in the list below) of schools that have used this material.

#### Other schools using this material.

* [Alfred University](https://www.garegin.info/blog/17/) who also co-developed the data structures assignment.
