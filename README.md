# Programmable Neurorepair

Programmable Neurorepair is a computational engine for mapping neural cell-state transitions and identifying molecular control points that can shift cells toward desired functional states.

The current proof of concept focuses on remyelination, using single-cell transcriptomic data to model how oligodendrocyte-lineage cells move between precursor-like and mature repair states. The broader goal is to build frameworks that make neural state transitions more mappable, more predictable, and eventually more guideable across the central nervous system.

---

## Core idea

Modern neuroscience can measure cells, circuits, and molecular states in extraordinary detail, but still lacks principled frameworks for understanding what actually controls transitions between neural states.

Programmable Neurorepair aims to address this by building computational systems that:

- map neural cell-state landscapes
- identify molecular control points associated with transitions between those states
- simulate how perturbations could shift cells toward desired functional outcomes

---

## Module 1: Remyelination

The first module focuses on oligodendrocyte lineage dynamics during demyelination and remyelination.

This module models transitions between:

- precursor-like oligodendrocyte states
- mature oligodendrocyte repair states

across multiple single-cell datasets.

The goal is to identify candidate molecular levers that increase the probability of cells entering a remyelinating state.

---

## Current workflow

The current version of the engine includes:

1. **State mapping**  
   Reconstruction of repair-state structure across demyelination, normal, and remyelination conditions.

2. **Cross-dataset validation**  
   Testing whether state patterns generalize across independent datasets.

3. **Candidate prioritization**  
   Ranking molecular control nodes associated with state transitions.

4. **Transition modeling**  
   Simulating how candidate activation shifts the probability of mature repair states.

---

## Current outputs

Current analyses support biologically plausible repair gradients across datasets and identify multiple mechanistically distinct intervention candidates.

### Current candidate layers
- **Tspan2** — flagship repair-state lever
- **Gjc2** — repair-architecture candidate
- **Ptgds** — signaling candidate
- **Ptprd** — control-node candidate
- **Aspa / Fa2h / Abca2** — repair-support program genes

### Current engine components
- repair-state signature derivation
- cross-dataset validation
- candidate prioritization
- intervention simulation
- transition engine v1

---

## Project status

Early computational prototype.

The current repository is being used to organize the first proof of concept and public-facing materials for the project.

---

## Long-term vision

The long-term goal of Programmable Neurorepair is to develop computational systems that can identify molecular control points governing neural cell-state transitions across the central nervous system.

Remyelination is the first tractable test case, but the broader vision is to extend this framework toward additional neural systems, including inflammatory-state control, astrocyte state transitions, and more general models of neural adaptation and repair.

The larger objective is to help move neuroscience from observation toward prediction and principled intervention.

---

## Repository structure

- `figures/` — project figures and visual outputs
- `results/` — selected tables and model outputs
- `docs/` — summaries and supporting materials

---

## Contact

GitHub repository created as the public-facing project page for the early development of Programmable Neurorepair.
