# Claude for Consultants · Team in Claude: 39 Claude Skills

39 Claude skills for winning and shaping client work when the client has AI too, from their brief to the signed scope. For independent consultants and partners in advisory practices.

**Guide and download:** [meet-polar-bear.com/skills/consultants-pack](https://meet-polar-bear.com/skills/consultants-pack)

## What this is

A team of eight desks behind one consultant. When you sell the work and do the thinking yourself, there is nobody to read the brief with you, take notes on the call, argue with your first answer or read the proposal cold before it goes out. Each desk does one of those jobs and hands its output to the next. The Intake desk reads the client's brief and helps you decide whether to bid. The Discovery desk prepares the call and keeps the client's words. The Problem desk structures the problem and tests your reading of it. The Strategy desk builds options and a recommendation you can defend. The Pricing desk shapes fees and scope. The Proposal desk writes the proposal and the statement of work. The Client room prepares you to present, answer and negotiate, including the question "why can't AI do this?". The Follow-through desk follows up, helps your contact decide and reviews the result. No desk is a person or plays a character; every skill produces one artifact and names the skill to run next.

The red line: Claude structures, drafts and checks; it never invents a reference, a result, a number or a client quote, and you run the conversation, make the recommendation and send everything yourself.

```
Intake desk -> Discovery desk -> Problem desk -> Strategy desk -> Pricing desk -> Proposal desk -> Client room -> Follow-through desk
```

## Install

### In Claude Code

```
/plugin marketplace add polar-bear-org/claude-skills
/plugin install consultants-pack@polar-bear-skills
```

### In Claude.ai

1. Turn on "Code execution and file creation" under Settings > Capabilities.
2. Go to Customize > Skills, click "+", choose "+ Create skill", then "Upload a skill", and upload a skill's zip from the `install/` folder. Repeat for each skill you want.
3. On Team and Enterprise plans, an owner enables "Cloud code execution and file creation" and "Skills" under Organization settings > Plugins & skills (Policy tab), and can share skills with the organization.

Several skills name a Claude surface where it helps: Claude Docs for the proposal, the memo and the statement of work, Claude Slides or Claude for PowerPoint for the walk-through deck, Claude in Chrome (paid plans) for reading a company's public pages, the Gmail connector for reading a thread (you send every message), and a Project per engagement to keep the notes together. Every skill also works in a plain chat with pasted text.

## The skills

### 1 · Intake desk

*Read the brief, decide to bid.*

| Skill | What it does | When to run it |
|---|---|---|
| [AI-Written Brief Review](skills/firm-ai-brief-review/SKILL.md) | Line-by-line reading, six constraint checks, client questions in priority order | The brief looks finished, probably drafted with AI, and you still cannot scope or price from it |
| [MEDDIC Qualification](skills/firm-meddic-qualification/SKILL.md) | Known and unknown per letter with sources, fit against your practice brief, call questions | Prospects take the call and sound keen, and the proposals that follow still do not close |
| [Buying Committee Map](skills/firm-buying-committee-map/SKILL.md) | Six buying roles, stated needs with sources, unmet roles with one question each | You pitched to one friendly contact and the person who signs has never seen you |
| [Bid/No-Bid Decision](skills/firm-bid-no-bid/SKILL.md) | Criteria before facts, shortlist check, cost of pursuit, decision record, no-bid reply | An RFP or an AI-compiled shortlist arrives and you suspect you are the comparison quote |

### 2 · Discovery desk

*Prepare the call, keep their words.*

| Skill | What it does | When to run it |
|---|---|---|
| [Pre-Call Research Brief](skills/firm-pre-call-brief/SKILL.md) | Sourced public facts, likely trigger, two or three hypotheses with test and kill answers | The call is in twenty minutes and you want to walk in with a view, not a fact sheet |
| [Discovery Call Agenda](skills/firm-discovery-call-agenda/SKILL.md) | Agenda note to send ahead, attendees by role, plain consent line for recording | First calls wander, the wrong roles attend and nobody agreed how the call should end |
| [Discovery Call Questions](skills/firm-discovery-call-questions/SKILL.md) | One-page SPIN guide, open gaps first, decision process block, what to listen for | Your discovery calls gather facts and never reach what the problem costs or who decides |
| [Cost of Inaction](skills/firm-cost-of-inaction/SKILL.md) | Consequences in the client's figures, arithmetic shown, timing pressure, questions for blanks | The client enjoys the conversations and nothing makes the work urgent |
| [Discovery Call Notes](skills/firm-discovery-call-notes/SKILL.md) | Verbatim words, facts, figures, your inferences, contradictions, open questions, next step | You took notes in a rush and the proposal will need the client's exact words |
| [Discovery Recap Email](skills/firm-discovery-recap-email/SKILL.md) | "Here is what I heard" in their words, their priorities, open points, dated next step | You want the client to confirm you understood before you write any proposal |

### 3 · Problem desk

*Structure the problem.*

| Skill | What it does | When to run it |
|---|---|---|
| [Problem Statement](skills/firm-problem-statement/SKILL.md) | Point of view in their words, the decision it serves, success measures, impact, rival test | Your proposals describe your practice instead of their problem, and nobody has said which decision the work serves |
| [Issue Tree](skills/firm-issue-tree/SKILL.md) | One stated cut, branches tested or untested, the client's AI answer placed on the tree | The client already holds an AI answer and needs someone to show which parts rest on evidence |
| [Hypothesis Test Plan](skills/firm-hypothesis-test-plan/SKILL.md) | Hypotheses that can fail, a rival for each, the telling observation, checks with owners | You already believe you know the answer and work without a colleague to argue the other side |
| [Stakeholder Interview Plan](skills/firm-stakeholder-interview-plan/SKILL.md) | Whom to hear by role, neutral brief, same core questions, synthesis of unique information | The room agreed as soon as the most senior person spoke, and you doubt you heard the facts |

### 4 · Strategy desk

*Options and a recommendation.*

| Skill | What it does | When to run it |
|---|---|---|
| [Strategic Options](skills/firm-strategic-options/SKILL.md) | Three to five distinct ways to solve it, including doing nothing and doing it in house | The client sees two options and dislikes both, or you see one and it happens to be yours |
| [Trade-Off Table](skills/firm-trade-off-table/SKILL.md) | Criteria in the client's terms, consequences with sources, who bears each cost, no score | Someone wants the options compared and you will not make up a score to do it |
| [Outside View Check](skills/firm-outside-view-check/SKILL.md) | Forecast stated precisely, comparable cases and their range, your revised estimate | Your timeline or result estimate is mostly a story about why this client is different |
| [Recommendation Pre-Mortem](skills/firm-recommendation-premortem/SKILL.md) | Failure defined at a date, ways it fails, early signals, prevention, what stays exposed | You are about to commit to a recommendation and nobody has tried to break it |
| [Sensitivity Analysis](skills/firm-sensitivity-analysis/SKILL.md) | Load-bearing assumptions varied, the switching point, evidence worth getting, a verdict | The client asks what would change your mind and you want a straight answer ready |
| [Recommendation Memo](skills/firm-recommendation-memo/SKILL.md) | Your position first, options rejected, costs accepted, what would change it, review date | The analysis is done and the client needs your position on a single page, with your name on it |

### 5 · Pricing desk

*Fees and scope.*

| Skill | What it does | When to run it |
|---|---|---|
| [Good-Better-Best Options](skills/firm-good-better-best-options/SKILL.md) | Three priced ways to buy the work, what each leaves out, decoy test on every pair | One price gets you a yes or a no, and too often it is a no |
| [Fee Structure Choice](skills/firm-fee-structure/SKILL.md) | Five fee models compared on four counts, protections needed, your answer on hours | The client asks why they should pay for your hours now that AI makes the work quicker |
| [MoSCoW Scope](skills/firm-moscow-scope/SKILL.md) | Every item on one line, won't list with reasons, effort split, what moves if budget changes | The AI-drafted brief asked for everything and the fee can cover only part of it |

### 6 · Proposal desk

*The proposal and the statement of work.*

| Skill | What it does | When to run it |
|---|---|---|
| [Consulting Proposal](skills/firm-consulting-proposal/SKILL.md) | Answer-first proposal with the decision asked, their problem, three options, proof, AI use | The client needs something they can read in five minutes and pass to people who missed the call |
| [Win Themes](skills/firm-win-themes/SKILL.md) | Two or three themes with proof, the AI-shortlist test, where each lands in the proposal | The buyer compared advisers with AI and every one of you now sounds the same |
| [Case Study Paragraph](skills/firm-case-study-paragraph/SKILL.md) | 120 to 180 word case, a 40-word version, permission status, results as approved | You need proof no model can generate, and only work you really did will count |
| [AI Use Statement](skills/firm-ai-use-statement/SKILL.md) | Task-by-task AI use, who checks and signs, data handling, what you will not use AI for | You are unsure whether to tell clients you use AI, and they have begun to ask |
| [Statement of Work](skills/firm-statement-of-work/SKILL.md) | Results, deliverables with acceptance criteria, dated timeline, won't list, change control | The client has agreed and the scope has to survive the new ideas that arrive next month |
| [Proposal Red Team Review](skills/firm-proposal-red-team/SKILL.md) | Cold read as the absent signer, every claim traced or flagged, edit list by severity | You are about to press send and have no colleague to read it the way the buyer will |

### 7 · Client room

*Present and answer.*

| Skill | What it does | When to run it |
|---|---|---|
| [Proposal Walk-Through Deck](skills/firm-proposal-walkthrough-deck/SKILL.md) | Six to ten slides, full-sentence headlines, options side by side, speaker notes, read version | Proposals you email cold go quiet, so you want to take the client through this one live |
| [Proposal Executive Summary](skills/firm-executive-summary/SKILL.md) | Decision asked and date first, situation, complication, question, options in one line each | The person who signs has never met you and will read exactly one page |
| [AI Objection Answer](skills/firm-ai-objection-answer/SKILL.md) | The question behind the words, a three-column task split, what you say, a shared option | A client says AI could do this in seconds, or asks what they pay you for now they have Claude |
| [Like-for-Like Quote Comparison](skills/firm-quote-comparison/SKILL.md) | Both quotes on the same lines, risk per missing line, gaps in your own, neutral questions | The client slides a quote across the table at a fraction of your fee |
| [Objection Handling Map](skills/firm-objection-handling/SKILL.md) | One row per objection, the real concern, an honest response, proof held, lines to avoid | The same objections return on every engagement and you improvise the answer each time |
| [Negotiation Plan](skills/firm-negotiation-plan/SKILL.md) | Your alternative and walk-away, tradables with asks, concession order, the pre-discount question | The client is haggling and you are tempted to cut the fee just to end the awkwardness |

### 8 · Follow-through desk

*Follow up, decide, review.*

| Skill | What it does | When to run it |
|---|---|---|
| [Proposal Follow-Up Emails](skills/firm-proposal-follow-up/SKILL.md) | Two follow-ups each with one useful reason, then a short close-the-loop note | A proposal sits unanswered and every draft you start begins "just checking in" |
| [Client Decision Brief](skills/firm-client-decision-brief/SKILL.md) | Neutral page for your contact, every route including in house, what would make each right | Your contact backs the work and has to persuade people you will never meet |
| [Mutual Action Plan](skills/firm-mutual-action-plan/SKILL.md) | Every step from yes to day one, owners by role, dates, questions for ownerless steps | The client says yes in the meeting and then nothing happens for six weeks |
| [Win/Loss Review](skills/firm-win-loss-review/SKILL.md) | Plan against what happened, causes sorted, where it was decided, changes as concrete edits | You lost a pitch, or won one you cannot explain, and want the next one to go better for it |

## How to choose a skill

```
Need to know what a polished brief actually decided?  -> AI-Written Brief Review
Need to see what you really know about an opportunity?  -> MEDDIC Qualification
Need to see who decides beyond your one contact?  -> Buying Committee Map
Need to decide whether to answer an RFP at all?  -> Bid/No-Bid Decision
Need a point of view before the first call?  -> Pre-Call Research Brief
Need a first call with an agreed purpose and ending?  -> Discovery Call Agenda
Need questions that reach cost and the decision?  -> Discovery Call Questions
Need to show what waiting costs, in their numbers?  -> Cost of Inaction
Need their exact words kept apart from your reading?  -> Discovery Call Notes
Need proof you listened, before any proposal?  -> Discovery Recap Email
Need their problem and the decision it serves, on one page?  -> Problem Statement
Need to show where a fluent answer could be wrong?  -> Issue Tree
Need someone to argue with your first answer?  -> Hypothesis Test Plan
Need independent views before the group meets?  -> Stakeholder Interview Plan
Need real alternatives for the client's problem?  -> Strategic Options
Need options compared without an invented score?  -> Trade-Off Table
Need a reality check on your estimate?  -> Outside View Check
Need to break your recommendation before the client does?  -> Recommendation Pre-Mortem
Need a straight answer to "what would change your mind?"?  -> Sensitivity Analysis
Need your position on one page, with your name on it?  -> Recommendation Memo
Need three ways to buy the work, not one price?  -> Good-Better-Best Options
Need to choose how to charge, and explain it?  -> Fee Structure Choice
Need to fit an oversized wish list to the fee?  -> MoSCoW Scope
Need a proposal people can read in five minutes?  -> Consulting Proposal
Need reasons to choose you that survive a comparison?  -> Win Themes
Need real proof, written short and with permission?  -> Case Study Paragraph
Need to tell the client plainly how you use AI?  -> AI Use Statement
Need a scope that holds after the yes?  -> Statement of Work
Need a second reader before you send?  -> Proposal Red Team Review
Need a walk-through instead of a cold email?  -> Proposal Walk-Through Deck
Need one page for the signer who never met you?  -> Proposal Executive Summary
Need an honest answer to "why can't AI do this?"?  -> AI Objection Answer
Need to compare your quote with a cheaper one fairly?  -> Like-for-Like Quote Comparison
Need honest answers to the objections you keep hearing?  -> Objection Handling Map
Need to hold your fee, or trade it knowingly?  -> Negotiation Plan
Need a follow-up worth replying to?  -> Proposal Follow-Up Emails
Need a neutral page your contact can argue from?  -> Client Decision Brief
Need to get from a yes to a start date?  -> Mutual Action Plan
Need to learn from a win or a loss?  -> Win/Loss Review
```

## Example prompts

- "Run firm-ai-brief-review on the attached brief. I think it was written with AI. Tell me which lines the client actually decided and what I must ask before quoting."
- "Run firm-issue-tree. The client pasted an AI answer to their own question; put it on the tree and show me what nobody has checked."
- "Run firm-strategic-options. The client thinks the choice is restructure or carry on. Give me real alternatives, including doing it in house with their own AI."
- "Run firm-ai-objection-answer. The client said: couldn't we just ask Claude to do this? Here is my scope. Tell me honestly which tasks they could do themselves."
- "Run firm-proposal-red-team on my draft. The person who signs was not on the call. Flag anything I cannot source."
- "Run firm-proposal-follow-up. The proposal went out ten days ago with no reply, and on the call they asked a question I never answered properly."

## Quality bar

Every skill in this set holds the same standards:

- **Their words, with a source.** A fact, figure or quote appears only if it traces to your notes, your files or the client's own pages. Anything else is a blank with the question that would fill it.
- **Your numbers only.** Fees, rates, effort and results are yours or the client's. No benchmark, market rate or typical figure is supplied.
- **Honest about AI.** What AI does well is said first. Nothing sells against AI, and your own use of it is never hidden. Doing the work in house with the client's own AI is written as a real option.
- **Roles, never ratings.** Maps and plans record roles and stated positions. Nothing grades, ranks, scores or profiles a person, and options are compared without a weighted score unless you ask for one and own the weights.
- **A decision at the end.** Every output closes with what a named person decides, and by when.
- **Advisers for legal points.** Contract, tax, data and recording questions are flagged "check with a qualified adviser", never answered as advice. Recordings and transcripts are used only with everyone's consent.
- **The red line.** Claude structures, drafts and checks; it never invents a reference, a result, a number or a client quote, and you run the conversation, make the recommendation and send everything yourself.

## Where it comes from

The sources behind each method are in `resources/evidence-and-sources.md`.

## About the makers

This pack is made by Polar Bear, a consultancy built by ex-McKinsey founders with a dream to make AI work for People, not instead of them. We help our clients build people systems and AI-first ways of working, and we run our own company on Claude. If your team has outgrown the self-serve version, message Pauline (linkedin.com/in/paulinebertry).

---

*Free to use inside your company, not for resale.*
