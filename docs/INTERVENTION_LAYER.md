# Intervention Layer

## Purpose

This document explains the current intervention-facing layer of **Programmable Neurorepair**.

The project no longer stops at identifying repair-relevant state structure. It now includes a structured attempt to translate that state structure into intervention-facing logic: not finished therapeutic claims, but organized programs derived from the current architecture, external support, and validation-preparation framework.

This layer exists to answer a simple question:

**If the project identifies meaningful state structure and a minimal control architecture, how should that begin to translate into intervention logic?**

## Why this layer exists

A project like this cannot stop at state description if its deeper goal is to move toward neural state control.

State structure matters, but on its own it is not enough. Once the project identifies:

- a dominant repair-compatible basin
- intermediate / review-like structure
- boundary / frontier behavior
- and a minimal push-anchor-support architecture

the next step is to ask how that architecture should be interpreted in a way that could eventually support interventions.

That is what this layer does.

It does **not** claim therapeutic efficacy.  
It does **not** claim completed mechanism.  
It does **not** claim finished intervention design.

It provides a structured intervention-facing logic layer.

## Architecture foundation

The current minimal architecture is:

- **Tspan2 = push**
- **Ptprd = anchor**
- **Aspa = support**

These roles should be read as the current best minimal control logic organizing the observed state-transition structure.

### Push
**Tspan2 = push**

Push is the architecture component that helps reopen movement out of stuck, under-transitioned, or insufficiently repair-committed states.

### Anchor
**Ptprd = anchor**

Anchor is the architecture component that stabilizes commitment, directionality, and repair-compatible structure.

### Support
**Aspa = support**

Support is the architecture component that helps consolidation, maturation, and maintenance of a more repair-compatible state.

## Why programs are needed

The architecture does not translate into only one intervention mode.

The project now supports a more differentiated reading:

- some states need preservation of an already good basin
- some states need controlled upward transition
- some states sit in ambiguity-rich frontier zones
- some states may require more aggressive rescue-oriented probing

That is why the system now includes **four intervention-facing programs** rather than one generic intervention concept.

## Program overview

The current intervention-facing program layer includes:

1. `default_safe_translation_program`
2. `balanced_state_transition_program`
3. `boundary_probe_program`
4. `maximum_rescue_program`

These should be read as distinct program logics, not cosmetic variants of the same idea.

---

## 1. default_safe_translation_program

### Core role
This is the safest first-line intervention-facing program.

It is designed for contexts where the system is already near a repair-compatible basin and the main goal is to preserve, reinforce, or stabilize that basin rather than introduce unnecessary destabilization.

### Best use
Use this program when the goal is:

- to reinforce a good basin
- to preserve repair-compatible commitment
- to avoid unnecessary destabilizing movement
- to begin from the most conservative intervention logic

### Architecture emphasis
This program is most closely aligned with:

- **Ptprd = anchor**
- **Aspa = support**

Push may still matter, but it is not the dominant emphasis here.

### Biological interpretation
This program is best interpreted as a **preserve-and-reinforce mode**.  
It is appropriate when the problem is not lack of movement, but maintaining or consolidating a good state.

### Main caution
This program may underperform when the system first needs meaningful movement rather than stabilization.

---

## 2. balanced_state_transition_program

### Core role
This is the strongest current second-line intervention-facing program.

It is designed for intermediate but recoverable states that are not yet stably repair-compatible, but are not best treated as pure frontier or high-risk rescue cases either.

### Best use
Use this program when the goal is:

- to move an intermediate state upward
- to preserve as much structure as possible during transition
- to balance movement with stability
- to avoid both passivity and over-aggressive rescue logic

### Architecture emphasis
This program is most closely aligned with:

- **Tspan2 = push**
- **Ptprd = anchor**

Support still matters, but the central problem here is controlled upward transition.

### Biological interpretation
This program is best interpreted as a **controlled transition mode**.  
It is the strongest current compromise between movement and stability.

### Main caution
This program still inherits a real rescue-vs-precision tradeoff and should not be mistaken for a universal solution.

---

## 3. boundary_probe_program

### Core role
This program exists to interrogate ambiguity-rich frontier behavior.

It is not primarily a program for safe default use. It is a program for learning where productive transition ends and destabilizing ambiguity begins.

### Best use
Use this program when the goal is:

- to study frontier behavior
- to distinguish productive movement from unstable motion
- to understand ambiguity-rich transitions
- to map the boundaries of interpretable rescue

### Architecture emphasis
This program is most closely aligned with:

- **Tspan2 = push**
- **Ptprd = anchor**

The key difference is not the components alone, but the operating context: this program is used near the frontier.

### Biological interpretation
This program is best interpreted as a **frontier-probing mode**, not as a final first-line intervention program.

### Main caution
Frontier motion should not be mistaken for durable rescue. This program is informative, but not the default.

---

## 4. maximum_rescue_program

### Core role
This is the most aggressive program in the current intervention-facing layer.

It exists to test the upper bound of rescue-oriented logic when lower-risk programs may not be sufficient.

### Best use
Use this program when the goal is:

- to probe maximum rescue potential
- to test high-risk, high-movement intervention logic
- to understand the outer edge of intervention leverage
- to ask what stronger rescue might reveal that safer programs leave unseen

### Architecture emphasis
This program is most closely aligned with:

- **Tspan2 = push**
- **Aspa = support**

Anchor still matters, but this mode accepts more instability risk than the safer programs.

### Biological interpretation
This program is best interpreted as an **upper-bound rescue probe** rather than a preferred default intervention.

### Main caution
This program has the highest risk of over-reading unstable motion as success and should remain downstream of safer programs.

## State-to-program logic

The intervention-facing layer is not random. It is tied to state structure.

### WT-like dominant basin
Best aligned with:

- `default_safe_translation_program`

Reason: the main task is to reinforce or preserve a strong repair-compatible basin.

### PLP_iCKO-like intermediate state
Best aligned with:

- `balanced_state_transition_program`

Reason: the main task is to move an intermediate but recoverable state upward without losing too much structure.

### PLP_iCKO-like frontier-adjacent state
Best aligned with:

- `boundary_probe_program`

Reason: the main task is to interrogate ambiguity-rich transition behavior rather than treat it as already stabilized rescue.

### PLP_iCKO-like rescue target
Best aligned with:

- `maximum_rescue_program`

Reason: the main task is to test upper-bound rescue-oriented logic under higher ambiguity and risk.

### Sox10_iCKO-like low-commitment floor
This is better treated as:

- a low-commitment reference floor
- not the first or best direct intervention target in the current logic

## Validation order

The current validation-preparation order is:

1. `default_safe_translation_program`
2. `balanced_state_transition_program`
3. `boundary_probe_program`
4. `maximum_rescue_program`

This order is one of the most important discipline layers in the current project.

Why this order:

- safer dominant-basin reinforcement should be evaluated before aggressive rescue logic
- controlled transition should be evaluated before frontier-only probing
- maximum rescue should remain downstream, not first-line

## Program-level failure modes

### default_safe_translation_program
Main failure mode:
- preserving a state that actually requires movement rather than reinforcement

### balanced_state_transition_program
Main failure mode:
- trying to move a state upward but losing too much structure or precision during the process

### boundary_probe_program
Main failure mode:
- mistaking frontier motion for meaningful rescue

### maximum_rescue_program
Main failure mode:
- reading aggressive destabilization as success when the resulting state lacks durability or coherence

## What this layer already supports

The current intervention-facing layer supports:

- a structured translation from architecture to programs
- differentiated program logic instead of one generic intervention concept
- explicit ranking of validation priority
- state-to-program mapping
- biologically interpretable distinctions between programs

## What this layer does not yet support

The current intervention-facing layer does **not** yet support:

- proof of therapeutic efficacy
- completed causal mechanism
- clinical claims
- the idea that one program is universally optimal
- the idea that aggressive rescue should be treated as the default interpretation

## Current interpretation

The intervention-facing layer is best understood as a structured hypothesis portfolio built on top of the current state-transition architecture.

That matters because it means the project no longer stops at:
- describing repair states
- ranking genes
- or naming candidate levers

It now begins to organize those findings into a system that can support future validation logic.

## Related documents

See also:

- `README.md`
- `docs/PROJECT_OVERVIEW.md`
- `docs/SYSTEM_STACKS.md`
- `docs/EXTERNAL_VALIDATION.md`
- `docs/PLATFORM_THESIS.md`
- `docs/RESULTS_INDEX.md`
