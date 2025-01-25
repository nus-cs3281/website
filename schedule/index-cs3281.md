<frontmatter>
title: "CS3281 Schedule"
pageNav: 2
layout: cs3281-layout.md
</frontmatter>

{% set sem_start = "2025-01-13" %}
{% set weeks = [
    {num: "0", day: (sem_start | date("Do MMM", -7))},
    {num: "1", day: (sem_start | date("Do MMM", 0))},
    {num: "2", day:(sem_start | date("Do MMM", 7))},
    {num: "3", day:(sem_start | date("Do MMM", 14))},
    {num: "4", day:(sem_start | date("Do MMM", 21))},
    {num: "5", day:(sem_start | date("Do MMM", 28))},
    {num: "6", day:(sem_start | date("Do MMM", 35))},
    {num: "7", day:(sem_start | date("Do MMM", 49))},
    {num: "8", day:(sem_start | date("Do MMM", 56))},
    {num: "9", day:(sem_start | date("Do MMM", 63))},
    {num: "10", day:(sem_start | date("Do MMM", 70))},
    {num: "11", day:(sem_start | date("Do MMM", 77))},
    {num: "12", day:(sem_start | date("Do MMM", 84))},
    {num: "13", day:(sem_start | date("Do MMM", 91))}
] %}

# CS3281 Schedule

{% if is_pre_sem %}
<box type="important" icon=":fas-exclamation-triangle:" light>

The info given below is from the previous round, as a reference only. **Major changes are highly unlikely**, however.
</box>
{% endif %}

<p/>
<!-- ----------------------------------------------------------------------------------- -->

<box type="important" icon=":fas-exclamation-triangle:" light>

The schedule for future weeks is tentative, given as a reference only. The prof will finalize the details of a week near to the start of the week, although **major changes are highly unlikely**.
</box>

## Week 1 [{{ weeks[1].day }}]

#### Todo

* {{ icon_todo }} Update GitHub profile: As most of your work will be submitted via GitHub, you are encouraged to update your GitHub profile with your full or partial name.
* {{ icon_todo }} Add your info to the repo [nus-cs3281/{{ year }}](https://nus-cs3281.github.io/{{ year }}/instructions.html) [:alarm_clock: Deadline: Friday]. You will be given write permission to the repo by Monday.
* {{ icon_todo }} Set up the dev environment of your project in your Computer. Follow instructions provided by the project for new contributors.
* {{ icon_todo }} Join `nusossprojects` slack channel when you receive the invitation. As our projects use slack for chats, please ==keep slack running (and notifications enabled)== during periods in which you are actively involved in our projects (or check slack at least once a day).

#### Monday

* {{ icon_lecture }} Lecture: **A 'dev-experiments' session**
  * Objectives: for you to get to know team members (and possibly, some mentors), and help each other set up (and get familiar with) the dev environment.
  * Structure:
    1. Starts with a brief course intro (by prof)
    1. Sit together with team members
    1. Get to know team members
    1. Help team members set up dev environment
    1. Start doing some experimental changes to code, with the aim of getting familiar with the code base

<box type="tip" seamless>

**Keep records of your work**{.text-success}

As you learn the codebase, investigate issues, learn related tools etc., try to get them recorded somewhere. Some options:

* record in your 'knowledge' page e.g., a tool you learned
* post it an issue in the issue tracker e.g., investigating the applicability of a tool to the project
* an update to project documentation e.g., a solution you found to a problem that happens in the dev environment

Reasons: It increases the visibility of your work. Those records can be useful references to you and others.

</box>
<!--
#### Saturday (Code Sprint)

* The code sprint is an opportunity for you to spend an extended amount of time on the project so that you get a solid start to the coding activities. Some project mentors may be available during this time for you to discuss project related matters with them.

* Venue: SR10
* Schedule:
  * 0930 - 1200 : Project work
  * 1200 - 1300 : Lunch break (lunch  provided :stew:)
  * 1300 - 1530 : Project work

* Agenda
  * 10-11am: A common Zoom session for students and  mentors to introduce themselves. Try to join from a private location where you can **use the webcam and appear without a mask**. The Zoom link will be posted in Canvas.
  * 11am onwards:  Separate briefings for each project, on Zoom, led by mentors. e.g., technical overview, on-boarding, etc. Will be recorded in case some students are interested to learn a 2nd project. The Zoom links will be provided by the mentors on the day.
  * Afternoon: Students do tasks indicated by mentors earlier and consult mentors if needed.
  * 4-5.30pm: Prof to meet with each team separately for a short debriefing. Mentors need not join.<br>
    Use the same Zoom link used for the intro session.
 -->

<!-- ----------------------------------------------------------------------------------- -->

## Week 2 [{{ weeks[2].day }}]

#### Monday

* {{ icon_lecture }} Lecture: **A 'user-experiments' session**
  * Brief product intro (by prof)
  * Experiment with the product _as a user_ i.e., try to use the product, and stretch its limits, simulate use cases etc.<br>
    You can **follow the suggested 'user experiments' in [this page](../admin/mentors.md)**.
  * Show your 'dev experiments' (done last week) and 'user experiments' to prof.<br>
    If you have queries about the product (e.g., motivations behind some features), this is a good time to clarify them.
* **Record your dev/user experiments** in your `progress.md`, and keep updating the `knowledge.md` as you learn new things.
<!-- ----------------------------------------------------------------------------------- -->

<div id="week3-monday"/>

## Week 3 [{{ weeks[3].day }}]

#### Monday

* {{ icon_lecture }} Lecture: **Product demos**
* Demo the product created by your project.
  * MarkBind, RepoSense, TEAMMATES: ~15-20 minutes each
  * The main objective is to learn/explain the product from the user's POV. Focus on giving an overview of the product from the user's POV, and limit to highlights of the features if there are many features (i.e., no need to do a comprehensive demo of every little feature). No need (but preferred) for every team member to take part either. Decide among yourselves who will demo which feature.
* Guidelines for the demos:
  * Everyone must contribute, and take part in the demo. Also include a self-intro (name, year, major, something interesting about yourself).
  * Showcase some of the more impressive features in a reasonable order. There is no need to demo _all_ features.
  * The aim is to impress the audience about the product, not to educate them on how to use it (it is not a 'how-to' tutorial)
  * Plan, and follow, a specific path that you know well and has been proven to work (the so called _golden path_), rather than plan to 'wing it'.
  * Use good demo data that puts the product in a good light, rather than use trivial demo data (`aaa`, `test123` etc.).
  * Some parts may be covered using pre-recorded screencasts, to save time (e.g., parts that takes a longer time to demo in real-time).


<!-- ----------------------------------------------------------------------------------- -->

## Week 4 [{{ weeks[4].day }}]

#### Monday

* {{ icon_lecture }} Lecture: Project-specific discussions


#### Sunday

* :alarm_clock: Update the [progress page]({{ students_site }}/instructions.html#updating-your-project-progress) and the [knowledge page]({{ students_site }}/instructions.html#updating-the-knowledge-gained-page).

<!-- ----------------------------------------------------------------------------------- -->


## Week 5 [{{ weeks[5].day }}]

#### Todo

* If you haven't started already, this is a good time to start getting ==at least one peer-review from classmates== before requesting reviews from a senior developer.
  * You can request a review from a peer directly or you can post a 'call for reviewers' in the respective chat channels.
  * You can get early inputs from senior devs if necessary, %%e.g., you are not sure about the overall direction of the PR, you want to know the rationale for the current code, etc.%%
* You can also ==help to manage new/external contributors== %%e.g., answer their questions, review their PRs etc.%% Even if their question is directed at a senior dev or the prof, you can jump in and answer if you know the answer.

#### Monday

* {{ icon_lecture }} ~~Project-specific discussions~~ (public holiday)


#### Sunday

* Keep updating the the _progress page_ and the _knowledge page_ on a weekly basis, as was done in the previous week. These pages are used in grading.
* :alarm_clock: PR to update [these csv config files]({{ dashboard_repo }}/tree/master/configs) if all your internal project work is not captured in the [dashboard]({{ dashboard_site }}). More info about the file format can be found [here](https://reposense.org/ug/customizingReports.html#customize-using-csv-config-files).

<box type="tip" seamless>

Don't worry if your RepoSense graph doesn't have as many ramps as others. Data shown on the RepoSense report are not directly comparable across projects or even within a project, as different projects have different commit rates and the nature of one dev's work may be very different from another. The RepoSense report is just a means for conveniently accessing your work in one page, %%and also a means of stress testing RepoSense%%.
</box>

## Week 6 [{{ weeks[6].day }}]

#### Monday

* {{ icon_lecture }} Lecture: Project-specific discussions

---

**Recess**

---

## Week 7 [{{ weeks[7].day }}]

<div id="plan-for-second-half">

By the end of this semester, we expect you to,

1. deliver substantial value to the project, which may be through developing a fairly big feature
(working solo or with others) or doing a bunch of tasks in a specific area,
1. more importantly, to gain expertise in a substantial part of the codebase
(while being fairly familiar with the rest).

If you can't work out a plan that achieves the above, you can seek guidance from the seniors and/or the prof as well.
</div>

* :alarm_clock: by Friday
  * Peer evaluations
* :alarm_clock: by Sunday
  * Update the progress page

#### Monday

* {{ icon_lecture }} Lecture: Project-specific discussions


<!-- ------------------------------------------------------------------------------------ -->

## Week 8 [{{ weeks[8].day }}]

#### Monday

* {{ icon_lecture }} Lecture: Project-specific discussions

<!-- ------------------------------------------------------------------------------------ -->

## Week 9 [{{ weeks[9].day }}]

#### Monday

* {{ icon_lecture }} Lecture: Project-specific discussions

<!-- ------------------------------------------------------------------------------------ -->

## Week 10 [{{ weeks[10].day }}]

<box type="info">

**As you are now entering the [_managing_ phase](../admin/cs3281.html#stage-3-managing)**, get more involved in management activities of the project.
</box>


#### Monday

* {{ icon_lecture }} Lecture: Project-specific discussions

<!-- ----------------------------------------------------------------------------------- -->

## Week 11 [{{ weeks[11].day }}]

<box type="tip" id="create-beginner-issues">

**Help to maintain a healthy supply of beginner-friendly issues**: If you encounter small non-urgent issues (so called 'low hanging fruits'), it is best to leave them for future new contributors, because we expect several new contributors to join the project during the upcoming summer.

In fact, go the extra mile to create such issues when you can, as a good supply of such beginner-friendly issues is an essential asset for an OSS project.
</box>

#### Todo

* Plan to finish ongoing (and new) PRs by end of week 12, with one week to spare. If PRs are stalling due to lack of reviews from mentors, feel free to nag.

<!--
* STePS preparations:
  * Start planning the posters. Note that here are some requirements from STePS regarding the poster format (e.g., include some sponsor logos). While STePS let you print the poster for free, you'll have to print it by the schedule they give, and the printing date is likely to be earlier than presentation date. Please get my feedback for the poster before printing it. You can get a copy of the previous year poster from the whoever did the poster last year. As the poster is not graded, it is ok to reuse some of the stuff from the previous year poster, but best not to copy it wholesale.
  * Submit project info (screenshots, videos etc.) to the STePS website. We want our projects to appear well in the STePS website because our main goal of participating in STePS is to gain exposure for your projects within the industry.
  -->

#### Monday

* {{ icon_lecture }} Lecture: Project-specific discussions


<!-- ----------------------------------------------------------------------------------- -->

## Week 12 [{{ weeks[12].day }}]

#### Monday

* {{ icon_lecture }} Lecture: Project-specific discussions


<!-- ----------------------------------------------------------------------------------- -->

## Week 13 [{{ weeks[13].day }}]

#### Monday

* {{ icon_lecture }} Lecture
  * Project specific discussions

<box type="important">

As we are now reaching the end of the semester:
* **Wrap up any ongoing PRs** soon. Only merged work can be counted for grading.
* **Update your knowledge and progress pages**. Those will be used in grading.

Soft deadline: end of week 13; hard deadline: end of reading week
</box>

<!-- ----------------------------------------------------------------------------------- -->

## Reading week, exam period

* **Ensure the progress/knowledge pages are up-to-date** latest by the end of the first
  week in the exam period.

<!-- ----------------------------------------------------------------------------------- -->

## Work done after the semester

* The work done after the semester is over can earn credit when taking CS3282 later.
  * Any value addition towards the course (e.g., PR reviews, mentoring, development work, etc.)
    can be used for the above.
  * The work done prior to CS3282 start date can count up to 40% of the course load i.e.,
    at least 60% of the course work needs to be done during the semester itself.
  * Keep good records of the work done so that they can be included in CS3282 work later when you take the course.
* While keeping in touch with the project during the intervening period is not compulsory,
  it is **strongly encouraged as it would help you to deepen your expertise in the project**.
  The more expertise you have in the project, the better you will be able to do
  project management and mentoring tasks included in the CS3282 workload.
* See [here](../admin/cs3282.html) for more info on CS3282 workload.
