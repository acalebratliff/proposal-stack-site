---
title: "How to Write a Basis of Estimate (BOE)"
description: "A basis of estimate justifies the hours and resources behind your price. How to build one that survives cost realism, for technical GovCon teams who got handed the cost story."
date: 2026-07-10
lastmod: 2026-07-10
draft: false
---

A basis of estimate, or BOE, is the written explanation of how you arrived at the numbers in your cost proposal. It is the paper trail behind "we need 4,200 labor hours for this task": what the work is, how you decomposed it, what method you used to size it, what you assumed, and why the total is credible. If someone handed you a spreadsheet and asked you to "write the BOE for your piece," they are asking you to justify your hours in a way a skeptical stranger can follow and believe.

Here is the part that catches technical people off guard. You are being asked because you are the only one who actually knows how much work the task takes. The pricing team can apply rates and roll up totals, but they cannot invent the level of effort for a system migration or a security accreditation. That number is yours, and the BOE is where you defend it.

## Why a BOE exists, and when you will be asked for one

Not every proposal requires a BOE. They show up on cost-reimbursement contracts, large or complex fixed-price efforts, IDIQ and GWAC task orders, and any solicitation whose instructions ask for a narrative behind the price. [Section L](/guides/section-l-and-section-m/) is where you find out. Look for language like "provide a narrative explanation of cost assumptions" or "submit a basis of estimate for proposed labor." When the solicitation asks, the BOE is a scored, evaluated part of your proposal, not a back-office formality.

The reason it exists is that a price with no explanation is impossible to trust. A number by itself could be careful analysis or a wild guess, and the government cannot tell which from the figure alone. The BOE converts a bottom-line price into a reviewable argument. That is why the rationale matters as much as the total, and often more.

## The BOE starts from the work, not the number

A defensible BOE is built from the work definition outward, in a specific order. Reversing that order, starting from a target price and working backward to justify it, is exactly what evaluators are trained to catch.

The chain runs like this. The [SOW, PWS, or SOO](/guides/sow-pws-soo/) defines the work. You decompose that work into a structure of tasks and subtasks, commonly a work breakdown structure (WBS), so that every piece of effort has a home. For each element, you estimate the resources it needs: labor hours by skill category, materials, subcontracted effort, and other direct costs such as travel or specialized equipment. Then you explain, element by element, how you arrived at each estimate. The pricing team takes it from there, applying labor rates, indirect rates, and fee to turn your hours into dollars. Your job stops at the credible estimate of what the work requires. The accounting is theirs.

Two things make this chain hold together. Every estimate traces to the work breakdown, so there are no orphaned hours and no gaps. And every estimate traces to a source, whether that is historical data from a similar contract, a vendor quote, or a documented rationale. An estimate you cannot trace is an estimate an evaluator will discount.

## The estimating methods, and when to use each

How you size a task determines how defensible it is. There are four standard estimating methods, and a strong BOE names the one it used and says why. They are not interchangeable, and picking the wrong one for the situation is a common way to produce a number that does not hold up.

| Method | How it works | Best when | Watch out for |
| --- | --- | --- | --- |
| Analogy | Scale a similar past effort to fit the new one, adjusting for the differences | An early estimate, or a close analog exists | Differences you fail to account for |
| Parametric | Drive cost from a measured relationship, such as hours per server migrated | The work is well-characterized and repeatable | A relationship that does not actually hold here |
| Engineering build-up | Decompose to the lowest tasks, estimate each, and sum | You need a detailed, defensible BOE | The effort it takes, and double-counting |
| Expert judgment | Structure the input of people who have done the work | Little historical data exists yet | No paper trail, and hard to defend on its own |

Engineering build-up, also called a bottoms-up estimate, is the most defensible and the most work, because it forces you to account for every task. It is the default for a detailed BOE. The others have their place, especially early or where data is thin, but the more your estimate rests on judgment alone, the more an evaluator has to take on faith, and faith is not what wins a cost evaluation.

## What a strong BOE element contains

Whatever method you use, each element of the estimate should make four things explicit:

- **The task, tied to the work breakdown.** What effort this covers, mapped to the SOW or PWS requirement it satisfies, so nothing is orphaned and nothing is missing.
- **The estimate, quantified.** Hours by labor category, quantities of materials, subcontractor scope. "Three full-time engineers over twelve months at 1,920 hours each" is reviewable. "A team of engineers" is not.
- **The rationale.** The method you used and the reasoning behind the number. This is the actual basis, and it is the part technical writers most often skip. A number with no rationale is a number an evaluator strikes.
- **The assumptions and exclusions.** What you assumed to be true (government-furnished equipment available on day one, a stable requirement, a given environment) and what you deliberately left out. Stated assumptions protect you later; unstated ones become disputes during performance.

## Cost realism: the number has to be believable

Here is the concept that decides whether a BOE survives evaluation. On many procurements, the government does not just check whether your price is reasonable (not too high). It checks whether your price is *realistic* (not too low). That analysis is called cost realism, defined in FAR 15.404-1(d)(1) as independently reviewing each offeror's proposed cost elements to determine whether they are realistic for the work, reflect a clear understanding of the requirements, and are consistent with the offeror's own technical proposal.

Read that last clause again, because it is the technical writer's whole stake in the cost volume. Your BOE has to be consistent with what your [technical approach](/guides/technical-approach-section/) promised. If the technical volume says you will automate a process and the BOE prices five people doing it by hand, the evaluator sees a contradiction, and a contradiction reads as one of two things: either you do not understand your own solution, or you are padding. Both cost you.

The teeth are sharpest on cost-reimbursement work. Under FAR 15.404-1(d)(2), the government performs a cost realism analysis and calculates a "probable cost" for each offeror, which can differ from what you proposed, and it evaluates you on that probable cost rather than your number. In plain terms, if you low-ball the hours to win, the government can adjust your evaluated cost upward to what it believes the work will actually take, erasing the advantage you were reaching for. Under-scoping to look cheap is not a shortcut. It is a way to be judged on a number you did not write, and often to signal that you did not understand the job.

## Common failure modes

- **Reverse-engineering from a target price.** Deciding the answer and back-filling rationale. Evaluators are specifically looking for this, and thin or generic justification is the tell.
- **Hours with no basis.** A number in a cell with no method and no source behind it. It cannot be defended and will be discounted.
- **A BOE that contradicts the technical volume.** The fastest way to fail cost realism. The two documents have to tell the same story about how the work gets done.
- **Unstated assumptions.** What you left unsaid becomes a fight during performance, usually one you lose. Write the assumptions down.
- **Under-scoping to win.** On cost-type work the government can reprice you to probable cost, so buying in with low hours often backfires and damages your credibility on understanding.
- **Gaps and orphans.** Effort in the estimate that maps to no requirement, or requirements with no effort estimated. The work breakdown is what keeps both from happening.

## The one-line takeaway

A basis of estimate is the argument behind your hours: build it from the work breakdown outward, size each element with a named method and a traceable source, state your assumptions, and keep it consistent with your technical approach. The evaluator is checking whether your number is believable, so write to be believed, not just to be low.

---

*The Proposal Stack is a newsletter for technical GovCon professionals who get pulled into proposal work and want to contribute well without becoming full-time proposal writers. The guides here decode the vocabulary. The newsletter covers how this plays out in practice, issue by issue. [Subscribe here](https://read.theproposalstack.com).*
