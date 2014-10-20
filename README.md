# ICCP syllabus

***See this README with a table of contents [here](http://documentup.com/advanced-js/syllabus).  If you are a teacher or interested in the design of the course, see the [meta](meta.md) document.***

* **Course:** [PHY480/905, MSU](http://http://www.pa.msu.edu/~duxbury/courses/ComputationalPhysics.html)
* **Instructor:** Phil Duxbury ([duxbury@pa.msu.edu](mailto:duxbury@pa.msu.edu))
* **TAs:** Connor Glosser ([glosser1@msu.edu](mailto:glosser1@msu.edu)), Jenni Portman ([jenniportman@gmail.com](mailto:jenniportman@gmail.com)) 
* **Need help?**
   * Look through and create [issues](https://github.com/ICCP/syllabus/issues)
   * Office Hours during [Hacker Hours](http://hackerhours.org/) (see [Meetup page](http://www.meetup.com/hackerhours/events/calendar/) for schedule)
   * [Email](mailto:alf9@nyu.edu) for 1-on-1 help, or to set up a time to meet

## Course Description

Learn best practices in JavaScript in this intensive, five-session course. Topics include data encapsulation, closures, binding, inheritance, and name spacing. Discover some of the lesser-known, yet useful, features of the language, such as how to debug JavaScript problems on different browsers and improve performance. Create interactive webpages using third-party JavaScript libraries.

Computers are provided in the lab, though you are encouraged to bring a laptop for in-class exercises.

## Prerequisites

* [INFO1-CE9755 - JavaScript](http://scps.nyu.edu/content/scps/academics/course_detail.html?id=INFO1-CE9755) ([syllabus](http://samsultan.com/javascript)) or equivalent
* Understanding of variables, data types, control flow, and basic function usage in JavaScript - see [Beginner Materials](#beginner-materials)
* Strong intermediate knowledge of HTML, and at least basics of CSS
* Basic jQuery knowledge (DOM interaction) is a plus

These won't be enforced by the instructor, but you will be pretty lost without understanding those concepts.

## Course Overview

We will dive into the nuances of JavaScript, how prototypal inheritance compares to classical inheritance, and how this can be used to build dynamic and complex web applications.  Modern tools like jQuery and BackboneJS will be discussed, but students will learn the building blocks of these frameworks and after this course be able to understand what is happening under the hood.  The focus will be on development for browsers, though most applies to other systems like Node.js, Phonegap, etc.  Topics covered include:

* Encapsulation, closures and scope
* Classical vs. prototypal inheritance
* The event loop
* AJAX and JSONP
    * local
    * remote (e.g. Foursquare)
* Creating MVC-style models (a'la Backbone.js) from scratch
* Test- and Pseudocode-Driven Development

Topics will be demonstrated through live-code examples/slides, available at [advanced-js.github.io/deck](http://advanced-js.github.io/deck/).  Additional exercises will completed in-class.

See [this interview](http://masterstreet.wordpress.com/2013/09/05/interview-with-aidan-feldman-instructor-at-nyu-scps/) for more background.

## Homework/Projects

All assignments are listed within the [Course Outline](#course-outline).

### Workflow

1. Fork the repository for the exercise/project (found under [github.com/advanced-js](https://github.com/advanced-js))
1. Clone the repository to your computer
1. Open the `index.html` file in a browser and open the Developer Tools
1. Modify the files to complete your solution
1. Refresh the `index.html` page to see the results, and repeat
1. Make sure all of your code is committed
1. Push/sync up to GitHub
1. [Create a pull request](https://help.github.com/articles/creating-a-pull-request) on the original repository by the due time (generally the start of the following class)
1. You can continue to push fixes and improvements until the close date (listed in Classes) – just add a comment in the pull request to let me know it's been updated.

When the pull request is created, you should see a message saying that "the Travis CI build is in progress" – this means that your solution is being automatically checked for syntax errors.  If this "build" ends up failing (which will show a red "X"), click through the "details" link and scroll to the bottom to see what the errors were.  Per the [requirements](#requirements) below, please fix the issues and push up the changes.

Feedback will be given in the pull request, so please respond with your thoughts and questions!  You are welcome to open the pull request as the work is still in-progress if you are stuck and want to ask a question – just mention `@afeld` with the question to make sure I know to look at it sooner.

Note that your solution will also be live at `http://USERNAME.github.io/EXERCISE`.  For exercises with multiple levels/versions, leave a new comment in the pull request saying "Level X finished!" before pushing commits for the next level.

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

From MSU's [Academic Integrity](https://www.msu.edu/unit/ombud/academic-integrity/plagiarism-policy.html) page:

>Plagiarism (from the Latin plagiarius, an abductor, and plagiare, to steal) is defined by the White House Office of Science and Technology Policy on Misconduct in Research as “ . . . the appropriation of another person’s ideas, processes, results or words without giving appropriate credit.” At MSU, General Student Regulation 1.00 states in part that “no student shall claim or submit the academic work of another as one’s own.” (For the complete regulation, see Protection of Scholarship and Grades.) Plagiarism may be accidental or blatant and there is even self-plagiarism.  However, students are held to the same standards whether or not they knew they were plagiarizing or whether or not they were plagiarizing themselves or someone else.

### Instructor

Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers.  I won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate an algorithm or code from elsewhere, credit the original source with an inline comment.

### License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">work</span> and all other materials under https://github.com/advanced-js are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
