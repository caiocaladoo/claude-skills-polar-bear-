# Claude Guide for Training Impact: 30 Claude Skills

30 Claude skills for proving what a training programme changed, from the request to the decision about what comes next. For L&D managers, L&D specialists and L&D leaders.

**Guide and download:** [90n.ai/resources/training-impact-pack](https://90n.ai/resources/training-impact-pack)

## What this is

The guide follows one programme in the order the work happens. It questions the request before anything is built (the brief, the sponsor conversation, the diagnosis, the options that are not training). It agrees what proof looks like while there is still time to capture it (the behaviours, the measures, the baseline, the data plan). It collects the evidence (two surveys, an observation checklist, an interview guide, a data request), reads it honestly (the before and after table, the comment themes, the contribution analysis) and tells the sponsor (the success cases, the return as a range, the one-pager, the early warning). Then it reports to the business (the metrics set, the quarterly report, the executive briefing, the overclaim check) and feeds the evidence back into what runs next (the review meeting, the decision record, the shortfall note, the needs update, the priority plan, the business case). The last skill hands back to the first. Each skill keeps one method or one artifact inside, with the inputs it needs, where it breaks, a fixed output template, a finish line and the next skill to run. You hold the conversations, collect the data and stand behind the figures; Claude prepares, drafts and checks. Where a skill fits a Claude surface (Claude Docs, Claude Slides, Projects, file upload), it says so, and beta features are marked beta. Nothing here connects to your LMS or your survey tool: you export, then paste or upload.

Every skill holds one line: Claude plans the evaluation and drafts the report from your data: it never invents a result, a benchmark or a quote, never claims a cause the evidence does not support, never turns evidence about a programme into a judgement of a person, and a named person stands behind every number.

```
Question the request -> Agree what proof looks like -> Collect the evidence -> Read it honestly -> Tell the sponsor -> Report to the business -> Feed it back
```

## Install

### In Claude Code

```
/plugin marketplace add polar-bear-org/claude-skills
/plugin install training-impact-pack@90n-skills
```

### In Claude.ai

1. Turn on "Code execution and file creation" under Settings > Capabilities.
2. Go to Customize > Skills, click "+", choose "+ Create skill", then "Upload a skill", and upload the skill's zip from the `install/` folder. Repeat for each skill you want.
3. On Team and Enterprise plans, an owner first enables "Cloud code execution and file creation" and "Skills" under Organization settings > Plugins & skills (Policy tab), and can upload skills for the whole organization.

## The skills

### 1 · Question the request

| Skill | What it does | When to run it |
|---|---|---|
| [Training Request Brief](skills/impact-training-request-brief/SKILL.md) | The request as it arrived, restated as a performance problem, fixed versus open list, evidence asked for, a reply that books the sponsor conversation | "We need a training by Friday" lands with the format, the audience and the date already chosen |
| [Sponsor Discovery Questions](skills/impact-sponsor-discovery-questions/SKILL.md) | Question guide for the conversation you hold, lines for when the sponsor insists on the course, notes template, follow-up message | You must ask a senior sponsor "is this a training problem?" without sounding like a refusal |
| [Performance Problem Diagnosis](skills/impact-performance-problem-diagnosis/SKILL.md) | Gap by task, cause table at role level, evidence or "assumed" per cause, a cheap check per assumed cause, how much of the gap training could close | The conversation left you unsure whether people cannot do it or are not set up to do it |
| [Non-Training Options](skills/impact-non-training-options/SKILL.md) | The decision framed with owner and deadline, three to five real options per cause, cost and owner of each, a memo the sponsor can say yes to | The cause is not a skill gap and you need to offer something better than "no" |

### 2 · Agree what proof looks like

| Skill | What it does | When to run it |
|---|---|---|
| [Critical Behaviours Map](skills/impact-critical-behaviours-map/SKILL.md) | One measurable goal, the few observable actions that would move it, why each is not happening, which ones training can change, how each would be seen at work | The sponsor says "they need to understand X" and nobody has said what people will do differently |
| [Success Measures Agreement](skills/impact-success-measures-agreement/SKILL.md) | Expected result, leading indicators, behaviours, source and owner of each figure, what "worked", "partly" and "did not" mean, reporting dates, sign-off block | The build is about to start and nobody has agreed how anyone will know it worked |
| [Training Baseline Plan](skills/impact-training-baseline-plan/SKILL.md) | Where each before figure lives, period and group, comparison group or trend line, what is missing and how to get it, what cannot be claimed later | The programme launches in three weeks and no one has captured where things stand today |
| [Kirkpatrick Data Collection Plan](skills/impact-kirkpatrick-data-plan/SKILL.md) | Measure, instrument, source, owner, date and reporting group size per level, required drivers, how deep to go for this programme | The measures are agreed and you need to know who collects what, and when |

### 3 · Collect the evidence

| Skill | What it does | When to run it |
|---|---|---|
| [Post-Training Survey](skills/impact-post-training-survey/SKILL.md) | Four to six closed items with concrete answer options, open prompts on barriers, each item tied to a measure, a pretest, a group-level summary template | The satisfaction form says everyone loved it and tells you nothing you can act on |
| [Training Follow-Up Survey](skills/impact-training-follow-up-survey/SKILL.md) | A short survey on what people used, what happened and what got in the way, send date, reminder, minimum reporting group, an invitation to volunteer for an interview | The course ended a month ago and nobody has asked whether anyone used it |
| [Behaviour Observation Checklist](skills/impact-behaviour-observation-checklist/SKILL.md) | Critical behaviours as things a person can see, three marks (seen, not seen, no occasion), no name recorded, a tally by group, what blocked the behaviour | Surveys say people use it and you want to know whether it shows up in the work |
| [Learner Interview Guide](skills/impact-learner-interview-guide/SKILL.md) | Consent script, fixed question order, probes for evidence, notes template with no names, a rule for who never sees raw notes | You have twenty minutes each with five volunteers and want more than "it was useful" |
| [Business Data Request](skills/impact-business-data-request/SKILL.md) | The exact figures per measure at group level, a short data dictionary, the message to the data owner, a log of what arrived and who vouches for it | The measure that matters sits in someone else's system |

### 4 · Read it honestly

| Skill | What it does | When to run it |
|---|---|---|
| [Before-and-After Results Table](skills/impact-before-after-results-table/SKILL.md) | Each measure before and after, group size, absolute and relative change, the comparison, what else changed, the source and who vouches, small groups suppressed | The exports are in and you need one table you could defend line by line |
| [Open Comment Themes](skills/impact-open-comment-themes/SKILL.md) | Code list, themes with comment counts, a paraphrase per theme, minority views kept, what each theme suggests changing | You have three hundred open comments and time to read thirty |
| [Training Contribution Analysis](skills/impact-training-contribution-analysis/SKILL.md) | The chain from programme to behaviour to result, evidence per link, other explanations weighed, every claim marked shown, suggested or unknown | The number moved and someone will ask how you know it was the programme |

### 5 · Tell the sponsor

| Skill | What it does | When to run it |
|---|---|---|
| [Success Case Method Write-Up](skills/impact-success-case-write-up/SKILL.md) | How cases are picked from survey answers about use, anonymous write-ups of uses that worked and uses that stalled, evidence checked, barrier list, limits of the sample | The sponsor asks "did anyone actually do anything with it?" and a score cannot answer |
| [Training ROI Range](skills/impact-training-roi-range/SKILL.md) | Chain of evidence, share credited with the isolation method named, money conversion with sources, fully loaded costs, a low and a high case, intangibles unconverted | The budget holder asks what the programme returned and finance will check the working |
| [Sponsor Impact One-Pager](skills/impact-sponsor-impact-one-pager/SKILL.md) | The answer in the first two lines, each agreed measure against what happened, what is unknown, what helped and blocked, the decision asked and by when | The sponsor has five minutes and you have forty pages of evidence |
| [Programme Early Warning Note](skills/impact-early-warning-note/SKILL.md) | The indicator that is off, the evidence, what it means for the agreed result, options with costs, the help asked for, the triggers agreed in advance | Three weeks in, attendance or use is falling and the sponsor still thinks it is going well |

### 6 · Report to the business

| Skill | What it does | When to run it |
|---|---|---|
| [L&D Metrics Set](skills/impact-ld-metrics-set/SKILL.md) | A short fixed set of efficiency, effectiveness and outcome measures, each with definition, source, owner, reader and decision, plus a stop-reporting list | Your report is hours, completions and a satisfaction score, and nobody upstairs reads it |
| [Quarterly L&D Report](skills/impact-quarterly-ld-report/SKILL.md) | One page: outcome measures against plan, programmes with evidence and its strength, what stopped, what is at risk, capacity used, decisions asked | The quarter closes and you want a report that reads like the other functions' reports |
| [Executive Impact Briefing](skills/impact-executive-impact-briefing/SKILL.md) | Five slides or two pages on one flagship programme, speaker notes, the hard questions with answers drawn only from the evidence | You have ten minutes with the executive team and one chance to be taken seriously |
| [Overclaim Check](skills/impact-overclaim-check/SKILL.md) | Every claim in a draft listed and tested, a rewrite for each weak one, what must come out | The report reads well and you are about to send it |

### 7 · Feed it back

| Skill | What it does | When to run it |
|---|---|---|
| [Evidence Review Meeting](skills/impact-evidence-review-meeting/SKILL.md) | One-hour agenda, a pre-read of one line per programme, a proposal to continue, change, stop or scale, decisions with owners and dates | Evaluation reports pile up and next year's plan looks exactly like this year's |
| [Programme Decision Record](skills/impact-programme-decision-record/SKILL.md) | The decision in the owner's words and its status, options rejected, evidence known at the time, dissent, conditions, review date and what would reopen it | The sponsor said "let's keep going" in a corridor and in six months nobody will remember why |
| [Programme Shortfall Note](skills/impact-programme-shortfall-note/SKILL.md) | What was expected, what the evidence shows, the likely reasons sorted, what stops now, what was learned for the next request | The programme did not move the measure and you would rather say so yourself than be found out |
| [Training Needs Assessment Update](skills/impact-needs-assessment-update/SKILL.md) | Needs by role and task refreshed from this cycle's evidence, what training can and cannot fix, needs dropped because they were not needs | You are planning next year from last year's wish list |
| [L&D Priority Plan](skills/impact-ld-priority-plan/SKILL.md) | Programmes ranked on criteria you set, the capacity line, a stop list with its evidence, a not-now list sponsors can see | Eight sponsors each think theirs is first and you have evidence about only three |
| [Training Business Case](skills/impact-training-business-case/SKILL.md) | The problem and its evidence, options including doing nothing, full cost, benefit as a range from your own figures or left blank, risks, measures, the ask | You need budget for the next programme and "people liked the last one" will not get it |

## How to choose a skill

```
Need to turn "we need a training" into a problem?    -> Training Request Brief
Need questions for a senior sponsor?                 -> Sponsor Discovery Questions
Need to know if it is a skill gap at all?            -> Performance Problem Diagnosis
Need something better to offer than "no"?            -> Non-Training Options
Need what people will do differently?                -> Critical Behaviours Map
Need success agreed before the build?                -> Success Measures Agreement
Need the before figures while you can still get them? -> Training Baseline Plan
Need who collects what, and when?                    -> Kirkpatrick Data Collection Plan
Need an end-of-course form you can act on?           -> Post-Training Survey
Need to ask a month later whether anyone used it?    -> Training Follow-Up Survey
Need to see whether it shows up in the work?         -> Behaviour Observation Checklist
Need more than "it was useful" from volunteers?      -> Learner Interview Guide
Need figures from someone else's system?             -> Business Data Request
Need one table you can defend line by line?          -> Before-and-After Results Table
Need to read three hundred comments?                 -> Open Comment Themes
Need to answer "how do you know it was the course"?  -> Training Contribution Analysis
Need to show how it was used, and where it stalled?  -> Success Case Method Write-Up
Need a return figure finance can rerun?              -> Training ROI Range
Need five minutes of the sponsor's attention?        -> Sponsor Impact One-Pager
Need to say early that it is going off track?        -> Programme Early Warning Note
Need measures executives will read?                  -> L&D Metrics Set
Need the quarter on one page?                        -> Quarterly L&D Report
Need ten minutes with the executive team?            -> Executive Impact Briefing
Need a last check before you send a report?          -> Overclaim Check
Need evidence to change next year's plan?            -> Evidence Review Meeting
Need the decision written down with its reasons?     -> Programme Decision Record
Need to say it did not work, in your own words?      -> Programme Shortfall Note
Need next year's needs from this year's evidence?    -> Training Needs Assessment Update
Need to rank programmes and name what stops?         -> L&D Priority Plan
Need budget for the next programme?                  -> Training Business Case
```

## Example prompts

- "Run impact-training-request-brief. Here is the email from the head of operations: they want a half-day course for all team leads before the end of the month."
- "Run impact-sponsor-discovery-questions. I have thirty minutes with the sponsor on Thursday and she has already picked the format."
- "Run impact-success-measures-agreement. The build starts in two weeks. Here are my notes from the sponsor conversation and the three behaviours we mapped."
- "Run impact-before-after-results-table. I am uploading two exports as CSV, one from before the programme and one from last month. Leave any cell blank that the files cannot fill."
- "Run impact-open-comment-themes on this survey export. Keep the minority views and remove anything that could identify a person."
- "Run impact-overclaim-check on this draft report before I send it to the sponsor."

## Quality bar

- Every figure comes from you, with its source and the person who vouches for it. A cell with no data stays blank.
- No benchmark, industry average or quote appears unless you supplied it and can name where it came from.
- Every claim is marked shown, suggested or unknown, and a report never says the programme caused a change the evidence only sits beside.
- Evidence is collected and reported for groups. No name is recorded, groups below the minimum size you set are suppressed, and nothing rates a learner, a manager or a trainer.
- Interviews and case write-ups are voluntary, with consent, and anonymous. Privacy and data protection points: check with a qualified adviser.
- Every output ends with the decision a named person makes, and by when.
- The red line: Claude plans the evaluation and drafts the report from your data: it never invents a result, a benchmark or a quote, never claims a cause the evidence does not support, never turns evidence about a programme into a judgement of a person, and a named person stands behind every number.

## Where it comes from

The sources behind each method are in `resources/evidence-and-sources.md`.

## About the makers

This pack is made by 90n ([90n.ai](https://90n.ai)): AI-native ways of working and tools for Product, Marketing and HR teams, built by ex-McKinsey founders. We map where time and money leak, redesign the work around AI and stay until your people run it themselves, and we run our own company on Claude. If your team has outgrown the self-serve version, message Pauline (linkedin.com/in/paulinebertry).

---

*Free to use inside your company, not for resale.*
