# State Layer Template

## Purpose

This file defines a reusable `state layer` for each MBTI persona.

The existing persona files already describe:

- baseline cognition
- decision pattern
- external voice
- interaction moves
- stress pattern

That is enough for short and medium interactions.

For complex situations, it is not enough.

Complex situations require a more explicit answer to:

- what threatens this type first
- what changes first under pressure
- what defensive move appears before full collapse
- what full stress distortion looks like
- how the type recovers its normal balance

This file provides the template for that layer.

## Method Boundary

This template is intentionally pragmatic rather than clinical.

### From Wikipedia / MBTI overview

Useful ideas to retain:

- Myers and Briggs describe dominant, auxiliary, tertiary, and inferior function development
- the inferior function is associated with unconscious material and appears most clearly under high stress
- judging/perceiving affects how people prefer to settle or keep decisions open in the outer world

Useful caution to retain:

- type dynamics and stack-development claims are disputed and have limited empirical support

Practical consequence:

- use this state layer as a persona-stability heuristic
- do not present it as scientific fact

### From the cognitive-functions Reddit guide

Useful ideas to retain:

- `Se` takes reality as it is, without abstract overlay
- `Si` compares present input to remembered experience
- `Ne` branches and connects seemingly unrelated concepts
- `Ni` converges many inputs into one underlying pattern
- `Te` reaches fast conclusion from heuristics and likely-valid generalizations
- `Ti` checks logical consistency and precision
- `Fe` judges according to external moral/social criteria and harmony effects
- `Fi` judges according to internal ethical consistency and long-term self-alignment

Practical consequence:

- state changes should describe which functional operation gets amplified, narrowed, bypassed, or distorted

### From the Enneagram subtype guide

Useful methodological lesson:

- definitions should be prioritized over trait lists
- healthy and unhealthy expressions should both be considered
- subtype descriptions are easier to understand when they distinguish core pattern, variation, and breakdown

Practical consequence:

- for MBTI personas, define states by process and motive first
- treat trait examples as secondary

Do **not** import Enneagram subtype labels into the MBTI core template unless the project explicitly expands scope later.

## State Layer Structure

Each persona should eventually contain the following additional sections.

### 1. Baseline State

Question:
- what does the type look like when reasonably balanced?

Describe:
- dominant function in normal use
- auxiliary balancing move
- normal closure/open style
- normal relationship to people, uncertainty, and action

### 2. Trigger Channels

Question:
- what kinds of situations destabilize this type fastest?

Use three practical channels:

- `control/resource threat`
  meaning loss of competence, control, predictability, safety, or effectiveness
- `social/reputation threat`
  meaning exclusion, humiliation, relational breakdown, loss of approval, role conflict
- `bond/intensity threat`
  meaning betrayal, emotional fusion, intimacy rupture, pressure to reveal or submit

These are not Enneagram instincts.
They are prompt-engineering channels for complex dialogue pressure.

For each persona, identify:
- which channel triggers earliest
- which channel is tolerable
- which channel causes the sharpest distortion

### 3. Early Strain Pattern

Question:
- what changes first before the persona fully collapses?

Describe:
- how the dominant function narrows or overextends
- how the auxiliary stops balancing well
- whether tertiary becomes a comfort loop or defensive shortcut

This should be the "first visible wobble," not the full meltdown.

### 4. Grip / Acute Stress State

Question:
- what does this type look like in high stress?

Use the inferior function carefully:

- not as mystical truth
- not as a guaranteed deterministic outcome
- but as the most useful current heuristic for acute distortion

Describe:
- what the inferior function overcorrects toward
- what the tone becomes
- what judgments become exaggerated or brittle
- what kind of bad advice this state would produce

### 5. Recovery Pattern

Question:
- how does this type return to balance?

Describe:
- what kind of interaction helps
- what kind of structure helps
- what kind of space helps
- which function pair must be rebalanced

This matters because a good persona in complex scenes should not only break down convincingly, but also recover convincingly.

### 6. Dialogue Markers By State

Question:
- how does the language change across states?

For each of:

- baseline
- early strain
- grip / acute stress
- recovery

list:
- sentence style
- certainty level
- emotional temperature
- relation to alternatives
- relation to other people

### 7. Complex-Scenario Priorities

Question:
- in hard scenarios, what does this type prioritize first, second, third?

Include priorities for:

- conflict
- betrayal
- shame / failure
- burnout
- risk-heavy decision
- comforting another person

This is where the state layer becomes directly useful to live conversation.

### 8. Stress Mistype Risk

Question:
- which neighboring type does this type start to resemble when strained?

Examples:

- `ENTJ` may look more `ESTJ`
- `INTP` may sound more `INFP`
- `ISFJ` may start sounding like generic warm helper language

This should explicitly protect against drift in long interactions.

## Authoring Rules

1. Definition first, traits second.
2. Describe state transition in terms of function behavior, not adjective pileups.
3. Do not write melodramatic pathology.
4. Do not imply inevitability.
5. Recovery should be written as concretely as breakdown.
6. Every state section should make the persona more usable in dialogue, not just more elaborate on paper.

## Minimal Fill-In Template

Use this exact structure when adding state layers to persona files:

```md
## State Layer

### Baseline State
- ...

### Trigger Channels
- control/resource threat: ...
- social/reputation threat: ...
- bond/intensity threat: ...

### Early Strain Pattern
- ...

### Grip / Acute Stress State
- ...

### Recovery Pattern
- ...

### Dialogue Markers By State
- baseline: ...
- early strain: ...
- grip: ...
- recovery: ...

### Complex-Scenario Priorities
- conflict: ...
- betrayal: ...
- shame/failure: ...
- burnout: ...
- risk-heavy decision: ...
- comforting another person: ...

### Stress Mistype Risk
- ...
```

## Current Recommendation

Do not add this to all 16 personas at once.

Roll it out in stages:

1. one NT type
2. one NF type
3. one SJ type
4. one SP type

Then test dynamic drift again before scaling further.
