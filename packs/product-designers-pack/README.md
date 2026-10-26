# Claude for Product Designers: 32 Claude Skills

32 Claude skills to frame, explore, design, prototype, critique, test, hand off and show the impact of one piece of design work. For product designers, UX and UI designers, and designers who do their own research.

**Guide and download:** [90n.ai/resources/product-designers-pack](https://90n.ai/resources/product-designers-pack)

## What this is

The pack follows one piece of design work from the request to the result. It starts by framing the problem (what was asked, what is known, what success will look like), then explores real options and records why one was chosen. It gives Claude the context it needs before it designs anything (the design system as rules, the product as a file, the flow, the copy, every state), plans a prototype around the one question it must answer, and checks the work before a room or a user sees it. It then plans and reads tests with real people, hands the design to engineering with nothing left to guess, and ends with the review, the feedback, the pushback, the impact write-up and the portfolio case study.

Every skill holds one line: Claude drafts, checks and explains; you make the design decisions, real users test the work, and nothing is presented as tested, accessible or ready to ship that was not.

```
Frame the problem -> Explore and decide -> Design with context -> Prototype -> Critique and quality -> Test with real users -> Hand off -> Defend and show the impact
```

## Install

### In Claude Code

```
/plugin marketplace add polar-bear-org/claude-skills
/plugin install product-designers-pack@polar-bear-skills
```

### In Claude.ai

1. Turn on "Code execution and file creation" under Settings > Capabilities.
2. Go to Customize > Skills, click "+", choose "+ Create skill", then "Upload a skill", and upload the skill's zip from the `install/` folder. Repeat for each skill you want.
3. On Team and Enterprise plans, an owner first enables "Cloud code execution and file creation" and "Skills" under Organization settings > Plugins & skills (Policy tab), and can upload skills for the whole organization.

Every skill works in a normal chat with what you paste in. Some name an optional Claude surface: Claude Design to put real options or a prototype on a canvas beside the chat, Claude Docs for briefs, rationale docs and write-ups, Claude Slides for review decks (download as PowerPoint or PDF), and a Project or memory to keep a log, a register or a context file across weeks. The Figma connector is optional too: it reads frames, variables and components and creates FigJam diagrams, and screenshots come back to Claude as text descriptions. No skill edits your design file, and no skill needs a connector to run.

## The skills

### 1 · Frame the problem

| Skill | What it does | When to run it |
|---|---|---|
| [Problem Framing Brief](skills/pdes-problem-framing-brief/SKILL.md) | The request as handed over, the problem with no fix in it, evidence and gaps, a "not solving" list, hypotheses placed by risk and value | You were handed a feature and a deadline, and nobody has said what problem it solves |
| [User Journey Map](skills/pdes-user-journey-map/SKILL.md) | One group, one scenario, stages, actions, thoughts, feelings, touchpoints and pain points, every cell tagged to its evidence | You design one screen of a journey nobody has drawn, and the team's picture of it is a guess |
| [HEART Metrics Plan](skills/pdes-heart-metrics-plan/SKILL.md) | Chosen dimensions, goal, signal and metric for each, baselines or "baseline needed", instrumentation asks, guardrails | The project starts and nobody agreed what design success will look like |

### 2 · Explore and decide

| Skill | What it does | When to run it |
|---|---|---|
| [Design Principles](skills/pdes-design-principles/SKILL.md) | Four to seven stands for this product, what each gives up, "this, not that" pairs, a conflict check | Every review turns into a taste argument because nothing written says what this product chooses |
| [Design Options Trade-off Table](skills/pdes-design-options-tradeoffs/SKILL.md) | Two to four options that differ in structure, criteria, consequences in words, what each option gives up | Stakeholders saw one design and think it is the only one, so every comment is a tweak |
| [Design Rationale Doc](skills/pdes-design-rationale-doc/SKILL.md) | The decision, why each option lost, evidence or visible gaps, trade-offs accepted, risks, the signal that reopens it | You are asked "why is it like this?" in every meeting |
| [Design Decision Log](skills/pdes-design-decision-log/SKILL.md) | Numbered decision records with context, status, consequences, decider, revisit trigger and an index | A decision made months ago is reopened and nobody remembers why it was made |

### 3 · Design with context

| Skill | What it does | When to run it |
|---|---|---|
| [Design System Rules File](skills/pdes-design-system-rules-file/SKILL.md) | Tokens by name and role, component rules and states, do and do not pairs, a list of what is missing, a five-prompt test | Your design system reads well to people, and Claude still invents values and components you do not have |
| [Product Context File](skills/pdes-product-context-file/SKILL.md) | One file Claude reads first: users, jobs, voice, principles, constraints, what the product never does, where each fact came from | Every chat starts from zero and the first draft looks like a product for nobody in particular |
| [User Flow](skills/pdes-user-flow/SKILL.md) | Entry points, steps with system responses, decision points, error and recovery branches, exits, open questions | You have a brief and a blank canvas, and the happy path is the only path anyone has described |
| [UX Writing Copy Deck](skills/pdes-ux-writing/SKILL.md) | Every string for one flow in one table, errors that say what to do next, length limits, terms checked, approvals still needed | The screens are done and the copy is still placeholder text and "Submit" |
| [UI States and Edge Cases](skills/pdes-ui-states-and-edge-cases/SKILL.md) | Screens against states, an edge-case sweep per screen, each cell marked designed, missing or not needed with the reason | Engineering asks "what happens when the list is empty?" on day three of the build |

### 4 · Prototype

| Skill | What it does | When to run it |
|---|---|---|
| [Prototype Brief](skills/pdes-prototype-brief/SKILL.md) | The one question, the audience, the lowest fidelity that answers it, real and faked parts, the pass line, what it does not prove | Someone says "just prototype it" and nobody has said what the prototype is for |
| [Claude Design Prototype Plan](skills/pdes-claude-design-prototype/SKILL.md) | The written brief for Claude Design, the look specified, three or more directions, what to fix by hand, saved copies, limits to plan around | You want a clickable prototype this afternoon and the first result looks like everyone else's |
| [Prototype Share Check](skills/pdes-prototype-share-check/SKILL.md) | A list a person runs before sharing: the label, what is faked, invented data only, link access, a contrast and keyboard look, the words to say | A prototype is about to go to users or a stakeholder, and it looks finished enough to be mistaken for the product |

### 5 · Critique and quality

| Skill | What it does | When to run it |
|---|---|---|
| [Design Quality Bar](skills/pdes-design-quality-bar/SKILL.md) | Yes or no checks by stage, a must-pass list proposed for the person who owns quality to confirm | "Raise the bar" is said every quarter and nobody has written the bar |
| [Design Self-Critique](skills/pdes-design-self-critique/SKILL.md) | Your pass and a second-opinion pass against ten heuristics, merged issues, trade-offs, what needs a real user, the fix list | The review is tomorrow and you want to find the obvious problems before the room does |
| [Accessibility Review](skills/pdes-accessibility-review/SKILL.md) | Design-stage checks marked pass, fail or cannot tell from a design, the fixes, and what only code, assistive technology and disabled users can show | Accessibility gets looked at after the build, or an automated check said everything passed |
| [Design Sameness Check](skills/pdes-design-sameness-check/SKILL.md) | An inventory of default choices, each chosen or inherited, three places for a real decision, what stays standard | The screen looks fine and could belong to any product |
| [Critique Session Brief](skills/pdes-critique-session-brief/SKILL.md) | Numbered objectives, the stage, the one question for the room, out of scope, the walkthrough, a framing sentence | You present at crit on Thursday and "thoughts?" will get you opinions |
| [Critique Notes to Actions](skills/pdes-critique-notes-to-actions/SKILL.md) | Notes merged and sorted, your call on each, actions with owners and dates, a three-line reply | You left crit with twenty comments, half of them contradicting each other |

### 6 · Test with real users

| Skill | What it does | When to run it |
|---|---|---|
| [Usability Test Plan](skills/pdes-usability-test-plan/SKILL.md) | Goals, task scenarios with the path unstated, success criteria set first, a moderator script, an observer grid, the sample, a pilot | The prototype is ready, the sessions are booked, and the script is a guided tour |
| [Accessible Test Sessions](skills/pdes-accessible-test-sessions/SKILL.md) | How to invite disabled and older people, access needs asked in advance, their own technology, accessible consent, session adjustments | The accessibility review passed on paper and no disabled person has ever used the design |
| [Usability Test Findings](skills/pdes-usability-findings/SKILL.md) | Task outcomes as "n of N", what people did beside what they said, issues with evidence and a proposed severity, clips to pull | The tests "went well" and your notes say four people failed the core task |

### 7 · Hand off

| Skill | What it does | When to run it |
|---|---|---|
| [Design Handoff Spec](skills/pdes-design-handoff-spec/SKILL.md) | Which version is final, flows, rules next to screens, tokens by name, motion, focus order, copy status, open questions, a ready check | The file is polished and engineering still cannot tell which design is final or what happens on error |
| [Design System Change Record](skills/pdes-design-system-change-record/SKILL.md) | One proposed change, what exists and why it does not serve, the "build it from what exists" check, who is affected, the decision left blank for the owner | Your feature needs something the system does not have |
| [UX Debt Register](skills/pdes-ux-debt-register/SKILL.md) | One row per issue as user impact, frequency from evidence, effort set with engineering, value against effort, a short list to propose | The broken empty state and the copy nobody rewrote never make the plan |

### 8 · Defend and show the impact

| Skill | What it does | When to run it |
|---|---|---|
| [Design Review Deck](skills/pdes-design-review-deck/SKILL.md) | The decision asked on slide one, options and what the recommendation gives up, real evidence, feedback in scope, next steps | You present to stakeholders and the room argues about colours instead of the decision |
| [Stakeholder Feedback Log](skills/pdes-stakeholder-feedback-log/SKILL.md) | Every comment by role and objective, duplicates merged, conflicts side by side for the decider, reply drafts you send | Three stakeholders gave three opposite notes and the next round undoes the last |
| [Design Pushback Brief](skills/pdes-design-pushback-brief/SKILL.md) | The request and its goal, the risk with evidence, two alternatives, what you will and will not do, who decides | You are asked to ship a deceptive pattern or a change you believe will hurt users |
| [Design Impact Write-Up](skills/pdes-design-impact-writeup/SKILL.md) | What design changed, before and after from your data, what else moved, a confidence level, results that got worse kept in | Someone asks what the redesign delivered and you have screens, not outcomes |
| [Portfolio Case Study](skills/pdes-portfolio-case-study/SKILL.md) | One project told through three to five decisions, your role, what real users did, real outcomes, a confidentiality check | Your portfolio shows twenty polished frames and reads like every other case study |

## How to choose a skill

```
Need to know what problem the feature solves?          -> Problem Framing Brief
Need the whole journey around your screen?             -> User Journey Map
Need to agree what success looks like?                 -> HEART Metrics Plan
Need criteria that end taste arguments?                -> Design Principles
Need to show the real choice, not one design?          -> Design Options Trade-off Table
Need to answer "why is it like this?" once?            -> Design Rationale Doc
Need a record of what was decided and when?            -> Design Decision Log
Need Claude to follow your design system?              -> Design System Rules File
Need Claude to know your product before it designs?    -> Product Context File
Need every path, not only the happy one?               -> User Flow
Need real copy for every string in a flow?             -> UX Writing Copy Deck
Need every state and edge case accounted for?          -> UI States and Edge Cases
Need to say what a prototype is for?                   -> Prototype Brief
Need a prototype that does not look like a default?    -> Claude Design Prototype Plan
Need to check a prototype before it leaves the team?   -> Prototype Share Check
Need the standard written down, by stage?              -> Design Quality Bar
Need to find the obvious problems before the review?   -> Design Self-Critique
Need a design-stage accessibility check?               -> Accessibility Review
Need to know which choices are defaults?               -> Design Sameness Check
Need useful feedback at crit?                          -> Critique Session Brief
Need to turn crit notes into a plan?                   -> Critique Notes to Actions
Need tasks and a script for test sessions?             -> Usability Test Plan
Need disabled people in this round of testing?         -> Accessible Test Sessions
Need to write up what happened in the sessions?        -> Usability Test Findings
Need engineering to build it without guessing?         -> Design Handoff Spec
Need something the design system does not have?        -> Design System Change Record
Need the small issues seen together?                   -> UX Debt Register
Need a decision from stakeholders?                     -> Design Review Deck
Need to sort conflicting stakeholder comments?         -> Stakeholder Feedback Log
Need to push back on a request?                        -> Design Pushback Brief
Need to show what the redesign delivered?              -> Design Impact Write-Up
Need a case study built on your decisions?             -> Portfolio Case Study
```

## Example prompts

- "Run pdes-problem-framing-brief. Here is the ticket for the new export feature and the three support threads behind it. What problem are we solving, and what do we not know yet?"
- "Claude keeps inventing colours and a card we do not have. Here are our token file and the component docs. Write the Design System Rules File and tell me which rules failed the five-prompt test."
- "Here are the frames for the invite flow. Build the UI States and Edge Cases table and mark every cell designed, missing or not needed."
- "I have six sessions booked for Thursday with this prototype. Write the Usability Test Plan, and do not let any task give the path away."
- "Here are my notes from five test sessions and the success criteria we set before testing. Write the Usability Test Findings and mark every severity as proposed."
- "Engineering starts on Monday. Here is the file structure, the states table and the open questions. Write the Design Handoff Spec and run the ready check."

## Quality bar

- **One method, applied properly.** Each skill uses the real mechanics of its source (the hypothesis placements, the question, options and criteria form, the decision record statuses, the ten heuristics, the 0 to 4 severity scale, goals to signals to metrics), not a generic "gather, analyse, recommend".
- **Real evidence or a visible gap.** Research findings, user quotes and numbers come only from what you paste. Anything missing stays a bracketed placeholder, "not researched" or "not measured".
- **A person checks before anything is shown.** Every output a user, customer or stakeholder will see has a check a person runs first, and a prototype is labelled as a prototype.
- **Problems are rated, people are not.** Severity, effort and value describe issues in the work. Nothing rates a designer, a participant or a colleague.
- **Every output ends with a decision.** Each template closes with what a named person decides next, and by when.
- **Adviser points stay with an adviser.** Accessibility duties, consent, data and other legal points end with "check with a qualified adviser".
- **The red line:** Claude drafts, checks and explains; you make the design decisions, real users test the work, and nothing is presented as tested, accessible or ready to ship that was not.

## Where it comes from

The sources behind each method are in `resources/evidence-and-sources.md`.

## About the makers

This pack is made by 90n ([90n.ai](https://90n.ai)): AI-native ways of working and tools for Product, Marketing and HR teams, built by ex-McKinsey founders. We map where time and money leak, redesign the work around AI and stay until your people run it themselves, and we run our own company on Claude. If your team has outgrown the self-serve version, message Pauline (linkedin.com/in/paulinebertry).

---

*Free to use inside your company, not for resale.*
