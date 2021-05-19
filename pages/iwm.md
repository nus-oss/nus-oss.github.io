<frontmatter>
  title: "Independent Work Modules @NUS-OSS"
  footer: footer.md
  pageNav: 2
</frontmatter>

<include src="common.mbdf" />

<h1 class="display-4">Independent Work Modules @NUS-OSS</h1>

<p class="lead"><md>[CP3108A and CP3108B](http://www.comp.nus.edu.sg/cug/catalogue/idm/#CP3108A) are _independent work_ modules run by the SoC UG office. To enroll in one of them, you first need to secure a project supervised by a professor. This page describes how to secure a place in an [NUS-OSS project](../index.html) (supervised by [prof Damith](https://www.comp.nus.edu.sg)) so that you can enroll in one of independent work modules.</md></p>

---

## {{ icon_tick }} Objectives

Here are the intended objectives of doing an IWM in an NUS-OSS project (IWM@NUS-OSS for short):
* **To gain skills of an _OSS Contributor_**, which can boost your SE credentials.
* **To improve your chances of getting into CS3281&2.** Entry into [CS3281 and CS3282](https://nus-cs3281.github.io/website/admin/callForApplications.html) is highly competitive because the class size is only ~20 students. Given those modules are also based on NUS-OSS projects, ==an IWM@NUS-OSS can greatly enhance your chances of getting a place== in those modules.
* **To serve as the first step in securing a long-term role NUS-OSS project.** The typical path you can follow over the next few semesters is: contributor (via the IWM@NUS-OSS) →  developer → senior developer → lead developer → alumni mentor (after graduation).

---

## {{ icon_tick }} Prerequisites

Given below are the prerequisites that you need to satisfy to be eligible for an <tooltip content="Independent Projects @NUS-OSS">IWM@NUS-OSS</tooltip>. These can only be waived under exceptional circumstances.
* You have at least **3-4 semesters left** till graduation.
* You have done well in programming and SE modules (**at least B+** for most, if not all).
* You have done [CS2103/T](www.comp.nus.edu.sg/~cs2103) or an equivalent module.<br>
  Alternatively, you have substantial programming experience, including experience with Git/GitHub.
* You have ==**an interest in working with NUS-OSS**== beyond the IWM@NUS-OSS, to become a regular NUS-OSS dev team member.

---

## {{ icon_tick }} Structure

* IWM slots are available in the following [NUS-OSS projects](../index.html#projects):
  * CATcher: 2-3 slots/year
  * MarkBind: 2-3 slots/year
  * RepoSense: 2-3 slots/year
  * TEAMMATES: 3-6 slots/year
* If you are selected for an IWM@NUS-OSS, you will be **_officially_ enrolled in the <tooltip content="i.e., CP3108A/B">target module</tooltip> in semester 1** (i.e., Aug-Dec) of the following AY.
  * However, the work can begin earlier e.g., during the summer. You can even finish the work during the summer itself.
  * You are responsible for ensuring that you are officially eligible to take the target module.

---

## {{ icon_tick }} Enrolling

* A _call for application_ will be sent out year 2 computing students around mid-May (and in some years, again in late-July).
* You can also apply any time using [this form](https://forms.gle/56mfhBmeksr2hju58) but the chance of acceptance is higher when applying between late April and early Aug.
* If you are selected (after some initial screening), you will be informed how to enroll officially in the target module.

---

## {{ icon_tick }} Phases

A student in IWM@NUS-OSS project goes through the following typical phases.

### Phase 1: set up

1. **Set up**
   * Locate the developer documentation of the project.
   * Fork the repo, clone it to your computer, and set up the developer environment in your computer as described in the dev docs.
1. **Learn** the tool stack (at least the basics), and then, the code base.
   * The dev docs might provide some pointers on how to go about this.
   * If you encounter any problems or need help, please post in the project's issue tracker or the discussion board (on GitHub).
1. **Build** the product locally, and run the tests.

### Phase 2: experiment

1. **Do a small _experimental_ enhancement** to the product (e.g., tweak the UI, improve an existing feature, add a new feature) as follows:
   1. Ensure the change is in a ==separate branch==.<br>
      As this enhancement is not meant to be merged, it is optional to update/add tests, to get CI to pass, or to update documentation.
   1. Push the branch to your fork.
   1. Create a PR ==within your fork== (do not send the PR to the upstream repo), from your new branch to the master/main branch.<br>
     In the PR description, explain your change, and if applicable, provide screenshots (or screen recordings) of how the change looks to an end-user.
   1. **You can even do multiple enhancements** (optional), but keep each enhancement in a separate branch and  in a separate PR.

<box type="tip" seamless>

**Aim to showcase your ability** to understand the product and work with the codebase, when doing this phase. Hence,
  * non-trivial enhancements are preferred over trivial/superficial ones (e.g., changing a button label or fixing a minor typo is unlikely to achieve the aim of this phase).
  * positive/useful enhancements are preferred over <tooltip content="a change that makes the product worse">negative</tooltip>/useless ones.
</box>

2. **Send the PR link(s)** to the prof (email: `nus-oss` at `comp.nus.edu.sg`), when ready.<br>
   After that, wait for further instructions from the prof (which should reach you within 2-3 days).

### Phase 3: contribute

This phase starts only after you have been accepted for an IWM@NUS-OSS slot, which in turn depends on your performance in the phase 2 above.

1. **Learn the workflow** and various conventions followed by the project. These are likely to be found among the dev docs of the project.
1. **Start submitting PRs** for issues in the issue tracker of the project.
   * You can start with an issue set aside for new-comers (if any). Such issues usually have an indicative label e.g., `good first issue`.<br>
   Do not do more than one such 'beginner issue' though.
   * **Ask before starting** work on an issue, as some issues may be outdated. You can simply post in the same issue to ask if it is OK to work on it.
   * When choosing issues to work on, you can pick based on your interest %%e.g., if you are more interested in the front-end, you can pick issues related to the front-end%%.
1. **Record progress** in online document (e.g., a Google Doc) regularly.
   * ==Suggested progress report template== is [here](https://docs.google.com/document/d/13C1IRkDGSmfEkQD9RQsJMaE-WU9xCRiedpu8FqdMBNs/edit?usp=sharing)  -- you can use the `File` -> `Make a copy` option to create your own copy (Google login required).
   * Weekly updates is recommended, spanning at least 10 weeks is expected.
   * Include links to PRs, external resources you referred, problems faced, solutions found, etc.
1. **Send the link** to above document (view-only permission is enough) to the prof at the end of the first week.

<box type="info" seamless>

**Project guidance** will be provided by senior dev team members, mostly in the form of PR reviews. You can also post in the issue tracker or the project discussion board (on GitHub) to ask for further guidance. After you've been added to the project's slack channel, you can ask questions through that too.<br>
There are no lectures but you can arrange a meeting with the prof if needed.
</box>


### Phase 4: wrap up

These are things to do when nearing the deadline (the deadline will be given to you at the start of phase 3).
1. **Finish up** any ongoing PRs.
1. **Add a _summary of achievements_ section** at the end of your project progress document.
1. **Inform the prof** that you are done with the module work.

---

## {{ icon_tick }} Grading

* **Both quality and quantity** of work will be considered. Aim to get better over the course of the project. It's fine to make mistakes as long as you learn from them and avoid them later in the project.
* **The level of competency gained** will matter too. It is better to do progressively deeper/harder/bigger PRs as you progress through the project, compared to doing a lot of simple PRs.
* **The expected workload** is indicated by the modular credits.
  * CP3108A (2MC): about 5 hours/week, over 10-12 weeks
  * CP3108A (4MC): about 10 hours/week, over 10-12 weeks
* You can ask prof if the work you have done so far is enough or whether you are progressing fast enough.

---

## {{ icon_tick }} Questions?

* If you have questions, you can contact us at `nus-oss` at `comp.nus.edu.sg`