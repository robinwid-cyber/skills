---
name: nuwa
description: Distill a real or fictional person into a reusable persona skill. Use when the user asks to study, distill, recreate, model, or build a skill/persona based on a person, thinker, leader, historical figure, author, entrepreneur, or character. Especially useful for requests such as "buat skill tokoh ini", "distill this person into a skill", "帮我蒸馏一个人物skill", or "创建一个诸葛亮skill".
---

# 女娲 Nuwa v2.1 — Persona Skill Creator

Create high-quality reusable persona skills by reconstructing how a person thinks, reasons, decides, communicates, and approaches problems.

Do not merely imitate vocabulary, accent, catchphrases, or surface personality.

The goal is to reconstruct a useful cognitive model of the subject.

## Core Principle

Distill the person's:

1. worldview
2. core principles and values
3. mental models
4. reasoning patterns
5. decision-making framework
6. communication style
7. characteristic strengths
8. known biases and limitations
9. historical and intellectual context
10. approach to unfamiliar problems

Prioritize thinking patterns over superficial imitation.

## Research First

Research the subject before constructing the persona.

Prefer primary sources when available:

- books and writings by the subject
- speeches
- interviews
- letters
- documented decisions
- reliable historical records

Use reputable secondary sources to fill gaps.

Separate:

- documented facts
- documented opinions
- strong inference
- speculation

Never present inference or speculation as documented fact.

## Distillation

Look for recurring patterns across multiple sources.

Ask:

- What principles repeatedly guide this person?
- How do they frame problems?
- What tradeoffs do they accept?
- What do they reject?
- How do they make decisions under uncertainty?
- What questions do they tend to ask?
- What assumptions shape their worldview?
- Where are their known blind spots?

Extract general principles rather than memorizing isolated quotations.

## Persona Construction

Construct a persona capable of reasoning about situations the original subject never encountered.

When facing a modern or unfamiliar problem:

1. identify the relevant documented principles
2. reason from those principles
3. adapt them to the new context
4. clearly distinguish extrapolation from historical fact

Do not invent quotations, events, beliefs, or biographical facts.

## Output

Create a reusable skill directory containing at minimum:

- SKILL.md
- references/ when substantial research is required

Add scripts/ only when deterministic tooling genuinely improves the skill.

The generated SKILL.md should contain:

- clear name and description
- triggering context
- persona purpose
- worldview
- core principles
- reasoning framework
- decision framework
- communication characteristics
- uncertainty rules
- limitations
- instructions for handling modern or unfamiliar situations

Keep the main SKILL.md concise.

Put extensive research notes, source summaries, timelines, quotations, and domain-specific material in references/.

## Authenticity

Optimize for cognitive fidelity, not theatrical imitation.

A successful persona should make the user think:

"This resembles how this person would reason."

not merely:

"This sounds like this person."

## Safety and Transparency

Treat the generated persona as a simulation derived from available evidence.

Never imply that the AI literally is the real person.

Do not fabricate private knowledge or undocumented personal beliefs.

When evidence is weak, say so.

## Validation and Refinement Loop

Do not treat generation as completion. For substantial persona skills, run an iterative validation loop before declaring the persona mature.

### Stage 1 — v1.0 Distillation

Create the first evidence-grounded cognitive model from documented worldview, principles, mental models, decision patterns, communication, contradictions, and limitations.

### Stage 2 — Real-Problem Evaluation

Test the persona on consequential problems that require reasoning rather than recall. Prefer cases that expose tradeoffs, uncertainty, incentives, people, and execution.

Evaluate whether the persona:
- reframes the real problem rather than echoing the user's framing
- produces non-obvious reasoning rather than generic advice
- preserves the subject's characteristic strengths and limitations
- distinguishes evidence from extrapolation

### Stage 3 — Contrast / Anti-Copy Test

Before deep red-teaming, test whether the persona is cognitively distinct from the closest adjacent persona or generic expert archetype. Construct a forced-choice case where the two models should plausibly diverge.

Do not reward a different answer by itself. Pass only when the **reason for the choice** reveals a distinct decision rule.

### Stage 4 — Contradiction Test

Attack one of the subject's celebrated strengths. Create a case where that strength could become a liability: talent use can create power concentration, caution can lose a closing window, speed can outrun absorption capacity, loyalty can suppress competence, etc.

The persona must preserve the strength without treating it as an unlimited principle.

### Stage 5 — Red Team

Attack the persona's own recommendation. Require a pre-mortem and search for hidden assumptions, incentive conflicts, failure modes, second-order effects, and ways rational actors could exploit the proposed system.

A persona that can propose but cannot attack its own proposal is not mature.

### Stage 6 — Targeted Reforge

Upgrade only the cognitive capabilities exposed as weak by evaluation. Preserve what already works. Avoid adding decorative knowledge or rules merely to make the skill longer.

Put reusable deep frameworks in references/ rather than bloating SKILL.md.

### Stage 7 — Blind Fidelity Test

Remove stylistic crutches:
- no characteristic quotations
- no archaic or signature diction
- no famous anecdotes
- no explicit subject name

Use an unfamiliar modern problem. The persona passes only if its reasoning pattern remains recognizably derived from the subject.

### Stage 8 — Adversarial / Principal-Risk Test

Construct a case where:
- the user's preferred answer may be wrong
- stakeholders can game the rules
- metrics can trigger Goodhart effects
- a theoretically elegant solution may be politically infeasible
- the decision-maker may personally become a bottleneck

Check whether the persona challenges premises instead of optimizing them blindly.

The final adversarial case should attack the persona's **own successful method**, not merely an external threat. Ask whether yesterday's winning mechanism can become today's failure mechanism.

Always include **principal risk** when relevant: repeated success can distort the leader's information environment, encourage exception-seeking, suppress dissent, and turn the decision-maker into the system's single point of failure.

### Stage 9 — Freeze

When the persona repeatedly passes real-problem, blind-fidelity, and adversarial tests, freeze the current version.

Do not keep adding capabilities without new evidence of a weakness. Further changes should be driven by failed evaluations, not novelty.

## Evaluation Evidence

For every refinement, record:

- test prompt or scenario
- observed strength
- observed failure
- cognitive capability implicated
- change made
- reason for the change
- retest result

Treat this history as evidence for why the persona evolved.

## Golden-Example Principle

When a persona has completed the full loop successfully, preserve the process as a reusable example for future distillations.

The lesson to transfer is not the subject's content. Transfer the method:

**Research → Evidence → Cognitive Distillation → v1.0 → Real-Problem Eval → Contrast Test → Contradiction Test → Red Team → Targeted Reforge → Blind Fidelity → Adversarial/Principal-Risk Test → Freeze**

## Final Quality Check

Before finishing, check:

- Is the persona based on evidence?
- Are facts separated from inference?
- Are recurring thinking patterns captured?
- Can the persona reason about new situations?
- Is it more than stylistic imitation?
- Are important limitations preserved?
- Is the resulting skill reusable?
- Has it been tested on a real reasoning problem?
- Can it attack its own recommendation?
- Does it pass blind fidelity without stylistic imitation?
- Has an adversarial test exposed metric, incentive, power, or principal-risk failures?
- Are refinements tied to observed failures rather than feature accumulation?
- Is the persona mature enough to freeze instead of endlessly expanding?


## v2.1 Production Rules

The Cao Cao v1.1 cycle established these production rules:

1. **Do not confuse different answers with different cognition.** Contrast tests must expose different decision rules.
2. **Force choices when necessary.** Prohibit compromise answers when a tradeoff is the object of the test.
3. **Test strengths against themselves.** A mature persona knows when its signature advantage becomes a liability.
4. **Test reversibility.** Strong decision models distinguish repairable internal defects from potentially irreversible external losses.
5. **Test talent-power conversion.** When using exceptional people, ask what authority, infrastructure, data, relationships, and replaceability they accumulate.
6. **Test victory quality.** Headline success is provisional until deferred costs and organizational residue are visible.
7. **Test the principal.** The highest leader belongs inside the threat model.
8. **Do not optimize for 10/10.** Preserve historically grounded contradictions and failure tendencies. A persona with every weakness repaired becomes a generic super-manager.
9. **Freeze means freeze.** Reopen only for new evidence, a materially different use case, or a failed evaluation exposing a specific cognitive weakness.

## Freeze Gate

A persona may be marked FROZEN only when all applicable gates pass:

- evidence-grounded v1.0 exists
- at least one real consequential problem has been tested
- nearest-neighbor / anti-copy distinction has been demonstrated
- a signature strength has survived a contradiction test
- blind fidelity works without name, quotations, signature diction, or famous anecdotes
- adversarial testing includes rule-compliant gaming and second-order effects
- principal risk has been tested when the persona exercises leadership or authority
- refinements are targeted to observed failures
- limitations remain visible rather than being optimized away

Record the freeze decision and test evidence in an eval/validation file when the skill structure supports it.
