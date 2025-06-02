<frontmatter>
  title: "NUS-OSS Projects"
  footer: footer.md
  pageNav: 2
</frontmatter>
<br>
<div class="jumbotron jumbotron-fluid">
  <div class="container">
    <h1 class="display-4">OSS Projects at NUS SoC</h1>
    <p class="lead"><md>NUS-OSS is an initiative to help interested [NUS SoC](https://www.comp.nus.edu.sg) students become OSS developers.<br>
        Projects under the NUS-OSS initiative have benefited **more than a million users**.</md></p>
  </div>
</div>

## {{ icon_tick }} Projects
We have a number of OSS projects that are especially suitable for NUS students to level-up their SE within the context of OSS projects.

{% set mentor_damith = "Mentor: [Dr. Damith](http://www.comp.nus.edu.sg/~damithch)" %}

Project(s) | KLoC | Languages | Description |
--- | --- | --- | --- |
[CATcher](https://github.com/CATcher-org/CATcher/) and [WATcher](https://github.com/CATcher-org/WATcher/) | 10 | TypeScript, Angular | A Desktop App for anonymous peer testing of software products. ([:fas-home: product website](https://catcher-org.github.io/), [:fab-github: project website](https://github.com/CATcher-org/CATcher/)).|
[MarkBind](https://markbind.org) | 10 | Node.js, HTML, JavaScript, CSS, Vue | A tool for generating educational websites from Markdown syntax. ([:fas-home: product website](https://markbind.org/), [:fab-github: project website](https://github.com/markbind/markbind)).|
[RepoSense](https://reposense.org) | 10 | Java, Javascript, HTML, CSS, Vue | A tool to monitor contributions to multiple Git repositories. ([:fas-home: product website](https://reposense.org), [:fab-github: project website](https://github.com/reposense/reposense)).|
[SE-EDU](https://se-education.org) | 1-10 | Java, Jekyll | A collection of sample projects and other resources for SE students and teachers  ([:fas-home: website](https://se-education.org)).|
[TEAMMATES](https://teammatesv4.appspot.com/) | 125 | Java EE, Angular, Javascript, HTML, CSS, Google Cloud | An online feedback management system for education used by more than **1,200,000** users ([:fas-home: product website](https://teammatesv4.appspot.com/), [:fab-github: project website](https://github.com/teammates/teammates)). |
[~~PowerPointLabs~~](http://www.comp.nus.edu.sg/~pptlabs/) now defunct | 60 | C# | A productivity plugin for Microsoft Powerpoint estimated to have benefited more than **1,000,000** people ([:fas-home: product website](http://www.comp.nus.edu.sg/~pptlabs/), [:fab-github: project website](https://github.com/powerpointlabs/powerpointlabs)).|

Note that in addition to the OSS projects listed above, there are many other OSS projects based in NUS SoC.

## {{ icon_tick }} Benefits

Doing work outside courses will set you apart from those who are only good in academic work and will increase your chances of getting,

* good internship offers from other companies for SIP/ATAP
* entry to selection-based courses such as CS3281&2, CS3217
* FYPs in NUS-OSS projects
* tutor positions in related courses (CS2103/T, CS2113, CS3218&2)

## {{ icon_tick }} How to get started

Each of the projects have their own documentation on how to get started.

If you have limited experience outside project in school courses, you can start with a smaller project such as those in [SE-EDU](https://github.com/se-edu) and move to bigger projects after a while.

Vacations are especially good times to get started on our projects as our projects are more active during those times.

## {{ icon_tick }} Earning course credit

There are several ways to earn course credit for OSS work

* [CS3281&2 (Thematic Systems Project)](https://nus-cs3281.github.io/website/) : In these two courses, student work on existing OSS projects, including NUS-OSS projects.
* [CS2103R (Software Engineering - Research)](https://docs.google.com/document/d/1jY9gYuNP9GBpYlGaLGEaYjusrQfBolmluX1rSc9x9dM/pub?embedded=true) : This is a 1 MC add-on to CS2103/T that you can do in the year immediately after you completed CS2103.
* [CP3108A/B, 2/4MC CS/CU), CP3106 (4MC, Graded)]({{ info_link }}): These courses can be used to earn 2MC/4MC for work done in NUS-OSS projects. ==See [here](pages/isc.html) for more info.==<br>
  Note: Doing NUS-OSS project under these courses is available only in semester 1 (i.e., not available in semester 2) of each academic year, and only for students who have at least 4 more semesters left in their degree program.
* [CP3200 (SIP)](https://www.comp.nus.edu.sg/programmes/ug/beyond/sip/sip-is/), [CP3880 (ATAP)](http://www.comp.nus.edu.sg/programmes/ug/beyond/atap/student/) : Some of the NUS-OSS projects hire interns through these internship programs.
* [FYP (CP4101)](https://www.comp.nus.edu.sg/programmes/ug/project/fyp/), [Computing Project (CP4106)](https://www.comp.nus.edu.sg/programmes/ug/project/cp4106/): Courses aimed at final year students.

<!--
## {{ icon_tick }} Paid internships

<img src="images/2017-interns.png" width="800"/><br>
<sub>Some of the interns from 2017 summer batch</sub>

For NUS students, it is possible to get paid for work done in these projects.

* Part time internships : Pay depends on the amount of work, at normal [NSWS scheme](http://www.nus.edu.sg/osa/about/join-us/nsws)
* Full time internships : **$1000-1500** per month. These internships are eligible for SIP and ATAP credit.

In the past, we also took part in [Google Summer of Code](https://developers.google.com/open-source/gsoc/). Our projects have taken part in GSoC 2014 (4 internships), 2015 (6 internships), 2016 (7 internships) 2017 (9 internships), 2018 (5 internships).

**Before you apply**

Before you apply, ensure that you match both our expectations given below.
* Due to the nature of our projects, ==we prefer to select interns who can remain involved with the project== (on a lightweight basis, possibly paid as part time work) even after the internship is over, and help with running the project e.g., mentoring new contributors, review PRs, etc. These projects are currently run by such alumni and that is the only way we can sustain these projects.
* We prefer to recruit students who are interested in our projects for the right reasons (e.g., as an opportunity to improve SE skills, make an impact to many users, or due to genuine interest in the product or the technologies being used etc.) rather than those looking at it purely as an opportunity to earn some money.


**How to apply:**
* SIP/ATAP internships (NUS students): Apply via the school's internship application system.
* Other full time internships: contact project mentor prof Damith (contact given below)
* Part time work: After you have contributed a few PRs to any of the projects above, contact project mentor prof Damith (contact given below) to explore possibilities for paid internships.

-->

## {{ icon_tick }} Queries

If you have questions, please contact project mentor [Dr Damith](http://www.comp.nus.edu.sg/~damithch) or write to `nus-oss`at`comp.nus.edu.sg`.
