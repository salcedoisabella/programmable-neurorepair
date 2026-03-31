# External Validation

## Purpose

This document explains the current external validation layer of **Programmable Neurorepair**.

The project was not designed to remain only an internal sandbox built from one dataset. A core requirement of the system is that at least part of its logic should survive outside the original derivation environment.

This document clarifies:

- what the external validation layer currently supports
- what role each external dataset plays
- what counts as meaningful external support
- what is still not claimed

## Why external validation matters here

A project like this cannot rely only on internal coherence.

If the system is meant to move from:

- state structure
- to transition logic
- to minimal control architecture
- to intervention-facing programs

then at least some of that structure must remain legible beyond the original derivation dataset.

External validation matters because it helps answer a harder question:

**Does the system still make sense outside the environment in which it was first built?**

## External validation design

The current external validation layer was organized with two distinct roles:

### Dataset B
Dataset B is the **primary external benchmark**.

Its role is to test whether the project’s architecture, dominant-basin logic, intermediate/frontier structure, and integrated stack behavior remain externally interpretable.

### Dataset C
Dataset C is a **supportive triangulation layer**.

Its role is not to replace Dataset B. Its role is to reinforce or qualify the broader external story, especially around recovery-order structure.

These two datasets are not treated as interchangeable.

## What “external support” means in this project

External support does **not** mean proving identical geometry or claiming fully solved transfer.

At the current stage, meaningful external support means that one or more of the following remain directionally interpretable outside the original derivation dataset:

- minimal architecture portability
- dominant repair-basin portability
- intermediate / review-like structure portability
- boundary / frontier-like structure portability
- integrated stack portability
- recovery-order reinforcement

This is a first-pass external validation layer, not a final transfer proof.

## Dataset B

## Role

Dataset B is the main external validation dataset in the current system.

It is the strongest external benchmark because it supports a more structured interpretation of dominant basin, intermediate state, frontier-adjacent state, and stack-level logic.

## What Dataset B currently supports

Dataset B currently provides **promising first-pass external support** for:

- architecture portability
- dominant-basin portability
- review / boundary structure portability
- integrated stack portability

This makes Dataset B the strongest current external support layer in the project.

## Architecture portability

The current minimal architecture is:

- **Tspan2 = push**
- **Ptprd = anchor**
- **Aspa = support**

Dataset B supports a promising first-pass external reading of this architecture.

The strongest directional reading is:

- **Ptprd / anchor** remains externally interpretable
- **Aspa / support** remains externally interpretable
- **Tspan2 / push** remains externally interpretable, but not as a simple terminal-best-state marker

That last point matters. Push is not best read as a naive “higher is always better” signal. In the external setting, it is more consistent with a transition-pressure or movement-opening logic.

## Dominant-basin portability

Dataset B supports a promising first-pass external reading of the dominant repair-compatible basin.

The strongest current external dominant-basin candidate is:

- **WT-like state**

This matters because it means the dominant internal repair-compatible basin is not only an internal construct. It has a plausible first-pass external counterpart.

## Review / boundary structure portability

Dataset B also supports a promising first-pass reading of intermediate / review-like and frontier-adjacent structure.

The strongest current external intermediate / frontier-like candidate is:

- **PLP_iCKO-like state**

This matters because it suggests that the project is not only externally recovering a dominant basin, but also externally recovering a more differentiated state landscape.

## Integrated stack portability

Dataset B also supports a promising first-pass reading of the integrated stack logic.

The strongest current external interpretation is:

- **default_safe_stack** aligns most naturally with the WT-like dominant-basin state
- **balanced_analysis_stack** aligns most naturally with the PLP_iCKO-like intermediate state
- **boundary_probe_stack** also aligns most naturally with PLP_iCKO-like frontier-adjacent behavior
- **maximum_rescue_probe_stack** remains externally interpretable as an upper-bound rescue-oriented mode, but not as a default truth layer

This is an important step because it means the external layer is not only preserving single components. It is preserving a more system-level logic.

## Dataset B verdict

The current overall Dataset B reading is:

- **promising_supported_first_pass**

That is the strongest current external validation claim in the project.

---

## Dataset C

## Role

Dataset C is not the primary benchmark.

Its role is to provide **supportive triangulation**, especially around recovery-order structure.

It exists to reinforce, qualify, or complicate the broader external story — not to replace Dataset B.

## Initial reading

Dataset C initially supported a useful triangulation layer around recovery-order structure.

However, after expectation-aware auditing, the correct interpretation became more qualified.

## Expectation-aware audit

The key biological expectation for Dataset C was an ordered recovery-compatible directionality.

The expectation-aware audit showed that Dataset C is **useful but mixed**:

- some parts of the expected directionality are supported
- some parts are not cleanly reproduced
- it remains informative
- but it is not strong enough to serve as the main external benchmark

## Dataset C verdict

The correct current reading for Dataset C is:

- **supportive_mixed**

This is a strength, not a weakness, if stated honestly. It means the system is disciplined enough to distinguish between primary external support and secondary, partially supportive reinforcement.

---

## Current external hierarchy

The current external hierarchy is:

### Primary benchmark
- **Dataset B**

### Supportive triangulation
- **Dataset C**

This hierarchy should remain explicit in all serious descriptions of the project.

## What is already supported externally

At the current stage, the external layer already supports:

- a first-pass external reading of the minimal architecture
- a first-pass external dominant-basin read
- a first-pass external intermediate / frontier read
- a first-pass external integrated stack read
- supportive mixed triangulation from Dataset C

## What is not yet supported externally

The current external layer does **not** yet support:

- a claim of identical geometry between datasets
- a claim of universal transfer across all domains
- a claim that every ambiguity-rich structure is fully resolved externally
- a claim that Dataset C independently proves the full external story
- a claim that broader neural state control has already been externally validated

## Why this external layer still matters

Even with guardrails, the external layer is a major shift in what the project is.

The project no longer reads as:

- a single-dataset sandbox
- an internal map with no external contact
- or a purely descriptive internal story

It now includes a real first-pass external benchmark, supportive triangulation, and a more serious basis for saying that the architecture and program logic may be more than internal artifacts.

## Current interpretation

The best current interpretation is:

- **Dataset B provides the main first-pass external support**
- **Dataset C reinforces the external story in a supportive but mixed way**
- **the project now has a meaningful external validation layer, but not a final transfer proof**

## Related documents

See also:

- `README.md`
- `docs/PROJECT_OVERVIEW.md`
- `docs/SYSTEM_STACKS.md`
- `docs/INTERVENTION_LAYER.md`
- `docs/PLATFORM_THESIS.md`
- `docs/RESULTS_INDEX.md`
