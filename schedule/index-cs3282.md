<frontmatter>
title: "CS3282 Schedule"
pageNav: 2
layout: cs3282-layout.md
</frontmatter>

{% from "schedule/index-cs3281.md" import weeks with context %}

# CS3282 Schedule
{% if is_pre_sem %}
<box type="important" icon=":fas-exclamation-triangle:" light>

The info given below is from the previous round, as a reference only. **Major changes are highly unlikely**, however.
</box>
{% endif %}

<!-- ----------------------------------------------------------------------------------- -->

## Week 1 [{{ weeks[1].day }}]<a id="week-1"/>

#### Todo

* {{ icon_todo }} **Check your details in [nus-cs3281/{{ year }}](https://nus-cs3281.github.io/{{ year }}/cs3282-index.html)** [:alarm_clock: Deadline: Friday] and [update](https://nus-cs3281.github.io/{{ year }}/instructions.html) if necessary. You will be given write permission to the repo by Monday.
* {{ icon_todo }} **Discuss with other senior team members to plan onboarding activities for CS3281 students.**


#### Monday

* Attend the CS3281 session if possible, meet new devs (from CS3281), and help them set up the project.


#### Thursday

* {{ icon_lecture }} Lecture : CS3282 Course Intro
  * Hybrid lecture (Zoom link is in Canvas homepage) -- ==F2F by default== unless you obtained permissions to not attend F2F.

#### Kick-Off Team Meeting

* Within the first two weeks of the semester (the earlier, the better), you should arrange a 'kick-off' team meeting.
* All CS3281 and CS3282 students of the project should attend. Even better if other senior devs can attend, if they are available.
* A food budget of $10/attendee will be given.
* Minimally, use the meeting for team bonding. In addition, you can do technical briefings, tutorials, workshops etc. to get CS3281 students started on the project work.
* Suggested duration 1.5 hours. OK to have this on a weekend, if all attendees are agreeable.
* Approach prof if you need help booking a venue.

<panel type="info" header="#### Activity: Book Chapter Report" expanded>

The purpose of this activity is to encourage you to read SE books.

Steps:

1. Have a quick look at the default recommended book [**Software Engineering at Google**](https://abseil.io/resources/swe-book) (PDF available for free). You may also pick a different SE book that you have read before or want to read this semester. Pick a chapter that you want to read/use for this activity.
1. Post an issue in [nus-cs3281/{{ year }}](https://github.com/nus-cs3281/{{ year }}/issues) indicating which book and which chapter you plan to read. Assign the issue to yourself.<br>
  Doing this early will help you avoid clashing with chapters chosen by others. We prefer not to have multiple book reports on the same chapter.
1. Read the book chapter.
1. Post a short summary of the chapter in the same issue. Just a few bullet points is enough. Optionally, you can also comment on the relevance of the chapter to your NUS-OSS project.

Try to finish the above by the end of the recess week.

You are welcome to do more than one book/chapter too.
</panel>
<p/>

<!-- ----------------------------------------------------------------------------------- -->

## Week 2 [{{ weeks[2].day }}]<a id="week-2"/>

#### Todo

* {{ icon_todo }} **Keep updating `progress.md` and `knowledge.md`**, in the [nus-cs3281/{{ year }} repo](https://github.com/nus-cs3281/{{ year }}) periodically.
  * `progress.md`: Your contributions to the internal project(s). Update similar to how you did in CS3281.
  * `knowledge.md`: Keep evolving your `knowledge.md` to showcase things you have learned in various areas (e.g., your chosen expertise areas): resources explored, lessons learned, deliverables produced, etc.
* {{ icon_todo }} **If you plan to contribute to an external project,** start looking for one if you haven't done so already. Once you have found a potential project, you can follow their instructions to get started on contributing. You can even try multiple projects if you are not sure the chosen project will work out.

#### Thursday

* {{ icon_lecture }} Lecture: Tips for tech talks - Part 1
* Choosing topics for Lightning Talks:
  * :alarm_clock: By the end of today, post an issue in repo [nus-cs3281/{{ year }}](https://github.com/nus-cs3281/{{ year }}/issues) as follows %%&nbsp;Reason: posting titles in advance will help us avoid topic duplications%%:
    * Issue subject: the title of your talk
    * Issue body: 2-3 sentence preview of the talk
  * Check to see if there are duplicate topics already posted. You are discouraged from (but not prevented from) choosing a topic already chosen by another.
  * It is in your interest to choose a topic related to one of your [expert areas](../admin/cs3281.html#expertise-areas:~:text=and%20instructor%20observations.-,Expertise%20Areas,-While%20this%20is). It is not a strict requirement though.
  * Note that you will be peer-evaluated for the ==quality of delivery as well as the usefulness of the talk==. It is recommended to pick topics that are potentially useful to the audience.
* Read next week's schedule to find more info about the upcoming lightning talks. The order of talks %%(i.e., who presents in which week)%% is given there too.


<!-- ----------------------------------------------------------------------------------- -->

<div id="week3-monday"/>

## Week 3 [{{ weeks[3].day }}]<a id="week-3"/>

#### Todo

* Decide primary/secondary mentor allocation for your project


<panel type="warning" header="##### Wrap-up the previous in-lecture exercise" expanded no-close>

In a recent in-lecture exercise, you started on creating a PUMA <tooltip content="because we left out the supporting points, it is just a skeleton only (i.e., not fleshed out)">skeleton</tooltip> for a hypothetical talk. Let's wrap it up before you start working on your real lightning talk.

==#r#Action item: Finalize the PUMA skeleton (in the Google Doc) by week 3 Tuesday.##==

To help you further with the above, here is a walkthrough of how we can come up with a PUMA skeleton for a sample talk.

1. Let's start with a rough goal: `a talk to promote NUS-OSS projects among first-year CS students`.
1. Next, we decide what's the impact we want to achieve from this talk.
   * We want the attendees to `do: contribute code to NUS-OSS projects`.
   * For them to do that, they need to `believe: contributing to NUS-OSS projects is possible, and beneficial`.
   * For them to believe that, they need to `know: benefits of contributing to NUS-OSS projects`.
1. Before we go any further, let's figure out what the attendees will get out of this talk (i.e., the WIIFY). Without a strong WIIFY, it is unlikely we can get them to pay attention.<br>
   To define a good WIIFY, we should understand fears/desires/aspirations/knowledge of our attendees (i.e., first year CS students). Most likely they got into CS due to good job prospects but worried about competition for good jobs.<br>
   `WIIFY: this talks is about a way that can help you get into better SE jobs/internships`.
1. Now, let's come up with a few key points that are aligned with intended impact, and matches the WIIFY as well.
   * `KP1: Contributing to OSS projects shows recruiters that you can write production quality code`. This is not something you can prove through normal school projects.
   * `KP2: NUS-OSS projects are of manageable size, and in relatable domains` i.e., they are not 'too big', and are related to education.
   * `KP3: NUS-OSS projects come with guidance from NUS seniors/profs`. This is not the case for other OSS projects.
   * `KP4: If you are willing to try, you have a good chance of getting into one`, even if you are not a strong programmer now.
1. Next, let's decide how to present the content (covering the above key points) in an agenda.
   * `Section A. What is NUS-OSS`
   * `Section B. How it can help you get better internships/jobs`
   * `Section C. What you need to do to get in`
1. Now, let's look for a PUNCH. Here are some choices:
   * **P**ersonal: share how some work you contributed to an NUS-OSS project is now benefitting thousands of students/teachers, how something you learned from an NUS-OSS project helped you during an interview, how the interviewer was also an alumni of an NUS-OSS project etc.
   * **U**nexpected: `Did you know that NUS-MODS that you all use is an open source project created by SoC students?`
   * **N**ovel: ?
   * **C**hallenge: `What percentage of the code you write in the school will be actually used by someone? 10%? 2%? 1%? 0%? Most likely closer to 0%, right? But it doesn't have to be like that.`
   * **H**umor: ?
1. How about a catchy call-to-action? `Join an NUS-OSS project, to aim for better jobs`?
1. Finally, let's decide on how to phrase the topic. Well, the call-to-action can serve as the talk topic as well.

Putting it all together:

<blockquote>

**Title:** Join an NUS-OSS project, to aim for better jobs

**Audience:** First year CS students in SoC

**PUNCH:** What percentage of the code you write in the school will be actually used by someone? 10%? 2%? 1%? 0%? Most likely closer to 0%, right? But it doesn't have to be like that.

**WIIFY:** I'm going to tell you a way that can help you get into better SE jobs/internships.

**Agenda:**<br>
[A] First, I'll explain what NUS-OSS is.<br>
[B] Then, how it can help you get better internships/jobs.<br>
[C] Finally, what you need to get in.

**Key points:**
* KP1: Contributing to OSS projects shows recruiters that you can write production quality code. %%(-> to be covered in section B)%%
* KP2: NUS-OSS projects are of manageable size, and in relatable domains %%(-> in section A)%%
* KP3: NUS-OSS projects come with guidance from NUS seniors/profs %%(-> in section A)%%
* KP4: If you are willing to try, you have a good chance of getting into one %%(-> in section C)%%

**Call to action:** Join an NUS-OSS project, to aim for better jobs
</blockquote>


</panel>
<p/>

#### Thursday

* ~~{{ icon_lecture }} Lecture:~~ No lecture due to holidays




<!-- ----------------------------------------------------------------------------------- -->

## Week 4 [{{ weeks[4].day }}]<a id="week-4"/>

#### Todo

If you haven't already,
* {{ icon_todo }} [If applicable] get started with contributing to the external project. If you don't make any progress by week 5, you need to find another project.

#### Thursday

* {{ icon_lecture }} Lecture: Lightning Talks Round A - Part 1
* See the **<a href="{{ students_site }}/students/talksSchedule.html" target="_blank">Lightning Talks Schedule</a>** (created based on a random order).

<panel type="danger" header="##### Steps to follow when preparing for the lightning talk" expanded no-close>

<div id="tips-roundA">

<box type="warning">

Give priority to applying the techniques covered in week 2 lecture even if you feel like they are cramping your natural presentation style or you can do better without them. Harmonizing your style with the new techniques can come later. In particular, *WIIFY*, *Key Points*, and *Impact* should be the driving forces of your presentation. Figure them out at the start of your preparations, not as an afterthought.
</box>

Try to follow these steps in the given order:

  1. **Define the _intended impact_ of the talk.**
     * Try to choose an impact that has a _do_ component (e.g., `get audience to switch to technology X`), not just _know_ and _believe_ components (e.g., `tell audience about X`). The _do_ component will make the talk motivational and higher-impact; without it, the talk will be simply informational.
     * Frame the intended impact as a _call-to-action_ (CtA).
  1. **Find a _WIIFY_** i.e., a good reason for the audience to follow your CtA. The WIIFY can work better if it relates to this _specific_ audience at a _concrete_ level.
     For example, explaining `how Foo technology can benefit SoC students right now` is better than making a general claim that `Foo is a useful technology`. Sometimes realizing that ‘there is a cool technology out there benefiting many others, but it is not accessible to me right now’ can be a turn off.<br>
     If you cannot find a convincing WIIFY, reconsider the topic as there is a risk that the audience may not find the talk useful.
  1. **Choose _key points_** that help you achieve that impact. Be clear about your key points.
     * We look for **points, not topics** %%e.g., `how to use X` is a topic while `X is easy to use` is a point%%. In the past years, I found that some students still confused _points_ with _topics_. A point forms a sentence e.g., `The tool X is easy to use.` whereas a topic may not e.g., `Tool X usage`.
     * Make sure your key points are aligned with the intended impact. If you key points are `a`, `b`, `c`, you should be able to say "`a`; `b`; `c`; _therefore_, `CtA`" %%e.g., "`X is fast`; `X is free`; `X is getting popular`; _therefore_, `switch to X!`"%%
  1. **Decide the talk _roadmap_** (aka the _agenda_, or the _promise_). They may be similar to key points but not necessarily the same. The roadmap can be topics (rather than points) and can be questions (rather than answers).
     Roadmap | Key points
     --- | ----
     `What is X?`<br> `Demo of X`<br> `Benefits of X` | `X is fast`<br> `X is free`<br> `X is getting popular`
  1. **Find a PUNCH.** This is hard, but give it your best shot. One good tactic is to find an extreme example of a pain point that can be solved by your topic %%e.g, if your CtA is `switch to X`, you can start with an example that shows how bad something can be without X%%.
  1. **Design the slides**.
     * One common mistake is inadvertently including big holes in the talk, for example, forgetting to explain some concept that is vital to understanding the topic. Critically review your talk from the target audience point of view.<br>
     * Also mention how the topic fits into the big picture.<br>
       %%e.g., if your talk is about X, the big picture can be like this:%%
       >%%There are two categories of tools for doing Bar which is an essential part in building apps. Category 1 tools work inside-out and Category 2 tools work outside-in. Tool X is the currently a hot tool in category 2 because it is faster and more secure than other popular tools in that category, namely Y and Z.%%
     * Ensure the last slide has the key points (not a big `Thank You` or `Q&A`)
     * Limit the content to what you can deliver in **7 minutes** (in rehearsals, aim to finish in 6 minutes; the actual talk is likely to take longer than the rehearsal). The remaining 3 minutes is for Q&A.
  1. **Start the talk with a _PUNCH_, _WIIFY_, and the _Roadmap_**. ==Avoid the traditional `My name is A, my topic is B` type start.==<br>
     To keep things simpler in this round, assume the host/MC will introduce you first (i.e., ==no need to do a self-intro yourself==).
  1. **End the talk with key points and CtA.** It is also good to reiterate WIIFY together with key points.

<box type="important" seamless>

**No open laptops during lightning talks!**{.text-danger}

One important way we can support the speakers is to give them our undivided attention. To that end, we have a policy of not allowing any open laptops (among the audience) during lightning talks.<br>
**Speakers: Please finalize your slides _before_ the session starts**, as you will not be able to do last minute tweaks to slides during the session itself (due to the above policy).
</box>
</div>

</panel>

<panel type="secondary" header="##### After the session" expanded no-close>

* :alarm_clock: by Thursday midnight: Speakers should _update_ the issue description (rather than add as a new comment) as follows:
  * Add a link to the slides. %%&nbsp;Note that GitHub allows attaching ppt files. Just drag-drop the files to the comment box.%%
  * State **WIIFY, Key Points, Impact**
* :alarm_clock: by Friday midnight:
  * All must submit feedback to speakers (via TEAMMATES). The quality of feedback is considered in grading.
  * Feel free to continue the discussion about each talk in the issue tracker.

</panel>
<p/>


#### Sunday

* :alarm_clock: Update the [progress]({{ students_site }}/instructions.html#updating-your-project-progress) page.

<!-- ----------------------------------------------------------------------------------- -->


## Week 5 [{{ weeks[5].day }}]<a id="week-5"/>

#### Todo

* As you mentor CS3281 students, try to get them to peer-review each others' PRs and to help guide other contributors.


#### Thursday

* {{ icon_lecture }} Lecture: Lightning Talks Round A - Part 2
  * See the **<a href="{{ students_site }}/students/talksSchedule.html" target="_blank">Lightning Talks Schedule</a>** (created based on a random order).


## Week 6 [{{ weeks[6].day }}]<a id="week-6"/>

#### Thursday

* {{ icon_lecture }} Lecture: Tips for Tech Talks - Part 2

#### Todo

* :alarm_clock: by Friday : Post _Lightning Talks Round B_ topic in the issue tracker, as was done in Round A
* :alarm_clock: by end of recess week : Aim to finish the ['Book Chapter Report' activity](#activity-book-chapter-report)

#### Resources

* Online article of interest: [Steve Jobs's Masterful Presentation Ability Came Down to 1 Underrated Thing. ...](https://www.inc.com/jason-aten/steve-jobs-masterful-presentation-ability-came-down-to-1-underrated-thing-anyone-can-do-it.html)
---

**Recess**

---

<br>

## Week 7 [{{ weeks[7].day }}]<a id="week-7"/>

For your reference, below are the instructions given to CS3281 students regarding their plan for the second half of the semester.
<blockquote>
<include src="index-cs3281.md#plan-for-second-half" />
</blockquote>

==Deliverables for you (i.e., CS3282 mentors):==

1. guide mentees achieve the above goals,
1. to ensure CS3281 students collectively gain expertise in the full codebase, and is able to 'manage' the project in future by themselves.

#### Todo

* :alarm_clock: by Monday
  * [If applicable] Some progress expected on the external project

#### Thursday

* {{ icon_lecture }} Lightning Talks Round B - Part 1 (see <a href="{{ students_site }}/students/talksSchedule.html" target="_blank">Lightning Talks Schedule</a>)
  * In your slide design and delivery, try to apply the tips covered in week 6 lecture. Some of those points are given in the panel below but you are advised to look at the lecture slides again before you prepare for the talk. While are you not required to use the _generic slide deck_ pptx file, do take a look at it and make sure all its elements are also present in your slide deck.
  * In addition, aim for a stronger application of tips given for round A (see the panel below for a reference)
* {{ icon_lecture }} Team-specific discussions (if there's time left)


<panel type="info" header="Tips for round B" expanded no-close>

* **Make slides more visual**:
  * Instead of bullet points, use other suitable visual structures %%e.g., a flow chart%%
  * Instead of text, use graphical forms
  * But avoid visual clutter such as background graphics that do not add value

  * {{ icon_video }} Given below is a video containing some slide design tips:

    @[youtube](9yXZTylf32k)

* **Make the point clear**:
  * Ask yourself "what is the point I want to make in this slide?" Once you have determined the point, ask yourself "can I improve the slide to make the point clearer?"
  * Use _assertion-evidence_ type slides rather that _topic-content_ type where applicable.
  * Ensure every technical term used is either known to the audience or you define it explicitly. If you are not sure if the audience know the definition, _slip in_ the definition casually to your explanations.
  * Demo/describe your solution early to avoid setting expectations too high. %%If you spend a lot of time explaning the problem or criticising competing solutions, audience expectations of your own solution might climb too high.%%

* **Animate meaningfully**: Use animations/transitions to enhance the meaning of your slide content.

* **Use the Click-Look-Recall technique** instead of using cue cards:
  * Ensure that you know the sequence of your talking points in advance.
  * Map each point to a click on your slide, which should add a visual cue onto the slide that reminds you of the point you are supposed to talk about.
  * During delivery, _look_ at the screen as you _click_, and use the visual cue to _recall_ the point.

</panel>

<panel type="secondary" header="For reference: Tips from round A" no-close>

<include src="./index-cs3282.md#tips-roundA" />

</panel>
<p/>

<!-- ------------------------------------------------------------------------------------ -->

## Week 8 [{{ weeks[8].day }}]<a id="week-8"/>

#### Todo

* :alarm_clock: by Sunday
  * Update the progress page

#### Thursday

* {{ icon_lecture }} Lecture :
  * Lightning Talks Round B - Part 2
  * Team-specific discussions

<!-- ------------------------------------------------------------------------------------ -->

## Week 9 [{{ weeks[9].day }}]<a id="week-9"/>

#### Todo

* :alarm_clock: by Thursday
  * Have a sync-up meeting with CS3281 mentees (at least, your primary mentees) and ensure they are clear on expectations and timelines of any significant deliverables expected from them.<br>
  Also brief them on project management tasks they are supposed to gradually take on in the coming weeks (as they enter the [_managing_ phase](../admin/cs3281.html#stage-3-managing)).

#### Thursday

* {{ icon_lecture }} Lecture:
  * Tips for Tech Talks - Part III
  * Team-specific discussions


<!-- ------------------------------------------------------------------------------------ -->

## Week 10 [{{ weeks[10].day }}]<a id="week-10"/>

<box type="info">

**As CS3281 students are now entering the [_managing_ phase](../admin/cs3281.html#stage-3-managing)**, get them more involved in management activities of the project.
</box>

#### Todo

* :alarm_clock: by Thursday [If applicable] Document your observations about the workflow of your external OSS project:
  * Info to include:
    1. Links to any online documents about the workflow of external project
    1. Important things you learned from contributing to that project, if any
    1. Practices/tools of the external project that you think can be adopted by your NUS-OSS project
    1. [Optional] Suggested areas of improvement for the external project
  * Submission:
    * Add your observations to the file `{{ students_repo }}/students/yourName/observations.md`.<br>
      Afterward, your additions will appear in the [Observations page](https://nus-cs3281.github.io/{{ year }}/students/observations.html).
    * Recommended length: about 0.5 - 1 A4 page
  * If you contributed to multiple projects, you may document all those projects in your observations or choose one of them to include.
  * If some of your classmates contributed to the same project, you should still write your own observations.

#### Thursday

* {{ icon_lecture }} Lecture:
  * Discussion about observations from the external project.
  * Strategize how to wrap up the semester's work
<!-- ----------------------------------------------------------------------------------- -->

## Week 11 [{{ weeks[11].day }}]<a id="week-11"/>

<box type="tip">

<include src="index-cs3281.md#create-beginner-issues" />
</box>

#### Todo

* Help CS3281 students finish ongoing (and new) PRs by end of week 12, with one week to spare.

<!--
* STePS preparations:
  * Start planning the posters. Note that here are some requirements from STePS regarding the poster format (e.g., include some sponsor logos). While STePS let you print the poster for free, you'll have to print it by the schedule they give, and the printing date is likely to be earlier than presentation date. Please get my feedback for the poster before printing it. You can get a copy of the previous year poster from the whoever did the poster last year. As the poster is not graded, it is ok to reuse some of the stuff from the previous year poster, but best not to copy it wholesale.
  * Submit project info (screenshots, videos etc.) to the STePS website. We want our projects to appear well in the STePS website because our main goal of participating in STePS is to gain exposure for your projects within the industry.
  -->

#### Thursday

* {{ icon_lecture }} Lecture : Lightning Talks Round C
  * No Q&A
  * This should be an improved version of the talk you gave in round B, based on feedback you received for it.<br>
    * You can also consider incorporating into the talk answers to relevant questions raised during round B Q&A session.
    * Also consider adding info on the cons/downsides of the topic so that the talk can become more balanced, and your message to the audience become more credible (i.e., it appears like advice from an expert rather than a sales pitch).
  * ==Talk length should be strictly 7 minutes or less==, as we have 10-11 talks per session.
  * Assume some audience members have not seen round A or B (we plan to invite CS3281 students to attend this round of talks). So, don't refer to past rounds during your talk.

<panel type="info" header="**Targets for LT Round C**" expanded no-close>

In this round you are ==expected to hit almost all targets(:dart:)== given below. You are recommended to follow tips (:bulb:) given under each target closely.

**Talk structure**

1. :dart: The talk is well-structured and the following are clear.
      * PUNCH
      * WIIFY
      * Roadmap/agenda
      * Key points
      * Call-to-action
1. :dart: The talk is well-rounded and balanced.
   * Cover downsides, not just upsides only %%e.g., if the talk is about X, you can cover use cases for which X fits well (thus implying where it doesn't fit too), instead of giving the impression that it fits _every_ use case%%. { icon="fas-lightbulb" i-class="text-success" }
   * Cover the 'big picture aspect' %%e.g., if the talk is about a coding tool X, where does X fit into the big picture of coding tools, what are the competing/complementary tools, how is it different/similar to other tools etc.%%.
   * Cover all pertinent aspects %%so that the audiences is not left wondering "you talked about A,B,D but why leave out C?"%%.

**Slide design**

1. :dart: No visual clutter
   * Remove any conspicuous background graphics that do not add value. { icon="fas-lightbulb" i-class="text-success" }
   * Avoid using <tooltip content="done without good reason; uncalled for">gratuitous</tooltip> images that don't really add value
1. :dart: Slides are 'visual'
   * Wherever you have bullet points (or paragraph text), look for another suitable structure such as a table, flow chart, map, graph, etc. { icon="fas-lightbulb" i-class="text-success" }
   * Use graphics instead of (or in addition to) text
1. :dart: Important elements of the talk are captured prominently in slides
   * Ensure WIIFY, Roadmap, start/end of sections of the Roadmap, and each keypoint are captured as separate slides or as noticeable visual elements { icon="fas-lightbulb" i-class="text-success" }
   * Use words `Key point` in text so that they are hard to miss<br>
    %%e.g., `KEY POINT: Java is verbose!`%%
   * Use a different (and more prominent) design for important slides and key elements<br>
    %%e.g., use a brighter background, bigger font size%%
   * Revisit the agenda slide when you transition from one section of the talk to another, to show the audience the progression of the talk through the agenda items.
1. :dart: Last slide is used to good effect
   * At least it should contain key points and the call-to-action. Good to have the agenda items too -- show that you've completed all of them. { icon="fas-lightbulb" i-class="text-success" }
   * as the last slide should contain the essence of the talk, it is ok to be 'crowded'.<br>
      Augmenting the key points with some additional 'specifics' helps them to stick in the audience's mind -- otherwise they can become generic statements that are easily forgotten.
   * you may want to include your contact details in the last slide too.
1. :dart: Slides optimized to convey the point, and help your delivery
   * Write down in slide notes the point(s) a slide is supposed to convey. Each slide should have at least a main point, and possibly some sub points. e.g., { icon="fas-lightbulb" i-class="text-success" }
      ```{.no-line-numbers}
      Java is still the most popular language today.
      * Java positions lead job vacancies.
      * Highest percentage of devices support JVM.
      * All fortune 500 companies use Java for their enterprise systems.
      ```
   * If possible, use the assertion-evidence format to bring out the main point. i.e., show the main point as the slide title.<br>
    %%e.g., the slide title can be `Java is still the most popular language today.` (i.e., the main point) instead of `Java popularity` (i.e., a phrase/topic)%%
   * For each sub point, ensure there is a corresponding click.<br>
    %%e.g., the slide should have at least three clicks so that you can use the click-look-recall technique as a prompt to talk about each of the three sub points.%%
1. :dart: Kept jargon usage to a minimum
   * Format jargon in a different way e.g., use a different font so that you remember to define them. Alternatively, put the definition on the slide. { icon="fas-lightbulb" i-class="text-success" }
1. :dart: Used meaningful animations
   * Use meaningful slide transitions e.g., use a more drastic transition when moving from one major section to another. { icon="fas-lightbulb" i-class="text-success" }
   * When possible, gradually remove/introduce elements into a slide so that the audience can maintain context i.e., minimize drastic change of scenery.

**Delivery**

1. :dart: Started with a PUNCH (instead of traditional self-intro)
   * Open with a brief greeting, and jump starlight into your PUNCH { icon="fas-lightbulb" i-class="text-success" }
1. :dart: WIIFY and Roadmap clearly communicated.
   * Use clear 'marker' phrases to draw attention to these important elements of the talk. e.g., `"I think this is a very important topic to you because ..."` `"In the next few minutes, I'm going to talk about (a)... (b)... and (c)"` { icon="fas-lightbulb" i-class="text-success" }
1. :dart: Each key point is clearly made
   * When the key slide comes up, use the marker phrase `"So, the key point here is ..."` to draw attention to it. { icon="fas-lightbulb" i-class="text-success" }
1. :dart: Finished by reiterating key points, and call-to-action.
   * Follow the call-to-action with a clear `"Thank you!"` and if applicable, `"I'm ready for your questions"` to indicate the end of your talk. { icon="fas-lightbulb" i-class="text-success" }
1. :dart: Finished within the allotted time limit (e.g., 7 minutes).

</panel>
<p/>


<!-- ----------------------------------------------------------------------------------- -->

## Week 12 [{{ weeks[12].day }}]<a id="week-12"/>


#### Thursday

* Project-specific discussions:
  * Discuss the future of the project, for the summer and beyond

#### Todo

* {{ icon_todo }} before week 13 Thursday: Have a project wrap-up meeting with mentees and brief them on any leftover tasks, summer plans, etc.

<!-- ----------------------------------------------------------------------------------- -->

## Week 13 [{{ weeks[13].day }}]<a id="week-13"/>

#### Thursday

* {{ icon_lecture }} Lecture : Wrap up

