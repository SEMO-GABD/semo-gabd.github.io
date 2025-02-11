
<!--
NOTE to MST: Have you create a team for the year and add students to the
team, then give team access to this repo for it to work.
-->

This is the course outline and schedule for the 2020 Summer course
Graphical Analysis of Biological Data (BI 485 / 685).

The official syllabus and grades are on the [course Moodle
page.](https://learning.semo.edu)

The structure of course is based on the content of the
[original](http://stat545.com) and
[current](http://stat545.com/Classroom/) versions of Stat545A offered at
the University of British Columbia, and [other
courses](http://socviz.github.io/soc880/) courses with [similar
content.](http://uc-r.github.io/data_wrangling) Our course includes
considerable material developed in full or in part by [Dr. Jenny
Bryan](https://github.com/jennybc). I am grateful to her and all of the
other people who developed the original content. I have modified it as
necessary to suit the needs of our
course.

## Quick Navigation

| Tool + Link                                                                            | Description                                                                                                                                                         |
| :------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <http://gabd.semo.edu> (here)                                                          | The course “home” and your launch pad to other destinations. Contains notes, assignments, and course information.                                                   |
| [Assignments](https://semo-gabd.github.io/assignments)                                 | Info for assignments, notes, and other activities can be found here.                                                                                                |
| [Public Discussion](https://github.com/SEMO-GABD/public_discussion) GitHub repository. | For public discussion. The world can see this. Click the “Watch” button to be notified when someone posts here.                                                     |
| [GABD Students](https://github.com/gabd-students/) Organization                        | Contain one GitHub repository per student, for you to submit homework. Go to your repo and click the “Watch” button to be notified when your instructor posts here. |
| [Moodle](http://learning.semo.edu/)                                                    | This is for grade management and the official syllabus.                                                                                                             |
| [Resources](https://semo-gabd.github.io/resources)                                     | A page of external resources that you may find helpful during the course and beyond.                                                                                |

<!-- Goes above Public Discussion
| [Internal Discussion](https://github.com/SEMO-GABD/internal_discussion/) GitHub repository | For internal discussion. The world cannot see this. Apparently, neither can you. Click the "Watch" button to be notified when someone posts here.|
-->

## About the course

Graphical Analysis of Biological Data will teach you how to

  - explore, groom, and visualize data;
  - make all of that reproducible, reusable, and shareable;
  - use R, RStudio, and the “Tidyverse” to accomplish these tasks; and
  - use basic Git functions to maintain your code and data.

This course is built on and emphasizes [open
access](https://en.wikipedia.org/wiki/Open_access) to data, analysis,
and reproducible results.

**Credits:** 3

## Learning outcomes

By the end of this course, you will be able to write code in
[R](http://www.r-project.org) and [RStudio
IDE](http://www.rstudio.com/products/rstudio/) to

1.  create and manipulate basic R data structures,
2.  import data from a variety of sources,
3.  wrangle data into format suitable for efficient analysis.
4.  display data using appropriate graphical techniques, such as
    boxplots, histograms, and Cleveland plots with
    [ggplot2](http://ggplot2.org);
5.  create reports with reproducible analyses using [R
    Markdown](http://rmarkdown.rstudio.com); and
6.  manage your data and R scripts via the Git version control system.

## Prerequisites

You must have completed BI 283 or have the permission of the instructor.

## Textbook

We will use [R for Data Science](http://r4ds.had.co.nz) by [Hadley
Wickham](https://twitter.com/hadleywickham) and [Garrett
Grolemund](https://twitter.com/statgarrett) (hereafter, R4ds) as a
tutorial for some readings and a source of assignment questions. The
text is freely available online. Other open-source resources may be used
as needed.

## Assignments and Notes

Assignments will consist of readings from notes provided by the
instructor, readings and questions to answer from
[R4ds](https://r4ds.had.co.nz), and exercise sets for you to develop and
practice your R scripting skills. In some cases, notes and assignments
will be provided separately. In other cases, they will be provided
together.

You will have three assignments per week for the first three weeks, and
two assignments on the final week. Assignments are due two days after
they are assigned (e.g., assignments given on Tuesday are due on
Thursday) by 23:55. Most assignments will take several hours to
complete, including reading and coding time. Start each assignment as
soon as possible so that you have plenty of time to ask questions, solve
problems, and complete the assignment before it is due. If you start an
assignment too late, you will run out of time.

I will *probably* release all three assignments for each week on Sunday.
You may work ahead but you may not work behind. For example, a “Tuesday”
assignment released on Sunday evening is officially assigned on Tuesday
and due on Thursday. You can submit it before Thursday but not after.

The [Assignments](https://semo-gabd.github.io/assignments) page has all
assignments as they become available.

## Expectations

#### Reality Check For You

A regular semester is 15 weeks long, not counting final exams. During
that time, a 3 credit hour course will have 37.5 hours of class time.
The university expects two hours of additional work by the student for
each hour of class time. That is another 75 hours, for a a total 112.5
hours. This summer course is only 39 *days,* including weekends. Thus,
to meet the requirements for a regular semester, you will need to
average about 2.8 hours of work per day. Some exercises will not need
all that time. Others might need more, depending on how fast you work.

Be realistic. You have a lot of learning to do in the coming six weeks.
Odds are, you will be learning a new skill set in an unfamiliar setting.
You will have many exercises to complete that will drill those skills
into your fingers and your brain. The exercises will go slowly at first
but you will get faster with practice. Do not cheat yourself by copying
and pasting. You will not learn the skills and you will begin to
struggle.

#### Reality Check For Me

This is the second time I have taught this course. I have smoothed out
some bumps from the first time but I still expect glitches. Please let
me know as soon as possible of any problems you have so that I can fix
them quickly.

I continue to work hard behind the scenes to make this a good course. I
expect that you will work hard to get the most from this course. The
skills you will learn are real and valued by employers and graduate
schools.

## Assessment

You earn your grade in this course by completing all assignments (11 at
the moment but that may change as I rearrange assignments from a 4-week
to 6-week format). All assignments will given given by me and submitted
by you via GitHub. **You must have a free GitHub account.** You should
also have [filled out and submitted this
form.](http://bi163.shinyapps.io/485info/)

Here’s the breakdown of your course
grade:

| Assessment                                                     | Weight |
| :------------------------------------------------------------- | :----- |
| Assignments ([link](https://semo-gabd.github.io/assignments/)) | 100%   |
| 0 exams                                                        | 0%     |
|                                                                |        |

## Conversations and Getting Help

Are you stuck? First, try to get unstuck by yourself by following this
advice:

  - Open an issue in the [Public
    Discussion](https://github.com/SEMO-GABD/public_discussion)
    repository and ask your question. Peer-to-peer help is a powerful
    way to share ideas and help each other. Click the “Watch” button
    near the upper right to be notified by email whenever someone,
    including your instructor, posts to this forum.

  - Search Google. [Google is your friend.](https://xkcd.com/627/) Also,
    [this.](http://bfy.tw/8NPu)

  - Search [Stackoverflow](https://stackoverflow.com). Include the `r`
    tag, the `ggplot2` tag, `dplyr` tag, `tidyverse` tag, or other tag
    as needed to limit your search.

  - You can email me. I am happy to help but I would prefer that you ask
    a question in the [Public
    Discussion](https://github.com/SEMO-GABD/public_discussion) repo so
    that your question and any answers are available to help everyone.
    Chances are, if you have the question, so do others.

  - Zoom video conference. We can use this format when necessary to
    easily share screens.

The options are sort of listed in order of preference but every
situation is different and your comfort level with these approaches will
change as you learn more.

### Basic Issue workflow

Some advice on opening an Issue on GitHub:

  - Give it a specific title.
      - BAD: “aaaaaarrrrrrgh\!”, “things not working”, “i need help”
      - GOOD: ‘error when indexing a matrix: “incorrect number of
        dimensions”’
  - Stay specific and be complete-but-concise in the body of the
    description. Don’t expect anyone (including me) to play 20 questions
    with you.
  - (Optional) Tag someone:
      - To get the attention of the instructor, add the `@instructor`
        tag to notify me.
      - To get the attention of your fellow students, add the
        `@students_2020` tag to notify them.
  - Don’t just create Issues – also respond to them\! Think about this
    in terms of adding to the conversation, not in terms of
    “correctness”.
  - Don’t forget to click “Submit new issue”\!

Typically, this will trigger an email to the person or team you tagged.
The title of your issue will be in the subject line, so I repeat, *make
it specific.* Your description will become the body of the email. At the
bottom will be a link to the issue on GitHub.

If all goes well, one or more of your colleagues will respond. I almost
always do this directly via GitHub, though simply replying to the email
basically works. In any case, this back-and-forth will show up as a
series of comments on your original issue. It’s like an email dialogue
but better:

  - It’s embedded in a relevant Organization/project/repo, so it will be
    easier to find later vs. digging out of your giant vat of unfiled
    email.
  - It’s potentially visible to others (depending on the repo), which
    could save us from asking/answering the same questions repeatedly.
  - The whole discussion will be mirrored via email, so that still
    serves as a great way to prompt participants to tune in.
  - Later you can get fancy and refer to commits and other issues within
    the repo in slick ways.

Once the problem is resolved, I will close the issue. Closed issues
remain accessible for future consultation.

## Annotated Resources

I’ve assembled a [page of
resources](https://semo-gabd.github.io/resources.html) that will help
you develop your R programming skills for years to come.
