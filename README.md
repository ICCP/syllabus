# ICCP syllabus

* **Course:** [PHY480/905, MSU](http://http://www.pa.msu.edu/~duxbury/courses/ComputationalPhysics.html)
* **Instructor:** Phil Duxbury ([duxbury@pa.msu.edu](mailto:duxbury@pa.msu.edu))
* **TAs:** Connor Glosser ([glosser1@msu.edu](mailto:glosser1@msu.edu)), Jenni Portman ([jenniportman@gmail.com](mailto:jenniportman@gmail.com)) 
* **Need help?**
  * Open an issue ticket for the project's repository
  * Virtual office hours
    * Connor:
    * Jenni:
  * Email for 1-on-1 help, or to set up a time to meet
* **Exchange weeks:**
  * @MSU: February 2 - February 6
  * @TU Delft: May 11 - May 15

## Table of Contents
* [Contents](#contents)
* [Course description](#course-description)
* [Prerequisites](#prerequisites)
* [Course overview](#course-overview)
* [Grading](#grading)
* [Homework/projects](#homeworkprojects)
  * [Requirements](#requirements)
  * [Workflow](#workflow)
  * [Submission](#submission)
* [External links](#external-links)
  * [Required reading](#required-reading)
  * [Beginner materials](#beginner-materials)
  * [Tools](#tools)
  * [GitHub help](#github-help)
  * [Statements on Plagiarism](#statements-on-plagiarism)
  * [License](#license)

## Course description

ICCP develops students’ ability to write computer programs for simulating many-body classical and quantum physics systems. Groups choose either Fortran 90 or C++ as their coding language. The course is project based and Socratic in style. Students are encouraged to think of their own solutions to setting up the simulation problems and coding them. All students do the same warm up project (MC for and Ising model) and the same first joint project which involves writing a molecular dynamics code for simulation of Argon. The second project involves writing a Monte Carlo code and students may choose between simulation of polymer conformations, quantum Monte Carlo or cluster Monte Carlo. The third and/or fourth projects may be chosen from many possibilities, and can involve suggestions by the students. Each group works on a different project and makes a presentation on the last day of the course. Students from MSU receive $300 to assist with their air ticket to the Netherlands. Often MSU graduate students are able to cover the rest of their airfare from either their research group, from the College of Natural Science or from the Graduate School. The hotel costs and a per diem of about 20 euros are provided by Delft University of Technology while students are visiting Delft to participate in the course.

## Prerequisites

* Basic programming skills in a language like Fortran, C, or C++ 
* Working understanding of numerical methods
* Understanding of quantum and statistical mechanics at the junior/senior
  undergraduate level

These won't be enforced by the instructor, but you'll likely find the course difficult without understanding them.

## Course overview

* **Project 0:** Ising model *(due: Friday, January 30, 2014)*
  * Introduction to Fortran. Investigation of ferromagnetic dependence on temperature. The Metropolis algorithm. Lattices & boundary conditions.
* **Project 1:** Molecular dynamics *(due: Sunday, March 1, 2014)*
  * Numerical integration of EoM for a model of argon gas. Minimum image criterion and periodic boundary conditions in a continuum. Free energy, pair correlation, and temperature calculatons. Data blocking and energy fluctuations.
* **Project 2:** Advanced Monte Carlo *(due: Sunday, March 29, 2014)*
  * Ising model revisit: the Wolff algorithm, critical phenomena, and data
    structures
  * Polymer conformations: the Rosenbluth algorithm(s), convergence, on- and
    off-lattice models
  * Variational Monte Carlo: the He/H2 ground states
* **Project 3:** Students' choice *(due: Sunday, May 3, 2014)*
  * Lattice Boltzmann
  * Tight-binding
  * Percolation
  * DTFD quantum mechanics
  * etc.

## Grading

* Projects & reports – 75%
* Final exam – 25%

## Homework/projects

### Requirements

To submit a completed project, simply issue a [pull request](https://help.github.com/articles/creating-a-pull-request/) on the original repository before the due date. Your branch should contain:

1. The source code you developed to solve the problem in the `src/` directory and,
1. A written report of your findings in the `writeup/` directory, typeset in LaTeX

Each project repository contains a skeleton LaTeX file for you to fill in with your report. Your report should follow the style of a research paper (abstract, intro,
etc.) and should contain about five or six pages. Please remember to include all figures in your submission branch!

### Workflow

1. To start, [**fork**](https://guides.github.com/activities/forking/) a project repository
1. [**Clone**](http://gitref.org/creating/#clone) the repository to your computer.
1. Modify the files and [**commit**](http://gitref.org/basic/#commit) changes to complete your solution.
1. [**Push**](http://gitref.org/remotes/#push)/sync the changes up to GitHub.
1. [Create a **pull request**](https://help.github.com/articles/creating-a-pull-request) on the original project repository to turn in the assignment. You can continue to submit changes after you create your pull request -- simply commmit and push them.

### Submission
Your pull request should contain subdirectories for both your source code and your typeset report. E.g.,
```
molecular-dynamics/
  src/
    Makefile
    molecular_dynamics.f90
    parameters.f90
  report/
    md_report.tex
    figures/
      energy.pdf
      fig2.pdf
```
Please **do not** include binaries or compiled PDFs (we need image PDFs to produce your document, so you should absolutely include them!) We will compile both your program and your report on the HPCC, so please test everything there before submitting.

## External links

### Required reading

* [Computational Physics](http://www.amazon.com/Computational-Physics-Jos-Thijssen/dp/0521833469)
* [The Coding Notes](https://github.com/ICCP/coding-notes/releases/download/v2014/notes.pdf)
* [Real Programmers Don't Use Pascal](http://www.pbm.com/~lindahl/real.programmers.html)

### Beginner materials

In case you need a refresher...

* [PHY201 – Introduction to Fortran](http://www.pa.msu.edu/~duxbury/courses/phy201_f06/phy201_home.html)
* [Fortran 90 reference card](http://www.pa.msu.edu/~duxbury/courses/phy480/fortran90_refcard.pdf)
* [Useful Unix commands](http://www.pa.msu.edu/~duxbury/courses/phy201_f06/UnixCommands.htm)
* [The LaTeX Wikibook](http://en.wikibooks.org/wiki/LaTeX)

### Tools

* sharing code snippets: [gist.github.com](https://gist.github.com/)
* asking questions: [Stack Overflow](http://stackoverflow.com/)

### GitHub help

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
    * [Recommended resources](https://help.github.com/articles/what-are-other-good-resources-for-learning-git-and-github)
    * Git: The simple guide [(EN)](http://rogerdudler.github.io/git-guide/)/[(NL)](http://rogerdudler.github.io/git-guide/index.nl.html)
* GitHub Pages
    * [Official site](http://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)


### Statements on Plagiarism

From MSU's statement on [Academic Integrity](https://www.msu.edu/unit/ombud/academic-integrity/plagiarism-policy.html):

>Plagiarism (from the Latin plagiarius, an abductor, and plagiare, to steal) is defined by the White House Office of Science and Technology Policy on Misconduct in Research as “ . . . the appropriation of another person’s ideas, processes, results or words without giving appropriate credit.” At MSU, General Student Regulation 1.00 states in part that “no student shall claim or submit the academic work of another as one’s own.” (For the complete regulation, see Protection of Scholarship and Grades.) Plagiarism may be accidental or blatant and there is even self-plagiarism.  However, students are held to the same standards whether or not they knew they were plagiarizing or whether or not they were plagiarizing themselves or someone else.

Of course you're free to collaborate with others while working on your projects--that's the whole point of ICCP, after all--just give credit where credit is due. Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate an algorithm or code from elsewhere, credit the original source with an inline comment.

### License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work and all other materials under https://github.com/ICCP are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a> (where applicable). Adopted from the advanced-js course syllabus found [here](https://github.com/advanced-js/syllabus).

