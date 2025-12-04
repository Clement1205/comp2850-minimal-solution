COMP2850
HCI Portfolio Task

Privacy and Ethics Statement
•	 I confirm all participant data is anonymous (session IDs use P1_xxxx format, not real names).
•	 I confirm all screenshots are cropped/blurred to remove PII (no names, emails, student IDs visible).
•	 I confirm all participants gave informed consent.
•	I confirm that all results are real and not fabricated.
•	 I confirm this work is my own.

Name:
Date: 
Job Stories

Paste in your job stories here, in the format:
Story #X
When [situation/context],
I want [motivation/capability],
So [outcome/benefit],
Because [underlying need].
You should have 3-6 stories in total. One story may inform more than one pilot study task.

Story #1
When I have lots of assignments, deadlines or meetings to keep track of,
I want to store them in one organised place,
So I can avoid forgetting important tasks.

Story #2
When I need to recall an action I made earlier,
I want to check my previous tasks easily,
So I can remember what I planned without confusion.

Story #3
When my tasks change,
I want to edit my existing tasks,
So I can keep my task list updated.

Story #4
When I have many tasks in progress,
I want to filter them by category, name, or type,
So I can focus only on similar tasks that I want to work on right now.

Story #5
When I finish a task,
I want to delete it or mark it as done,
So I can keep my task tidy and up to date.

Story #6
When I am trying to read the tasks but the text is too small,
I want to zoom it to my own need
So I am able to see the tasks clearly.

 
Pilot Study – Planning & Consent-Gathering
This section will contain your planning of the pilot study.
Task 1
Scenario: You need to record an upcoming meeting so you don’t forget it.
Action: Add a task: “Meeting with John on Monday in Room A.”
Success Criteria: Task successfully appears in the list with no validation errors
Target Time: < 20 seconds
Linked to: Story #1

Task 2
Scenario: You previously added something but forgot what it was.
Action: Locate the previously created “meeting” task in the task list.
Success Criteria: User can scroll to and find the task and it is visible at the top
Target Time: < 10 seconds
Linked to: Story #2

Task 3
Scenario: Your plans change and your task details need updating.
Action: Edit “Buy milk” to “Buy corn flakes.”
Success Criteria: Inline edit opens, success message announced, updated results can be seen
Target Time: < 15 seconds
Linked to: Story #3

Task 4
Scenario: You have many tasks but want to view only a subgroup.
Action: Use the filter to show only the “buy” tasks.
Success Criteria: Filter displays only relevant items, count is correct
Target Time: < 20 seconds
Linked to: Story #4

Task 5
Scenario: You just bought bananas
Action: Delete "Buy Bananas" from the list
Success Criteria: User sees a confirmation message, task is removed from the list
Target Time: < 10 seconds
Linked to: Story #5

Task 6
Scenario: A user with low vision wants larger text.
Action: Zoom the interface using "Ctrl +".
Success Criteria: Text scales with layout, no overlapping
Target Time: < 20 seconds
Linked to: Story #6

Consent Script
# Peer Pilot Protocol — Week 9

## Study Overview

**Purpose**: Evaluate usability and accessibility of task list prototype with peer participants.

**Type**: Low-risk formative evaluation, peer-to-peer within module.

**Scope**:
- 5–6 participants (lab pairs)
- 4 tasks per session (~15–20 minutes)
- No audio/video recording
- No personally identifiable information collected

**Ethical approval**: Covered by module's blanket low-risk consent for peer learning activities (verified with module leader).

**Data retention**: Anonymised logs stored in private repo for academic year, deleted after module assessment complete.

---

## Participant Requirements

**Inclusion**:
- Enrolled in COMP2850
- Comfortable using web browsers
- Able to provide informed consent

**Exclusion**:
- None (module is inclusive by design)

**Accessibility accommodations**:
- Screen reader users: allowed extra time, SR-specific observations recorded separately
- Keyboard-only users: explicitly invited to test no-mouse variant
- No-JS users: at least one session conducted with JS disabled

---

## Consent Process

**Before starting** (read aloud):

> "Thanks for agreeing to pilot our prototype. This is a quick usability test—about 15 minutes. I'll ask you to complete 4 tasks while I observe and take notes. I'm testing the interface, not you, so there are no wrong answers.
>
> **What we're collecting**:
> - Task completion times (from server logs)
> - Whether you complete each task successfully
> - Errors or validation issues
> - Your confidence ratings after each task
> - My notes on any hesitations or accessibility issues
>
> **What we're NOT collecting**:
> - Your name, email, or student ID
> - Screen recordings or audio
> - Your device details beyond 'keyboard-only' or 'screen reader'
>
> I'll assign you a random session code (like `sid=X7kL9p`) which will appear in the logs. You can request that I delete all data linked to your session code at any time, even after today.
>
> **You can stop at any time**, no questions asked, and it won't affect your grade.
>
> Do you have any questions before we start?"

**Verbal consent**: "Are you happy to proceed?"

Record in `wk09/lab-wk9/research/consent-log.md`:


Participant Consent
Participant Number	Read consent script to the participant?	Date and time that consent was given:
EXAMPLE	X	20/11/2025 11:15
P1		X   04/12/2025 16:45
P2		X   04/12/2025 21:48

 
Participant 1
Details of Participant:
How did this user access the webapp? Keyboard + Mouse

Notes:
Task 1 — 10:57  |  “Would like notifications to be clearer”
Task 2 — 03:23  |  “Easy unless there are many tasks”
Task 3 — 09:73  |  “Inline edit was easy”
Task 4 — 12:02  |  “Notification was useful”
Task 5 — 07:15  |  “Confirmation helped”
Task 6 — 15:18  |  “Zoom shortcut familiar and useful”

Metrics:
ts_iso,session_id,request_id,task_code,step,outcome,ms,http_status,js_mode
2025-12-04T16:48:53.695557Z,b7975e,r_eef83b7f,T0_list,success,,137,200,off
2025-12-04T16:49:08.253793Z,b7975e,r_62fc2a36,T3_add,success,,34,200,on
2025-12-04T16:51:05.470305Z,b7975e,r_63d40035,T1_filter,success,,30,200,on
2025-12-04T16:51:05.944124Z,b7975e,r_a6fb421d,T1_filter,success,,7,200,on
2025-12-04T16:51:07.659613Z,b7975e,r_b56ec052,T1_filter,success,,9,200,on
2025-12-04T16:51:08.261787Z,b7975e,r_6d4c7757,T1_filter,success,,9,200,on
2025-12-04T16:51:10.090835Z,b7975e,r_13817116,T1_filter,success,,6,200,on
2025-12-04T16:51:50.199609Z,b7975e,r_59b08915,T4_delete,success,,7,200,on


Participant 2
Details of Participant:
How did this user access the webapp? Keyboard + Mouse + No-JS

Notes:
Task 1 — 13:30  |  “Better if have a more visible notification”
Task 2 — 05:67  |  “Cannot see on top left corner, but can see it when scroll to the bottom”
Task 3 — FAIL   |  “Cannot edit as the webpage refreshes and nothing happened”
Task 4 — 09:44  |  “Notification was useful”
Task 5 — 07:82  |  “No confirmation message showed, would be better if it did”
Task 6 — 15:16  |  “Able to zoom with shortcuts”

Metrics:
2025-12-04T21:52:31.252001Z,b7975e,r_5eb8e3e1,T3_add,success,,65,200,off
2025-12-04T21:52:31.279235Z,b7975e,r_8bed19c9,T0_list,success,,14,200,off
2025-12-04T21:54:43.841924Z,b7975e,r_a091fc84,T0_list,success,,24,200,off
2025-12-04T21:54:49.463697Z,b7975e,r_150c4cbc,T0_list,success,,15,200,off
2025-12-04T21:54:52.259532Z,b7975e,r_43e9a6f7,T0_list,success,,13,200,off
2025-12-04T21:54:56.963408Z,b7975e,r_554d036d,T0_list,success,,14,200,off
2025-12-04T21:55:38.001539Z,b7975e,r_c5ee4664,T0_list,success,,18,200,off
2025-12-04T21:56:26.525748Z,b7975e,r_d684a801,T4_delete,success,,21,200,off
2025-12-04T21:56:26.543164Z,b7975e,r_a974aa86,T0_list,success,,9,200,off

 
Metrics Breakdown
Task	Target Time	Mean Time	Median Time	Range of Times	Target - Mean
EXAMPLE TASK    < 10	12.7	9.3	        7.6 – 17.3	    -2.7
1       < 20        11.935      11.935      10.57 - 13.30   -8.065
2       < 10        04.45       04.45       03:23 - 05:67   -5.55
3       < 15        12.365      12.365      09.73 - FAIL    -0.135
4       < 10        10.73       10.73       09.44 - 12.02   -2.635
5       < 10        7.485       7.485       07.15 - 07.82   -2.515
6       < 20        15.17       15.17       15.16 - 15.18   -4.83




Reflection / Initial Thoughts
Use this space to informally discuss your results, both qualitative and quantitative, and any initial trends which you spotted.
Example:
Although mouse, keyboard and screen users were able to consistently complete tasks in under the target time, keyboard-only users found it more challenging due to having to move backwards and forwards on the page, leading to significantly higher times for all tasks. 
Findings
You will now formalise your thoughts, reflections and data gathered from your pilot study into some findings which should be single issues with the site which you have identified from your evidence.
Finding	Source	Observation	WCAG	Impact
(1-5)	Inclusion
(1-5)	Effort
(1-5)	Priority
(Im + In – E)
EXAMPLE
Screen reader – errors not announced	metrics.csv L47-49 + P2 notes 14:23	P2: “I didn’t hear any error”	3.3.1 Level A	5	5	3	7

Finding 1: Inline Edit Does Not Work in No-JS Mode
Source: Participant 2, Task 3 (“FAIL… page refreshes and nothing happened”).
WCAG: 3.3.1 Error Identification (A), 2.1.1 Keyboard Accessible (A), 1.3.1 Info & Relationships (A).
Impact: Very high — core task fails entirely.
Inclusion: High — excludes no-JS users.
Effort: Medium.
Priority Score: 5 + 5 − 3 = 7 (High priority)

Finding 2 — Status Messages Are Not Very Visible
Source: Both participants, Task 1 (“would like notification to be more clear”, “better if more visible”).
WCAG: 4.1.3 Status Messages (AA).
Impact: Medium — users complete task but experience uncertainty.
Inclusion: Medium — especially affects low-vision users.
Effort: Low.
Priority Score: 3 + 4 − 2 = 5

Finding 3 — No Visible Delete Confirmation in No-JS Mode
Source: Participant 2 Task 5 (“better if there is a confirmation message”).
WCAG: 3.3.1 Error Identification / User Awareness
Impact: Medium — destructive action happens silently.
Inclusion: Medium.
Effort: Low.
Priority Score: 3 + 3 − 2 = 4

/Citation: These findings are formatted by ChatGPT/

Fixes To Implement
In this section you will select and explain up to three fixes you will be making based on your findings from the table.
These should be high priority findings, particularly those with WCAG Level A issues.
Fix 1
Finding: [the finding from the table above]
Explanation: [explain what the current issue is in simple terms]
Original Code: [paste/screenshot the code which you believe caused this error]
Fix: [Explain how you fixed this issue or explain what you did if you cannot work out how to fix the issue in a reasonable amount of time]
Final Code: [paste/screenshot the final, edited code of your fix – if you used generative AI to support your coding you should acknowledge that here.]

Fix 2
Finding: [the finding from the table above]
Explanation: [explain what the current issue is in simple terms]
Original Code: [paste/screenshot the code which you believe caused this error]
Fix: [Explain how you fixed this issue or explain what you did if you cannot work out how to fix the issue in a reasonable amount of time]
Final Code: [paste/screenshot the final, edited code of your fix – if you used generative AI to support your coding you should acknowledge that here.]

Fix 3
Finding: [the finding from the table above]
Explanation: [explain what the current issue is in simple terms]
Original Code: [paste/screenshot the code which you believe caused this error]
Fix: [Explain how you fixed this issue or explain what you did if you cannot work out how to fix the issue in a reasonable amount of time]
Final Code: [paste/screenshot the final, edited code of your fix – if you used generative AI to support your coding you should acknowledge that here.]
WCAG Checklist
Once you have made your code changes and tested the site yourself, you should work through the WCAG checklist below, recording whether your app passes or fails, with a note stating why.
Be honest – if you have not met a criterion, you can explain why in the next section.
Check	Criterion	Level	Pass/Fail?	Notes
Keyboard
K1	2.1.1 All actions keyboard accessible	A	[pass/fail]	e.g., “Tested Tab/Enter on all buttons”
K2	2.4.7 Focus visible	AA	[pass/fail]
K3	No keyboard traps	A	[pass/fail]
K4	Logical tab order	A	[pass/fail]
K5	Skip links present	AA	[pass/fail/n/a]
Forms
F1	3.3.2 Labels present	A	[pass/fail]
F2	3.3.1 Errors identified	A	[pass/fail]
F3	4.1.2 Name/role/value	A	[pass/fail]
Dynamic Content
D1	4.1.3 Status messages	AA	[pass/fail]
D2	Live regions work	AA	[pass/fail]
D3	Focus management	A	[pass/fail]
No-JS
V1	1.4.3 Contrast minimum	AA	[pass/fail]
V2	1.4.4 Resize text	AA	[pass/fail]
V3	1.4.11 Non-text contrast	AA	[pass/fail]
Semantic
S1	1.3.1 Headings hierarchy	A	[pass/fail]
S2	2.4.1 Bypass blocks	A	[pass/fail]
S3	1.1.1 Alt text	A	[pass/fail]	
 

Any Missing Criteria
If you did not meet any criteria, please note the number of the criteria (e.g. K2) and a brief (1-2 sentence) explanation of how you are not currently meeting it and a quick explanation of how you could address this.
Example with an alternative WCAG criterion:
E7 Error Suggestion – At present, when you try and edit a priority to a non-numerical value it gives an error but does not clarify how to meet the validation check. I could change this by giving more details in the alert such as ‘This must be a positive number’.
 
Second Pilot
You will re-run your pilot with 1-2 participants in order to evidence whether your changes improved the site.
Participant Consent
Participant Number	Read consent script to the participant?	Date and time that consent was given:
P1		
P2		
(Add or remove rows as needed)

Participant 1
Details of Participant:
How did this user access the webapp? Keyboard/Mouse/Screenreader/No-JS etc.

Notes:
Copy here, or link the location of this participant’s pilot study notes

Metrics:
Copy here from metrics.csv, or link to the location of this participant’s pilot study log.

Participant 2
Details of Participant:
How did this user access the webapp? Keyboard/Mouse/Screenreader/No-JS etc.

Notes:
Copy here, or link the location of this participant’s pilot study notes

Metrics:
Copy here from metrics.csv, or link to the location of this participant’s pilot study log.

Metrics Breakdown – Study 2
Task	Target Time	Mean Time	Median Time	Range of Times	Target - Mean






Original Study Metrics
-copy and paste your filled metrics table from your first pilot study here for comparison -


Comparison to Original Pilot Study
Compare the results of this re-pilot to your original – did your fixes resolve the issues? Use both qualitative and quantitative data to support your argument

Conclusion
Explain one full evidence chain by filling out the following table for one finding from your initial pilot study which you implemented a fix for.
Section

Explanation	Your evidence
Raw data

The line from the metrics file where you saw the issue
Observation

What did your pilot study participant say about it?
Screenshot of the issue

Both the code and the webapp if possible
WCAG?

If this error aligns to a certain WCAG criterion note that here	
 
Prioritisation

What priority was the issue calculated at?
Fix implemented

Screenshot of the fix which you completed (or attempted). 	
Verification

How do you know it was fixed?
Before/After improvement

Re-pilot outcome

The data from your re-pilot study showing the improvement working.	
