---
layout: project
title: Teaching Responsible Computing
description: Incorporating responsible computing and ethics in computing courses
tagged_people: Matthew Bolton,Varun Chandola,Kenneth Joseph,Jonathan Manes,Atri Rudra,Mark Shepard,<a href = 'https://cse.buffalo.edu/~hartloff/index.html' target='_blank'>Jesse Hartloff</a>,<a href = 'https://cse.buffalo.edu/~mhertz/' target='_blank'>Matthew Hertz</a>,<a href = 'https://nsr.cse.buffalo.edu/?page_id=272' target='_blank'>Steve Ko</a>,<a href = 'https://cse.buffalo.edu/~jwinikus/' target='_blank'>Jennifer Winikus</a>
key: Teaching Responsible Computing
---

## Project Overview
Computing is ubiquitous in our daily lives. Increasingly computing makes decisions in our lives starting from the mundane (e.g. Netflix recommending  us movies/TV shows or sensors dispensing soap), to the somewhat more relevant (e.g. algorithms deciding which ads Google shows you or a car parking itself) to the downright worrisome (e.g. automated systems deciding the risk of a person who is arrested committing a crime in the future or automated "killer drones"). 

While we have (and continue to) educate our computing students on the  technical aspects of building computing systems that are used in our daily lives, there has been relatively less focus on incorporating ethics and responsible computing in such courses. Our project aims to incorporate ethics and more generally responsible computing in a wide range of computing courses.

While most of our work in this project has been in incorporating responsible computing in our [courses](#courses), we have also created [grading rubric](#rubric) for ethical/responsible computing related assignments.

## <a name="courses">Courses</a>

We have currently targeted a mix of courses: three required courses (spanning the first year, sophomore and senior year) for the BS Computer Science degree, one popular elective and created one new elective. Here is a quick overview of the courses that we targeted:

- _Required courses_
    - First year seminar ([CSE 199](https://cse.buffalo.edu/faculty/ahunt/classes/internet/)): Module on history, society and diversity and module on societal computing were targeted. Each module is a two week long combination of lectures and in-class activities. CSE 199 is required for BS Computer Science and BS Computer Engineering programs.
    - Algorithms course ([CSE 331](http://www-student.cse.buffalo.edu/~atri/cse331/fall19/index.html)): Homework assignments and a project based on access to high-speed Internet in Western New York (WNY) were introduced. CSE 331 is required for the BS Computer Science program.
    - Capstone course ([CSE 442](https://cse.buffalo.edu/~mhertz/2019fall/cse442/)): Students review a made-up dossier of government data to identify if an individual should be added to the government’s No-Fly list. Students must then discuss biases in the data provided and, finally, how they would respond if their job assigned them to the team automating this analysis.  A second assignment asks students to document the ethical implications of the capstone project they chose. CSE 442 is the capstone course for the BS Computer Science program.
- _Existing elective_
    - Machine learning course ([CSE 474](http://www.cse.buffalo.edu/~chandola/machinelearning.html)): Students worked in a group project exploring bias in data driven criminal risk assessment
- _New course_
    - [Algorithms and Society](http://www-student.cse.buffalo.edu/~atri/algo-and-society/spr20/index.html): This course has separate sections for CSE and non-CSE majors (but seated in the same room). The goal is to give non-CSE students a non-trivial understanding of various stages of the ML pipeline and for CSE students to get a deep dive into societal implications of machine learning systems. The class is a [mix of lectures and discussions](http://www-student.cse.buffalo.edu/~atri/algo-and-society/spr20/schedule.html).

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
* [Week 1 assignment](https://docs.google.com/document/d/1VJysWektxtvgN3dCEw27hbm-qtMLC8RTEYquUUxEdvA/edit)
* [Week 1 recitation activity](https://docs.google.com/document/d/1F5TFkLTMWxkAvpA_azIlYBH1yB6Blms0OIeOzGdROjY/edit)

##### Week 2 material

In the second week, we turn to social media, taking another critical lens as we chart the history of social media, its benefits (e.g. as a space for [networked counterpublics](https://onlinelibrary.wiley.com/doi/abs/10.1111/jcom.12185)) and its many, many failings.

Here are all the relevant material for week 2 of the module:
* [Lecture Slides for week 2]({{ site.url | append: "assets/resources/cse199/societal-computing/week_2_slides.pdf"}})
* [Week 2 assignment](https://docs.google.com/document/d/1ceubk3sRtbOfluykNZtWQbQaZS2_X0O2ccEcEIJ_vxw/edit)
* [Week 2 recitation activity](https://docs.google.com/document/d/10N7VnfAPHU4SPGfuBq4DlIefNmpSQPwUzmPUgnZnqKI/edit)

### <a name="cse331">Algorithms course (CSE 331)</a>

There are multiple activities/assignments in CSE 331 that all have the common thread of accessing high speed Internet. The main reason for this choice was because this is an issue all of our students could appreciate at a personal level. COVID-19 hit _after_ we implemented/ran these activities in Fall 2019. In future iterations we plan to incorporate increased awareness of the structural inequalities when it comes to access to high speed Internet (see e.g. this [Netgain Partnership](https://www.netgainpartnership.org/)  webinar on [Broadband Access in the US](https://www.netgainpartnership.org/events/covid19/broadband-access-in-the-us)) that has been brought to the fore by the pandemic.

Below we provide an overview of four activities/assignments that we piloted in Fall 2019 

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

(Details on the project will appear here soon.)



### <a name="cse442">Capstone course (CSE 442)</a>

The capstone course includes responsible computing in  at least two components: an in-class activity and the capstone project itself.

#### In-class activity

Students review a made-up dossier of government data to identify if an individual should be added to the government’s No-Fly list. Students must then discuss biases in the data provided and, finally, how they would respond if their job assigned them to the team automating this analysis.

_(If need be, the text above can be expanded on)_

Here are all the relevant material for the activity:
* _(Links needed for the material: ideally at least the "sheet" the students get)_

#### Capstone project

_(Description needed)_

_(If possible, would be good to add some course material as well)_

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

We created a rubric to assess ethics related assignments, which was then used in both [CSE 331](#cse331) and [CSE 442](#cse442). Somewhat interestingly, when we started assessing student work the rubric was not effective. The problem was not with the rubric or student work, but that the  assignments discussed ethical issues but did not require students perform any analysis. We first used this rubric while rewriting existing assignments and creating ones to make certain they require students respond to the ethical issues they raised. Once this was complete, we then presented the rubric to teach students the different criteria for them to consider when evaluating the ethics of a situation and, finally, to evaluate their responses.

_(If need be, the text above can be expanded on)_

_(Need a link to the rubric itself)_


