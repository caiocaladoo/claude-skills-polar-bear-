# Claude Guide for Product Strategy: 32 Claude Skills

32 Claude skills for one product strategy cycle, from the diagnosis to the roadmap and the quarterly review. For product managers and product leaders who own a strategy or a roadmap, and for founders and fractional product people who write one for a client.

**Guide and download:** [90n.ai/resources/product-strategy-pack](https://90n.ai/resources/product-strategy-pack)

## What this is

The guide follows one strategy cycle in the order you do it. You diagnose (the strategic question, the product's real state, an issue tree, hypotheses that can fail). You read the market and the customer (competitors by the customer's job, segments by need, an opportunity solution tree, a market size, a lean canvas for one bet). You choose (a vision, options that differ in kind, a decision matrix, the bets, the list of what you will not do). You stress-test the choice (scenarios, a red team review, a pre-mortem, a recommendation memo), put numbers on it (business case, north star metric, strategy KPIs), turn it into a roadmap (impact map, Now-Next-Later roadmap, quarterly OKRs), tell it (the strategy document, the one page, the deck, the roadmap review, the board memo) and review it (the decision record, the quarterly strategy review, the note you send when it changes). Each skill holds one method or one artifact, with the inputs it needs, where it breaks, a fixed output template, a finish line and the skill to run after it. Where a skill fits a Claude surface (Claude Docs, Claude Slides, file creation, read-only connectors, Claude in Chrome, Projects), it says so, and every skill also works in a plain chat.

Every skill holds one line: Claude structures the thinking and drafts the documents; the strategy is a set of choices a named person makes and can defend, built on what real customers did, and every figure names its source or is marked as an assumption.

```
Diagnose -> Market and customer -> Choose -> Stress-test -> Numbers -> Roadmap -> Tell it -> Review
```

## Install

### In Claude Code

```
/plugin marketplace add polar-bear-org/claude-skills
/plugin install product-strategy-pack@90n-skills
```

### In Claude.ai

1. Turn on "Code execution and file creation" under Settings > Capabilities.
2. Go to Customize > Skills, click "+", choose "+ Create skill", then "Upload a skill", and upload the skill's zip from the `install/` folder. Repeat for each skill you want.
3. On Team and Enterprise plans, an owner first enables "Cloud code execution and file creation" and "Skills" under Organization settings > Plugins & skills (Policy tab), and can upload skills for the whole organization.

## The skills

### 1 · Diagnose

| Skill | What it does | When to run it |
|---|---|---|
| [Strategic Question Frame](skills/strat-strategic-question/SKILL.md) | The one strategic question, the decision it feeds with its owner and date, horizon, scope in, out and taken as given, one alternative framing | A leader asks for "a strategy for X" and nobody in the room knows which decision is due |
| [Product Health Read](skills/strat-product-health-read/SKILL.md) | Four lenses (usage, quality, revenue signals, feedback), a source and date range per line, tracking changes flagged, what the data cannot tell | Planning starts from last quarter's deck and nobody has checked what is true today |
| [Issue Tree](skills/strat-issue-tree/SKILL.md) | The root question word for word, sub-questions split by one logic per level, overlap and coverage checks, the data that answers each leaf | The question is big and the team argues about which part to look at first |
| [Hypothesis Board](skills/strat-hypothesis-board/SKILL.md) | One hypothesis per branch that could be false, kill criteria written before any test, an importance by evidence map, the cheapest test for the top three | Everyone "knows" why the number fell and the team has collected data for weeks without a point |

### 2 · Market and customer

| Skill | What it does | When to run it |
|---|---|---|
| [Competitive Analysis](skills/strat-competitive-analysis/SKILL.md) | Landscape by the customer's job with workarounds and doing nothing as rows, a source and read date per cell, win and loss themes from buyers, where we differ, what not to copy | "The competitor has it" is setting the roadmap |
| [Needs-Based Segmentation](skills/strat-needs-based-segments/SKILL.md) | Job statements with circumstance and trigger, the current alternative, a size signal from aggregate data, the segment the strategy serves first and the ones it does not | "Our users" means four groups and the strategy tries to serve all of them |
| [Opportunity Solution Tree](skills/strat-opportunity-solution-tree/SKILL.md) | One outcome, opportunities that each cite an interview, a target opportunity, three ideas with the riskiest assumption, the slots marked "needs an interview" | The strategy's customer claims rest on what the team believes, not on what customers did |
| [Market Sizing (TAM, SAM, SOM)](skills/strat-market-sizing/SKILL.md) | Top-down and bottom-up estimates as low, base and high, every input sourced or labelled assumption, the gap between methods, the share the plan needs | Leadership asks how big this is and the number must survive "where does that come from?" |
| [Lean Canvas](skills/strat-lean-canvas/SKILL.md) | One canvas per segment filled problem first, every entry marked tested or untested, the three riskiest untested assumptions with the cheapest test | A new product or bet is moving from a conversation to a plan and every box is confident and unchecked |

### 3 · Choose

| Skill | What it does | When to run it |
|---|---|---|
| [Product Vision Board](skills/strat-product-vision/SKILL.md) | Vision statement options with what each rules out, target group by need, needs marked confirmed or assumed, product, business goals | The choices have no destination, so every option looks equally reasonable |
| [Strategic Options](skills/strat-strategic-options/SKILL.md) | Three to five options that differ in kind, "do nothing" with the cost of waiting, the bet each makes, what each gives up, reversibility | The options on the table are the leader's idea in three sizes |
| [Decision Matrix](skills/strat-decision-matrix/SKILL.md) | Criteria and weights dated before any score, pass or fail gates, a consequence table per option, scores with evidence, weight sensitivity | The decision meeting goes to whoever argues loudest |
| [Strategic Bets](skills/strat-strategic-bets/SKILL.md) | Three to five bets written as what would have to be true, the evidence today, the test or early signal, a kill criterion and date, an owner by role | The strategy is chosen and nobody has written what would prove it wrong |
| [Not-Doing List](skills/strat-not-doing-list/SKILL.md) | "We will not" lines with the reason, what saying no costs and who hears it, the short answer to give, the condition that would reopen it | The strategy was "agreed" and everything is still a priority |

### 4 · Stress-test

| Skill | What it does | When to run it |
|---|---|---|
| [Scenario Planning Model](skills/strat-scenario-planning/SKILL.md) | Base, upside and downside per option on two or three drivers, every value sourced or marked assumption, the assumption that flips the choice, early signals, as an editable spreadsheet | One forecast line is in the plan and everyone knows it is wrong |
| [Red Team Review](skills/strat-red-team-review/SKILL.md) | The assumptions the plan cannot survive losing, the strongest case against, counter-evidence on file, three sceptic questions, a change-now list, accepted risks | The plan looks finished and nobody has argued with it yet |
| [Pre-Mortem Analysis](skills/strat-pre-mortem-analysis/SKILL.md) | Failure defined at a date, failure stories gathered independently and clustered, early signal, prevention, contingency with trigger, owner by role | You are about to commit people and a quarter to the strategy |
| [Recommendation Memo](skills/strat-recommendation-memo/SKILL.md) | The call and the ask in the first line, three reasons tied to evidence, every rejected option with its fair case, risks, a one-minute answer to "why not the other option?" | The options are scored and stress-tested, and the next meeting will reopen it all unless one page says what to do |

### 5 · Numbers

| Skill | What it does | When to run it |
|---|---|---|
| [Business Case](skills/strat-business-case/SKILL.md) | One page in five parts, options including do nothing, an assumptions table with low, base, high, source and owner by role, what would change the answer | Finance wants a number and everyone knows the return is a guess |
| [North Star Metric](skills/strat-north-star-metric/SKILL.md) | Candidates tested against customer value, strategy and leading the business result, the exact definition, three to five inputs, a counter-metric per input | The team ships a lot and cannot say which number the strategy is meant to move |
| [Strategy KPIs](skills/strat-strategy-kpis/SKILL.md) | Per bet, the goal, signal and metric, leading and lagging indicators, baseline with source, a guardrail, the review date and the threshold to change course | Six months in, nobody can say whether the strategy is working |

### 6 · Roadmap

| Skill | What it does | When to run it |
|---|---|---|
| [Impact Map](skills/strat-impact-map/SKILL.md) | The goal with its measure, the actors, behaviour changes marked seen or assumed, every roadmap item under an impact or on a cut-or-justify list | The roadmap is a feature list and nobody can say whose behaviour each item changes |
| [Product Roadmap (Now, Next, Later)](skills/strat-product-roadmap/SKILL.md) | Items as problems linked to a strategy action, ordered by cost of delay over duration, placed by horizon with confidence, dated commitments flagged, "not on the roadmap", a one-screen executive cut | Every date becomes a promise and the board reads the roadmap as a commitment |
| [Quarterly OKRs](skills/strat-quarterly-okrs/SKILL.md) | One to three objectives tied to strategy actions, outcome key results with baseline, target and source, a capacity split, a stop list, grading of key results only | The quarter's goals are a task list and the plan is filled to the brim |

### 7 · Tell it

| Skill | What it does | When to run it |
|---|---|---|
| [Product Strategy Document](skills/strat-product-strategy-doc/SKILL.md) | The argument leadership reads and signs, two pages at most: diagnosis with evidence, guiding policy and what it rules out, three to five coherent actions, "we will not" lines, the bets | Nothing is written down to say no against |
| [One-Page Strategy](skills/strat-one-page-strategy/SKILL.md) | The signed strategy cut to one page for the teams who act on it, with no new content: what it means per team, a say-no test on three real requests, a repeat-from-memory test | Leaders signed the strategy and teams still cannot repeat it or use it to turn down a request |
| [Product Strategy Deck](skills/strat-product-strategy-deck/SKILL.md) | A ghost deck with action titles, presented in a room to win an endorsement: what is against what could be, the obstacle, the approach, the endorsement asked, a source on every claim slide | Leadership wants "the strategy on slides" and the meeting has to end in a yes, an amendment or a no |
| [Roadmap Review Deck](skills/strat-roadmap-review-deck/SKILL.md) | The ask first, shipped against said from the last review, the horizons by theme with confidence, the costed no list, the one decision needed | The roadmap shown in March is quoted back in September as broken promises |
| [Board Memo](skills/strat-board-memo/SKILL.md) | The product section in one or two pages read ahead: questions for the board first, progress against plan, the few metrics that matter with source, horizons with confidence, risks | The chief executive needs the product section by Friday and the last one was a dashboard dump |

### 8 · Review

| Skill | What it does | When to run it |
|---|---|---|
| [Strategy Decision Record](skills/strat-decision-record/SKILL.md) | Status, owner and date, the choice in the owner's words, options rejected, evidence and assumptions known at the time, dissent, review date and reopening triggers | Three months on, nobody remembers why this option won and the decision is argued again |
| [Quarterly Strategy Review](skills/strat-quarterly-strategy-review/SKILL.md) | Expected against happened, each bet read as holding, weakening or broken against its kill criterion, the cause, a keep, adjust or stop proposal per bet | Nobody can say whether the strategy is working, so direction changes with the loudest result |
| [Strategy Change Note](skills/strat-strategy-change-note/SKILL.md) | What changed and what did not, the evidence and the bet that broke, what stops and starts per team, the effect on the roadmap and on dated commitments | The strategy shifts and teams learn it from a reshuffled roadmap |

## How to choose a skill

```
Need to know which decision the strategy is for?         -> Strategic Question Frame
Need the product's real state before planning?           -> Product Health Read
Need to split a big question into parts?                 -> Issue Tree
Need first answers that can be proved wrong?             -> Hypothesis Board
Need to answer "the competitor has it"?                  -> Competitive Analysis
Need to say which customers the strategy serves first?   -> Needs-Based Segmentation
Need customer claims tied to interviews?                 -> Opportunity Solution Tree
Need a market number that survives questions?            -> Market Sizing (TAM, SAM, SOM)
Need the business logic of one new bet on a page?        -> Lean Canvas
Need a destination for the choices?                      -> Product Vision Board
Need options that are not one idea in three sizes?       -> Strategic Options
Need to compare options on criteria agreed first?        -> Decision Matrix
Need to write what would prove the strategy wrong?       -> Strategic Bets
Need a written list of what you will turn down?          -> Not-Doing List
Need base, upside and downside instead of one line?      -> Scenario Planning Model
Need the plan argued against before the review?          -> Red Team Review
Need the ways it could fail, before you commit?          -> Pre-Mortem Analysis
Need one page that makes the call and the ask?           -> Recommendation Memo
Need the money case for the chosen option?               -> Business Case
Need the one number the strategy should move?            -> North Star Metric
Need measures that show whether each bet is working?     -> Strategy KPIs
Need to tie roadmap items to behaviour changes?          -> Impact Map
Need a roadmap that is not read as a promise?            -> Product Roadmap (Now, Next, Later)
Need the quarter's goals as outcomes?                    -> Quarterly OKRs
Need the strategy written down for leadership to sign?   -> Product Strategy Document
Need the signed strategy on one page for the teams?      -> One-Page Strategy
Need to present the strategy and win an endorsement?     -> Product Strategy Deck
Need to report on the roadmap and ask for one decision?  -> Roadmap Review Deck
Need the product section of the board papers?            -> Board Memo
Need to record why this option won?                      -> Strategy Decision Record
Need to check each quarter whether the bets hold?        -> Quarterly Strategy Review
Need to tell teams the strategy changed, and why?        -> Strategy Change Note
```

## Example prompts

- "Our 'strategy' is a slide of goals and a feature list. Run strat-product-strategy-doc on it: tag the lines first, then draft the diagnosis from the evidence I paste."
- "The options on the table are the chief executive's idea in three sizes. Give me options that differ in kind, with do nothing as option zero."
- "We chose the self-serve option. Write the bets as what would have to be true, with a kill criterion and a date for each."
- "Here is our roadmap export. Rewrite the items as problems, order them by cost of delay over duration, and flag every dated commitment with who made it."
- "Everything is still a priority. Test these twelve live requests against the signed strategy and draft the not-doing list with the short answer for each."
- "It is the end of the quarter. Read each bet against the kill criterion we wrote in advance and propose keep, adjust or stop for the owner."

## Quality bar

- One method or one artifact per skill, with a fixed output template, so the output has the same shape every time.
- Real customers are not optional. Customer claims are tied to an interview or to data, or they are marked assumed, with the conversations still to have.
- No market number, baseline, cost or forecast comes from memory. Every figure names its source or carries the word assumption, and estimates are ranges.
- Options are scored and key results are graded. People, teams and sponsors never are.
- Kill criteria, criteria weights and review dates are written before the results arrive.
- Tax, accounting, contract, disclosure and board-duty points are flagged "check with a qualified adviser", never stated as advice.
- The red line: Claude structures the thinking and drafts the documents; the strategy is a set of choices a named person makes and can defend, built on what real customers did, and every figure names its source or is marked as an assumption.

## Where it comes from

The sources behind each method are in `resources/evidence-and-sources.md`.

## About the makers

This pack is made by 90n ([90n.ai](https://90n.ai)): AI-native ways of working and tools for Product, Marketing and HR teams, built by ex-McKinsey founders. We map where time and money leak, redesign the work around AI and stay until your people run it themselves, and we run our own company on Claude. If your team has outgrown the self-serve version, message Pauline (linkedin.com/in/paulinebertry).

---

*Free to use inside your company, not for resale.*
