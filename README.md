# CSC417/CSC2549-Physics-based Animation *Fall 2025*
![_image courtesy David Levin_](images/EolPenguinFallZoomedOut.gif)

- [CSC417/CSC2549 - Physics-based Animation *Fall 2025*](#csc417---physics-based-animation-fall-2025)
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

Office Hours: Upon request via email 

## TA  

Coming Soon
  
Email Instructor and TAs: csc417tas@cs.toronto.edu

## Lectures

Wednesday 11:00-13:00 [ES](https://map.utoronto.ca/?id=1809#!bm/?m/494499?s/ES) B142 

## Tutorials

Monday 11:00-noon (starts September 8th)


## Links

Discussion board using [Piazza](https://piazza.com/utoronto.ca/fall2025/csc417) (monitored by TAs)
Hand in assignments using MarkUs (Coming Soon).   

## Course Overview

This course is designed to introduce students to the field of physics-based animation by exposing  them to the underlying mathematical and algorithmic techniques required to understand and develop efficient numerical simulations of physical phenomena such as rigid bodies, deformable bodies and fluids. In Physics-Based Animation we will learn how to develop algorithms that produce visually compelling representations of physical systems.  We will learn the underlying continuous mathematics describing the motion of physical objects, explore how to discretize them and how to solve the resulting discrete equations quickly and robustly. 

**IMPORTANT: The course is all new this year including a change to Python for the primary programming language using both PyTorch and NVIDIA Warp along with new assignments and lectures. All previous content from the course is available in previous commits of this website**

**Prerequisites:** Python Programming, Linear Algebra, Calculus, Numerical
Methods 

The student is expected to read background material as necessary and should be comfortable with elementary linear algebra, geometry,
and vector calculus. It is also assumed that the student is comfortable
programming in Python.

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

[libigl for geometry processing](https://libigl.github.io)

[NVIDIA Warp Documentation](https://nvidia.github.io/warp/)

[Physics-Based Animation Textbook by Minchen Li](https://phys-sim-book.github.io)
  
## Lecture Schedule (Due dates are day/month)
| **Dates**  | **Topic**                             | **Assignments**                                     |
| ---------- | ------------------------------------- | --------------------------------------------------- |
| 9/3/2025   | [Introduction](lectures/01-introduction.pdf) [Video (old)](https://youtu.be/5j37DOD8q4U?si=8GO7cPZwF80AkF4q)                        |                                                     |
| 9/10/2025  | [Deformation and Finite Element Method](lectures/02-deformation_and_fem.pdf) [Video (old)](https://youtu.be/ngaYNdNtbec?si=ROJ-lVhrbFdENgW1) [Matrix Derivatives Video](https://youtu.be/ny-i8_9NtHA?si=VuHnOxAzNsfposkM)|                                                     |
| 9/17/2025  | [Deformation and Finite Element Method](lectures/02-deformation_and_fem.pdf) continued               |                                                     |
| 9/24/2025  | [From Energy to Motion](lectures/03-from_energy_to_motion.pdf) [Video (old)](https://youtu.be/RsdyeUyWss0?si=Bu_vsOBtaWVRQq2J)                   | Release [A1: Finite Element Methods](https://github.com/dilevin/pba-assignment-fem)                 |
| 10/1/2025  | [Rigid Bodies / Affine Body Dynamics](lectures/04-rigid-and-affine-bodies.pdf) [Rotaion Matrix Derivative](https://youtu.be/1RF7j-Yc21c?si=WfkdPLmxO6DqN1pV)   |                                                     |
| 10/8/2025  | [Collisions](lectures/05-affine-bodies-contact.pdf)                          |                                                     |
| 10/15/2025 | [Intro to Fluid Simulation](lectures/CSC417-Fluids-Annotated.pdf) [Fluids Video (old)](https://youtu.be/VddQZH_Ppd0?si=NWFouKxs3XK0c3JA)             | Assignment 1 Due, Release [A2: Affine Body Dynamics](https://github.com/dilevin/pba-assignment-abd)   |
| 10/22/2025 | Material Point Method                 |                                                     |
| 11/5/2025  | Reduced-Order Models                  | Release A3: Fluids, Assignment 2 Due November 7th                |
| 11/11/2025 | ***Drop Deadline***                   |                                                     |
| 11/12/2025 | Fast Physics Solvers                  |                                                     |
| 11/19/2025 | Beyond Elasticity                     | Assignment 3 Due, Release A4:  Reduced/Fast Methods  |                                         
| 11/26/2025 | ***Final Exam***                      | Assignment 4 Due  December 3rd                                    |


## Grading

| % | Item |
| ----: | :-------------- |
| 50% | Assignments 
| 30% | In-Tutorial Quizzes 
| 20% | Final Exam (must get >= 50% to pass course)

Details on quizzes are coming soon

## Lateness Policy

**Please read, this course has an involved late policy aimed at giving you maximum flexibility in scheduling your semester**

Assignments are **_due by 11:59pm_** on the three due dates below.

Every student will recieve 21 "late days" that will be automatically applied before the late penalty begins to accumulate. You only have to inform the instructor if you **DO NOT** wish to use your late days for a particular assignment.

After late days have been exhausted, assignemnts accrue a penalty at the following rate: 0.007% off for every minute late.

Further extensions can only be issued by the instructor.

### AI Policy 

You can freely use AI tools such as CoPilot, ChatGPT or Cursor for your assignments but not for quizzes or the final exam.

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

- Remark requests will be handled through MarkUs. 
- Do NOT broadcast pieces of your code or answers to written assignments to the
   issues page. Specific or general implementation questions whose answer
  would benefit all students in the class are appropriate.
- Questions of the form "I cannot find the problem with my code; here it is, can
  you help me" are unlikely to be replied, so don't count on it. 
