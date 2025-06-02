<frontmatter>
  title: "Independent Study Courses @NUS-OSS"
  footer: footer.md
  pageNav: 3
</frontmatter>

{% set info_link = "https://www.comp.nus.edu.sg/programmes/ug/project/isc/" %}

<h1 class="display-4">Independent Study Courses @NUS-OSS</h1>

<p class="lead"><md>CP3108A and CP3108B are [_independent study_ courses]({{ info_link }}) (previously called independent work modules) run by the SoC UG office. To enroll in one of them, you first need to secure a project supervised by a professor. This page describes how to secure a place in an [NUS-OSS project](../index.html) so that you can enroll in one of <tooltip content="Independent Study Courses">ISCs</tooltip>.</md></p>

---

## {{ icon_tick }} Objectives

Here are the intended objectives of doing an ISC in an NUS-OSS project (ISC@NUS-OSS for short):
1. **To gain skills of an _OSS Contributor_**, which can boost your SE credentials, especially when you apply for internships or jobs in the near future.
1. **To improve your chances of getting into CS3281&2.** Entry into [CS3281 and CS3282](https://nus-cs3281.github.io/website/admin/callForApplications.html) is highly competitive because the class size is only ~20 students. Given those courses are also based on NUS-OSS projects, ==an ISC@NUS-OSS can greatly enhance your chances of getting a place== in those courses.
1. **To serve as the first step in securing a long-term role NUS-OSS project.** The typical path you can follow over the next few semesters is: contributor (via the ISC@NUS-OSS) →  developer → senior developer → lead developer → alumni mentor (after graduation). The work you do for NUS-OSS projects later can be used to earn more course credit through other course codes.

<box type="tip" seamless>

You can do an ISC@NUS-OSS 'unofficially' too (i.e., without officially enrolling in a course) if you are not interested in receiving course credits but you are still interested to join an NUS-OSS project. In that case,
* the procedure is the same except you can skip the step of enrolling for the course with the UG office.
* you can opt to receive a reference letter from the prof instead of course credit.
</box>

---

## {{ icon_tick }} Prerequisites

Given below are the prerequisites that you need to satisfy to be eligible for an <tooltip content="Independent Study Courses @NUS-OSS">ISC@NUS-OSS</tooltip>. These can only be waived under exceptional circumstances.
* You have at least **3-4 semesters left** till graduation %%(reason: see objective 3 above)%%.
* You have done well in programming and SE courses (**at least B+** for most, if not all).
* You have done [CS2103/T](https://www.comp.nus.edu.sg/~cs2103) or an equivalent course.<br>
  Alternatively, you have substantial programming experience, including experience with Git/GitHub.
* You have ==**an interest in working with NUS-OSS**== beyond the ISC@NUS-OSS, to become a regular NUS-OSS dev team member.

---

## {{ icon_tick }} Structure

* ISC slots are available in the following [NUS-OSS projects](../index.html#projects):
  * CATcher: 2-3 slots/year
  * MarkBind: 2-3 slots/year
  * RepoSense: 2-3 slots/year
  * TEAMMATES: 2-3 slots/year
* CP3108A is worth 2 units while CP3108B is worth 4 units. Both are graded CS/CU. More info given [here]({{ info_link }}) (requires login). The only difference between the two is the workload.<br>
  FAQ: Can I do both courses? Yes. In addition, there is an option to do CP3108A first and, extend it to CP3108B in a subsequent semester.
* There are two main intakes for ISC@NUS-OSS:
  * **Summer intake**: You will do the bulk (>80%) of the work during the summer. You will be ==_officially_ enrolled in the <tooltip content="i.e., CP3108A/B">target course</tooltip> in semester 1== (i.e., Aug-Dec) of the following AY.
  * **Semester 1 intake**: You will enroll in the course, and do the work, during the semester 1 (i.e., Aug-Dec) itself.
* You are responsible for ensuring that you are officially eligible to take the target course.
    CP3108A/B enrollment is controlled by the SoC UG office (not by NUS-OSS or prof Damith).

---

## {{ icon_tick }} Enrolling

* The _call for application_ for the summer intake will be sent out to year-2 computing students around late-May. In some years (if there are vacancies), another call for the semester 1 intake will be sent in late-July.
* **To apply, fill [this form](https://forms.gle/56mfhBmeksr2hju58)**. You can apply any time but the chance of acceptance is higher when applying during the summer period.<br>
  Note that only _some_ applicants will be accepted for the program, as there will be many more applicants than vacancies.
* ISC@NUS-OSS **<span class="text-danger">does not</span> follow the normal ISC application procedure** given [here]({{ info_link }}).<br>
  Instead, we'll pass selected student list to the UG office so that they can pre-allocate the course (i.e., CS3108A or CS3108B) to you, at the start of the corresponding semester.

---

## {{ icon_tick }} Phases

A student in ISC@NUS-OSS project goes through the following typical phases.

### Phase 1: Set up

1. **Set up**
   * Locate the developer documentation of the project.
   * Fork the repo, clone it to your computer, and set up the developer environment in your computer as described in the dev docs.
1. **Learn** the tool stack (at least the basics), and then, the code base.
   * The dev docs might provide some pointers on how to go about this.
   * If you encounter any problems or need help, please post in the project's issue tracker or the discussion board (on GitHub).
1. **Build** the product locally, and run the tests.

### Phase 2: Experiment

1. **Do a small _experimental_ enhancement** to the product (e.g., tweak the UI, improve an existing feature, add a new feature) as follows:
   1. Ensure the change is in a ==separate branch==.<br>
      As this enhancement is not meant to be merged, it is optional to update/add tests, to get CI to pass, or to update documentation.
   1. Push the branch to your fork.
   1. Create a PR ==within your fork <span class="text-danger">(do not send the PR to the upstream repo)</span>==, from your new branch to the master/main branch.<br>
     In the PR description, explain your change, and if applicable, provide screenshots (or screen recordings) of how the change looks to an end-user.
   1. **You can even do multiple enhancements** (optional), but keep each enhancement in a separate branch and  in a separate PR.

<box type="tip" seamless>

**Aim to showcase your ability** to (a) understand the product, and, (b) work with the codebase, when doing this phase. Hence,
  * non-trivial enhancements are preferred over trivial/superficial ones (e.g., changing a button label or fixing a minor typo is unlikely to achieve the aim of this phase).
  * positive/useful enhancements are preferred over <tooltip content="a change that makes the product worse">negative</tooltip>/useless ones.
</box>

2. **Send the PR link(s)** to the NUS-OSS team (email: `nus-oss` at `comp.nus.edu.sg`), when ready.<br>
   After that, wait for further instructions (which should reach you within 2-3 days).

### Phase 3: Contribute

This phase starts only after you have been accepted for an ISC@NUS-OSS slot, which in turn depends on your performance in the phase 2 above.

**In this phase, you can do a mixture of [A] and [B] given further below.** You are expected to do at least one (the more, the better) PR for [A]. Doing [B] is optional but given your progress in [A] will be limited by how quickly you receive PR reviews from the dev team (who may be busy with internships etc. too), you are recommended to use [B] to compensate and still achieve the required progress/workload.

<box>

#### [A] Contribute PRs

1. **Learn the workflow** and various conventions followed by the project. These are likely to be found among the dev docs of the project.
1. **Start submitting PRs** for issues in the issue tracker of the project.
   * You can start with an issue set aside for new-comers (if any). Such issues usually have an indicative label e.g., `good first issue` or `d.FristTimers`.<br>
   Do not do more than one such 'newcomers issue' though.
   * **Ask before starting** work on an issue, as some issues may be outdated. You can simply post in the same issue to ask if it is OK to work on it.
   * When choosing issues to work on, you can pick based on your interest %%e.g., if you are more interested in the front-end, you can pick issues related to the front-end%%.

----

#### [B] Contribute a PoC feature

In this path, you will implement a Proof-of-Concept (PoC) version of a feature/enhancement that may or may not be currently mentioned in the issue tracker or project road map. It is considered a PoC because merging it into the production version is not the intended end goal -- rather, the goal is to see the user-visible impact, effort required, impact on the code base etc. It is possible that the feature may eventually be merged too.

1. **Propose a feature** (or a significant enhancement to an existing) feature. You can also propose multiple such features. This can also be an expanded version of the enhancement you did in phase 2.
2. **Get approval from the dev team** to go ahead. In case of multiple proposals in step 1, the dev team can help you prioritise them.
3. **Implement the feature in your fork**, in a separate branch (similar to Phase 2).
4. **Send a PR to the upstream repo** when the work is ready for review. Include screenshots/recordings of how the feature works.
</box>


**Record progress** in an online document (e.g., a Google Doc) regularly. **Send the link** to above document (view-only permission is enough) to the prof at the end of the first week.
* ==Suggested progress report template== is [here](https://docs.google.com/document/d/13C1IRkDGSmfEkQD9RQsJMaE-WU9xCRiedpu8FqdMBNs/edit?usp=sharing)  -- you can use the `File` -> `Make a copy` option to create your own copy (Google login required).
* Weekly updates is recommended. Work spanning at least 10 weeks is expected.
* Include links to PRs, external resources you referred, problems faced, solutions found, etc.

<box type="info" seamless>

**Project guidance** will be provided by senior dev team members, mostly in the form of PR reviews. You can also post in the issue tracker or the project discussion board (on GitHub) to ask for further guidance.<br>
There are no lectures, but you can arrange a meeting with the prof if needed.
</box>


### Phase 4: Wrap up

These are things to do when nearing the deadline (the deadline will be given to you at the start of phase 3).
1. **Finish up** any ongoing PRs.
1. **Add a _summary of achievements_ section** at the end of your project progress document.
1. **Inform the prof** that you are done with the course work.

---

## {{ icon_tick }} Grading

* **Both quality and quantity** of work will be considered. Aim to get better over the course of the project. It's fine to make mistakes as long as you learn from them and avoid them later in the project.
* **The level of competency gained** will matter too. It is better to do progressively deeper/harder/bigger PRs as you progress through the project, compared to doing a lot of simple PRs.
* **The expected workload** is indicated by the modular credits.
  * CP3108A (2 units): about 5 hours/week, over 10-12 weeks
  * CP3108B (4 units): about 10 hours/week, over 10-12 weeks
* You can ask prof if the work you have done so far is enough or whether you are progressing fast enough.

---

## {{ icon_tick }} FAQ

* **Q**: Can ISC@NUS-OSS be done while on SIP/ATAP etc.?<br>
  **A**: Yes, if selected for ISC@NUS-OSS, you can do the work of the ISC while doing the internship (but outside of office hours) and register for the course officially in a subsequent semester.

* **Q**: What if I plan to go SEP or NOC during the semester following the summer?<br>
  **A**: You can do the ISC@NUS-OSS work during the summer, and register for the course officially after you are back from SEP/NOC. You cannot earn course credit for ISC@NUS-OSS for a semester in which you are not studying full-time in NUS.

---

## {{ icon_tick }} Questions?

* If you have questions, you can contact us at `nus-oss` at `comp.nus.edu.sg`
