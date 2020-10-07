# CSC417/CSC2549-Physics-based Animation *Fall 2020*
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

Office Hours: Tuesdays 17:00-18:00 on Zoom **Zoom link will be sent to registered students**

## TA  

Vismay Modi  
Honglin Chen

Email Instructor and TAs: csc417tas@cs.toronto.edu

## Lectures

Tuesdays 16:00-17:00 on Zoom  
Wednesday 14:00-15:00 on Zoom  
**Zoom link will be emailed to registered students**

## Links

Discussion board using [Piazza](https://piazza.com/utoronto.ca/fall2020/csc417)  
Hand in assignments using [MarkUs](https://markus.teach.cs.toronto.edu/csc417-2020-09).   

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

[Real-time Collision Detection (Book)](https://dl.acm.org/citation.cfm?id=1121584)

[Real Time Physics (Website)](http://matthias-mueller-fischer.ch/realtimephysics/)  
  
[FEM Simulation of 3D Deformable Solids (Website)](http://www.femdefo.org)

[Matrix and Linear Algebra Identities](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf)
  
## Lecture Schedule (Due dates are day/month)
**NOTE: Video and Assignment links will go live as the course progresses**  
| Week | Topic / Event |
| ---- | :------------ |
| 1    | **Reading**<br>[Academic Policy](#academic-honesty)<br>[Grading Scheme](#grading)<br>[Late Policy](#lateness-policy)<br>**Videos**<br>[Introduction](https://www.youtube.com/watch?v=5j37DOD8q4U)<br>[**Slides**](lectures/01-Intro-plain_final.pdf)<br>**Research Highlight**<br>[Fast Mass-Spring Systems](https://www.cs.utah.edu/~ladislav/liu13fast/liu13fast.html)<br>**[Assignment 1 (1D mass-springs)](https://github.com/dilevin/CSC417-a1-mass-spring-1d) due 2/10**
| 2    | **Video**<br>[Explicit and implicit time integration](https://youtu.be/wpZe1PI7uhQ)<br>[**Slides**](lectures/02-time-integration_final.pdf)<br>**Research Highlight**<br>[Discrete Elastic Rods](http://www.cs.columbia.edu/cg/rods/)<br>**Working on A1**
| 3    | **Video**<br>[Mass-spring systems in three dimensions](https://youtu.be/9DcKg77nQBA)<br>[**Slides**](lectures/03-Mass-Spring-3d-final.pdf)<br>**Research Highlight**<br>[Shape Matching](https://matthias-research.github.io/pages/publications/MeshlessDeformations_SIG05.pdf)<br>**[Assignment 2 (3d mass-springs)](https://github.com/dilevin/CSC417-a2-mass-spring-3d) due 9/10**
| 4    | **Videos**<br>[Finite Elements for Solids I](https://www.youtube.com/watch?v=ngaYNdNtbec&t=1s)<br>[Gradients and Hessians  with MATLAB’s Symbolic Toolkit](https://www.youtube.com/watch?v=fqGNoUV67lI&t=1s)<br><br>[**Slides**](lectures/04-finite-elements-I-final.pdf)<br>**Assignment 3 (3d FEM) due 23/10**
| 5    | **Video**<br>Finite Elements for Solids II<br>**Working on A3**
| 6    | **Video**<br>Finite Elements for simulating cloth and shells<br>**Assignment 4 Finite Elements for Cloth Simulation due (6/11)**
| 7    | *Tutorial Only (Catch up, last minute questions about Assignments 1-4)*
| 8    | **Video**<br>Rigid body mechanics<br>**Assignment 5 (Rigid body simulation) due (20/11)**
| **November 9** | *Drop date (consider if grade so far is <50%)*
| 9    | **Video**<br>Jointed Rigid Body Systems<br>**Work on A5**
| 10   | **Video**<br>Rigid Body Collision<br>**Assignment 6 (Collision Resolution) due (4/12)**
| 11   | **Video**<br>Fluid Simulation<br>**Research Highlight**<br>Variational Stokes (coming soon)<br>**Work on A6**
| 12   | *Tutorial Only (Last Minute Questions about A5-6, Final Project)*

[Academic Honesty (required reading)](#academic-honesty)

## Final Project
The final project should involve implementing a physics-simulation of any kind. It can be an algorithm from a paper or a new algorithm altogether. You can write the code from scratch or extend one of the course assignments. Projects can be done individually or in groups of two. The expectation is that the amount of work per-group member is equivalent, thus two person groups should be more ambitious in their project plans. 

**Deliverable:** The code for your algorithm (in Python, C++ or MATLAB) along with instructions to compile and run the implementation. A **two (2) page** writeup of the algorithm in the style of a short SIGGRAPH paper. A **5-minute** SIGGRAPH style video showing the results of your method.  

**Due Date:** December 21st at 11:59pm.  

## Grading

| % | Item |
| ----: | :-------------- |
| 60% | Assignments (top 5 of 6)
| 40% | Final Project 

## Lateness Policy

**Please read, this course has an involved late policy aimed at giving you maximum flexibility in scheduling your semester**

Assignments are **_due by 11:59pm_** on the due date.

0.007% off for every minute late.

Assignments 1,2,3,4 must be handed in by **November 16th at 11:59 pm**.  
Assignments 5 and 6 must be handed in by **December 10th at 11:59 pm**.  
The final project must be handed in by **December 21st at 11:59 pm**. 
These dates are not extendable. 

However, every student will be given **twenty-one (21) days** of late credits which are automatically applied to all other deadlines aside from the ones above. 

Students who hand in their assignments on the due dates in the [schedule](#lecture-schedule) above will be awarded a **five (5) percent** bonus on the assignment grade up to a maximum score of **one-hundred (100) percent**.  

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
