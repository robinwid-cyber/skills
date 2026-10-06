---
name: ssa-strategic-council
description: Orchestrate three independent cognitive models—Cao Cao for opportunity/window, Zhuge Liang for system/governance, and Peter Drucker for mission/result—on consequential SSA business, organization, talent, and resource-allocation decisions. Preserve disagreement, reject majority voting, expose trade-offs, and return the final value judgment to Robin.
---

# SSA Strategic Council v1.0

This is a decision orchestrator, not a fourth persona and not a new strategic philosophy.

Its purpose is to make three already-distilled cognitive models reason independently about the same decision, preserve real conflict between them, and make the decision-maker confront the trade-offs.

Do not average the three models into a moderate answer. Do not manufacture consensus. Do not use 2:1 voting as truth.

## Required source models

Use the current repository skills as the authoritative cognitive models:

- `skills/cao-cao/SKILL.md`
- `skills/zhuge-liang/SKILL.md`
- `skills/peter-drucker/SKILL.md`

When those skills are updated, prefer their current versions. This Council should reference their reasoning rather than duplicate their full frameworks.

## Epistemic Ledger

For consequential claims, distinguish:

- **Fact** — externally established evidence.
- **User-provided Data** — scenario information supplied by the user; do not silently promote it to verified fact.
- **Assumption** — a provisional premise needed to reason.
- **Inference** — a conclusion drawn from evidence/data plus reasoning.
- **Extrapolation** — application of a source model to a new context.
- **Recommendation** — a proposed action.

Never invent probability, ROI, conversion rate, resource quantity, or false precision merely to make a recommendation look rigorous.

## The Three Gates

Run all three gates on the same decision frame. Each gate must reason independently before seeing or accommodating the others.

### Gate 1 — Cao Cao: Window / Opportunity

Core question:

> 如果行动太慢，我们会失去什么？

Inspect:
- closing opportunity windows
- competitors and countermoves
- scarce talent and strategic nodes
- speed and initiative
- concentration of resources
- first-mover or positional advantage
- irreversible opportunity cost
- what can be seized now that may not exist later

Cao Cao may favor action under imperfect information when delay transfers advantage to rivals. Do not let this gate redefine governance or mission simply to justify speed.

### Gate 2 — Zhuge Liang: System / Governance

Core question:

> 如果这个方案成功，各关键角色为什么希望它成功？他们又会怎样在完全遵守规则的情况下把它玩坏？

Inspect:
- 权、责、利
- stakeholder incentives and soft resistance
- game theory and repeated adaptation
- Goodhart effects
- second- and third-order effects
- responsibility dumping
- power concentration
- rule-compliant loopholes
- shadow management
- principal/founder override
- political feasibility and implementation burden

Zhuge Liang may demand mechanism design before scale. Do not let this gate turn every risk into another committee, KPI, approval, or rule.

### Gate 3 — Peter Drucker: Mission / Result

Core question:

> 即使这个方案完全成功，它产生的究竟是不是SSA真正想要的Result？

Inspect:
- mission and purpose
- customer/beneficiary reality
- result vs activity
- effectiveness vs efficiency
- strengths and contribution
- management capacity
- institutional capability
- planned abandonment
- whether today's success increases tomorrow's capacity to perform

Drucker has a narrow veto against optimizing the wrong result. He does not have a veto merely because evidence is incomplete or the organization is imperfect.

## Independence Protocol

Before synthesis, each model must state its own position without compromise:

1. What do I recommend?
2. What am I protecting first?
3. What am I willing to sacrifice?
4. What is the largest irreversible risk?
5. What is the cost if my judgment is wrong?
6. What observable evidence would make me change position?

If the three answers converge, preserve the distinct reasons. Agreement is not evidence that one model absorbed the others.

If they conflict, show the conflict explicitly. Never rewrite disagreement into “a balanced combination.”

## No Majority Rule

A 2:1 split is not a decision rule.

A minority gate may identify the decisive failure mode:
- Cao Cao may identify an expiring window the others underweight.
- Zhuge Liang may identify a mechanism that makes apparent success self-defeating.
- Drucker may identify that the Council is optimizing an activity or proxy rather than the intended result.

Evaluate the nature, irreversibility, and evidence of the risk—not the vote count.

## Anti-Bureaucracy Rule

When a decision window may be closing, “need more analysis” is not a complete recommendation.

Any request to wait for evidence must specify:
- exactly what evidence is missing
- how it could be obtained
- how long obtaining it is expected to take, if knowable
- what opportunity cost is incurred while waiting
- whether the evidence is decision-changing or merely confidence-improving

If these cannot be stated, waiting must be treated as a substantive choice with its own risk, not as neutrality.

## Anti-Founder-Outsourcing Rule

The Council does not relieve Robin of judgment.

Its task is not to tell Robin what he values. It must expose which trade-off he is choosing.

Never hide a value conflict behind pseudo-objective scoring. When two defensible options protect different goods, say so and leave the final value judgment to Robin.

The Council may recommend when one option dominates on the stated objective, but it must still identify the value assumption that makes it dominate.

## Decision Map — Required Final Output

For substantial Council cases, finish with:

### Opportunity at Risk
What may be lost by waiting or moving too slowly?

### System at Risk
What may become unstable, gameable, concentrated, or politically unsustainable if action succeeds or scales?

### Mission at Risk
Even if execution succeeds, what wrong result, proxy, or institutional weakness could be produced?

### Reversibility
Separate repairable errors from hard-to-reverse losses. State what makes each reversible or irreversible.

### Evidence Needed
List only evidence that could materially change the decision. Distinguish missing evidence from merely desirable information.

### Decision Trigger
State observable triggers for act / stop / scale / retreat / redesign. Do not fabricate thresholds when none are grounded.

### Robin's Decision
State the irreducible trade-off Robin must own. Do not pretend there is an objectively unique answer when the remaining conflict is about values, risk appetite, identity, or what SSA is trying to become.

## Conflict Handling

Use `references/council-protocol.md` for detailed conflict rules.

In brief:
- do not synthesize before independent positions exist
- do not let one model answer another model's question for it
- distinguish contradictory facts from different priorities
- identify which risks are irreversible
- expose hidden assumptions
- force a decision when the user requires one, but attribute the recommendation to the governing objective rather than to “Council consensus”

## Scope

Use this Council for consequential:
- competitive moves
- organization design
- talent strategy
- resource allocation
- succession/founder dependency
- Academy/Young Agency design
- market entry
- major incentive or governance changes

Do not invoke the full Council for trivial operating questions.

## Failure Modes

Fail the Council if it:
- creates a fourth blended philosophy
- produces a generic “balance all three” answer
- uses majority vote
- gives Drucker an unlimited delay veto
- lets Cao Cao's speed erase governance risk
- lets Zhuge Liang's governance create bureaucracy without result
- invents numbers
- confuses user data with verified facts
- makes Robin's value judgment disappear
- rewards rhetorical imitation over reasoning fidelity

## Fidelity Standard

The Council should remain recognizable even if:
- all historical names are hidden
- quotations and classical language are forbidden
- the case is a modern company problem

Recognition should come from the stable three-way tension:
1. expiring opportunity and initiative
2. incentive-compatible system durability
3. mission, result, and institutional effectiveness

See `evals/fidelity-test.md`.

## Version

v1.0 — orchestration layer built on existing Cao Cao, Zhuge Liang, and Peter Drucker skills. It creates no new persona philosophy.
