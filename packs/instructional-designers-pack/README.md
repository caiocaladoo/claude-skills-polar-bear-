# Claude for Instructional Designers: 32 Claude Skills

32 Claude skills for building one course from the request to the release, with the checks a person runs before it ships. For instructional designers, learning experience designers, e-learning developers and the L&D person who builds courses alone.

**Guide and download:** [90n.ai/resources/instructional-designers-pack](https://90n.ai/resources/instructional-designers-pack)

## What this is

The pack follows one course in the order you build it. You scope it (the brief, the learners, an action mapping session, an estimate the sponsor signs), get the content from experts (the interview, the triage of what they sent, the review plan), design it (objectives, the design document, the course map, the assessment blueprint), write it (branching scenarios, the storyboard, video scripts, questions, job aids) and build it (a practice activity to prototype in Claude, slides, a short series, a live session moved on screen). Then you check it: accuracy against the sources you approved, whether it teaches, accessibility, your own run-through, the expert round and a pilot with learners. You ship it with a sign-off record and a release note, read what the data says, and keep your own practice in order. The check group is the centre of the pack. Each skill holds one method or one artifact, with the inputs it needs, where it breaks, a fixed output template, a finish line and the next skill to run. Where a skill fits a Claude surface (Claude Docs and Claude Slides, both beta, Claude Design, artifacts, Projects), it says so, and it says what Claude does not do: the package and the tracking happen in your authoring tool and your LMS.

Every skill holds one line: Claude drafts and checks, but you decide what the learner needs, you run through the course yourself before anyone else does, and a named person signs it off; nothing invented is passed off as real, and no learner's result is ever used to grade them.

```
Scope the course -> Get the content from experts -> Design it -> Write it -> Build it -> Check it -> Ship and improve -> Your practice
```

## Install

### In Claude Code

```
/plugin marketplace add polar-bear-org/claude-skills
/plugin install instructional-designers-pack@polar-bear-skills
```

### In Claude.ai

1. Turn on "Code execution and file creation" under Settings > Capabilities.
2. Go to Customize > Skills, click "+", choose "+ Create skill", then "Upload a skill", and upload the skill's zip from the `install/` folder. Repeat for each skill you want.
3. On Team and Enterprise plans, an owner first enables "Cloud code execution and file creation" and "Skills" under Organization settings > Plugins & skills (Policy tab), and can upload skills for the whole organization.

## The skills

### 1 · Scope the course

| Skill | What it does | When to run it |
|---|---|---|
| [Course Brief](skills/isd-course-brief/SKILL.md) | The request restated as a problem, what is fixed and open, a "course, job aid or neither" line, a reply the requester can sign | "Can you just make it a course?" arrives with the format and the date already chosen |
| [Learner Analysis](skills/isd-learner-analysis/SKILL.md) | Learners by role and task, device, place and real time, each line marked evidence or assumption, five questions for real learners | The brief says "all staff" and nobody has asked who will sit in front of the screen |
| [Action Mapping Workshop](skills/isd-action-mapping-workshop/SKILL.md) | A one-hour run of show, the map (goal, actions, causes, practice, minimum information), replies to "but they need to know", the cut list | The sponsor's list is everything people should know and nothing they should do |
| [Course Estimate and Timeline](skills/isd-course-estimate/SKILL.md) | Effort by phase from your own past builds, three scope options for the date, review gates, the scope line the sponsor signs | The sponsor expects it next week "because AI writes it now" |

### 2 · Get the content from experts

| Skill | What it does | When to run it |
|---|---|---|
| [SME Interview Script](skills/isd-sme-interview-script/SKILL.md) | A pre-interview note asking for one real case, questions in three passes, a live notes sheet, the decision-point table, the follow-up message | You asked the expert for answers and got a slide deck, or pages an AI wrote |
| [Source Content Triage](skills/isd-source-content-triage/SKILL.md) | An inventory with dates, owners and conflicts, the practise, remember, look up, cut table, AI-written passages marked, a cut list the expert accepts | The source is a 147-slide deck, two manuals that disagree, and a page nobody can date |
| [Review and Sign-Off Plan](skills/isd-review-plan/SKILL.md) | Who reviews what at each gate, one named decider, rounds and dates, the change rule, the sign-off table | Six people will review the course and nobody has said who breaks a tie |

### 3 · Design it

| Skill | What it does | When to run it |
|---|---|---|
| [Measurable Learning Objectives](skills/isd-measurable-objectives/SKILL.md) | One objective per action with condition, verb and criterion, the level the job needs, the evidence each will need | The only objective on the page is "understand the policy" |
| [Course Design Document](skills/isd-course-design-document/SKILL.md) | Need, audience, strategy and practice per objective, format choices with reasons, the decisions log, the sign-off block | The sponsor sees finished screens and none of the decisions that made them |
| [Course Curriculum Map](skills/isd-course-curriculum-map/SKILL.md) | Modules and lessons in order, objective, practice and check per lesson, the gaps, the learner's path | The course grew lesson by lesson and nothing connects |
| [Assessment Blueprint](skills/isd-assessment-blueprint/SKILL.md) | Objectives by level, evidence type and number of items, where practice ends and assessment begins, what a result is used for | The quiz is written last, from whatever is on the slides |

### 4 · Write it

| Skill | What it does | When to run it |
|---|---|---|
| [Branching Scenario Script](skills/isd-branching-scenario/SKILL.md) | The setup, numbered decision nodes, options from real mistakes, consequence and feedback for each, a path map with every ending | Learners pass every screen and still freeze on the real call |
| [E-Learning Storyboard Template](skills/isd-storyboard-template/SKILL.md) | One row per screen with text, visual, narration, interaction, build note and alt text, coverage by objective, the cut list | The build starts from the expert's slides and ends as narration over bullet points |
| [Training Video Script](skills/isd-video-script/SKILL.md) | A two-column script (heard, seen), a spoken-word rewrite, the shot list, caption and transcript text | The script reads well on paper and sounds like a manual when said aloud |
| [Knowledge Check Questions](skills/isd-knowledge-check-questions/SKILL.md) | Items written to the blueprint as short decisions, distractors from real mistakes, feedback for every option, the retake rule | An AI can pass your quiz from a screenshot, so it proves nothing |
| [Job Aid Template](skills/isd-job-aid-template/SKILL.md) | A checklist, decision table or one-page flow, the mistake next to its step, where it sits in the work, who updates it | People need the answer in the middle of the task, and a module is the wrong place for it |

### 5 · Build it

| Skill | What it does | When to run it |
|---|---|---|
| [Interactive Practice Activity](skills/isd-interactive-practice/SKILL.md) | One practice activity as a Claude artifact to prototype and pilot, the spec behind it, a test log, a plain note on where it can live | You want to try a practice idea this afternoon, before anyone opens the authoring tool |
| [Course Slides Build](skills/isd-course-slides/SKILL.md) | A slide-by-slide deck from the storyboard, notes kept apart from slide text, the practice slides, an export check | Part of the course is delivered as slides, or your authoring tool starts from a deck |
| [Microlearning Series](skills/isd-microlearning-series/SKILL.md) | Short units of one action each, a retrieval prompt and a decision in each, the order and the gaps, what the series replaces | Nobody will finish the long module, and chopping it into pieces is not the answer |
| [Live Session to E-Learning Conversion](skills/isd-live-to-elearning/SKILL.md) | What the room did, what replaces each part on screen, what must stay live, the new outline, what is lost and who accepts that | "Put the workshop online" means a recording of slides |

### 6 · Check it

| Skill | What it does | When to run it |
|---|---|---|
| [AI Content Accuracy Check](skills/isd-ai-accuracy-check/SKILL.md) | Every factual claim traced to an approved source, untraced and conflicting items flagged for the expert, the expert's decision per flag | The draft reads beautifully and nobody can say where its numbers came from |
| [Does It Teach Review](skills/isd-does-it-teach-review/SKILL.md) | Per objective: shown, tried, feedback that explains; screens that tell against screens that ask; fixes for the designer to accept or reject | The course looks finished and you suspect it teaches nothing |
| [Accessibility Check](skills/isd-accessibility-check/SKILL.md) | A first pass marked pass, fail or cannot check here, the list a person must test with assistive technology, fix owners | Accessibility is found after the build, when every fix costs a rebuild |
| [Designer Run-Through](skills/isd-designer-run-through/SKILL.md) | A protocol for taking the whole course yourself as a named kind of learner, an issues log with severity, your own verdict | You built it, you reviewed it screen by screen, and you have never once taken it |
| [SME Review Round](skills/isd-sme-review-round/SKILL.md) | The brief for one round, a comment sheet by lane, comments consolidated with conflicts side by side, a change log, the reply | Comments arrive in four formats, two contradict each other, and one reopens the objectives |
| [Learner Pilot Test](skills/isd-learner-pilot-test/SKILL.md) | Who to invite by role, the "we are testing the course, not you" wording, a think-aloud script, findings by screen | The course is about to go to everyone and not one learner has tried it |

### 7 · Ship and improve

| Skill | What it does | When to run it |
|---|---|---|
| [Release Sign-Off Record](skills/isd-release-sign-off/SKILL.md) | The result of each check with its date and who ran it, open issues with owners, the decision: release, fix first, or stop | Launch is tomorrow and "it was reviewed" is the only evidence |
| [Course Release Note](skills/isd-release-note/SKILL.md) | Purpose and audience, version, what changed in the learner's terms, known limits, owner and review date, the upload note | The course goes live with a file name and nothing else |
| [Course Data Review](skills/isd-course-data-review/SKILL.md) | Questions most people miss and the option that draws them, where people leave, comments in aggregate, a ranked fix list | The report says nearly everyone completed it, and that is all anyone reads |

### 8 · Your practice

| Skill | What it does | When to run it |
|---|---|---|
| [Course Project Setup](skills/isd-course-project-setup/SKILL.md) | A setup sheet for one course in Claude: approved sources, standing instructions, what never goes in, a version naming rule | Every chat starts from zero and Claude fills the gaps with plausible detail |
| [Learning Content Style Guide](skills/isd-style-guide/SKILL.md) | Voice and reading level, terms, how feedback is worded, rules for examples, a before and after pair per rule | Three courses sound like three different organisations |
| [Portfolio Case Study](skills/isd-portfolio-case-study/SKILL.md) | The problem, your decisions and why, what you checked and changed, what Claude drafted and what you did, a confidentiality check | Your portfolio is screenshots, and the decisions behind them are what make you worth hiring |

## How to choose a skill

```
Need to answer "just make it a course"?            -> Course Brief
Need to know who will actually take it?            -> Learner Analysis
Need the sponsor to move from know to do?          -> Action Mapping Workshop
Need an estimate the sponsor will sign?            -> Course Estimate and Timeline
Need a real case from the expert, not slides?      -> SME Interview Script
Need to sort a pile of source material?            -> Source Content Triage
Need to say who reviews what and who decides?      -> Review and Sign-Off Plan
Need to replace "understand the policy"?           -> Measurable Learning Objectives
Need the design decisions signed before the build? -> Course Design Document
Need the lessons to connect?                       -> Course Curriculum Map
Need the checks planned before the content?        -> Assessment Blueprint
Need decision practice with consequences?          -> Branching Scenario Script
Need the course screen by screen?                  -> E-Learning Storyboard Template
Need a script that works when spoken?              -> Training Video Script
Need questions that ask for a decision?            -> Knowledge Check Questions
Need the answer available mid-task?                -> Job Aid Template
Need to try a practice idea today?                 -> Interactive Practice Activity
Need a deck from the storyboard?                   -> Course Slides Build
Need a short series instead of a long module?      -> Microlearning Series
Need to move a workshop on screen?                 -> Live Session to E-Learning Conversion
Need every fact traced to a source?                -> AI Content Accuracy Check
Need to know whether it teaches?                   -> Does It Teach Review
Need a first accessibility pass?                   -> Accessibility Check
Need to take the course yourself, properly?        -> Designer Run-Through
Need one review round under control?               -> SME Review Round
Need real learners to try it first?                -> Learner Pilot Test
Need a release decision on record?                 -> Release Sign-Off Record
Need to tell people what changed?                  -> Course Release Note
Need to read the data beyond completion?           -> Course Data Review
Need Claude to work from your sources only?        -> Course Project Setup
Need every course to sound like one team?          -> Learning Content Style Guide
Need a portfolio that shows decisions?             -> Portfolio Case Study
```

## Example prompts

- "Run isd-course-brief. Here is the email asking for a 30-minute course by the end of the month. Restate it as a problem and draft the reply I can send."
- "The expert sent 147 slides and two manuals that disagree. Run isd-source-content-triage and show me the conflicts before anything else."
- "Run isd-ai-accuracy-check on this storyboard against the three sources attached. Flag what you cannot trace. Do not correct anything."
- "The course looks finished. Run isd-does-it-teach-review against these objectives and tell me which ones are never practised."
- "I am about to send the build to reviewers. Run isd-designer-run-through: I will take it as a new starter on a phone, and you sort my notes."
- "Here is the export from our LMS. Run isd-course-data-review and show me which questions most people miss, by question, with no names."

## Quality bar

- **One method or one artifact, applied properly.** Each skill uses the real mechanics of its method (the gates, the passes, the grid, the questions asked at each step), not a generic "gather, analyse, recommend".
- **It tells you where it breaks.** Every skill says when not to use it and which skill in the pack fits instead.
- **Same shape every time.** A fixed output template, a short "done when" check, and a decision that a named person makes.
- **Flag, never fix, on facts.** Claude lists what it cannot trace to a source you approved. The expert corrects it. Cases and characters are marked real or fictional.
- **Courses are checked, people are not.** Results are read by question and in aggregate to fix the course. Nothing grades, ranks, scores or profiles a learner, a reviewer or an expert.
- **Exact about Claude.** Skills name a Claude surface only where it helps, and say plainly that nothing here exports a standard e-learning package or reports to an LMS. Legal and accessibility-law questions end with "check with a qualified adviser".
- **The red line:** Claude drafts and checks, but you decide what the learner needs, you run through the course yourself before anyone else does, and a named person signs it off; nothing invented is passed off as real, and no learner's result is ever used to grade them.

## Where it comes from

The sources behind each method are in `resources/evidence-and-sources.md`.

## About the makers

This pack is made by 90n ([90n.ai](https://90n.ai)): AI-native ways of working and tools for Product, Marketing and HR teams, built by ex-McKinsey founders. We map where time and money leak, redesign the work around AI and stay until your people run it themselves, and we run our own company on Claude. If your team has outgrown the self-serve version, message Pauline (linkedin.com/in/paulinebertry).

---

*Free to use inside your company, not for resale.*
