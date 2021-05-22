Learning Target Check 1
================

This Learning Target Check is due by **11:59 pm on Sunday, May 23**.
Learning Targets will be assigned roughly every two weeks and will
contain problems for targets that have been covered through class
Preparation, Team Activities, Follow-up, or Projects.

```
![convention](https:/images.app.goo.gl/GEbrMQCbSuXuCGBe8)
```

**Nikita**: This is a **Cow** that comes from the Bos *genus* and is a herbivore **Artiodactyla** which is domesticated and sleeps a total of 4 hrs a day.  It spends 0.7 hrs in *REM* sleep and spends about 20 hours being awake.

## Overview

All nineteen Learning Targets are being directly assessed!

-   \[**NEW**\] **DS.2 - CORE**: I can create graphical display of data
    that highlight key features
-   \[**NEW**\] **PD.1 - CORE**: I can use a project-based workflow to
    organize and run reproducible analyses
-   \[**NEW**\] **PD.4**: I can identify and correct common
    collaboration errors when working with Git/GitHub

Your final report should interweave code, output, and narrative. You
will submit a *clickable* link to your finalized `ltc01-<username>` repo
through Blackboard. This done at the same place where you created this
repo.

### Submission Checklist Statements

Prior to submitting your materials on Blackboard, verify these
statements:

-   For items that I already have two marks of *Sufficient*, I have
    deleted all of the text *except* for the Learning Target header.
-   For items that I have not yet earned two marks of *Sufficient*, I
    have answered the target to the best of my ability **and** provided
    a detailed explanation for my work (i.e., one that does not simply
    state what each line of code does).
-   I have have knitted the `ltc01.Rmd` file after completing all of the
    Learning Targets and verified that all output, plots, and
    explanations display correctly.
-   In the **Git** pane of RStudio, I have staged (checked), committed,
    and pushed **every** item listed to my GitHub repository
-   In my GitHub repository, I have verified that all items have
    uploaded and that my `ltc01.md` file contains all output, plots, and
    explanations as intended.
-   I have posted a *clickable* link to my `ltc01-<username>` repository
    in Blackboard.

## Getting Help

You can use books or searching online resources like Google/Bing or
StackOverflow to find suggestions during this Learning Target Check. If
you use a resource beyond class activities, R4DS, or the Primers, **you
must cite any resource** that you use (you do not need to cite R4DS or
the class activities, but this might help you remember where you pulled
the information from). Failure to cite a non-course resource is
considered academic dishonesty and will *minimally* result in a grade of
*Incomplete* (**I**).

You *may not* communicate with any person other than your instructor.
Violations of this policy include *any* consultation with other students
or former students, including Stat Tutoring Center tutors; using work
from another student or former student; submitting the problem to a
online help website like StackOverflow, Chegg, Coursehero, or any online
forum. All such violations will be treated as academic dishonesty and
will *minimally* result in a grade of **I** and being banned from
revising the work.

All questions for Learning Target Check should be initially emailed to
your instructor. If your instructor feels that a question asked would
benefit the entire class (e.g, it will clarify a general item), you will
be directed to post that as an Issue in the community repo. **You may
only post questions about Learning Target Checks on the community repo
if instructed to do so.**

You may not share information with other people about the content of
this Learning Target Check unless explicitly approved by your
instructor.

## Evaluation

Each Learning Target will be graded either *Sufficient* (**S**), *Not
Yet* (**N**), or *Incomplete* (**I**). All Learning Targets that do not
earn an **S** will be provided with feedback based on your attempt to
help you prepare for the next Learning Target Check in a couple of
weeks. It is difficult to provide feedback where there is not
substantial effort so the amount of feedback is dependent on your work.

Use efficient coding practices and follow the coding style guide (e.g.,
the `{tidyverse}`) that we have been using in the activities to produce
the desired output.

Along with showing the steps you took to solve the problem, *you must
explain your reasoning* in clear and logical terms. **Your mark will be
based on the quality of your reasoning, not only the correctness of your
answer.** These should be written for an audience that has the same
level of statistics background as you (i.e., they have successfully
completed an introductory statistics course), but they do not have the
same level of R coding background as you. Any Learning Target with
insufficient explanation will minimally earn an **N**.

Make your explanations stand out by beginning them with
`**First Name**:`. For example, your instructor would begin all of their
explanations with `**Bradford**:`.

Make sure that you committed/pushed everything in your repository
including your `ltc01.md` file and knitted figure folder. Repos that do
not contain a `ltc01.md` file will automatically be graded as
**Incomplete** for all Learning Targets.

## ☑️ Task 1: Git-ing Started

You are welcome to create branches to help you organize your work, but
this is not an expectation. Your instructor will only look at files
contained within your `main` branch.

1.  In the root of this GitHub repository (i.e.,
    `STA518-01-SS21/ltc01-<username>`), click on the “Code” button.

-   Verify that the drop-down says **Clone with HTTPS** (this is
    *probably* the default view; otherwise, select “Use HTTPS”)
-   Click on the clipboard-icon to copy the repo URL

2.  In RStudio Server, create a new Project. You can do this by clicking
    on the ![](README-img/new-project-icon.png) icon or through the
    menus (File &gt; New Project…).

-   In the *New Project Wizard* pop-up, select **Version Control** on
    the *Create Project* screen, then select **Git** on the *Create
    Project from Version Control* screen.
-   On the *Clone Git Repository* screen, paste the URL of your GitHub
    repository from (1) into the *Repository URL* dialog box. It should
    look like: `https://github.com/STA518-01-SS21/ltc01-<username>.git`
-   The *Parent directory name* dialog box will be automatically
    populated with your repository name. It should look like:
    `ltc01-<username>.git`
-   In the *Create project as subdirectory of* dialog box, click on
    **Browse**.
-   In the *Choose Directory* pop-up, **Browse** to the class-level
    folder you created in Activity 1.2 (and possibly the `activities`
    folder) and click **Choose**.
-   Verify that the *Create project as a directory of* dialog box
    contains the folder location that you previously specified, then
    click on **Create Project**. You may be asked to login with your
    GitHub credentials on a *Clone Repository* pop-up window - provide
    your GitHub username and PAT.

3.  After a few seconds, your RStudio session will refresh and you
    should be in your newly created RStudio Project! Remember that this
    is YOUR workspace.

## ☑️ Task 2: Complete the Report

Open the `ltc01.Rmd` file from the **Files** pane (lower-right-hand
pane).

Edit the `author` YAML item to contain your preferred first and last
name.

Work through the Learning Target Check 1 report. Complete the R code
chunks that I have provided.

## ☑️ Task 3: Submit your Learning Target Check 1

Back at your Learning Target Check 1 repo, copy the address to your
repo’s root directory. It should look like
`https://github.com/STA518-01-SS21/ltc01-<username>`.

Go to the Learning Target Check 1 assignment on
[Blackboard](https://mybb.gvsu.edu). Paste your repo’s link in the
submission box as a *clickable* link.

Congratulations! You just submitted a Learning Target Check and I will
have it assessed shortly.
