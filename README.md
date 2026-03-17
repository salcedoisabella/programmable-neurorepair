# Programmable Neurorepair

![Project status](https://img.shields.io/badge/status-early_prototype-blue)
![Focus](https://img.shields.io/badge/focus-neural_state_transitions-purple)
![Domain](https://img.shields.io/badge/domain-computational_neuroscience-green)

---

## Engine architecture

```mermaid
flowchart TD
    A[Single-cell neural datasets] --> B[State mapping]
    B --> C[Repair-state signature]
    C --> D[Candidate molecular control nodes]
    D --> E[Transition modeling]
    E --> F[Intervention simulation]

    F --> G[Module 1: remyelination]
    F --> H[Future modules: inflammatory-state control]
    F --> I[Future modules: neural adaptation]
```
Programmable Neurorepair is a computational engine for mapping neural cell-state transitions and identifying molecular control points that can shift cells toward regenerative or functional states.

The project is motivated by a broader question: how can neural systems move from being highly observable to becoming more predictable, interpretable, and eventually guideable? The current proof of concept focuses on remyelination, using single-cell transcriptomic data to model how oligodendrocyte-lineage cells move between precursor-like and mature repair states.

---

## Why this matters

Modern neuroscience can measure cells, circuits, and molecular states at extraordinary resolution, but still lacks principled frameworks for understanding what actually controls transitions between neural states.

As a result, many interventions remain blunt relative to the complexity of the systems they are trying to affect. We can often describe dysfunction in great detail without understanding which molecular control points govern the movement between damaged, adaptive, and repair-supporting states.

Programmable Neurorepair is an attempt to help close that gap.

---

## Core idea

The engine is designed to:

- map neural cell-state landscapes across conditions
- identify molecular control points associated with transitions between those states
- simulate how perturbations could shift cells toward desired functional outcomes

The long-term vision is to build computational systems that make neural state transitions more mappable, more predictive, and eventually more guideable across the central nervous system.

---

## Current focus: oligodendrocyte repair dynamics

The first module focuses on oligodendrocyte lineage dynamics during demyelination and remyelination.

Using single-cell transcriptomic datasets, the framework models transitions between:

- precursor-like oligodendrocyte states
- mature oligodendrocyte repair states

This allows the system to identify molecular control points associated with the probability of cells entering a remyelinating state.

---

## Repair-state signature

The current repair-state program includes genes strongly associated with mature oligodendrocyte function and remyelination:

- Mal
- Cldn11
- Plp1
- Mog
- Mobp
- Mbp
- Mag
- Cnp
- Abca2
- Tspan2
- Ptgds
- Myrf

These genes define the mature repair-state signature used by the engine to classify cellular states and model repair-associated transitions.

---

## Candidate molecular control layers

Initial analyses highlight several mechanistically distinct candidate layers associated with remyelinating states:

### Flagship repair-state lever
- **Tspan2**

### Repair architecture / support layer
- **Gjc2**
- **Fa2h**
- **Aspa**
- **Abca2**

### Signaling and control candidates
- **Ptgds**
- **Ptprd**

Together, these candidates suggest that remyelination may be decomposed into multiple functional layers rather than explained by a single marker or pathway.

---

## Engine components

The current version of the system includes:

- repair-state signature derivation
- cross-dataset validation
- candidate control node prioritization
- intervention simulation
- transition modeling

These components are designed to move from descriptive state mapping toward computationally guided hypotheses about which perturbations are most likely to shift repair probability.

---

## System components

| Component | Description |
|---|---|
| State mapping | reconstruction of neural state landscapes |
| Repair signature | identification of mature repair-state programs |
| Candidate prioritization | ranking molecular control nodes |
| Transition modeling | modeling probability of state shifts |
| Intervention simulation | testing perturbation hypotheses |

---

## Current status

Early computational prototype.

The first version has been developed across multiple independent datasets and is being used as a proof of concept for a broader framework centered on neural cell-state transitions and molecular control logic.

---
## Current evidence

Programmable Neurorepair already includes a visible operational layer rather than only a conceptual project description. The framework has been implemented across multiple single-cell datasets and already produces artifacts that support the broader neural-state-control thesis.

### Evidence artifacts

- [Dataset roles](results/dataset_roles.md)
- [Repair signature genes](results/repair_signature_genes.md)
- [Candidate control layers](results/candidate_control_layers.md)
- [Transition logic summary](results/transition_logic_summary.md)
- [Current outputs snapshot](results/current_outputs_snapshot.md)
- [Current candidate ranking (CSV)](results/current_candidate_ranking.csv)
- [Repair signature (CSV)](results/repair_signature_genes.csv)

## Evidence snapshot

![Operational Evidence Layer](figures/programmable_neurorepair_operational_evidence_layer_FINAL_fixed.png)

### Current operational status

| Evidence layer | Current status |
|---|---|
| State-structure derivation | implemented |
| Mature repair-state signature | derived |
| Candidate control-layer separation | implemented |
| Transition-oriented logic | implemented |
| Cross-dataset directional support | established |
| Intervention-oriented prioritization | implemented |

### Why this matters

The project is not only arguing that neural state transitions should be modeled differently. It already contains the first operational layers of that approach: state-structure derivation, repair-state definition, candidate control-layer separation, and transition-oriented intervention logic.
  

### Current outputs

- curated mature repair-state signature derived  
- candidate molecular control layers identified  
- transition-model logic implemented  
- intervention-oriented prioritization framework implemented  
- cross-dataset directional consistency established  

## Long-term vision

Programmable Neurorepair is designed as the first module of a broader platform for understanding and guiding neural cell-state transitions across the central nervous system.

Remyelination is the initial tractable test case, but the larger objective is to extend this framework toward additional neural systems and state dynamics, including neural adaptation, plasticity, and other forms of coordinated biological reorganization.

The long-term goal is to build computational systems capable of identifying molecular control points that govern neural plasticity, repair, and adaptation — and eventually make neural state transitions more predictable and guideable.

---

## Repository structure

- `figures/` — visual outputs
- `results/` — model outputs and tables
- `docs/` — technical notes and summaries
