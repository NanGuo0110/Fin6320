---
layout: basic
---

# Finance 6320: Computational Finance


### Spring Semester, 2018


## Course Information

- Course Dates: January 9 - April 27
- Course Time: TR 4:30 - 5:45 PM
- Course Room: HH 126 
- Lecture: T/Th in class & online at time TBD
- Mentoring sessions: TBD
- [Slack Channel](https://fin6320.slack.com)
- [Course Canvas](https://usu.instructure.com/courses/486407)
- [Course Homepage](https://broughtj.github.io/Fin6320)


## Instructor Information

- [Tyler J. Brough](http://tylerbrough.com)
- Office Hours: TBD & by appt.
- Office: BUS 605
- Phone: 435-797-2369 (nb: I check slack before voice mail)
- Email: tyler dot brough at aggiemail dot usu dot edu (please use this one!)


## Syllabus


### Course Description


This course is an introduction to numerical programming for finance. This is a very applied course by nature.  Although there will often be class lectures that focus on bits of theory, they will always be followed by computational exercises that focus on implementation. The computational tools that we refer to have two dimensions: 1) the mathematical tools that form _numerical analysis_ that are helpful for solving problems in finance, and 2) the actual implementation of said tools in a programming language. We will take a mixed language approach to financial computing focusing on the R and C++ programming languages, though we will mention and compare other approaches. The focus will be applied in nature and will focus on "getting things done" rather than on theoretical computer science. I will not attempt to teach you all of either R or C++, but only those parts of the languages that are helpful for computational finance (a sort of super best parts approach). We will also learn some techniques of modern software engineering that are helpful for producing reliable and reproducible research. This course will lay a foundation for a career in computational finance or advanced research in finance at the doctoral level.


### Course Objectives


- Develop specific skills, competencies and points of view needed by professionals in the finance industry and in academic finance.
	+ Learn the basics of R and C++ programming for financial computing.
	+ Develop computational skills necessary to implement theories from moder financial economics in practice.

- Learning fundamental principles and theories.
	+ Learn theories of advanced derivatives pricing.
	+ Learn the concepts of numerical methods useful in computational finance.
	+ Learn theories of advanced econometric methods.

- Learning to apply course materials.
	+ Learn to implement derivative pricing models for applications in trading and hedging.
	+ Learn to apply theories of advanced econometrics to estimate volatility and to measure transactions costs.


### Textbooks


There is only one required textbook for this course:

- [Art of R Programming](https://nostarch.com/artofr.htm)

I do however, suggest the following books (though they are not strictly _required_). I will be presenting material for class lectures based on them:

- [Advanced R](http://adv-r.had.co.nz/) by Hadley Wickham
- [C++ Primer 5th Edition](https://www.amazon.com/Primer-5th-Stanley-B-Lippman/dp/0321714113) by Lippman, Lajoie, & Moo
- [Seamless R and C++ Integration with Rcpp](https://goo.gl/WjBeVA) by Dirk Eddelbuettel

I will provide my suggested reading lists for R, C++, and numerical methods in the [Bookshelf]().


### Assessment and Grading


The grade that you earn in this course will be determined by your ranking in the class based on the weighted total points accumulated on class preparation and participation, a class project, and a final exam. There is no predetermined percentage of the class that will earn an A, or that will fail. If you all do excellent work, you will all earn high marks. The weights given to each part of the class are as follows:

- Class preparation, participation, and homework (30%) - I expect each student to come to class prepared for each class session. Preparation includes completing the assigned readings, writing down questions for sections of the reading that were not fully understood or internalized, and completing homework assignments. Class participation is crucial for understanding. I will call on students in class. There are two good answers when called upon. The first correct response is an informed answer based on your preparation. The second correct response is a question that shows that you have wrestled with the material in your preparations, though you may not yet have mastered it. A good question often lays the foundation for a more complete understanding. One important aspect of class participation is the professionalism with which you conduct yourself. There will be four main computational homework assignments that we will be working on.  

- Final project (45%) - The class project consists of a computational exercise in implementing a derivatives pricing model or econometric technique in R/C++. Further details of the project will be given in the near future. You may work in teams of two. I would like to know during the first week of class who your partner is. I am happy to make a market in arranging teams if that helps. The final deliverable for your project will be a GitHub repository together with a simple web cite showcasing your project. Further details will be given about Git, GitHub, and how to make a basic website using Markdown and GitHub Pages. You will be surprised at how easy it can actually be. I expect this form of a deliverable to be very helpful in enhancing your resume and portfolio for potential employers.  

- Final exam (25%) - The final exam will consist of a timed take-home computational exercise similar to homework assignments. Any day during finals week you can check out the exam from me by email or in person. You will then be required to check in the completed problems with the accompanying source code to a private GitHub repository before the time limit expires. 


### Format and Attendance


This course is designed to be as interactive and hands-on during class sessions as possible. I will deliver lectures during a live web session that you can "attend" online by joining the web conference through your browser. Lectures will be recorded automatically for your review. Lectures will be delivered at regularly scheduled dates and times. We will also hold some face-to-face lectures in the physical classroom. And more than perhaps anyother class you have taken, office hours will become a very important time for us in this course. My experience has been that face-to-face time with students is crucial to the learning process, but that we usually fill that time with the least effective use of that time. Instead I would like to use that time most effectively to help you learn how to solve computational problems in finance with hands-on coaching and to automate or nearly automate the more mundane material. An added benefit is that lectures will be recorded for your review. In addition, I would like to hold a few "pair programming" exercises with smaller groups of students during the semester. I will show you the technology that we will be using to accomplish this task. Attendance becomes essential in this approach. I will allow for a few missed online lectures, where you can review the recorded lecture. But the face-to-face meetings become crucial for success in this class. I will often collect a list of questions from each of you at the beginning of face time sessions, and may also give some simple quizzes on rare occasions. 


### Software Tools

We will be using the following programming and software resources in this class:

- All class communication will take place [Slack](https://slack.com), a message system that replaces email, instant message, etc that is often used by software engineering teams. I think it is important that we use real-world tools.  Students will receive an invitation to join the [Fin 6320 Slack channel](https://fin6320.slack.com) during the first week of class. 

- We will be using [GitHub](https://github.com) for software version control and for collaborative projects. Students should sign up for the [free educational account at GitHub](https://education.github.com/discount_requests/new).  Students will turn all homework assignments into a GitHub repository. Further details will be given. See [Exploring Git and GitHub](git.md) for additional information.

- In addition, students will receive a login to a Linux server that I maintain for computational research that contains all of the software tools and utilities that we will need. In a future lecture I will demonstrate how to connect to and use the system. This will help us streamline the difficulties of getting students set up with all of the different tools on their own systems (though I will aid students who wish to do so). 

- We will be using the free download of the [R Programming Language](www.r-project.org). I also highly encourage you to
  use the [RStudio IDE](https://rstudio.com). Install this on your own system. It will also be installed on the Linux
  server. There will be many additional packages that we will install as we make our way through the semester.  

- We will also learn about modern reporting using document processing tools such as R Markdown, Pandoc, LaTeX, and Bookdown. The use of Microsoft Word is ___not___ allowed in Fin6320! For additional information see [Document Processing](docs.md). 


### Topics (Subject to Change)


- __Module I:__ Core R, and R Markdown 
- __Module II:__ Basic C++ 
- __Module III:__ R and Rcpp

In both modules we will be covering numerical methods, in particular the Monte Carlo method.



