# CSC417/CSC2549-Physics-based Animation *Fall 2021*
![_image courtesy David Levin_](images/EolPenguinFallZoomedOut.gif)

- [CSC417/CSC2549 - Physics-based Animation *Fall 2020*](#csc417csc2549---physics-based-animation-fall-2020)
  - [Instructors](#instructors)
  - [TA](#ta)
  - [Lectures](#lectures)
  - [Links](#links)
  - [Course Overview](#course-overview)
  - [Helpful Resources](#helpful-resources)
  - [Lecture Schedule](#lecture-schedule)
  - [Final Project](#final-project)
  - [Grading](#grading)
  - [Lateness Policy](#lateness-policy)
    - [Academic Honesty](#academic-honesty)
    - [Email & Bulletin Board Traffic](#email--bulletin-board-traffic)

## Instructors

Prof. [David I.W. Levin](http://www.cs.toronto.edu/~diwlevin/)  
Email: diwlevin@cs.toronto.edu  
[Webpage](http://www.diwlevin.com)

Office Hours: Thursdays 17:00-18:00 first two weeks on Zoom **Zoom link will be sent to registered students**

## TA  

Yixin Chen
  
Haoda Li  

Jonathan Panuelos

Email Instructor and TAs: csc417tas@cs.toronto.edu

## Lectures

Thursday 15:00-17:00 first two weeks on Zoom  

## Tutorials

Tuesday 10:00-11:00 first two weeks on Zoom

## 
**Zoom links will be emailed to registered students**

## Links

Discussion board using [Piazza](https://piazza.com/utoronto.ca/fall2021/csc417)  
Hand in assignments using [MarkUs](https://markus.teach.cs.toronto.edu/csc417-2021-09).   

## Course Overview

This course is designed to introduce students to the field of physics-based animation by exposing  them to the underlying mathematical and algorithmic techniques required to understand and develop efficient numerical simulations of physical phenomena such as rigid bodies, deformable bodies and fluids. In Physics-Based Animation we will learn how to develop algorithms that produce visually compelling representations of physical systems.  We will learn the underlying continuous mathematics describing the motion of physical objects, explore how to discretize them and how to solve the resulting discrete equations quickly and robustly. 
  
**Prerequisites:** C/C++ Programming, Linear Algebra, Calculus, Numerical
Methods 

The student is expected to read background material as necessary and should be comfortable with elementary linear algebra, geometry,
and vector calculus. It is also assumed that the student is comfortable
programming in basic C++.

**_(Strongly)_ Recommended preparation:** Multivariable Calculus

## Helpful Resources  
[The Variational Principles of Mechanics (Book)](https://search.library.utoronto.ca/details?1576571&uuid=24e9601f-a561-440e-b4f7-0162225ae73d)  

[Calculus of Variations](https://books.google.ca/books/about/Calculus_of_Variations.html?id=YkFLGQeGRw4C&printsec=frontcover&source=kp_read_button&redir_esc=y#v=onepage&q&f=false)

[Numerical Methods for Evolutionary Differential Equations (Book) ](https://search.library.utoronto.ca/details?8723030)

[Fluid Simulation for Graphics (Book)](https://dl.acm.org/citation.cfm?id=1457699)   

[Fluid Simulation for Graphics (Notes)](https://www.cs.ubc.ca/~rbridson/fluidsimulation/fluids_notes.pdf)   

[Real-time Collision Detection (Book)](https://dl.acm.org/citation.cfm?id=1121584)

[Real Time Physics (Website)](http://matthias-mueller-fischer.ch/realtimephysics/)  
  
[FEM Simulation of 3D Deformable Solids (Website)](http://www.femdefo.org)

[Matrix and Linear Algebra Identities (PDF)](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf)

[Geometric Tools (Website)](https://www.geometrictools.com)

[Material Point Method SIGGRAPH Course (PDF)](https://www.seas.upenn.edu/~cffjiang/research/mpmcourse/mpmcourse.pdf)

[Two-Minute Papers (YouTube not strictly physics, but cool)](https://www.youtube.com/channel/UCbfYPyITQ-7l4upoX8nvctg) 

[Prof. Shinjiro Sueda's Rigid Body Mechanics Notes for Joints](https://github.com/sueda/redmax/blob/master/notes.pdf)

[Great Book on Geometric Time Integration by Hairer](https://www.springer.com/gp/book/9783540306634)
  
## Lecture Schedule (Due dates are day/month)
**NOTE: Video and Assignment content maybe updated as the course progresses**  
| Week | Topic / Event |
| ---- | :------------ |
| 1    | **Reading**<br>[Academic Policy](#academic-honesty)<br>[Grading Scheme](#grading)<br>[Late Policy](#lateness-policy)<br>**Videos**<br>[Introduction](https://www.youtube.com/watch?v=5j37DOD8q4U)<br>[**Slides**](lectures/01-Intro-plain_final.pdf)<br>**Research Highlight**<br>[Fast Mass-Spring Systems](https://www.cs.utah.edu/~ladislav/liu13fast/liu13fast.html)<br>**[Assignment 1 (1D mass-springs)](https://github.com/dilevin/CSC417-a1-mass-spring-1d) bonus 24/9**
| 2    | **Video**<br>[Explicit and implicit time integration](https://youtu.be/wpZe1PI7uhQ)<br>[**Slides**](lectures/02-time-integration_final.pdf)<br>**Research Highlight**<br>[Discrete Elastic Rods](http://www.cs.columbia.edu/cg/rods/)<br>**Working on A1**
| 3    | **Video**<br>[Mass-spring systems in three dimensions](https://youtu.be/9DcKg77nQBA)<br>[**Slides**](lectures/03-Mass-Spring-3d-final.pdf)<br>**Research Highlight**<br>[Shape Matching](https://matthias-research.github.io/pages/publications/MeshlessDeformations_SIG05.pdf)<br>**[Assignment 2 (3d mass-springs)](https://github.com/dilevin/CSC417-a2-mass-spring-3d) bonus 1/10**
| 4    | **Videos**<br>[Finite Elements for Solids I](https://www.youtube.com/watch?v=ngaYNdNtbec&t=1s)<br>[Gradients and Hessians  with MATLAB’s Symbolic Toolkit](https://www.youtube.com/watch?v=fqGNoUV67lI&t=1s)<br>[Derivatives!](https://www.youtube.com/watch?v=ny-i8_9NtHA&feature=youtu.be)<br>[Avengers:Endgame Simulation Breakdown](https://www.youtube.com/watch?v=51w4ZB_s528)<br>[**Slides**](lectures/04-finite-elements-I-final.pdf)<br>**Research Highlight**<br>[Position-Based Dynamics](https://www.sciencedirect.com/science/article/abs/pii/S1047320307000065)<br>**[Assignment 3 (3d FEM)](https://github.com/dilevin/CSC417-a3-finite-elements-3d) bonus 15/10**
| 5    | **Video**<br>[Finite Elements for Solids II](https://youtu.be/RsdyeUyWss0)<br>[**Slides**](lectures/05-finite-elements-II-final.pdf)<br>**Research Highlight**<br>[Frame-Based Elastic Models](http://www-ljk.imag.fr/Publications/Basilic/com.lmc.publi.PUBLI_Article@12f67a0f733_19a6a34/FBEM.pdf)<br>**Working on A3**
| 6    | **Video**<br>[Finite Elements for Simulating Cloth and Shells](https://www.youtube.com/watch?v=MJj17gpmrI4&feature=youtu.be)<br>[**Slides**](lectures/06-cloth-simulation-final.pdf)<br>**Research Highlight**<br>[Homogenized Yarn-Level Cloth](http://visualcomputing.ist.ac.at/publications/2020/HYLC/)<br>**[Assignment 4 Finite Elements for Cloth Simulation](https://github.com/dilevin/CSC417-a4-cloth-simulation) bonus 29/10**
| 7    | *Tutorial Only (Catch up, last minute questions about Assignments 1-4)*
| 8    | **Videos**<br>[Rigid body mechanics](https://www.youtube.com/watch?v=X0spyNYoZ1o&feature=youtu.be)<br>[Rotation Matrix Time Derivatives](https://www.youtube.com/watch?v=1RF7j-Yc21c&t=502s)<br>[**Slides**](lectures/07-rigid-bodies-final.pdf)<br>**[Assignment 5 Rigid body simulation bonus 5/11](https://github.com/dilevin/CSC417-a5-rigid-bodies)**
| **November 8** | *Drop date (consider if grade so far is <50%)*
| 9    | **Video**<br>Jointed Rigid Body Systems<br>**Work on A5**
| 10   | **Video**<br>[Rigid Body Collision](https://www.youtube.com/watch?v=8fFg7fOAHSA&feature=youtu.be)<br>[**Slides**](lectures/09-rigid-body-contact-final.pdf)<br>**Research Highlight**<br>[Anisotropic Elasticity for Inversion-Safety and Element Rehabilitation](http://www.tkim.graphics/ANISOTROPY/AnisotropyAndRehab.pdf)<br>[**Assignment 6 (Collision Resolution) due (26/11)**](https://github.com/dilevin/CSC417-a6-rigid-body-contact)
| 11   | **Videos**<br>[The Material Derivative](https://www.youtube.com/watch?v=ctvHp8YJ3ug&t=9s)<br>[Fluid Simulation](https://www.youtube.com/watch?v=VddQZH_Ppd0&feature=youtu.be)<br>[**Slides**](lectures/10-fluid-simulation-final.pdf)<br>**Research Highlight**<br>[Variational Stokes](http://poisson.cs.uwaterloo.ca/stokes/)<br>**Work on A6**
| 12   | *Tutorial Only (Last Minute Questions about A5-6, Final Project)*<br>**Research Highlight**<br>[On the accurate large-scale simulation of ferrofluids](http://computationalsciences.org/publications/huang-2019-ferrofluids/huang-2019-ferrofluids.pdf)

[Academic Honesty (required reading)](#academic-honesty)

## Final Project
The final project should involve implementing one  physics-simulation algorithm from a number of choices provided by the professor (**coming soon**). The projects will be taken from popular research papers. While the course will cover all the mathematical an technical concepts required to complete the projects, it will not cover the algorithms in detail. Projects can be done in up to groups of two (2) with no exceptions. 

**Deliverable:** The code for your algorithm (in Python, C++ or MATLAB) along with instructions to compile and run the implementation. A **two (2) page** writeup of the algorithm in the style of a short SIGGRAPH paper. A **5-minute** SIGGRAPH style video showing the results of your method.  

**Due Date:** December 21st at 11:59pm.  

[**Example Report**](https://www.siggraph.org/wp-content/uploads/2020/02/techbrief-sample.pdf)

[**Example Video**](http://www.nobuyuki-umetani.com/publication/2014_sca_positionbasedelasticrod/2014_sca_PositionBasedElasticRod.html)

**Suggested Structure**

Treat your video like a 5-minute presentation of your work (in lieu of a final presentation). You don't have to show yourself in the video, but a good suggested organization is (1) Introduce the problem (2) Mention the important resources you used (3) Outline the algorithm (4) show some results. 

[**Document Templates (use Technical Brief)**](https://www.siggraph.org/learn/instructions-authors/)

## Grading

| % | Item |
| ----: | :-------------- |
| 60% | Assignments (top 5 of 6)
| 40% | Final Project 

## Lateness Policy

**Please read, this course has an involved late policy aimed at giving you maximum flexibility in scheduling your semester**

Assignments are **_due by 11:59pm_** on the three due dates below.

0.007% off for every minute late.

Assignments 1,2,3,4 must be handed in by **November 19th at 11:59 pm**.  
Assignments 5 and 6 must be handed in by **December 17th at 11:59 pm**.  
The final project must be handed in by **December 21st at 11:59 pm**. 

Extensions to the dates above can only be issued by the instructor.

**THERE ARE NO LATE PENALTIES APPLIED TO ANY OTHER DEADLINES ASIDE FROM THE THREE (3) DEADLINES DIRECTLY ABOVE THIS TEXT**.   

**IMPORTANT: ** Students who hand in their assignments on the due dates in the [schedule](#lecture-schedule) above will be awarded a **five (5) percent** bonus on the assignment grade up to a maximum score of **one-hundred (100) percent**.  

### Academic Honesty

Academic honesty is a very serious matter and can result in very serious
consequences. Note that academic offences may be discovered and handled
retroactively, even after the semester in which the course was taken for credit.
This is a challenging class aimed at teaching you the fundamentals of computer
graphics. You wont learn much if you cheat but you might get a good grade if you
get away with it. If all you want is a good grade take an easier class where you
wont have to cheat!

For purposes of this class, academic dishonesty is defined as:

- Any attempt to pass off work on an assignment that didn't come straight out of your
  own head.
- Any collaboration on written or programming assignments (its ok to share ideas
  on programming assignments but the code MUST be your own) in which the
  collaborating parties don't clearly and prominently explain exactly who did
  what, at turn-in time.
- Any activity that has the effect of significantly impairing the ability of
  another student to learn. Examples here might include destroying the work of
  others, interfering with their access to resources (e.g., digital cameras), or
  deliberately providing them with misleading information.

### Email & Bulletin Board Traffic

- Use GitHub issues for answering questions about class subject matter or about the assignments. The TAs and the instructor will monitor the issues pages. Email sent to the instructor or TAs regarding these matters will be ignored. 
- Remark requests will be handled through MarkUs. 
- Appropriate use of issues page: clarifications on assignment, on lecture
  material, general concerns about the course, or other remarks that are
  appropriate for all students to see/participate in.
- Do NOT broadcast pieces of your code or answers to written assignments to the
   issues page. Specific or general implementation questions whose answer
  would benefit all students in the class are appropriate.
- Questions of the form "I cannot find the problem with my code; here it is, can
  you help me" are unlikely to be replied, so don't count on it. 
