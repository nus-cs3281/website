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
* Improve testing.
* Improve dev docs.
* Improve the user guide.
* [Hard] Find a way to make the tester's repo private during the PE (to prevent others copying bugs).
* [Less important] Add support for the _tutor moderation_ phase.

<box header="Mentors">

* Kang Su Min (`@kkangs0226`) (industry) <sup>1</sup>
* Goh Yee Chong, Gabriel (`@gycgabriel`)
* Lee Chun Wei (`@chunweii`)
* Lee Xiong Jie, Isaac (`@luminousleek`)
* Vignesh Sankar Iyer (`@vigneshsankariyer1234567890`)
* Wong Chee Hong (`@cheehongw`)
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

<box header="Mentors">

* Ang Ze Yu (`@ang-zeyu`) (industry) <sup>1</sup>
* Aaron Chong Jun Hao (`@acjh`) (industry) <sup>1</sup>
* Chan Yu Cheng (`@yucheng11122017`)
* Elton Goh Jun Hao (`@EltonGohJH`)
* Hannah Chia Kai Xin (`@kaixin-hc`)
* Jonah Tan Jun Zi (`@jonahtanjz`) (industry) <sup>1</sup>
* Jiang Sheng (`@Gisonrg`) (industry) <sup>1</sup>
* Jovyn Tan Li Shyan (`@jovyntls`)
* Lee Wei, David (`@itsyme`)
* Liu Yongliang (`@tlylt`) (industry) <sup>1</sup>
* Ong Jun Xiong (`@ong6`)
</box>

## RepoSense

**Current focus:**
* Improve performance of the report for large data sets e.g., [this report](https://nus-cs2103-ay2324s1.github.io/tp-dashboard/).
* Reduce memory use when viewing reports
* Ensure local report generation works for private repositories.
* Make it easy for someone to set up a 'moving window' report (e.g., show last 3 months) or a repo or multiple repos in an organization %%e.g., for a project manager/maintainer to keep an overview of the code changes to related repos%%.<br>
  Idea: Provide a ready-made repo they can fork and documentation on how to set it up with minimal effort required. Even better if there is a web page they can go to enter some data, click some buttons, which would set up the report automatically.
* Hard problems:
  * distinguish between <tooltip content="code touched only by one person">fully-owned</tooltip> and <tooltip content="code written by someone else but taken over by this author">partially-owned</tooltip> code. %%An FYP student is doing some work on this aspect.%%

<box header="Mentors">

* Chan Jun Da (`@chan-j-d`) (industry) <sup>1</sup>
* Charisma Kausar (`@ckcherry23`)
* David Gareth Ong (`@vvidday`)
* Gokul Rajiv (`@gok99`)
* Huang Chengyu (`@HCY123902`) (industry) <sup>1</sup>
* Marcus Tang Xin Kye (`@MarcusTXK`)
* Peh Xian Bin, Eugene (`@eugenepeh`) (industry) <sup>1</sup>
* Zhou Jiahao (`@Zhou-Jiahao-1998`) (industry) <sup>1</sup>
</box>

## SE-EDU

**Current focus:**
* Limited to maintaining and fine-tuning AB3 and Duke. AB1, AB2, AB4 are to be archived.
* Keep the code base updated to match the new versions of the tool stack.
* Tweak to make the students' life easier e.g., simplify where possible.
* Migrate Duke, AB3 to Java 17?
* Migrate Duke, AB3 to JavaFX 16?
<box header="Mentors">

Current [SE-EDU team](https://se-education.org/docs/team.html)
</box>

## TEAMMATES

**Current focus:**
* A list of project ideas is given in the [TEAMMATES wiki](https://github.com/TEAMMATES/teammates/wiki). The project ideas that are ear-marked for CS3281 will be given to you during the code-sprint).

<box header="Mentors">

* Chang Weng Yew, Nicolas (`@NicolasCwy`)
* Dominic Lim Kai Jun (`@domlimm`)
* Fang Junwei, Samuel (`@samuelfangjw`) (industry) <sup>1</sup>
* Jay Aljelo Saez Ting (`@jayasting98`)
* Kevin Foong Wei Tong (`@kevin9foong`)
* Li Jianhan (`@jianhandev`) (industry) <sup>1</sup>
* Mok Kheng Sheng Fergus (`@FergusMok`)
* Neo Wei Qing (`@weiquu`)
* Ong Jun Heng, Cedric (`@cedricongjh`)
* Sim Sing Yee, Eunice (`@EuniceSim142`)
* Wu Qirui (`@hhdqirui`) (industry) <sup>1</sup>
* Wison Kurniawan (`@wkurniawan07`) (industry) <sup>1</sup>
* Zhao Jingjing (`@zhaojj2209`) (industry) <sup>1</sup>
* Zhang Ziqing (`@ziqing26`)
</box>

---

<small>%%[1] Those marked as _industry_ are not official mentors. They are past developers who are still willing to provide moral support and help out in an advisory role when their input is required.%%</small>


