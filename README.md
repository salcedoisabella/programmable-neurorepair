# Programmable Neurorepair

Programmable Neurorepair is a computational framework for mapping neural cell-state transitions and identifying molecular control points that can shift cells toward regenerative or functional states.

The project focuses on building systems that move neuroscience beyond observation and toward the ability to predict and guide biological state transitions across the central nervous system.

---

# Core Question

Modern neuroscience can measure cells and molecular states at extraordinary resolution, particularly with single-cell transcriptomics. However, identifying which mechanisms actually control transitions between neural states remains extremely difficult.

Programmable Neurorepair addresses this gap by modeling how neural cell populations move across state landscapes and identifying candidate control nodes associated with those transitions.

---

# Current Focus: Oligodendrocyte Repair Dynamics

The first module of the system focuses on oligodendrocyte lineage dynamics during demyelination and remyelination.

The framework analyzes single-cell transcriptomic datasets to model transitions between:

- precursor-like oligodendrocyte states
- mature oligodendrocyte repair states

This allows the system to identify molecular control points associated with the probability of cells entering a remyelinating state.

---

# Repair-State Signature

The current repair-state program includes genes strongly associated with mature oligodendrocyte function and remyelination:

- Mal
- Cldn11
- Pll1
- Mog
- Mobp
- Mbp
- Mag
- Cnp
- Abca2
- Tspan2
- Ptgds
- Myrf

These genes define the mature repair-state signature used by the engine to classify cellular states.

---

# Candidate Molecular Control Nodes

Initial analyses highlight several candidate control layers associated with remyelinating states:

**Flagship repair-state lever**
- Tspan2

**Repair architecture genes**
- Gjc2
- Fa2h
- Aspa

**Signaling and regulatory candidates**
- Ptgds
- Ptprd

These genes represent potential molecular levers influencing the probability of oligodendrocyte maturation and myelin repair.

---

# Engine Components

Current system components include:

- repair-state signature derivation
- cross-dataset validation
- candidate control node prioritization
- transition modeling
- intervention simulation (v1)

---

# Vision

Programmable Neurorepair is designed as a general framework for mapping and guiding neural cell-state transitions.

Remyelination is the first tractable test case, but the broader objective is to extend the system toward additional neural cell types and state dynamics across the central nervous system.

The long-term goal is to build computational systems capable of identifying molecular control points that govern neural plasticity, repair, and adaptation, and eventually make neural state transitions more predictable and guideable.

---

## Repository Structure

- `figures/` — visual outputs  
- `results/` — model outputs and tables  
- `docs/` — technical notes and summaries
