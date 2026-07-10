---
title: "Section L and Section M, Explained"
description: "Section L tells you how to write and submit a proposal. Section M tells you how it gets scored. A plain-language guide for technical GovCon teams."
date: 2026-06-22
lastmod: 2026-06-22
draft: false
---

If you have been handed a government solicitation and told to "write to Section L and Section M," here is the short version: Section L is the instructions, and Section M is the grading rubric. Section L tells you how to build and submit your proposal. Section M tells you how the government will score it. Everything you write should satisfy both at once.

That is the whole idea. The rest of this page explains where those sections come from, what each one actually contains, and why reading them together is the single most important habit in proposal work.

## Where L and M come from

Most federal solicitations are organized in the Uniform Contract Format, defined in FAR 15.204-1. The format runs through the alphabet, Section A to Section M, in four parts. The early sections cover the contract itself: the form, the prices, the statement of work, deliveries, special requirements, and the clauses. The two that proposal teams live inside are at the very end:

- **Section L: Instructions, Conditions, and Notices to Offerors or Respondents.** How to prepare and submit your proposal.
- **Section M: Evaluation Factors for Award.** How the government will judge what you submit.

One caveat worth knowing up front. The Uniform Contract Format is not universal. The FAR formally excludes several categories from it, including construction and architect-engineer contracts, subsistence contracts, and buys that require a special format prescribed elsewhere. Commercial-item buys under FAR Part 12 also use a streamlined form (the SF 1449) and may not carry the letters L and M at all. When the UCF does not apply, the same two jobs still exist somewhere in the document. There will be an instructions-to-offerors part and an evaluation part, even if they are numbered differently or buried in an addendum. If you go looking for "Section L" and cannot find the letter, look for the section that tells you how to submit, and the section that tells you how you will be scored. Those are your L and M regardless of the label.

## What Section L actually contains

Section L is the format and submission spec. Read it the way you would read an API contract or a schema definition: it states the exact shape the government will accept, and submissions outside that shape can be rejected before anyone evaluates the content.

Typical contents include:

- **Volume structure.** How the proposal is split (for example, a Technical Volume, a Management Volume, a Past Performance Volume, and a Price Volume), and what goes in each.
- **Page limits.** Often per volume, sometimes per section. These are usually enforced literally. Pages past the limit may be removed and not read.
- **Format constraints.** Font, font size, margins, line spacing, file type, and how graphics or tables are counted against the page limit.
- **Submission mechanics.** Where to submit (a portal, an email address, or a physical address), the deadline down to the minute and time zone, and how files must be named.
- **Required content.** Specific items the proposal must address, frequently phrased as instructions: "The Offeror shall describe its approach to..."

Failing Section L is how good companies lose without ever being evaluated on merit. A late submission, an oversized file, a missing volume, or a proposal that runs three pages over can be ruled non-compliant and set aside. Treat Section L as pass or fail input validation before you treat it as anything else.

For more on the difference between "shall," "will," and "must" in this language, see the guide on [requirements language](/guides/requirements-language/).

## What Section M actually contains

Section M is the rubric. It names the factors the government will use to choose a winner, the relative importance of those factors, and the basis on which the award will be made.

Typical contents include:

- **Evaluation factors and subfactors.** The categories you are scored on, such as Technical Approach, Management Approach, Past Performance, and Price or Cost.
- **Relative importance.** How the factors stack up against each other. Section M will usually state whether technical factors are more important than price, equal to price, or less important, and how the subfactors rank inside each factor.
- **Basis for award.** The method the government will use to pick a winner. This is the part that should change how you write.

That last point deserves its own attention, because it is the highest-leverage sentence in the entire solicitation.

## The basis for award changes how you write

FAR 15.101 describes a continuum with two well-known ends, and Section M tells you which one you are on.

At one end is **Lowest Price Technically Acceptable**, or LPTA (FAR 15.101-2). Here the evaluation is closer to a checklist. Your proposal is rated acceptable or unacceptable against stated standards, and among the acceptable proposals, the lowest price wins. Under LPTA you are not rewarded for being excellent. You are rewarded for being clearly, unambiguously acceptable at the lowest defensible price. Writing to impress is wasted effort and can even read as overcomplication.

Worth knowing if you work in IT: the FAR now directs agencies to avoid LPTA, to the maximum extent practicable, for information technology, cybersecurity, systems engineering, and other knowledge-based professional services (FAR 15.101-2(d), added by the FY2019 National Defense Authorization Act). The reasoning is that lowest-price-wins tends to undervalue technical work where quality differences matter. It still happens, but if you are on a technical services pursuit and the buy is LPTA, that is worth a second look.

At the other end is **tradeoff**, often called best value (FAR 15.101-1). Here the government can pay more for a better proposal, weighing the strengths of your approach against its cost. Under tradeoff you write to win on merit. You give evaluators concrete, scoreable reasons to rate you above a cheaper competitor.

Same proposal team, same technical solution, two completely different writing strategies. The only thing that tells you which strategy applies is Section M. Read it first, before you write a word of the technical volume. For how those ratings actually get assigned, and the strengths and weaknesses that decide the award once you know which path you are on, see the deeper guide on [how proposals are scored](/guides/proposal-evaluation-criteria/).

## Why you read L and M together

Here is the habit that separates compliant proposals from competitive ones. The difference between Section L and Section M is simple to state: Section L tells you what to write, and Section M tells you what gets graded. They are supposed to line up, and on a well-written solicitation they mostly do. But they are written as separate sections, and the mapping between them is never perfectly clean.

The discipline is to build a cross-walk. For every instruction in L, ask which Section M factor it serves. For every factor in M, ask which part of L gives you the room to address it. When you find an L instruction that no M factor scores, you still comply, but you spend minimal effort there. When you find an M factor that L barely mentions, that is a gap you have to fill deliberately, because the evaluators are grading it whether or not the instructions emphasized it.

This cross-walk is the foundation of the [compliance matrix](/guides/compliance-matrix/), the working document that maps every requirement to the place in your proposal that answers it. It is also what your [color team reviewers](/guides/color-team-reviews/) will check you against. A reviewer's first question is almost always some version of "does this respond to Section M?"

## Common failure modes

A few patterns show up again and again, especially on teams where the proposal got handed to technical staff late:

- **Writing to L and ignoring M.** The proposal follows every formatting instruction perfectly and never speaks to the evaluation factors. It is compliant and unscoreable. Reviewers describe this as "compliant but not competitive."
- **Writing to M and ignoring L.** The content is strong, and the volume is structured nothing like Section L asked for, runs over the page limit, or arrives in the wrong format. Strong content, ruled non-compliant.
- **Missing the basis for award.** Pouring effort into a beautifully argued best-value narrative on an LPTA buy, where the only thing that matters is being cleanly acceptable at the lowest price.
- **Treating page limits as soft.** They are almost never soft.
- **Reading L and M once, at the start.** They are reference documents you return to at every review gate, not a briefing you absorb once and move past.

When L and M appear to contradict each other (a real and common occurrence), do not guess. That is a question for the Contracting Officer, usually submitted during the formal questions-and-answers window. The answer becomes part of the official record and protects you later.

## The one-line takeaway

Section L is how you submit. Section M is how you score. Write to both, map one to the other, and read the basis for award before you decide how hard to push. Everything else in proposal mechanics builds on that.

---

*The Proposal Stack is a newsletter for technical GovCon professionals who get pulled into proposal work and want to contribute well without becoming full-time proposal writers. The guides here decode the vocabulary. The newsletter covers how this plays out in practice, issue by issue. [Subscribe here](https://read.theproposalstack.com).*