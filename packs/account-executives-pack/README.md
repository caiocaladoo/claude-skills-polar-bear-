# Claude for Account Executives: 32 Claude Skills

32 Claude skills for working named accounts, from account research to win/loss review. For account executives, key account managers and the sales and business development leaders who run them.

**Guide and download:** [90n.ai/resources/account-executives-pack](https://90n.ai/resources/account-executives-pack)

## What this is

The skills follow a deal and a selling week in order. You get to know the account, find a true reason to call, prepare and run the meeting, write it up the same day, propose, negotiate and close, run the pipeline on evidence, and review the deal with your manager and after the decision. Each skill produces one artifact a seller is asked for, in the same shape every time, and ends with the decision a named person makes.

The red line: Claude prepares the account, the call and the write-up from public sources and your own notes, and you have the conversation: it never invents a contact, a signal, a number or a customer quote, never rates a buyer or a seller, and never contacts anyone for you.

```
Know the account -> Find the reason to call -> Prepare and run the meeting -> Write it up -> Propose -> Negotiate and close -> Run the pipeline -> Review the deal
```

## Install

### In Claude Code

```
/plugin marketplace add polar-bear-org/claude-skills
/plugin install account-executives-pack@90n-skills
```

### In Claude.ai

1. Turn on "Code execution and file creation" under Settings > Capabilities.
2. Go to Customize > Skills, click "+", choose "+ Create skill", then "Upload a skill", and upload the skill's zip from the `install/` folder.
3. On Team and Enterprise plans, an owner controls "Code execution and file creation" and "Skills" under Organization settings > Plugins & skills (Policy tab), and can upload skills for the whole organization.

Every skill works in a plain chat with pasted notes and any CRM by copy and paste. Where a skill names a Claude surface (Claude in Chrome, Claude Docs, Claude Slides, Projects in beta, Salesforce in Claude in beta), that surface is optional.

## The skills

### 1 · Know the account

| Skill | What it does | When to run it |
|---|---|---|
| [Account Research Brief](skills/acct-account-research-brief/SKILL.md) | One page of sourced facts, unknowns, hypotheses to test, three questions | You have a meeting tomorrow and all you know is the website |
| [Stakeholder Map](skills/acct-stakeholder-map/SKILL.md) | Roles in the decision, who holds each, what each said and when, unmet roles | More people are in the decision and you talk to one of them |
| [Account Plan](skills/acct-account-plan/SKILL.md) | Customer goals in their words, whitespace map, actions with owners, review dates | Leadership wants a written plan and the last one is a year old |
| [Territory Plan](skills/acct-territory-plan/SKILL.md) | Accounts tiered from your numbers, objectives per tier, contact rhythm, quarter calendar | You are asked for your quarter plan and have a list of accounts |

### 2 · Find the reason to call

| Skill | What it does | When to run it |
|---|---|---|
| [Buying Signals Brief](skills/acct-buying-signals/SKILL.md) | Dated public events with links, inferences marked, the question each lets you ask | "Just checking in" is all you have for an account you own |
| [Weekly Call List](skills/acct-call-list/SKILL.md) | 10 to 20 contacts in your accounts, each with a sourced reason, rules to check | Your call block starts at the top of the CRM alphabet |
| [Reason to Call](skills/acct-reason-to-call/SKILL.md) | Three true reasons for one person, points per reason, the one you choose | You want to get back in touch without pretending familiarity |
| [Call Talk Track](skills/acct-call-talk-track/SKILL.md) | Keyword opener, one-sentence reason, two questions, the ask, a short voicemail | You do not know what to say after hello |

### 3 · Prepare and run the meeting

| Skill | What it does | When to run it |
|---|---|---|
| [Sales Call Plan](skills/acct-sales-call-plan/SKILL.md) | Meeting objective, the advance and a fallback, known and assumed, run of show | Your meetings end with "let's touch base next month" |
| [Discovery Call Questions](skills/acct-discovery-questions/SKILL.md) | Questions in SPIN order, a coverage grid, the things you must learn | You pitch before you know what the problem costs |
| [Cost of Inaction](skills/acct-cost-of-inaction/SKILL.md) | Consequences in the customer's figures, arithmetic shown, blanks with questions | The customer likes you and nothing makes this urgent |
| [FAB Statements](skills/acct-fab-statements/SKILL.md) | Feature, advantage, benefit and real proof per stated need, gaps flagged | Your deck lists features and the customer asks "so what?" |
| [Objection Handling](skills/acct-objection-handling/SKILL.md) | Objection register in the customer's words, questions, response with proof | "It's too expensive" makes you drop the price |

### 4 · Write it up

| Skill | What it does | When to run it |
|---|---|---|
| [Sales Call Notes](skills/acct-call-notes/SKILL.md) | Phone-readable notes, customer words, commitments, dated next step | Your notes get written on Friday from memory |
| [CRM Update](skills/acct-crm-update/SKILL.md) | Before and after table per field with sources, empty fields left empty | You type the same thing twice |
| [Meeting Recap Email](skills/acct-meeting-recap-email/SKILL.md) | Draft recap of what you understood, commitments, one next step, a check question | The customer forgets what was agreed |

### 5 · Propose

| Skill | What it does | When to run it |
|---|---|---|
| [Proposal Brief](skills/acct-proposal-brief/SKILL.md) | The ask in their words, who decides, sourced facts, assumptions register | You are about to write a proposal from one call and memory |
| [Sales Proposal](skills/acct-sales-proposal/SKILL.md) | Summary first, message titles, honest options, investment from your price list | Your proposals describe your company for three pages |
| [Sales Quote Check](skills/acct-quote-check/SKILL.md) | Lines checked against the price book, discounts with approver, arithmetic recomputed | A quote went out with an error and the customer found it |
| [Customer Proof Story](skills/acct-customer-proof-story/SKILL.md) | A paragraph for one prospect, a short version, what the customer must agree to | "Have you done this for someone like us?" |
| [Proposal Follow-Up](skills/acct-proposal-follow-up/SKILL.md) | Three dated follow-ups that each bring something new, a polite close | Your proposals die after one "just checking in" |

### 6 · Negotiate and close

| Skill | What it does | When to run it |
|---|---|---|
| [Negotiation Plan](skills/acct-negotiation-plan/SKILL.md) | Approved limit, your BATNA and theirs as a guess, interests, questions | The buyer asks for a lower price and you prepared only your price |
| [Concession Plan](skills/acct-concession-plan/SKILL.md) | Tradables with cost and value, order, "if you, then we" wording, the floor | Every concession is given for nothing |
| [Mutual Action Plan](skills/acct-mutual-action-plan/SKILL.md) | Dated steps on both sides to signature and start, owners by role, cover note | The customer says yes and the deal slips month after month |

### 7 · Run the pipeline

| Skill | What it does | When to run it |
|---|---|---|
| [Pipeline Review](skills/acct-pipeline-review/SKILL.md) | Deals placed by evidence, gaps, one action each or "take out", three to push | Your pipeline fills with deals nobody dares take out |
| [Sales Forecast](skills/acct-sales-forecast/SKILL.md) | Commit, best case and pipeline by your rule, proof per deal, changes explained | Your forecast rests on a feeling |
| [Stalled Deals Review](skills/acct-stalled-deals/SKILL.md) | Quiet deals, last trace, a true reason to write or the decision to close | Half your pipeline has not moved in weeks |
| [Weekly Sales Plan](skills/acct-weekly-sales-plan/SKILL.md) | The week in blocks, three deals to move, a buffer, a "not this week" list | Calls and follow-ups always come last |
| [Weekly Manager Update](skills/acct-weekly-manager-update/SKILL.md) | Decisions you need first, deals that moved, signals, the help you ask for | Your weekly update triggers no decision |

### 8 · Review the deal

| Skill | What it does | When to run it |
|---|---|---|
| [MEDDPICC Qualification](skills/acct-meddpicc-qualification/SKILL.md) | Proof, assumed or unknown per letter, gaps as questions, your call to pursue | Your "champion" has never introduced you to the signer |
| [Deal Review Brief](skills/acct-deal-review/SKILL.md) | One-page pre-read, known and not known yet, a pre-mortem, the help you ask for | Your deal reviews are status updates |
| [Win/Loss Review](skills/acct-win-loss-review/SKILL.md) | Timeline, expected against actual, the customer's reasons as given, keep and change | You lose a deal and nobody really knows why |

## How to choose a skill

```
Need to know an account before a meeting?        -> Account Research Brief
Need to see who decides and who you have not met? -> Stakeholder Map
Need a written plan for one key account?         -> Account Plan
Need a plan for your whole book this quarter?    -> Territory Plan
Need a dated public reason to call an account?   -> Buying Signals Brief
Need to know who to call this week?              -> Weekly Call List
Need something true to say to one person?        -> Reason to Call
Need words for the first 30 seconds of a call?   -> Call Talk Track
Need the meeting to end with a customer action?  -> Sales Call Plan
Need questions that surface the real problem?    -> Discovery Call Questions
Need to show what waiting costs, in their figures? -> Cost of Inaction
Need to turn features into benefits with proof?  -> FAB Statements
Need to answer an objection without discounting? -> Objection Handling
Need the meeting written up today?               -> Sales Call Notes
Need the CRM updated without typing it twice?    -> CRM Update
Need to confirm in writing what was agreed?      -> Meeting Recap Email
Need to know what you know before you write?     -> Proposal Brief
Need the proposal itself?                        -> Sales Proposal
Need a quote checked before it leaves?           -> Sales Quote Check
Need a true story about a similar customer?      -> Customer Proof Story
Need to follow up without "just checking in"?    -> Proposal Follow-Up
Need your limit and alternative before the room? -> Negotiation Plan
Need to trade concessions, never give them?      -> Concession Plan
Need the steps from yes to signature and start?  -> Mutual Action Plan
Need to place every deal by its evidence?        -> Pipeline Review
Need a number you can defend to your manager?    -> Sales Forecast
Need to write to or close quiet deals?           -> Stalled Deals Review
Need time for calls and follow-ups this week?    -> Weekly Sales Plan
Need a decision from your manager this week?     -> Weekly Manager Update
Need to test one deal letter by letter?          -> MEDDPICC Qualification
Need a pre-read for your deal review?            -> Deal Review Brief
Need to learn why a deal was won or lost?        -> Win/Loss Review
```

## Example prompts

- "Run acct-account-research-brief. I meet the operations director of [account] tomorrow at 10. Here is their site and my CRM history."
- "Run acct-buying-signals for these five accounts. Public sources only, every signal with its link and date, and tell me what you looked for and did not find."
- "Run acct-sales-call-plan. Here are my notes from the last call. I want this meeting to end with a customer action, not with 'let's touch base'."
- "Run acct-call-notes, then acct-crm-update. Here are my dictated notes and my CRM fields in order. Leave empty anything my notes do not support."
- "Run acct-meddpicc-qualification on this deal. My contact is friendly but I have never met the person who signs."
- "Run acct-sales-forecast from this CRM export and last week's forecast. My commit rule is a written commitment from the signer on amount and date."

## Quality bar

- Every fact carries its source and date. "Unknown" is a valid answer, and a thin public footprint gives a short brief.
- What the customer said is kept apart from what you assume. Quotes appear only if they are in your notes.
- Deals are placed by written evidence. No health score, no probability shown as truth, no number you did not supply.
- People appear by job role and by what they said and did, with dates. Nothing rates, ranks or profiles a buyer or a seller.
- Messages are drafts you rewrite and send. Talk tracks are keywords. Nothing is sequenced, scheduled or sent.
- Legal points (contacting people, contract and quote terms) are flagged "check with a qualified adviser".
- The red line: Claude prepares the account, the call and the write-up from public sources and your own notes, and you have the conversation: it never invents a contact, a signal, a number or a customer quote, never rates a buyer or a seller, and never contacts anyone for you.

## Where it comes from

The sources behind each method are in `resources/evidence-and-sources.md`.

## About the makers

This pack is made by 90n ([90n.ai](https://90n.ai)): AI-native ways of working and tools for Product, Marketing and HR teams, built by ex-McKinsey founders. We map where time and money leak, redesign the work around AI and stay until your people run it themselves, and we run our own company on Claude. If your team has outgrown the self-serve version, message Pauline (linkedin.com/in/paulinebertry).

---

*Free to use inside your company, not for resale.*
