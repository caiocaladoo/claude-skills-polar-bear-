# Claude for Product Builders: 32 Claude Skills

32 Claude skills for taking one idea from a question to a prototype real users can try, and on to a build, change or stop decision. For product managers, product designers and founders shaping a first product.

**Guide and download:** [90n.ai/resources/product-builders-pack](https://90n.ai/resources/product-builders-pack)

## What this is

This pack follows one idea along its whole road. You frame the question, write the short spec, build a clickable prototype in Claude Design, make one flow really work in Claude Code when the test needs it, check it is safe to show, put it in front of five real target users, hand it to engineering with everything faked written down, and get a decision from a named person. Each skill produces one artifact, and each one names the skill to run next. The promise is a prototype good enough to learn from. It is not shipped software.

Claude builds the prototype, real users test it and engineers own what ships: a prototype is never called production, and nothing holding real customer data or a live key is shared until a named person has checked it.

```
Frame it -> Spec it -> Prototype it -> Make it work -> Check it is safe to show -> Test it with real users -> Hand it over -> Decide
```

## Install

### In Claude Code

```
/plugin marketplace add polar-bear-org/claude-skills
/plugin install product-builders-pack@polar-bear-skills
```

### In Claude.ai

1. Turn on "Code execution and file creation" under Settings > Capabilities.
2. Go to Customize > Skills, click "+", choose "+ Create skill", then "Upload a skill", and upload the skill's zip from the `install/` folder.
3. On Team and Enterprise plans, an owner enables "Cloud code execution and file creation" and "Skills" under Organization settings > Plugins & skills (Policy tab), and can upload skills for the whole organization.

## The skills

### 1 · Frame it

| Skill | What it does | When to run it |
|---|---|---|
| [Problem Frame](skills/build-problem-frame/SKILL.md) | One testable question, the decision it feeds and its owner by role, scope in three lists, a "how might we" line, one alternative framing | You have the idea and the screens in your head, and nobody has said what question it answers |
| [Idea One-Pager](skills/build-idea-one-pager/SKILL.md) | The ask at the top (prototype time and five real users), problem with its evidence source, the bet, one success measure, what you will not build, open questions | You want a go-ahead for a week of prototyping and all you have is a chat thread |
| [Prototype Test Card](skills/build-prototype-test-card/SKILL.md) | Beliefs sorted by what rides on them and how little evidence they have, one belief per card, the task, one observable measure, a dated pass line | The prototype is about to be built and nobody can say what result would make you stop |

### 2 · Spec it

| Skill | What it does | When to run it |
|---|---|---|
| [Prototype Brief](skills/build-prototype-brief/SKILL.md) | How real it must be (sketch, clickable, working), what is real and what is faked by hand, the Claude surface that fits, visual direction, what is out, a time box | You are about to type "build me an app" and have not decided how much of it has to work |
| [Screen-by-Screen User Flow](skills/build-user-flow/SKILL.md) | One journey from entry to done, each screen with its purpose, action and destination, dead ends, empty, error and loading states, one large-data case | The idea falls apart the moment you list what happens after the first click |
| [Prototype Spec](skills/build-prototype-spec/SKILL.md) | Answer-first summary, problem and evidence, non-goals, numbered requirements each with a pass or fail check, open questions with owners, a dated export | The prototype will be judged against "what we agreed" and nothing was agreed in writing |

### 3 · Prototype it

| Skill | What it does | When to run it |
|---|---|---|
| [Product Context File](skills/build-product-context-file/SKILL.md) | One short file about your product (users by need, terms, what exists, constraints, tone), what never goes in it, where it lives, a review date | You re-explain your product in every chat and the screens still use the wrong words |
| [Design System Brief](skills/build-design-system-brief/SKILL.md) | What to import and from where, the components and tokens to use, what the system does not cover, a three-screen spot check, gaps for the owner | Every prototype comes out in the same generic style |
| [Clickable Prototype](skills/build-clickable-prototype/SKILL.md) | The flow built screen by screen with requirement ids, two or three structurally different layouts, every state, sample content, a visible "prototype" label, decisions logged | You have a week, a spec and no engineer, and need something a user can click through |
| [Prototype Heuristic Review](skills/build-heuristic-review/SKILL.md) | A walk against the 10 usability heuristics, problems with proposed severity, an over-design check, a short accessibility pass, ranked fixes | Claude says it looks great and you are the only person who has seen it |

### 4 · Make it work

| Skill | What it does | When to run it |
|---|---|---|
| [Claude Code Setup](skills/build-claude-code-setup/SKILL.md) | A separate prototype folder, the permission mode that asks first, a short rules file, what you will and will not approve, the engineer's written yes | The clickable version is not enough and you have never opened Claude Code |
| [First Working Version](skills/build-first-working-version/SKILL.md) | The one flow that must really work, what stays faked and labelled, small steps each with a check on screen, save points, a stop rule | You asked for the whole app at once, got forty files, and cannot tell what works |
| [Error Fix Log](skills/build-error-fix-log/SKILL.md) | The error in plain words, the smallest steps that reproduce it, one change per attempt, when to rewind, when to stop and ask an engineer | It broke, the message means nothing to you, and each fix broke something else |
| [Sample Data Plan](skills/build-sample-data-plan/SKILL.md) | Each field the prototype needs, invented data for every one, the cases to cover, where real data is tempting and why it stays out, who approves an exception | You are about to paste a customer export "just to make the demo look real" |
| [Connector Plan](skills/build-connector-plan/SKILL.md) | Whether live tool data is needed at all, each connector page checked, reads allowed and writes off, personal data flagged, who turns it on, a first-run check | Real tickets or analytics would be more convincing and you do not know what Claude could change |
| [AI Prototype Input Check](skills/build-ai-prototype-check/SKILL.md) | Hand-picked inputs listed, a random share of real cases masked, runs per input, picked and random results reported apart, what one good run cannot show | The AI part worked beautifully on the three examples you chose |

### 5 · Check it is safe to show

| Skill | What it does | When to run it |
|---|---|---|
| [Secrets and Keys Check](skills/build-secrets-check/SKILL.md) | Where every key, password and token lives, the "could this be public" test, a search of files and history, revoke and replace steps, questions for an engineer | The prototype calls a real service and the key may be sitting in the page |
| [Personal Data Check](skills/build-personal-data-check/SKILL.md) | Every place data is shown, stored or sent, each item marked invented, masked or real, real items removed or approved by name, what shared storage and recordings hold | A real name, email or account number is on a screen you are about to send |
| [Access and Sharing Check](skills/build-access-check/SKILL.md) | Who can open the link today, what travels with it, the narrowest setting that lets testers in, a "prototype, not the product" label, the date access ends | You pasted the link in a channel and do not know who can now open it |
| [Pre-Share Sign-Off](skills/build-share-sign-off/SKILL.md) | One page: what is shared and with whom, the three checks as run, anything real that remains, what could go wrong, the named person who says yes | The checks are done in your head and nobody has said "yes, send it" |

### 6 · Test it with real users

| Skill | What it does | When to run it |
|---|---|---|
| [Tester Recruitment and Consent Note](skills/build-test-recruitment-note/SKILL.md) | Who counts as a real target user and who does not, where to find five, the invitation, a plain consent note | The easiest five people to ask are the ones sitting next to you |
| [Five-User Usability Test Plan](skills/build-usability-test-plan/SKILL.md) | Test goals tied to the belief, task scenarios with the path unstated, success criteria set first, a moderator script, an observer grid, a pilot | Your script says "click here and tell me if you like it" |
| [Usability Test Findings](skills/build-usability-findings/SKILL.md) | Per task: completed, with help, not completed; what people did beside what they said; problems with proposed severity; the moments to show | The sessions "went well" and four people could not finish the main task |
| [Prototype Iteration Plan](skills/build-iteration-plan/SKILL.md) | What to fix before the next round and what to leave, one change per problem, what the next round must show, what cannot be compared, when to stop | You want to fix everything after session two and have lost track of which version anyone saw |

### 7 · Hand it over

| Skill | What it does | When to run it |
|---|---|---|
| [Prototype Demo Script](skills/build-demo-script/SKILL.md) | The moment to show first, the path, what users did (counts as run), the limits said out loud, the decision asked, answers for "when can we have it" | You are about to demo to leaders and the first question will be a date |
| [Prototype vs Production Note](skills/build-production-gap-note/SKILL.md) | What it proved against its pass line, what it does not prove, what is faked, the gap as work items with an owning role and no dates | It looks finished, so someone has started calling it "version one" |
| [Engineering Handover Note](skills/build-engineering-handover/SKILL.md) | How to open and run it, a screen and requirement map, decisions and reasons, everything faked, known problems, keep, rebuild or throw away as a recommendation | You sent engineers a link and they have forty questions before they can start |
| [Engineering Review Request](skills/build-review-request/SKILL.md) | The one question for an engineer, what you are not asking, a thirty-minute walk-through plan, the three places you suspect, what you will do with the answer | Your prototype has sat in a review queue for two weeks |

### 8 · Decide

| Skill | What it does | When to run it |
|---|---|---|
| [Prototype Learning Card](skills/build-learning-card/SKILL.md) | What we believed, what we observed against the pass line, what we learned, what we still do not know, what we do next | The story of what happened changes each time someone tells it |
| [Build, Change or Stop Decision](skills/build-decision-memo/SKILL.md) | One page: the decision asked, the evidence, the gap to production, three options with their cost as engineering states it, who decides, the date | The prototype has been praised by everyone and decided on by no one |
| [Experiment Design Plan](skills/build-experiment-design/SKILL.md) | For the version engineers build: hypothesis, variants, one primary metric, guardrails, a sample and duration check, a decision rule set before launch | The decision was "build" and the argument is whether it will move the number |
| [Build Routine Skill](skills/build-routine-skill/SKILL.md) | Your own repeat steps turned into a skill: real trigger phrases, fixed steps, a quality bar with the pre-share checks, a test on three past inputs | The second idea arrives and you start again from a blank chat |

## How to choose a skill

```
Need to say what question the idea answers?          -> Problem Frame
Need a go-ahead for a week of prototyping?           -> Idea One-Pager
Need a pass line before anything is built?           -> Prototype Test Card
Need to decide how real the prototype must be?       -> Prototype Brief
Need every screen and state listed?                  -> Screen-by-Screen User Flow
Need "what we agreed" in writing?                    -> Prototype Spec
Need Claude to know your product?                    -> Product Context File
Need the prototype to look like your product?        -> Design System Brief
Need something a user can click through?             -> Clickable Prototype
Need a review before anyone else sees it?            -> Prototype Heuristic Review
Need a safe folder for your first Claude Code build? -> Claude Code Setup
Need one flow that really works?                     -> First Working Version
Need to get past an error you cannot read?           -> Error Fix Log
Need realistic data with no real person in it?       -> Sample Data Plan
Need live tool data in the prototype?                -> Connector Plan
Need to know if the AI part holds on unpicked input? -> AI Prototype Input Check
Need to know where the keys are?                     -> Secrets and Keys Check
Need to find real names and emails on screen?        -> Personal Data Check
Need to know who can open the link?                  -> Access and Sharing Check
Need a named yes before you send it?                 -> Pre-Share Sign-Off
Need five real target users and their consent?       -> Tester Recruitment and Consent Note
Need tasks and a script for the sessions?            -> Five-User Usability Test Plan
Need to read what the sessions showed?               -> Usability Test Findings
Need to choose what to change before round two?      -> Prototype Iteration Plan
Need to demo without promising a date?               -> Prototype Demo Script
Need to say what is prototype and what is not?       -> Prototype vs Production Note
Need engineers to be able to start from it?          -> Engineering Handover Note
Need thirty minutes of an engineer's time?           -> Engineering Review Request
Need one fixed account of what the test showed?      -> Prototype Learning Card
Need a decision from a named person?                 -> Build, Change or Stop Decision
Need to test the built version on real traffic?      -> Experiment Design Plan
Need to repeat all this for the next idea?           -> Build Routine Skill
```

## Example prompts

- "Run build-problem-frame. I want to add a saved-searches feature and I already have the screens in my head. Help me find the question first."
- "Run build-prototype-brief. Here is my test card. Does this need a working version or is a clickable one enough?"
- "Run build-clickable-prototype from this spec in Claude Design. Give me two layouts that differ in structure, and show every screen empty, loading and in error."
- "Run build-secrets-check. The prototype calls a real service and I do not know where the key ended up."
- "Run build-usability-test-plan. I have never moderated a session. Five target users, three tasks, here is my test card."
- "Run build-production-gap-note. People have started calling this version one. Here are the test results and the list of what I faked."

## Quality bar

Every skill in this pack holds these standards:

- **One artifact, one decision.** Each output ends with what a named role decides next, and by when.
- **The pass line comes first.** What counts as success is written and dated before anything is built or tested, and it is never moved after the results are in.
- **Real target users, real sessions.** Colleagues, the leaders who asked and simulated users are not testers. Only what people did in a session becomes a finding.
- **Nothing invented.** No made-up numbers, quotes, results or user reactions. What is unknown stays in [brackets] until you fill it in.
- **Faked is labelled as faked.** Every share carries a visible "prototype" label, and every handover lists what is hardcoded or done by hand.
- **Checks are run by a person.** Security points end with "check with your engineering or security lead"; legal, privacy and consent points end with "check with a qualified adviser". No skill declares a prototype secure.
- **Problems are rated, people are not.** Severity belongs to a usability problem. Participants are codes, and nothing grades a tester or a teammate.
- **The red line.** Claude builds the prototype, real users test it and engineers own what ships: a prototype is never called production, and nothing holding real customer data or a live key is shared until a named person has checked it.

## Where it comes from

The sources behind each method are in `resources/evidence-and-sources.md`.

## About the makers

This pack is made by 90n ([90n.ai](https://90n.ai)): AI-native ways of working and tools for Product, Marketing and HR teams, built by ex-McKinsey founders. We map where time and money leak, redesign the work around AI and stay until your people run it themselves, and we run our own company on Claude. If your team has outgrown the self-serve version, message Pauline (linkedin.com/in/paulinebertry).

---

*Free to use inside your company, not for resale.*
