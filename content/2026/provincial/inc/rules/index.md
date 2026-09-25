+++
title = 'INC Contest Rules'
date = '2026-08-02T00:00:00+07:00'
weight = 31

[params]
menuTitle = 'Rules'
+++


INC 2026 will be divided into two groups: {{< text/color "red" >}}**General group**{{< /text/color >}} and {{< text/color "red" >}}**Supplementary group**{{< /text/color >}}.

All teams have to be registered by the coach (following the ICPC rules) to the registration site (provided by the committee).
Universities that register 10 or fewer teams will have all their teams placed under the General group.
A university that sends more than 10 teams has to **choose 1 to 10 teams** to participate under the General group, and the remaining teams will participate under the Supplementary group.

{{< text/underline >}}Both groups will compete under the same contest and have the same problemset{{< /text/underline >}}, but prizes and advancement rules are different and will be detailed in the [INC Advancement](../advancement) page.

INC 2026 is a {{< text/color "red" >}}**closed-book contest**{{< /text/color >}}.


### Contest Time

The teams will compete to solve the given problems (typically 10 to 13 problems) in 5 hours of contest time.

Each problem has the following components:

  * Problem description — the description will be given in English.
  * Input specification — details on the input format, including the input constraint.
  * Output specification — details on the output format.
  * Sample input/output — an explanation for the samples might be provided, optionally.

Each problem has a time-limit and memory-limit constraint for its solution, i.e. the solution should run within the allowed time-limit and memory-limit to produce the correct output.
The time limit and memory limit can be seen in the Problemset tab within DOMjudge, the contest platform.

You may find the problems from the previous INC as examples in [TLX](https://tlx.toki.id/problems/problemsets?archive=inc).

During the contest, teams may ask for clarifications about the problems using the DOMjudge.
If the judges agree that an ambiguity or error exists, a clarification will be issued to all teams.
Clarification will always be open during the contest time.


### Solutions/Submissions

Each team should submit their solution (source code) through the contest management system (DOMjudge) anytime during the contest time.

A problem is considered solved by the team if a verdict of "{{< text/verdict correct >}}" is given to the corresponding submission by DOMjudge.

Each submission may get one of these responses from DOMjudge:

  * **{{< text/verdict CORRECT >}}** – the solution produced the correct output within the time and memory limit without any error. The corresponding problem is considered solved.
  * **{{< text/verdict WRONG-ANSWER >}}** – the solution did not produce the correct output.
  * **{{< text/verdict RUN-ERROR >}}** – the solution crashed (runtime-error) when processing the test data or the solution consumed more memory than the allowed memory limit for the problem (Memory Limit Exceeded).
  * **{{< text/verdict TIME-LIMIT >}}** – the solution took more time to produce the output than the allowed time limit for that problem.
  * **{{< text/verdict NO-OUTPUT >}}** – the solution produced no output.
  * **{{< text/verdict COMPILER-ERROR >}}** – the solution could not be compiled.

No other details will be given to each response.


### User Account & Contest Area

Each team will receive three different **user accounts**; one for each team member.
All accounts are connected to one team account.
Each team member is responsible for their own user account.
DO NOT SHARE YOUR USER ACCOUNT TO OTHER PEOPLE, even to your own team member and coach.

{{< text/underline >}}Each team member is allowed to use one computer with a single monitor{{< /text/underline >}} to access the contest platform through their own user account.
Make sure that one user account is only accessed by one computer.

We encourage teams to work in a single **contest area**, but a team is allowed to work in multiple contest areas.
However, communication between contest areas is not allowed and each contest area must provide a recording (see [Proctoring Rules](#proctoring-rules) section).

The following are allowed in a contest area.
  * Team members and their computers used for the competition, limited to 1 device per team member.
  * Blank papers/graph papers (at most 10 sheets per team member).
  * Stationeries.
  * Plush doll/stuffed animal.
  * Snacks, drinks, and meals.

The following are NOT allowed in the contest area:

  * Physical references, books, hard copy of TRD.
  * Any additional computer devices, including phones, smartphones, smart watches,calculators, etc.
  * Bags, purses, stationery cases.
  * People other than the participating team members.


{{< figure src="contrabands.png" width="500px" class="figure d-block text-center" >}}

{{< text/span class="d-block text-center small" >}}
  Fig 1. Example of INVALID contest area due to having bags, smart watches, smartphone, and a hard-copy of TRD on the table.
{{< /text/span >}}


### Proctoring Rules

{{< text/underline >}}All teams in the **General group** must comply with the following proctoring rules{{< /text/underline >}}.
Teams in the Supplementary group should perform the following proctoring rules if they want to appeal to the judge after the contest (see [Disqualification & Appeal](#disqualification--appeal) section).

**Each computer** must follow the following proctoring procedure during the entirety of the contest.

  * The only apps allowed during contest time are:
    * One window of browser, which **can only open** the contest platform and references (see [References](#references) section). Browsing is NOT allowed. Any form of generative AI integrated with the browser is NOT allowed.
    * One window of code editor, **without any form of generative AI** integrated with the code editor.
    * One window (and one tab) of command prompt/terminal that can only be used to compile/run codes written during contest time.
    * One window of screen recording apps, e.g., OBS.

  * All activities performed in the computer must be recorded through screen recording in full screen. These activities include but not limited to:
    * Any activities within the contest platform (reading the problems, submitting solutions, sending clarifications, etc.).
    * Any activities with the soft copy of team reference document (TRD) that has been submitted (see [References](#references) section), including copying from TRD.
    * Any activities within the code editor, including pasting from TRD; and
    * Any activities within the command prompt/terminal.

  * The taskbar should be included in the recording. It should display all running apps as well as the current date and time.

  * Any kind of communication apps is NOT allowed. Teams are encouraged to work from the same contest area.

An example of a valid screen recording layout can be seen in Fig 2.

{{< figure src="recording-layout-1.png" width="500px" class="figure d-block text-center" >}}
{{< figure src="recording-layout-2.png" width="500px" class="figure d-block text-center" >}}
{{< figure src="recording-layout-3.png" width="500px" class="figure d-block text-center" >}}

{{< text/span class="d-block text-center small" >}}
  Fig 2. Screen Recording Layout
{{< /text/span >}}

Teams are encouraged to work from the same contest area.
However, {{< text/underline >}}it is allowed for teams to work from multiple contest areas{{< /text/underline >}}.
**Each contest area** must have a recording of the whole area during the entirety of the contest.
As examples:

  * If a team works from the same contest area, they should upload 4 videos: 1 contest area recording and 3 screen recordings.
  * If a team works from three contest areas (one contest area for one team member), they should upload 6 videos: 3 contest area recordings and 3 screen recordings.

All team members in the contest area as well as their belongings must be visible through the recording, as shown in Fig 3.

{{< figure src="workstation-layout.png" width="500px" class="figure d-block text-center" >}}

{{< text/span class="d-block text-center small" >}}
  Fig 3. Example of contest area layout.
{{< /text/span >}}

Both screen recordings and contest area recordings must be made during the entire of the contest.
Then, the recordings must be uploaded to any online storage service or video sharing service.
The resolution must be 720p or 1080p, and the framerate must be 30 fps or 60 fps.

{{< text/underline >}}Teams must submit the URLs of all recordings through the DOMjudge clarification system within 24 hours after INC 2026 is finished{{< /text/underline >}}.
All recordings must be accessible by the judges through the URLs (do not set the recordings to private).


### References

This contest is a {{< text/color "red" >}}closed-book contest{{< /text/color >}}.
Teams can only access references such as:

  * Soft Copy of Team Reference Documents (TRD)
    * It contains up to 25 pages of reference materials.
    * It must have your team name and university name on the first page.
    * All texts and illustrations must be readable by a person with correctable eyesight without magnification from a distance of 0.5 meter.
    * The file must be a read-only PDF.
    * **You must submit your team's TRD** through the following [form](https://forms.gle/EL1dmEYaQWWFBLvm8) before **October 22, 2026**. During the contest, you can only access the same version of TRD that you submitted.
  * Official Programming Language References, which will be given inside the contest platform. You are NOT allowed to open other language references.

The action of copying codes from the references and pasting it to your editor must exist in your screen recording.


### Disqualification & Appeal

A team will be {{< text/color "red" >}}**disqualified**{{< /text/color >}} if the team is found to be cheating.
Cheating includes any attempt or activity by an individual, group, team members, and/or coach, to enhance or diminish their performance or that of other teams using methods that are unfair to the contest.
This includes but is not limited to efforts such as:

  * any usage of generative AI;
  * communication with {{< text/underline >}}**any people**{{< /text/underline >}} other than team members and the judges (through the clarification system) during the contest;
  * hacking (successful or not) the contest management system.

Teams in the General group will be {{< text/color "red" >}}**disqualified**{{< /text/color >}} if they do not follow the proctoring rules.
Disqualified teams in the Supplementary group can appeal to the judges only if they have followed the proctoring rules.

All teams should uphold the sportsmanship and the spirit of fair competition.


### Ranks

Teams are ranked according to:

  1. Most number of problems solved.
  1. If (1) tied, then least TOTAL TIME.
  1. If (1) and (2) are tied, then the earliest time of submission of the last accepted problem.

The total time is the sum of the time consumed for each solved problem (in minutes).
The time consumed for a solved problem is the time elapsed from the beginning of the contest to the submission of the first correct solution plus 20 penalty minutes for every previously incorrect solution for that problem.
{{< text/underline >}}Submissions with a **{{< text/verdict COMPILER-ERROR >}}** verdict will not be penalized{{< /text/underline >}}.
<!-- TODO: change this -->


### Pre-Contest

Teams are not required to attend the practice session.
However, the committee encourages teams to participate to become familiar with the contest environment.
Teams access DOMJudge for INC 2026 through their self-prepared computer with internet access.
The information regarding DOMjudge will be sent before the practice session.
If the team still has not received any email during the practice session, please contact us at [lombati@binus.edu](mailto:lombati@binus.edu).


### Frequently Asked Questions (FAQs)

  * Will there be a scoreboard freeze?
    * No.
  * If a team's network connection is interrupted, can the team rejoin the contest?
    * Yes, but there will be no extra time.
  * Can a team member leave the workstation for a short break, e.g., go to the bathroom?
    * Yes.
  * Can a team member stop the recording if they no longer work on the contest?
    * Yes, but **the whole team** is considered finished with the contest. Do not perform any further submission.
  * Can a team use more than one computer?
    * Yes, however each computer must follow the proctoring rules.
    * One team member can only use one computer.
  * Can a team use only one computer, i.e., similar to an on-site ICPC contest?
    * Yes, but this computer must be the only computer device used. Note that the problemset can only be accessed inside the contest and you do not have access to the hard copy of the problemset, unlike on-site ICPC contests.
    * You only need to submit one screen recording if this is the case.
  * Can a team work separately without gathering in the same place?
    * Yes, however any form of online communication between team members is not allowed.
    * Each contest area must provide their own recording. For example, three team members working on three contest areas should provide six recordings in total: one for each screen recording and one for each contest area recording.
  * Can teams from the General group appeal to the judges if they are disqualified?
    * Yes, but the final decision is made by the judges.
  * What if prohibited apps/browser tabs are accidentally opened?
    * Immediately close the apps/browser tab.
    * The final decision whether the action is accidental or not is made by the judges.
  * Can we use calculator apps or spreadsheets?
    * No. You cannot use your browser as a calculator as well.
    * Physical calculator is also not allowed.
  * Are online compilers allowed?
    * No.
