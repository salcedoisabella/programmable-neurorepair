# System Stacks

## Purpose

This document explains the current integrated stack system in **Programmable Neurorepair**.

The project no longer operates only as a descriptive remyelination analysis. It now includes an operational system for reading state structure, interpreting transition logic, and organizing intervention-facing programs under different operating modes.

These modes are called **stacks**.

Each stack represents a different balance between:

- conservatism
- interpretability
- rescue strength
- ambiguity tolerance
- frontier probing

They should not be read as four unrelated outputs. They are four controlled ways of interacting with the same underlying state-transition architecture.

## Why stacks exist

The project originally converged on a controller problem that could not honestly be solved by one universal policy.

The system revealed a real tradeoff:

- stronger rescue often came at the cost of lower precision
- stronger precision often came at the cost of weaker rescue
- frontier-sensitive behavior was informative, but not always suitable for default use

Instead of pretending that one single mode solved all contexts, the project formalized a **stack family**. This makes the system more honest, more usable, and more extensible.

## Shared foundation across all stacks

All stacks sit on top of the same shared foundation:

- a repair-state map
- a dominant repair-compatible basin
- intermediate / review-like structure
- boundary / frontier structure
- a minimal control architecture
- intervention-facing program logic
- ranked validation-preparation logic

The shared minimal architecture is:

- **Tspan2 = push**
- **Ptprd = anchor**
- **Aspa = support**

The differences between stacks are not differences in the underlying project thesis.  
They are differences in **operating stance**.

## Stack overview

The current integrated system includes four main stacks:

1. `default_safe_stack`
2. `balanced_analysis_stack`
3. `boundary_probe_stack`
4. `maximum_rescue_probe_stack`

---

## 1. default_safe_stack

### Core role
`default_safe_stack` is the most conservative and operationally safest stack.

It is designed to preserve interpretability, reinforce the dominant repair-compatible basin, and avoid over-reading aggressive rescue behavior as success.

### Best use
Use this stack when the goal is:

- to make the safest current reading
- to stabilize interpretation around the dominant repair-compatible structure
- to avoid overclaiming rescue
- to prioritize precision and structural discipline

### Strengths
- safest overall interpretation
- strongest alignment with the dominant repair-compatible basin
- lowest tendency to over-read ambiguous rescue
- best first-line operating mode

### Limitations
- may under-rescue states that require more aggressive movement
- may preserve caution where stronger intervention logic could reveal more
- should not be mistaken for the strongest exploration mode

### Biological reading
This stack is best read as an **anchor-first, stability-preserving mode**.  
It is closest to reinforcing a good basin rather than forcing movement.

### External reading
Externally, this stack maps most naturally to the strongest dominant-basin state, especially the **WT-like external read** in Dataset B.

### Intervention-facing alignment
This stack aligns most strongly with:

- **default_safe_translation_program**

---

## 2. balanced_analysis_stack

### Core role
`balanced_analysis_stack` is the strongest current compromise between movement and stability.

It exists because some states are neither clearly dominant-basin states nor pure frontier states. They require a mode that allows controlled upward movement without collapsing into over-aggressive rescue logic.

### Best use
Use this stack when the goal is:

- to interpret intermediate states seriously
- to model recoverable but not yet stable states
- to allow transition without giving up too much control
- to capture the best current compromise between rescue and precision

### Strengths
- strongest middle-ground mode
- best current stack for intermediate recoverable states
- more flexible than `default_safe_stack`
- more disciplined than maximum rescue logic

### Limitations
- still inherits a real rescue-vs-precision tradeoff
- not fully immune to ambiguity or review theft
- should not be described as a universal optimum

### Biological reading
This stack is best read as a **controlled transition mode**.  
It allows movement, but still tries to preserve directionality and structure.

### External reading
Externally, this stack maps most naturally to the **PLP_iCKO-like intermediate state** in Dataset B.

### Intervention-facing alignment
This stack aligns most strongly with:

- **balanced_state_transition_program**

---

## 3. boundary_probe_stack

### Core role
`boundary_probe_stack` exists to interrogate ambiguity-rich frontier behavior.

It is not designed as the safest default interpretation. It is designed to ask harder questions about what happens near the boundary between structured transition and destabilizing ambiguity.

### Best use
Use this stack when the goal is:

- to study frontier behavior
- to understand ambiguity-rich transitions
- to distinguish productive movement from noisy movement
- to probe how far transition pressure can be pushed before interpretation breaks down

### Strengths
- strongest dedicated frontier-interrogation mode
- useful for distinguishing stable transition from unstable motion
- helps characterize boundary logic explicitly

### Limitations
- not appropriate as the general-purpose default mode
- can look too aggressive if used as the main operational reading
- frontier behavior should not be mistaken for durable rescue

### Biological reading
This stack is best read as a **frontier-mapping mode**.  
It is useful for exploring ambiguous transition structure, not for issuing the safest final verdict.

### External reading
Externally, this stack also maps most naturally to the **PLP_iCKO-like frontier-adjacent state** in Dataset B.

### Intervention-facing alignment
This stack aligns most strongly with:

- **boundary_probe_program**

---

## 4. maximum_rescue_probe_stack

### Core role
`maximum_rescue_probe_stack` is the most aggressive mode in the current system.

It exists to test the upper bound of rescue-oriented logic when lower-risk modes may be insufficient.

### Best use
Use this stack when the goal is:

- to probe maximum rescue potential
- to test how far aggressive rescue-oriented logic can go
- to understand the outer edge of transition leverage
- to explore high-risk, high-ambiguity intervention logic

### Strengths
- strongest rescue-oriented probe
- useful for upper-bound hypothesis generation
- helps expose what conservative modes might leave unseen

### Limitations
- too aggressive for default interpretation
- highest risk of over-reading unstable motion as success
- should remain downstream of safer stacks
- must not be described as the best overall operating mode

### Biological reading
This stack is best read as an **upper-bound rescue probe**, not as the project’s default truth layer.

### External reading
Externally, this stack still points toward the **PLP_iCKO-like rescue-target state**, but with more caution than the balanced stack.

### Intervention-facing alignment
This stack aligns most strongly with:

- **maximum_rescue_program**

---

## Comparative summary

### default_safe_stack
- safest
- most conservative
- best first-line stack
- strongest dominant-basin discipline

### balanced_analysis_stack
- strongest compromise
- best current intermediate-state stack
- controlled transition logic

### boundary_probe_stack
- best for ambiguity / frontier analysis
- not a default operating mode
- useful for learning where transition logic becomes unstable

### maximum_rescue_probe_stack
- most aggressive
- best for upper-bound rescue probing
- should remain downstream, not first-line

## How the stacks relate to one another

These stacks should not be treated as competitors where only one can exist.

They are better understood as a structured stack family:

- `default_safe_stack` = safest baseline
- `balanced_analysis_stack` = strongest middle ground
- `boundary_probe_stack` = ambiguity/frontier interrogation
- `maximum_rescue_probe_stack` = upper-bound rescue probe

The presence of multiple stacks is not a weakness.  
It is a consequence of taking the underlying tradeoffs seriously instead of hiding them.

## What the stack system already supports

The current stack system supports:

- a disciplined default mode
- a serious intermediate-state mode
- an explicit frontier-analysis mode
- an upper-bound rescue mode
- a more honest and operationally useful reading of the project as a system

## What the stack system does not yet support

The current stack system does **not** yet support:

- a single universal optimum stack
- the claim that all rescue-vs-precision tradeoffs are solved
- the claim that frontier behavior is fully resolved
- the claim that aggressive rescue should be treated as default truth

## Current interpretation

The current stack system is best understood as a controlled family of operating modes built on top of a shared state-transition architecture.

That is one of the reasons the project now reads less like a narrow descriptive analysis and more like an early platform system.

## Related documents

See also:

- `README.md`
- `docs/PROJECT_OVERVIEW.md`
- `docs/INTERVENTION_LAYER.md`
- `docs/EXTERNAL_VALIDATION.md`
- `docs/PLATFORM_THESIS.md`
- `docs/RESULTS_INDEX.md`
