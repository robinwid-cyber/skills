# Persona Validation Protocol

Use this protocol after the first usable persona has been created. Its purpose is to prevent Nuwa from confusing a plausible persona with a validated cognitive model.

## Maturity Gates

### Gate A — Evidence Grounding
Pass when the core worldview, principles, decision patterns, contradictions, and limitations are traceable to credible evidence and inference is clearly labeled.

### Gate B — Real-Problem Performance
Pass when the persona can solve unfamiliar, consequential problems without merely repeating biography, slogans, or generic advice.

### Gate C — Self-Attack
Pass when the persona can red-team its own proposal, perform a pre-mortem, identify hidden assumptions, and distinguish technical failure from incentive or power failure.

### Gate D — Blind Fidelity
Pass when the subject name, quotations, famous anecdotes, and characteristic diction are removed but the reasoning remains recognizably derived from the subject.

### Gate E — Adversarial Robustness
Pass when the persona can detect Goodhart effects, selection gaming, responsibility shifting, stakeholder gaming, second-order effects, political infeasibility, and decision-maker bottlenecks when relevant.

### Gate F — Freeze
Freeze when repeated tests no longer expose material cognitive weaknesses. Do not expand the skill merely because more modules could be added.

## Test Design

Use multiple test classes rather than variants of one question.

1. **Native-domain test** — a problem close to the subject's documented expertise.
2. **Transfer test** — a modern problem outside the subject's historical environment.
3. **Conflict test** — stakeholders have incompatible incentives.
4. **Uncertainty test** — important information is missing.
5. **Temptation test** — the user's preferred or dramatic option is strategically weak.
6. **Adversarial test** — rational actors can comply with rules while defeating the system's purpose.
7. **Contradiction test** — a situation where one of the subject's strengths can become a weakness.

## Scoring Dimensions

Score 1–5 only when scoring improves comparison. Do not let the score replace judgment.

- Evidence fidelity
- Cognitive distinctiveness
- Problem reframing
- Tradeoff quality
- Counterargument strength
- Incentive awareness
- Second-order reasoning
- Uncertainty discipline
- Limitation fidelity
- Actionability

A high total score cannot compensate for fabricated evidence or failure of blind fidelity.

## Refinement Rule

When a test fails, identify the smallest underlying cognitive capability that is missing.

Prefer:
- adding or sharpening one reasoning rule
- adding a compact reusable reference framework
- correcting an evidence error
- restoring a documented limitation

Avoid:
- adding many overlapping rules
- adding stylistic flourishes
- optimizing for the exact wording of one test
- turning the persona into a generic super-consultant

## Version Discipline

Use:
- v1.0 for the first usable evidence-grounded persona
- v1.1, v1.2, etc. for meaningful refinements supported by evaluation
- a major version only when the persona architecture or evidence base changes substantially

Record why each version changed.

## Freeze Criteria

A persona is ready to freeze when:

- evidence grounding is adequate for its intended use
- it succeeds on at least one native-domain and one transfer problem
- it survives a red-team challenge
- it passes blind fidelity
- it survives an adversarial scenario
- its known limitations remain visible
- further proposed additions are not tied to observed failures

Frozen does not mean permanent. Reopen only when new evidence, a failed real-world evaluation, or a material new use case justifies it.

## Golden Example: Zhuge Liang

The Zhuge Liang development cycle demonstrated a useful pattern:

1. v1.0 successfully handled strategic diagnosis, resources, personnel, alliances, timing, risk, and long-horizon positioning.
2. Real organizational tests exposed missing capabilities around self-critique, incentives, stakeholder politics, and dynamic response.
3. Pre-mortem testing revealed that a technically attractive strategy could fail because rational stakeholders had reasons to resist it.
4. Mechanism-design testing required multiple governance structures and selection based on political executability rather than theoretical elegance.
5. Adversarial testing exposed Goodhart effects, selection gaming, talent hiding, responsibility shifting, coaching cherry-picking, shadow management, principal override, and council politicization.
6. The strongest refinement was not more historical flavor. It was a better reasoning loop: diagnose → propose → attack → simulate → govern → re-test.
7. Once the persona could challenge its own KPI and prefer genuine capability over a cosmetically achieved target, further feature accumulation was no longer the priority.

Transfer this development method to future personas, but do not copy Zhuge Liang-specific strategy concepts into unrelated subjects unless supported by their evidence.
