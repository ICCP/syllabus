# ICCP syllabus

***See this README with a table of contents [here](http://documentup.com/advanced-js/syllabus).  If you are a teacher or interested in the design of the course, see the [meta](meta.md) document.***

* **Course:** [PHY480/905, MSU](http://http://www.pa.msu.edu/~duxbury/courses/ComputationalPhysics.html)
* **Instructor:** Phil Duxbury ([duxbury@pa.msu.edu](mailto:duxbury@pa.msu.edu))
* **TAs:** Connor Glosser ([glosser1@msu.edu](mailto:glosser1@msu.edu)), Jenni Portman ([jenniportman@gmail.com](mailto:jenniportman@gmail.com)) 
* **Need help?**
  * Ask (& answer!) questions on [Piazza](https://piazza.com)
  * Office Hours
    * Connor:
    * Jenni:
  * Email for 1-on-1 help, or to set up a time to meet
* **Exchange weeks:**
  * @MSU: February 2nd - February 6th
  * @TU Delft: May 11 - May 15

## Course Description

ICCP develops students’ ability to write computer programs for simulating many-body classical and quantum physics systems. Groups choose either Fortran 90 or C++ as their coding language. The course is project based and Socratic in style. Students are encouraged to think of their own solutions to setting up the simulation problems and coding them. All students do the same warm up project (MC for and Ising model) and the same first joint project which involves writing a molecular dynamics code for simulation of Argon. The second project involves writing a Monte Carlo code and students may choose between simulation of polymer conformations, quantum Monte Carlo or cluster Monte Carlo. The third and/or fourth projects may be chosen from many possibilities, and can involve suggestions by the students. Each group works on a different project and makes a presentation on the last day of the course. Students from MSU receive $300 to assist with their air ticket to the Netherlands. Often MSU graduate students are able to cover the rest of their airfare from either their research group, from the College of Natural Science or from the Graduate School. The hotel costs and a per diem of about 20 euros are provided by Delft University of Technology while students are visiting Delft to participate in the course.

## Prerequisites

* Basic programming skills in a language like Fortran, C, or C++ 
* Working understanding of numerical methods
* Understanding of quantum and statistical mechanics at the junior/senior
  undergraduate level

These won't be enforced by the instructor, but you'll likely find the course difficult without understanding them.

## Course Overview

* **Project 0:** Ising model
  * Introduction to Fortran. Investigation of ferromagnetic dependence on temperature. The Metropolis algorithm. Lattices & boundary conditions.
* **Project 1:** Molecular dynamics
  * Numerical integration of EoM for a model of argon gas. Minimum image criterion and periodic boundary conditions in a continuum. Free energy, pair correlation, and temperature calculatons. Data blocking and energy fluctuations.
* **Project 2:** Advanced Monte Carlo
  * Ising model revisit: the Wolff algorithm
  * Polymer conformations: the Rosenbluth algorithm(s)
  * Variational Monte Carlo: the H2 ground state
* **Project 3:** Students' choice
  

## Homework/Projects



### Workflow

1. Fork the repository for the exercise/project (found under [github.com/advanced-js](https://github.com/ICCP))
1. Clone the repository to your computer
1. Modify the seed files as desired to work on your solution
1. Make sure all of your code is committed
1. Push/sync up to GitHub
1. [Create a pull request](https://help.github.com/articles/creating-a-pull-request) on the original repository by the due date to submit your assignment
  * You can continue to push fixes and improvements until the close date (listed in Classes) – just add a comment in the pull request to let us know it's been updated.

### Requirements

These apply to real life, as well.

* [Travis CI](http://docs.travis-ci.com) build should pass, which includes:
    * All HTML files should pass [W3C Markup Validation](http://validator.w3.org)
    * All written JS should pass [JSHint](http://jshint.com)
* Must apply "good programming style" learned in class
    * Functions should be "short" (see [Sandi Metz's rules for developers](http://robots.thoughtbot.com/post/50655960596/sandi-metz-rules-for-developers))
    * Optimize for readability
    * For projects, use Object-Oriented Programming
* Bonus points for:
    * [Automated tests](#test-frameworks)
    * Creativity (as long as requirements are fulfilled)

## Course Outline

## Pairing Tips

* Three people is possible, but two works best
* Agree on an editor and environment that you're both comfortable with
* The person who's less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it (clone!) to both people

## Resources

### Required Reading

* [The Coding Notes](https://github.com/ICCP/coding-notes)
* [Real Programmers Don't Use Pascal](http://www.pbm.com/~lindahl/real.programmers.html)

### Beginner Materials

This class assumes you are confident with this material, but in case you need a brush-up...

* Codecademy – [JavaScript](http://www.codecademy.com/tracks/javascript) and [jQuery](http://www.codecademy.com/tracks/jquery)
* [Eloquent JavaScript](http://eloquentjavascript.net/index.html) by Marijn Haverbeke, Chapters 1-5
* see also – [Other Lists](#other-lists)

### Recommended Reading

* [Front-end Job Interview Questions](https://github.com/darcyclarke/Front-end-Developer-Interview-Questions) by @darcyclarke (for testing yourself)
* [JavaScript Best Practices](http://www.thinkful.com/learn/javascript-best-practices-1/)
* [JavaScript Patterns](http://shichuan.github.com/javascript-patterns/) by @shichuan (thanks @iandrewfuchs)
* [JavaScript Patterns](http://www.amazon.com/JavaScript-Patterns-Stoyan-Stefanov/dp/0596806752) by Stoyan Stephanov
* [JavaScript Web Applications](http://www.amazon.com/JavaScript-Web-Applications-Alex-MacCaw/dp/144930351X/) by Alex MacCaw
* [JavaScript: The Good Parts](http://www.amazon.com/JavaScript-Good-Parts-Douglas-Crockford/dp/0596517742) by Douglas Crockford
* [Learning Advanced JavaScript slides](http://ejohn.org/apps/learn/) by John Resig
* [Static Web Apps](http://www.staticapps.org/)
* [Test-Driven JavaScript Development](http://www.amazon.com/Test-Driven-JavaScript-Development-Developers-Library/dp/0321683919) by Christian Johansen
* [The JavaScript Interpreter, Interpreted](http://www.slideshare.net/marthakelly/js-interpreter-interpreted) by Martha Girdler [(video)](http://www.youtube.com/watch?v=iSxNCYcPAFk)

#### Specific Topics

* [Classical Inheritance in JavaScript](http://www.crockford.com/javascript/inheritance.html) by Douglas Crockford
* [Partial Application in JavaScript](http://benalman.com/news/2012/09/partial-application-in-javascript/) by Ben Alman (thanks @michaelBenin)
* [HTML5 Rocks slides](http://slides.html5rocks.com/)
* [Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/) by Addy Osmani

#### Other Lists

### Tools

* sharing code snippets: [gist.github.com](https://gist.github.com/)
* asking questions: [Stack Overflow](http://stackoverflow.com/)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
    * [Recommended resources](https://help.github.com/articles/what-are-other-good-resources-for-learning-git-and-github)
* GitHub Pages
    * [Official site](http://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)

## Grading

* Projects & reports – 90%
* Final exam – 10%

## Statements on Plagiarism

From MSU's statement on [Academic Integrity](https://www.msu.edu/unit/ombud/academic-integrity/plagiarism-policy.html):

>Plagiarism (from the Latin plagiarius, an abductor, and plagiare, to steal) is defined by the White House Office of Science and Technology Policy on Misconduct in Research as “ . . . the appropriation of another person’s ideas, processes, results or words without giving appropriate credit.” At MSU, General Student Regulation 1.00 states in part that “no student shall claim or submit the academic work of another as one’s own.” (For the complete regulation, see Protection of Scholarship and Grades.) Plagiarism may be accidental or blatant and there is even self-plagiarism.  However, students are held to the same standards whether or not they knew they were plagiarizing or whether or not they were plagiarizing themselves or someone else.

### Instructor

Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers.  I won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate an algorithm or code from elsewhere, credit the original source with an inline comment.

### License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">work</span> and all other materials under https://github.com/advanced-js are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>. Adopted from the advanced-js course syllabus found [here](https://github.com/advanced-js/syllabus)
