<frontmatter>
title: "Projects and Mentors"
pageNav: 2
layout: cs3281-layout.md
</frontmatter>

# CS3281 Projects and Mentors

{% if is_pre_sem %}
<box type="important" icon=":fas-exclamation-triangle:" light>

The info given below is from the previous round, as a reference only. Will be updated in due course.
</box>
{% endif %}

## CATCher

**Current focus:**

* Build up the sister app: WATcher
* Support the 'Bug pruning' phase in CATcher
* Improve testing.
* Improve dev docs.
* Improve the user guide.
* [Hard] Find a way to make the tester's repo private during the PE (to prevent others copying bugs).
* [Less important] Add support for the _tutor moderation_ phase.

**Suggested user-experiments:**

* Use WATcher to visualize activities in different projects that similar to our target user i.e., small team projects { texts="['(a)','(b)','(c)','(d)']" }
* Set up a dummy PE session for CATcher

<box header="Mentors">

* ARIF KHALID (`@Arif-Khalid`)
* Li Zhaoqi (`@Eclipse-Dominator`)
* NGUYEN KHOI NGUYEN (`@nknguyenhc`)
* Sun Xinyu (`@Echomo-Xinyu`)
</box>

## MarkBind

**Current focus**:
* Make the following features _best-in-class_:
  * Tables (e.g., filter rows based on keyword)
  * Code blocks
  * Diagrams
  * Icons
  * Lists (e.g., customizing bullet points)
* Improve built-in search (e.g., include full-text search) so that we don't have to rely on external services.
* Solve these hard problems:
  * Add support for generating multiple versions of a website %%e.g., documentation for different product versions%%.
  * Find a way to add pop-over explanations for statements in a code block.
  * Find a way to support PR previews (the way Netlify does it).
* Internal:
  * Improve the robustness of the architecture.
  * Improve developer documentation.


**Suggested user-experiments:**

* Create and deploy a MarkBind website from scratch, for any use case you see fit (e.g., personal portfolio page) { texts="['(a)','(b)','(c)','(d)']" }
* Replicate the same using another static site generator ([here](https://jamstack.org/generators/) is a long list). Compare results.
* Make use of MarkBind's strong/unique features in the above two sites
* Set up [CS2103/T website](https://github.com/nus-cs2103/website-base) locally and play around with it, to get the experience of a fairly large/complex MarkBind site


<box header="Mentors">

* Lee Hyung Woon (`@lhw-1`)
* XU SHUYAO (`@Tim-Siu`)
* LAM JIU FONG (`@LamJiuFong`)
* Liu Yongliang (`@tlylt`) (industry) <sup>1</sup>
</box>

## RepoSense

**Current focus:**
* Improve performance of the report for large data sets e.g., [this report](https://nus-cs2103-ay2324s1.github.io/tp-dashboard/).
* Reduce memory use when viewing reports
* Ensure local report generation works for private repositories.
* Make it easy for someone to set up a 'moving window' report (e.g., show last 3 months) or a repo or multiple repos in an organization %%e.g., for a project manager/maintainer to keep an overview of the code changes to related repos%%.<br>
  Idea: Provide a ready-made repo they can fork and documentation on how to set it up with minimal effort required. Even better if there is a web page they can go to enter some data, click some buttons, which would set up the report automatically.
* Hard problems:
  * distinguish between <tooltip content="code touched only by one person">fully-owned</tooltip> and <tooltip content="code written by someone else but taken over by this author">partially-owned</tooltip> code. %%A recent FYP student made some progress on this aspect.%%


**Suggested user-experiments:**

* Set up a code dashboard to showcase your own project work { texts="['(a)','(b)','(c)','(d)']" }
* Deploy it, and set it to auto-update daily
* Add fairly-detailed blurbs to each project in that dashboard

<box header="Mentors">

* Chang Si Kai (`@sikai00`)
* JONAS ONG SI WEI (`@jonasongg`)
* POON YIP HANG, RYAN (`@sopa301`)
* Gokul Rajiv (`@gok99`)
</box>

## TEAMMATES

**Current focus:**

* A list of project ideas is given in the [TEAMMATES wiki](https://github.com/TEAMMATES/teammates/wiki). The project ideas that are ear-marked for CS3281 will be given to you during the code-sprint).


**Suggested user-experiments:**

* Set up a TEAMMATES course (in the production server) and add your project-mates as students { texts="['(a)','(b)','(c)','(d)']" }
* Set up feedback sessions in that course, targeting diverse use cases and different question types e.g.,
  * for grading a team project
  * for students to give feedback for presentations done by other classmates
  * for instructors to collect feedback for the course
* Get submit responses to dummy sessions set up by other team members (to experience the student POV)
* View the results of the sessions you set up

<box header="Mentors">

* DOMINIC BERZIN CHUA WAY GIN (`@domoberzin`)
* Qiu Jiasheng, Jason (`@jasonqiu212`)
* XENOS FIORENZO ANONG (`@xenosf`)
* ZHU YUANXI (`@yuanxi1`)
* YEO DI SHENG (`@dishenggg`)
* Wison Kurniawan (`@wkurniawan07`) (industry) <sup>1</sup>
</box>

## SE-EDU

**Current focus:**
* Limited to maintaining and fine-tuning AB3 and Duke. AB1, AB2, AB4 are to be archived.
* Keep the code base updated to match the new versions of the tool stack.
* Tweak to make the students' life easier e.g., simplify where possible.
* Migrate Duke, AB3 to JavaFX 16?


---

<small>%%[1] Those marked as _industry_ are not official mentors. They are past developers who are still willing to provide moral support and help out in an advisory role when their input is required.%%</small>


