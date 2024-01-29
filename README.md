# CSCI-395.48 - Practical Web Development <br/> Spring 2024, Hunter College
### Monday, 5:30pm - 8:00pm <br/> North Building C110

---

## Course Description

This elective course is meant to introduce Computer Science students to modern day web development practices, languages, and frameworks that are in use in the industry today to do full stack web development. The course is mostly practical and hands-on to give the students as close to a real-world industry experience as possible. Students will spend the majority of the semester building web applications of varying degrees, from small assignments with initial boilerplate/template code, to building their own web app from scratch as part of a final project.

After the completion of this course, students are expected to have at least a basic understanding of how web application development works, and should be comfortable setting up a basic fullstack web-apps from scratch.

---

## Course Prerequisites

- Successfully completed CSCI 235

Recommended prerequisites:
- Comfortable working on the command line
- Comfortable writing/testing/debugging code
- Experience with functional programming
- IDE/Code Editor (VSCode, WebStorm, Sublime)
- Familiarity with Git/GitHub/GitHub Classroom

---

## Grading

50% - Assignments (4 x 12.5%) (Late submission penalties applied at 10% per week) <br/>
40% - Final (Group) Project (30%) + Presentation (10%) <br/>
10% - Lab Report <br/>
10% - Extra Credit Presentation <br/>

Just to be completely transparent about grades, you can calculate your final grade with the formula below:

```text
FinalGrade =
.12.5 * (assignment 1 grade) +
.12.5 * (assignment 2 grade) +
.12.5 * (assignment 3 grade) +
.12.5 * (assignment 4 grade) +
.10 * (lab report grade) +
.10 * (extra credit grade) +
.40 * (final project grade)

*All calculations rounded up.
```

The formula should be pretty straightforward to understand. Your final letter grade is based on CUNY grading ranges as outlined [here](https://hunter.cuny.edu/students/registration/records-and-transcripts/grading-structure/).

---

## Course Materials/Readings
This is a zero-textbook cost course, and as such we don't have any required textbooks. Instead, we will mostly be going over API documentations, code samples, and other reading materials related to various frameworks and technologies that we will cover in this course. Below are links to some of the course materials we'll be using throuhgout the semester:

Books:

* https://eloquentjavascript.net/ <br/>
    * Amazon Link: https://www.amazon.com/Eloquent-JavaScript-3rd-Introduction-Programming/dp/1593279507
    * Useful book, content is also available online at the website above that the author made.


* JavaScript: The Good Parts
    * Amazon Link: https://a.co/d/83NUXkY
    * Excellent light/intro reading on JavaScript


Documentations:
* MDN Docs: https://developer.mozilla.org/en-US/
    * Useful documentation from Mozilla Developer Network
    * Has information on HTML/CSS/JS syntax and methods.

* ReactJS Docs: https://react.dev/reference/react
    * Official documentation for ReactJS


* NodeJS Docs: https://nodejs.org/en/docs/
    * Official documentation for NodeJS
    * We will be using Node.js 16.x and +
    * Recommend we use the current LTS version.


* ExpressJS Docs: https://expressjs.com/en/4x/api.html
    * Official documentation for ExpressJS
    * Minimal web framework build on top of NodeJS.

And additional documentations around frameworks that we'll take a look at.

---

## Slack
We'll be using Slack as our primary communication platform outside our class. This is probably the best way to reach me, aside from my email/in-person office hour meetings. I tend to check Slack throughout the day, especially if I'm at work, and will try and answer all questions/inquiries as soon as possible.

- Check our class Blackboard for the most up-to-date Slack invite link.
- Invites will not be emailed out individually, so it's import that you join our classroom Slack yourself via the link provided on Blackboard.
- Reach out to me if you run into any issues with joining Slack!

---
## Office Hours (Virtual ~30min sessions via Google Meet)

I'm usually available for a quick virtual meeting most days of the week, feel free to schedule a time with me via my appointment link below:

https://y3pio.setmore.com/

I'll send a Google Meet invite to the email you signed up with as a confirmation, or reply back to schedule a different time if it doesn't work!

### In-person Office Hours

```text
Mondays, 1:00pm - 5:00pm
Faculty Resource Center, 5th floor, Cooperman Library
```

I also try and reserve an office space on lecture days at the faculty resource center (5th floor Cooperman library). I'll also post in the `#announcement` Slack channel whenever I'm there, send a message on Slack if you'd like to stop by for in-person office hours.

---

## GitHub Classroom
We will be using GitHub classroom to complete our assignments. Each assignment link will be handed out via BlackBoard, which will give you access to your own personal assignment GitHub repository, where you will commit code/answers to your assignments.

As part of `assignment0` (not graded), you will be required to properly set up your GitHub account, and join our GitHub classroom.

---

## Lecture Stream/Recordings

One of the feedback I received from previous semesters was to make our live lectures available via Blackboard classroom, and also recordings of it available asynchronously.

### Lecture Streams
I've set up a Blackboard Class Collaborate Ultra open session which you can find in your Blackboard account under `Tools -> Class Collaborate Ultra -> Click on Lecture/Classroom Stream(Open Session)`. I will make sure to join this session and share my screen to allow students that can't make it to our in person lectures to follow along.

### Recordings
In the past, I've attempted to record our class lectures and upload them for the students to review/look back on at their own pace. However, due to the storage/editing/necessity requirements, I've found it not sustainable in the long run. To compromise, I will record a shortened (~30-45min) recap/recitation version of our lecture for the week and upload that instead.

Storage location can be found in this public Google drive folder on my personal Google account (link also on Blackboard): https://drive.google.com/drive/folders/103a4SXDVNlIo-ISXdVZIOpwjok6KH9yl?usp=drive_link

---

## Course Topics/Schedule
Content/order subject to change*

### Introduction
- Introductions and overview of web development
- Going over syllabus and course content
- Brief overview of full-stack web development, the internet, backend/frontend web development
### Assignment 0

### Git/GitHub
- Quick introduction/primer on using Git as a version control system
- Overview of GitHub as a service and GitHub classroom
- Going over assignment setup and submissions

### HTML/CSS
- Introduction to HTML
    - Overview of how websites are rendered. HTML and the DOM
    - Debugging HTML code via debugger console (rendered code, console, network tab, etc...)
- Introduction to CSS
    - CSS selectors and ordering
    - Flexbox and responsive designs/styling
### Assignment 1 (HTML/CSS)

### Javascript
- History of JS, ECMA script
- Functional programming pattern vs. OOP
- JS Basic syntax and primitive types.
- Objects and functions in JS
- DOM manipulation using JS
- Functional programming methods
    - Map, reduce, filter
- Intro to asynchronous programming
    - Callback functions
    - HTML Events
    - Network/API calls
### Assignment 2 (JavaScript Language Fundamentals)

### NodeJS
- What is a framework?
- Looking at different NodeJS modules
    - Focusing primarily on web related modules (HTTP, file I/O, streaming/sockets)
- NPM and package management
    - Looking at common/popular NPM packages

### ExpressJS
- Introduction to ExpressJS
    - ExpressJS as a framework based off of NodeJS
- REST-ful API development (CRUD, HTTP Requests)
- Integrating with other REST-ful APIs:
    - https://thecatapi.com/
    - https://www.deckofcardsapi.com/
### Assignment 3 (Backend JavaScript)

### ReactJS
- ReactJS overview and history
- Class vs functional ReactJS
- JSX and DOM manipulation
- React component props, states, refs.
- React Router
- Connecting React FE app to backend APIs

### ReduxJS
- ReduxJS overview and architecture pattern
    - Flux architecture
    - Single source of truth
- Redux store, actions, reducer.
- Integrating Redux with React app.
### Assignment 4 (Frontend Javascript) & Project Proposals

### Persisting Data/DBs
- FE vs BE persisting
    - Browser cache/cookies
    - BE caching
- DB setup and basic commands (SQL)
    - Setting up PostgreSQL
    - C.R.U.D operation with DB
- Sequelize ORM
    - What is an Object Relational Mapping?
    - Using Sequelize ORM to Node/ExpressJS
- A look at No-SQL DBs.
    - MongoDB, Firebase (realtime DB)
    - Connecting to MongoDB/Firebase
### Lab Report (Database/Data Persistence)

### Additional Topics/Studies
- ReactJS testing using react testing library
- RXJS: Realtime JS framework (also available in Java and other languages)
- NextJS: ReactJS with built-in routing
- Deploying webapps to production. Production build using webpacks, deploying backend services & monitoring
- a11y compliance

### Final Project
- Final project presentations

---

## Extra Credit Presentation

Aside from your final presentation, you may also present an individual extra credit presentation for 10% towards your final grade. The web dev field is one that's always evolving, with new technologies/frameworks being adopted every day, and to be good web devs, we often need to stay on top of the latest trends in the field.

As part of your presentation, you can give a short ~5-min talk/report on what are some of the interesting changes that are happening in our field. This can be anything from a new framework that you picked up, a new JS library, or new technologies being developed that impacts the internet/web dev field.

We will devote the start of the class session (limited to 3 presentations max per class) to presentation, sign up sheet link will be posted on BlackBoard, and are on a first come first serve basis!

Just to give an outline on what's expected in your presentation, consider the points below:

- What is your presentation on? Is it a new framework/library that you found? Bugs that you encountered? Latest news in the web dev world?
- Why is this topic important to our field, and how does it impact our work?
- How does it address/cause certain issues that we find on the web?

---

## Hunter Policies
**_Policy on Academic Integrity:_** Hunter College regards acts of academic dishonesty (e.g. plagiarism, cheating on examinations, obtaining unfair advantage,
and falsification of records and official documents) as serious offenses against
the values of intellectual honesty. The College is committed to enforcing the CUNY Policy on Academic Integrity and will pursue cases of academic dishonesty according to the Hunter College Academic Integrity Procedures.

**_ADA Compliance:_** In compliance with the American Disability Act of 1990
(ADA) and with Section 504 of the Rehabilitation Act of 1973, Hunter College is
committed to ensuring educational parity and accommodations for all students
with documented disabilities and/or medical conditions. It is recommended that
all students with documented disabilities (Emotional, Medical, Physical and/
or Learning) consult the Office of AccessABILITY located in Room E1124 to
secure necessary academic accommodations. For further information and assistance please call (212-772-4857)/TTY (212-650-3230).
Hunter College Policy on Sexual Misconduct: In compliance with the

**_CUNY Policy on Sexual Misconduct_**, Hunter College reaffirms the prohibition
of any sexual misconduct, which includes sexual violence, sexual harassment,
and gender-based harassment retaliation against students, employees, or visitors, as well as certain intimate relationships. Students who have experienced
any form of sexual violence on or off campus (including CUNY-sponsored trips
and events) are entitled to the rights outlined in the Bill of Rights for Hunter
College.

a. Sexual Violence: Students are strongly encouraged to immediately report
the incident by calling 911, contacting NYPD Special Victims Division Hotline
(646-610-7272) or their local police precinct, or contacting the College’s Public
Safety Office (212-772-4444).

b. All Other Forms of Sexual Misconduct: Students are also encouraged
to contact the College’s Title IX Campus Coordinator, Dean John Rose (jtrose@hunter.cuny.edu or 212-650-3262) or Colleen Barry (colleen.barry@hunter.cuny.edu or 212-772-4534) and seek complimentary services through the Counseling
and Wellness Services Office, Hunter East 1123. CUNY Policy on Sexual Misconduct Link: http://www.cuny.edu/about/administration/offices/la/Policy-onSexual-Misconduct-12-1-14-withlinks.pdf
