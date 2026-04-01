# Candidate Control Layers

## Purpose

This document summarizes the current candidate control-layer reading of **Programmable Neurorepair**.

The project no longer treats candidate control as a flat list of interesting genes. It now supports a more structured reading in which different candidate layers play different roles inside the state-transition architecture.

This document explains:

- what “candidate control layers” means in the current project
- how the current minimal architecture emerged
- how the main control roles differ from one another
- why these layers should not be treated as redundant
- what is supported now vs what remains future-facing

## Why control layers matter

A repair-state map on its own is not enough.

If the broader project is trying to move from state description toward neural state control, then one of the key questions becomes:

**What candidate control logic seems to organize movement toward better states?**

The answer should not be a flat ranked list. It should be a more structured reading of:

- movement-opening logic
- commitment-stabilizing logic
- support / maturation logic
- state-specific transition needs
- differing intervention roles across different operating contexts

That is what the current candidate control-layer framework attempts to capture.

## Current minimal architecture

The current minimal architecture is:

- **Tspan2 = push**
- **Ptprd = anchor**
- **Aspa = support**

This is the strongest current minimal control reading in the project.

It should not be interpreted as final mechanistic proof.  
It should be interpreted as the current best minimal architecture that organizes the state-transition structure and intervention-facing logic.

## What each control layer means

## 1. Tspan2 — push layer

### Core role
Tspan2 is currently best interpreted as the **push layer**.

### What that means
Push is the layer that helps reopen movement out of under-transitioned, insufficiently repair-committed, or stalled states.

### Why it matters
Without push, the system risks preserving weak or under-transitioned states rather than moving them toward something better.

### Best reading
Tspan2 is not best interpreted as a simple “terminal best-state marker.”

It is better read as:

- movement-opening
- transition-relevant
- especially informative in intermediate or frontier contexts
- useful when the problem is not only stabilization, but insufficient movement

### Main caution
Push without enough anchor or support may produce movement that is not durable or well-directed.

---

## 2. Ptprd — anchor layer

### Core role
Ptprd is currently best interpreted as the **anchor layer**.

### What that means
Anchor is the layer that stabilizes commitment, directionality, and repair-compatible structure.

### Why it matters
Without anchor, movement may occur without enough coherence, making it harder to distinguish meaningful transition from unstable motion.

### Best reading
Ptprd is best read as:

- commitment-stabilizing
- directionality-preserving
- strongest around dominant repair-compatible logic
- essential for disciplined upward movement

### Main caution
Anchor without enough push may preserve stability without producing needed transition.

---

## 3. Aspa — support layer

### Core role
Aspa is currently best interpreted as the **support layer**.

### What that means
Support is the layer that helps consolidation, maturation, and maintenance of a repair-compatible state.

### Why it matters
Without support, even a well-directed transition may fail to become durable or mature.

### Best reading
Aspa is best read as:

- consolidation-supporting
- maturation-supporting
- maintenance-relevant
- important for durability rather than initial transition alone

### Main caution
Support without enough push or anchor may stabilize an insufficiently transitioned state rather than move it toward a better one.

## Why these layers are not redundant

The current project supports a non-redundant reading of these layers.

### Tspan2
opens movement

### Ptprd
stabilizes commitment and directionality

### Aspa
supports consolidation and durability

This means the architecture is not currently best read as three versions of the same control role. It is best read as a minimal division of labor inside the state-transition problem.

That is one reason the project now feels more system-like than a flat gene-ranking exercise.

## Pair-level control logic

The project also supports useful pair-level readings.

## Tspan2 + Ptprd
Best interpreted as:

- movement + directionality
- controlled transition logic
- especially relevant for intermediate-state upward movement

This pair is closest to the logic behind:

- `balanced_state_transition_program`

## Tspan2 + Aspa
Best interpreted as:

- movement + supportive rescue
- less anchored, more rescue-oriented logic
- useful for probing upper-bound rescue cases

This pair is closest to the logic behind:

- `maximum_rescue_program`

## Ptprd + Aspa
Best interpreted as:

- stabilization + consolidation
- preserve-and-reinforce logic
- strongest when the system is already near a good basin

This pair is closest to the logic behind:

- `default_safe_translation_program`

## Control layers and state structure

The candidate control-layer reading is tied to the state map.

## Dominant repair-compatible basin
Best control reading:
- stronger anchor + support logic
- preserve and reinforce a coherent basin

## Intermediate / review-like zone
Best control reading:
- movement plus directionality
- controlled upward transition without excessive instability

## Boundary / frontier band
Best control reading:
- movement-opening logic is highly relevant
- but must be interpreted with caution because ambiguity is high

## Rescue-oriented high-need context
Best control reading:
- stronger push plus supportive rescue logic may be informative
- but higher rescue strength does not automatically mean durable success

## Candidate control layers and stack logic

The current stack family is one of the clearest demonstrations that the control-layer reading is no longer flat.

### `default_safe_stack`
Most aligned with:
- anchor + support emphasis

### `balanced_analysis_stack`
Most aligned with:
- push + anchor emphasis

### `boundary_probe_stack`
Most aligned with:
- push + anchor under ambiguity-rich conditions

### `maximum_rescue_probe_stack`
Most aligned with:
- push + support under higher rescue pressure

This is important because it shows that the candidate control-layer framework is not only descriptive. It is already shaping how the system is operated and interpreted.

## Candidate control layers and intervention programs

The control-layer framework also now supports distinct intervention-facing translations.

### `default_safe_translation_program`
Best aligned with:
- stabilization and reinforcement of a good basin
- stronger anchor/support logic

### `balanced_state_transition_program`
Best aligned with:
- controlled movement in recoverable intermediate states
- stronger push/anchor logic

### `boundary_probe_program`
Best aligned with:
- ambiguity-rich transition probing
- push/anchor logic under frontier conditions

### `maximum_rescue_program`
Best aligned with:
- upper-bound rescue probing
- stronger push/support logic

This matters because candidate control layers now function as part of a program logic, not just as ranked biological curiosities.

## External support for control-layer reading

The control-layer framework also has first-pass external support.

### Dataset B
Dataset B currently provides the strongest external support for:

- architecture portability
- dominant basin portability
- intermediate / frontier structure portability
- integrated stack portability

This strengthens the reading that the control-layer framework is not only an internal artifact.

### Dataset C
Dataset C remains supportive mixed triangulation.

It reinforces parts of the broader story but does not replace Dataset B as the main benchmark.

## What the current control-layer reading supports

The project currently supports the claim that:

- candidate control should be read as layered and non-redundant
- push, anchor, and support are meaningfully different roles
- pair-level combinations matter
- control layers help organize stack logic
- control layers help organize intervention-facing logic
- the project is beyond a flat candidate-gene ranking stage

## What the current control-layer reading does not yet support

The project does **not** yet support the claim that:

- the minimal architecture is a final causal proof
- every candidate control role is fully mechanistically established
- one layer alone is sufficient in every context
- the current architecture fully resolves all transition ambiguity
- the candidate control framework already proves general neural state control

## Current interpretation

The strongest current reading is:

**candidate control in this project is now best understood as a layered, non-redundant control architecture rather than a flat ranked list of repair-associated genes.**

That is a major shift in how the project should be read.

## Related files

See also:

- `README.md`
- `PHASE_INDEX.md`
- `current_outputs_snapshot.md`
- `transition_logic_summary.md`
- `dataset_roles.md`
- `repair_signature_genes.md`
- `../docs/SYSTEM_STACKS.md`
- `../docs/INTERVENTION_LAYER.md`
- `../docs/PLATFORM_THESIS.md`
