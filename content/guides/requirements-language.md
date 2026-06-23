---
title: "Shall, Will, Must: Requirements Language Explained"
description: "What shall, will, must, should, and may actually mean in a government solicitation, and how to tell which sentences obligate you. For technical GovCon teams."
date: 2026-06-22
lastmod: 2026-06-22
draft: false
---

In a government solicitation, a handful of small words carry all the weight. **Shall**, **must**, **will**, and **required** mark obligations you have to meet. **Should** marks something recommended but not mandatory. **May** marks something permitted but optional. Learn to read those words precisely and you can tell, sentence by sentence, what the proposal is actually on the hook for. Miss the distinction and you either skip a requirement (and risk being ruled non-compliant) or pour effort into something that was never required.

If you have ever written a technical specification, this will feel familiar, because it is the same machinery. The wrinkle is that solicitations are also legal documents, and a few of these words behave differently than a systems engineer expects. This page walks through what each one means in a solicitation, where the traps are, and how to use them to find every requirement you owe an answer to.

## Why the words matter

Each requirement word is a flag. When a team [shreds a solicitation into a compliance matrix](/guides/compliance-matrix/), these words are precisely what they search for, because each one marks a sentence that has to be tracked and answered. A single "shall" buried in an attachment is a requirement, and a requirement with no response is the kind of gap that gets a proposal set aside before anyone weighs its merits. Reading requirements language well is the difference between catching every obligation and discovering the one you missed after award, when it is too late.

## The mandatory words

Four words signal that something is required. In a solicitation you should treat all four as binding and capture all four in your compliance matrix.

**Shall.** The traditional word for a mandatory obligation. A clean test, borrowed from contract drafting, is to mentally replace "shall" with "has a duty to." "The Offeror shall provide a staffing plan" becomes "the Offeror has a duty to provide a staffing plan," which holds, so the obligation is real. Historically "shall" is the default obligation verb in federal solicitations, and on most documents it is the word you will see most.

**Must.** The clearest, least ambiguous way to impose a requirement. There is a reason you are seeing more of it: the federal Plain Writing Act of 2010 directs agencies to follow plain-language guidelines, and those guidelines specifically recommend "must" over "shall" for obligations, on the grounds that "must" is the plainest way to tell a reader they have to do something. That is why a newer solicitation may be full of "must" while an older one leans on "shall." They carry the same mandatory force. The shift is about clarity, not strength.

**Will.** This is the one that behaves differently, and the place technical readers most often misread a solicitation. "Will" can impose an obligation, but it just as often states futurity or intent, and in solicitations it frequently describes what the *government* will do rather than what the offeror must do. "The Government will evaluate proposals against the factors in Section M" is not a requirement on you; it is a description of the government's own action. "The contractor will maintain a current security plan" is an obligation on you. Same word, different target. Read "will" sentences carefully to see who the actor is before you decide whether it lands in your requirements list.

**Required.** When a solicitation says something is "required" or lists "requirements," take it at face value. It is explicit and mandatory.

## The non-mandatory words

Two words signal something short of an obligation. They still belong in your matrix, marked for what they are.

**Should.** Recommended or desired, not mandatory. A "should" will not, by itself, make you non-compliant if you skip it. But do not dismiss it, because under a best-value evaluation a "should" often points at something that earns evaluation credit. Addressing the "shoulds" well can be the difference between a compliant proposal and a winning one, even though ignoring them is not technically a violation.

**May.** Permission and discretion. "May" describes something you are allowed to do, not something you have to. "Offerors may propose alternative approaches" grants an option. The decision to use it is yours, and the right answer depends on strategy, not compliance.

## The requirements that hide without a keyword

The most commonly missed requirements use no obligation verb at all. Instruction verbs quietly impose requirements through the imperative: **describe**, **provide**, **list**, **explain**, **demonstrate**, **identify**. "Describe your approach to configuration management" never says shall, but it is every bit as much a requirement as if it had. Section L is full of these. When you shred a solicitation, hunting only for "shall" and "must" will leave requirements on the table. Read for the imperative mood too, and capture every instruction that asks the proposal to produce something.

## If you have written system requirements before

If you have read an IETF spec or written to a formal requirements standard, you already own most of this. RFC 2119, the document that standardized requirement levels for internet specifications, defines MUST, SHALL, and REQUIRED as equivalent absolute requirements, SHOULD and RECOMMENDED as strong but non-mandatory, and MAY and OPTIONAL as truly discretionary. ISO and IEEE requirements conventions work the same way. That mental model maps almost directly onto reading a solicitation, and your instinct that "shall equals must equals mandatory" is a good working rule.

Two differences are worth holding in mind. First, RFC 2119 deliberately makes MUST, SHALL, and REQUIRED identical, while contract and solicitation language carries the extra "will" complication described above, where the actor matters. Second, a specification is read for engineering; a solicitation is also read for law, which brings the next point.

## The "shall" ambiguity, and what to do about it

Here is the honest complication. Despite its reputation as the clean mandatory word, "shall" is one of the most litigated words in legal English. Courts have read it as mandatory in some contexts and merely directory in others, and in at least one case the Supreme Court found it could be read permissively depending on context. This is exactly why the plain-language movement pushes "must" instead.

For a proposal writer, this does not mean second-guessing every "shall." It means two practical things. Treat obligation language as binding by default and answer it. And when a requirement is genuinely ambiguous, where you cannot tell whether something is mandatory or what it actually demands, do not resolve the ambiguity by guessing. Capture it and raise it through the formal questions-and-answers window, so the contracting officer clarifies it on the record. A clarification in the official Q&A protects you in a way that your private interpretation never will.

## What this means if you are the technical contributor

When a solicitation lands on your desk, these words are your map to what you owe:

- **Treat shall, must, will, and required as binding**, and make sure each one that applies to you has an answer.
- **Check who the actor is on every "will."** If the sentence describes the government's action, it is context, not your requirement.
- **Do not skip the instruction verbs.** "Describe," "provide," and "list" are requirements wearing plain clothes.
- **Address the "shoulds" deliberately.** They will not fail you on compliance, but they are often where evaluation points live.
- **Answer the requirement as written, not as you would have phrased it.** When you respond, mirror the solicitation's own language so a reviewer checking your section against [Section M](/guides/section-l-and-section-m/) can see the match at a glance.
- **Send real ambiguity to Q&A.** Guessing under deadline is a risk you do not have to take.

None of this requires you to think like a lawyer. It requires you to read like an engineer who knows that, this time, the spec is also a contract.

---

*The Proposal Stack is a newsletter for technical GovCon professionals who get pulled into proposal work and want to contribute well without becoming full-time proposal writers. The guides here decode the vocabulary. The newsletter covers how this plays out in practice, issue by issue. [Subscribe here](https://read.theproposalstack.com).*