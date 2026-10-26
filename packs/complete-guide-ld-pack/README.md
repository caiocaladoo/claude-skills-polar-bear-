# The Complete Claude Guide for L&D: 40 Claude Skills

40 Claude skills for the whole L&D job, stage by stage, from the training request to the report to executives. For L&D managers and specialists, instructional designers, trainers and facilitators, and L&D leaders.

**Guide and download:** [90n.ai/resources/complete-guide-ld-pack](https://90n.ai/resources/complete-guide-ld-pack)

## What this is

The guide follows learning and development work in the order you do it. It diagnoses the need before anything is built (the request, the performance gap, the conversation with the sponsor, the needs by role, the action map), works with the experts (the interview, the task breakdown, the review plan), designs the learning (objectives, evaluation plan, design document, curriculum map), builds and tests it (scenarios, storyboard, knowledge check, role-play, the check of an AI draft, the learner walkthrough), runs the room (session plan, group work, slides, facilitator guide, pilot, trainer preparation), carries it into work (job aid, 70-20-10 plan, spaced practice, manager briefing, onboarding), measures what changed (feedback form, use on the job, ROI estimate, the one-page report, the programme review) and leads L&D through the year (the year plan, the business case, the vendor brief, the build plan, compliance training, the team's AI rules). Each skill is one action with its named method inside, and each one points to the next.

Every skill holds one line: Claude drafts and checks, people decide: you talk to the learners, the experts and the sponsor, a named person signs off what gets built and what counts as proof, and nothing a learner does in training is used to grade, rank or build a case against them.

```
Diagnose the need -> Work with the experts -> Design the learning -> Build and test -> Run the room -> Carry it into work -> Measure what changed -> Lead L&D
```

## Install

### In Claude Code

```
/plugin marketplace add polar-bear-org/claude-skills
/plugin install complete-guide-ld-pack@polar-bear-skills
```

### In Claude.ai

1. Turn on "Code execution and file creation" under Settings > Capabilities.
2. Go to Customize > Skills, click "+", choose "+ Create skill", then "Upload a skill", and upload the skill's zip from the `install/` folder. Repeat for each skill you want.
3. On Team plans this is on by default. On Enterprise plans, an owner first enables "Code execution and file creation" and "Skills" under Organization settings > Plugins & skills (Policy tab). Owners can also provide skills to the whole organization.

## The skills

### 1 · Diagnose the need

| Skill | What it does | When to run it |
|---|---|---|
| [Question the Request](skills/ldg-question-the-request/SKILL.md) | Intake questions, the business problem in one line, an "is it training?" triage, a reply with a next step and a date | "We need a training by Friday" lands with the answer already chosen |
| [Diagnose the Performance Gap](skills/ldg-diagnose-the-gap/SKILL.md) | Desired versus actual by task, a cause table, an option per cause, a recommendation that can say "no training" | Every performance problem becomes a training request, whatever the cause |
| [Prepare the Sponsor Conversation](skills/ldg-prepare-the-sponsor-conversation/SKILL.md) | One page for the meeting: findings with evidence, the interest behind the request, options, likely objections, shared criteria, the agreement record | A course will not fix it and you have to tell the person who asked for the course |
| [Assess the Training Needs](skills/ldg-assess-the-training-needs/SKILL.md) | Needs by role and task with evidence, a priority table on your criteria, a "training cannot fix" list | You need to know what a team lacks, not collect a wish list of course titles |
| [Map the Actions](skills/ldg-map-the-actions/SKILL.md) | One measurable goal, observable actions, why they are not happening, practice per action, minimum information, a cut list for the expert's material | The sponsor wants a course and the expert sends a 147-slide deck |

### 2 · Work with the experts

| Skill | What it does | When to run it |
|---|---|---|
| [Interview the Expert](skills/ldg-interview-the-expert/SKILL.md) | Incident questions in three passes, decision points with the cue the expert noticed, common mistakes, exceptions, scenario seeds | The expert gives you the standard workflow and solves real cases by intuition |
| [Break Down the Task](skills/ldg-break-down-the-task/SKILL.md) | Task list for one role, steps, decisions and standard per task, a difficulty, importance and frequency table, a call per task | The outline follows the manual's chapters and nobody listed what people in the role do |
| [Plan the Reviews](skills/ldg-plan-the-reviews/SKILL.md) | Who reviews what at each gate, one named decider, rounds and dates, a feedback log, a change rule for late requests | Six departments review one course and the revisions never end |

### 3 · Design the learning

| Skill | What it does | When to run it |
|---|---|---|
| [Write the Objectives](skills/ldg-write-the-objectives/SKILL.md) | Objectives with an observable verb at the level the job needs, a condition and a criterion, rewrites of "awareness only" goals | The only objective on the brief is "understand the topic" |
| [Plan the Evaluation](skills/ldg-plan-the-evaluation/SKILL.md) | The result in the sponsor's words, leading indicators, behaviours with drivers and owners, learning and reaction checks, a source, owner and date per measure | Leadership sees a completion rate and nobody agreed what should change |
| [Write the Design Document](skills/ldg-write-the-design-document/SKILL.md) | Audience by role, strategy, practice and check per objective, every design decision with its rationale, what was left out, a sign-off block | Leaders think AI can do the job and nobody sees the design decisions |
| [Map the Curriculum](skills/ldg-map-the-curriculum/SKILL.md) | Modules by objective, practice, check and format, orphan modules and objectives, a simple-to-hard sequence, the learning path | A programme has grown module by module and nothing connects |

### 4 · Build and test

| Skill | What it does | When to run it |
|---|---|---|
| [Write the Scenarios](skills/ldg-write-the-scenarios/SKILL.md) | Decision scenarios built from real mistakes, options that tempt, a consequence and feedback per choice, a path map, facts listed for the expert | New hires finished every module and still cannot make the call on the job |
| [Storyboard the E-Learning](skills/ldg-storyboard-the-elearning/SKILL.md) | Screen-by-screen text, visual, narration and interaction, the objective per screen, accessibility notes, a cut list, a build brief for your authoring tool | The build starts from slides and ends as a knowledge dump with voiceover |
| [Write the Knowledge Check](skills/ldg-write-the-knowledge-check/SKILL.md) | Scenario questions per objective, distractors from real mistakes, feedback for every option, low-stakes retake rules, reporting by item only | An AI can answer your quiz from a screenshot and it proves nothing |
| [Build the Role-Play](skills/ldg-build-the-role-play/SKILL.md) | Learning points, role cards, a good and a poor model, observer notes that go only to the learner, debrief questions, each learner's own goal | People sit through role-play, go out to real customers, and you hope it stuck |
| [Check the AI Draft](skills/ldg-check-the-ai-draft/SKILL.md) | Every claim traced to an approved source or flagged, alignment row by row, five accessibility checks, a myth and bias scan, the expert sign-off record | AI drafts the course, AI reviews it, and no person checks that it teaches anything |
| [Run the Learner Walkthrough](skills/ldg-run-the-learner-walkthrough/SKILL.md) | A plan for a handful of volunteers, tasks, think-aloud prompts, an observation sheet about the draft, a ranked issue list, the fix list and the release call | The course looked right in review and the first real learner got lost on screen three |

### 5 · Run the room

| Skill | What it does | When to run it |
|---|---|---|
| [Plan the Session](skills/ldg-plan-the-session/SKILL.md) | A timed flow (open, recall, show, practise, apply), activities per block, a first five minutes on a real problem, slack shown, a transfer close | A virtual session competes with email and chat from minute one |
| [Plan the Group Work](skills/ldg-plan-the-group-work/SKILL.md) | One activity card per practice block, an opener built on the work, a virtual variant, a fallback for a quiet room | The plan says "group discussion, 20 minutes" and the opener makes people cringe |
| [Build the Training Slides](skills/ldg-build-the-training-slides/SKILL.md) | A slide-by-slide outline tied to the session blocks, one idea per slide, practice slides, what moves to a handout, speaker notes as prompts, a cut list | The deck is the SOP pasted onto slides and the trainer reads it aloud |
| [Write the Facilitator Guide](skills/ldg-write-the-facilitator-guide/SKILL.md) | Purpose, cue and key points per segment, questions with what a good answer sounds like, activity set-ups, timing flex, four what-if notes | Another trainer has to run your session without reading slides aloud |
| [Plan the Pilot](skills/ldg-plan-the-pilot/SKILL.md) | The questions the pilot must answer, a pass line written in advance, the pilot group, what is observed, the debrief, a change list, a launch, fix or stop call | The first full run is also the launch |
| [Train the Trainers](skills/ldg-train-the-trainers/SKILL.md) | Delivery learning points, a model run, a teach-back plan, practice rounds that rise in difficulty, delivery notes, a readiness conversation with no score | The programme depends on facilitators who each need to learn it first |

### 6 · Carry it into work

| Skill | What it does | When to run it |
|---|---|---|
| [Build the Job Aid](skills/ldg-build-the-job-aid/SKILL.md) | A checklist, decision table or one-page flow chosen by task shape, where it lives in the workflow, the owner, the review date | People need the answer mid-task, not a 30-minute module |
| [Build the 70-20-10 Plan](skills/ldg-build-the-70-20-10-plan/SKILL.md) | Real assignments per capability, coaching and peer learning tied to them, only the formal pieces they need, owners and check-in dates | The programme is all classroom and nothing happens back at work |
| [Space the Practice](skills/ldg-space-the-practice/SKILL.md) | Retrieval prompts built on real mistakes, 5-minute micro-units, widening gaps you set, the schedule and channel, results read by item only | People can recite it in the room and freeze on a live case a month later |
| [Brief the Managers](skills/ldg-brief-the-managers/SKILL.md) | A before and an after conversation guide, the first on-the-job task, check-in dates in existing meetings, a barrier log about conditions | Learners go back to a manager who never asks what they learned |
| [Plan the Onboarding](skills/ldg-plan-the-onboarding/SKILL.md) | A week-by-week path built on the real tasks, practice before each live task, buddy sessions, sign-off by doing the task with a person | Ramp-up takes months and stakeholders blame the talent |

### 7 · Measure what changed

| Skill | What it does | When to run it |
|---|---|---|
| [Write the Feedback Form](skills/ldg-write-the-feedback-form/SKILL.md) | Four to six items with concrete answer options, open prompts on barriers, an aggregate summary template that rates the programme | The smile sheet says everyone loved it and tells you nothing |
| [Check Use on the Job](skills/ldg-check-use-on-the-job/SKILL.md) | A short anonymous follow-up, the group-level work measures to read beside it, a guide for volunteer conversations, a barrier list, the limits of the evidence | The sponsor asks "did anyone actually do anything with it?" |
| [Estimate the Training ROI](skills/ldg-estimate-the-training-roi/SKILL.md) | The chain from application to impact, how the effect was isolated, money conversion with sources, full costs, a low and a high case | The budget holder asks what the programme returned |
| [Report What Changed](skills/ldg-report-what-changed/SKILL.md) | One page for executives, bottom line first: what changed and how sure we are, the chain of evidence, what we cannot claim, the decision asked | Leaders ask whether it improved anything and the report shows completions |
| [Review the Programme](skills/ldg-review-the-programme/SKILL.md) | Intended versus actual, why, what to keep and change, a keep, fix or retire call, the items for next year's plan | Evaluation data is filed and next year's priorities are set from the inbox |

### 8 · Lead L&D

| Skill | What it does | When to run it |
|---|---|---|
| [Plan the L&D Year](skills/ldg-plan-the-year/SKILL.md) | Programmes ranked against business goals, a capacity and budget line from your own days, a quarterly calendar, a visible not-this-year list | One person must build two programmes at once and every sponsor thinks theirs is first |
| [Make the Business Case](skills/ldg-make-the-business-case/SKILL.md) | One page in five parts, an assumptions table with low and high values and owners, what would change the answer | You must ask for budget before anything is built and the numbers are guesses |
| [Brief the Vendor](skills/ldg-brief-the-vendor/SKILL.md) | A requirements brief, must-haves against nice-to-haves, a demo script on your own content, weighted selection criteria, the decision record | The tool was chosen from a feature list and a polished demo |
| [Plan the Build](skills/ldg-plan-the-build/SKILL.md) | Phases with a deliverable, an owner and a closing decision, review gates, durations from your own projects, a scope line, the risks to the date | The brief lands Thursday and the programme is due Monday |
| [Plan the Compliance Training](skills/ldg-plan-the-compliance-training/SKILL.md) | The few decisions each rule turns on, a scenario check per decision, a spaced refresh, a record-use statement, points for a qualified adviser | Compliance training is a box to tick and the quiz record is kept against people |
| [Set the Team AI Rules](skills/ldg-set-the-team-ai-rules/SKILL.md) | A use map by task, a never-put-in list, the check a person runs before anything ships, whose name is on the work, a disclosure line per output | Half the team uses AI quietly, the other half refuses, and nobody tells learners |

## How to choose a skill

```
Need to answer "we need a training by Friday"?      -> Question the Request
Need to know if training is the fix?                -> Diagnose the Performance Gap
Need to tell the sponsor it is not a course?        -> Prepare the Sponsor Conversation
Need what a team lacks, not a wish list?            -> Assess the Training Needs
Need to get from "know" to "do", and cut the deck?  -> Map the Actions
Need the know-how out of the expert's head?         -> Interview the Expert
Need the real tasks of a role, sorted?              -> Break Down the Task
Need the review rounds to end?                      -> Plan the Reviews
Need objectives you can observe?                    -> Write the Objectives
Need to agree what should change before the build?  -> Plan the Evaluation
Need the design decisions on paper and signed?      -> Write the Design Document
Need modules that connect?                          -> Map the Curriculum
Need practice for a decision?                       -> Write the Scenarios
Need the screens before the authoring tool opens?   -> Storyboard the E-Learning
Need questions that are not trivia?                 -> Write the Knowledge Check
Need a live conversation practised safely?          -> Build the Role-Play
Need an AI-made draft checked by a person?          -> Check the AI Draft
Need real learners to try the draft?                -> Run the Learner Walkthrough
Need a timed flow with real practice?               -> Plan the Session
Need group activities that are not filler?          -> Plan the Group Work
Need slides the trainer does not read aloud?        -> Build the Training Slides
Need another trainer to run your session?           -> Write the Facilitator Guide
Need a test run before the launch?                  -> Plan the Pilot
Need facilitators ready to deliver?                 -> Train the Trainers
Need the answer in the workflow, not a course?      -> Build the Job Aid
Need learning in real assignments?                  -> Build the 70-20-10 Plan
Need it remembered a month later?                   -> Space the Practice
Need managers to do their part?                     -> Brief the Managers
Need new hires ready for the real tasks?            -> Plan the Onboarding
Need a form that says what to fix?                  -> Write the Feedback Form
Need to know if anyone used it?                     -> Check Use on the Job
Need a return figure that survives finance?         -> Estimate the Training ROI
Need one page for executives?                       -> Report What Changed
Need to decide keep, fix or retire?                 -> Review the Programme
Need a year plan and a not-this-year list?          -> Plan the L&D Year
Need budget before the build?                       -> Make the Business Case
Need to choose a provider or a tool?                -> Brief the Vendor
Need dates, owners and a scope line?                -> Plan the Build
Need mandatory training that is not a box to tick?  -> Plan the Compliance Training
Need shared rules for AI in the team?               -> Set the Team AI Rules
```

## Example prompts

- "Run ldg-question-the-request. A sales director wants a negotiation course for the whole team by the end of the month. Here is the email."
- "The gap analysis says the cause is the approval process, not skills. Run ldg-prepare-the-sponsor-conversation for my meeting with the sponsor on Thursday."
- "Here are my notes from two expert interviews. Run ldg-write-the-scenarios and build the wrong options from the mistakes they described."
- "This module was drafted with AI. Run ldg-check-the-ai-draft against the attached procedure and list every claim you cannot trace."
- "Run ldg-plan-the-pilot for the new supervisor programme. I want the pass line written before the first session."
- "Leadership asked what the onboarding redesign changed. Run ldg-report-what-changed with these figures and tell me what we cannot claim."

## Quality bar

- **One method, applied properly.** Each skill uses the real mechanics of its method (the levels, the passes, the gates, the table columns), not a generic "gather, analyse, recommend".
- **It tells you where it breaks.** Every skill says when not to use it and which skill in the guide fits instead.
- **Same shape every time.** A fixed output template, a short "done when" check, and a decision a named person makes.
- **A person checks before it ships.** Facts are traced to sources an expert approved, a few learners try the draft, and a pilot runs against a pass line set in advance.
- **No invented facts.** No made-up results, retention figures, benchmarks, quotes or returns. Numbers are yours, or a placeholder in brackets.
- **Programmes are evaluated, people are not.** Checks, role-plays, forms and pilots measure the programme, in aggregate, with small groups suppressed. Nothing scores, ranks or tracks a learner, a trainer or a manager.
- **The red line:** Claude drafts and checks, people decide: you talk to the learners, the experts and the sponsor, a named person signs off what gets built and what counts as proof, and nothing a learner does in training is used to grade, rank or build a case against them.

## Where it comes from

The sources behind each method are in `resources/evidence-and-sources.md`.

## About the makers

This pack is made by 90n ([90n.ai](https://90n.ai)): AI-native ways of working and tools for Product, Marketing and HR teams, built by ex-McKinsey founders. We map where time and money leak, redesign the work around AI and stay until your people run it themselves, and we run our own company on Claude. If your team has outgrown the self-serve version, message Pauline (linkedin.com/in/paulinebertry).

---

*Free to use inside your company, not for resale.*
