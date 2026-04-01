Repository files navigation
README
Programmable Neurorepair

A computational wedge into neural state control, starting with remyelination and oligodendrocyte-lineage repair.

Why this project exists

Neuroscience still lacks a usable framework for identifying distinct neural state structure, understanding the logic of transitions between states, and discovering minimal control architectures that can move systems toward more functional states.

Most work still stops at description: cataloging damage, measuring recovery, or listing molecular correlates. What is still missing is a tractable way to move from state mapping to transition logic, from transition logic to control architecture, and from control architecture to intervention-facing programs.

Programmable Neurorepair is an attempt to build that bridge.

Current wedge: remyelination / oligodendrocyte-lineage repair

This project begins with remyelination because remyelination is not just a repair problem. It is one of the clearest biologically structured entry points into a broader problem.

Myelin sits close to the foundations of neural function: conduction timing, synchrony, signal propagation, circuit efficiency, and the stability of large-scale brain networks all depend on it. That makes remyelination especially important as a first wedge. It provides a tractable system in which repair-relevant state transitions can be modeled clearly enough to expose deeper principles of neural state control.

In that sense, remyelination is the beginning, not the destination.

Core thesis

The deeper goal of this project is not only to understand repair, but to help build a framework for neural state control:

identify distinct functional state structure
understand the logic of transitions between states
derive minimal control architectures that can redirect those transitions
organize intervention-facing programs around those architectures
prioritize what should be validated first
Programmable Neurorepair is the current working name. It reflects the first wedge, not the final scope. Neurorepair is where this work begins, but not where the long-term ambition ends.

What now exists

The project now includes:

a repair-state map
a dominant repair-compatible basin
intermediate / review-like structure
boundary / frontier logic
a minimal push-anchor-support architecture
an integrated stack system
first-pass external support
an intervention-facing program layer
a ranked validation-preparation ladder
reviewer-facing, founder-facing, and application-specific packaging
Minimal architecture

The current minimal architecture is:

Tspan2 = push
Ptprd = anchor
Aspa = support
This should not be read as a final mechanistic proof. It should be read as the current minimal control logic that best organizes the state-transition structure observed so far.

Integrated system logic

The project no longer functions only as a descriptive atlas or signature exercise.

It now behaves more like a system with multiple linked layers:

State layer
Identify repair-relevant state structure.

Transition layer
Interpret intermediate, review-like, and frontier states rather than forcing a binary good-vs-bad map.

Architecture layer
Derive minimal control logic from the observed structure.

Program layer
Translate the architecture into intervention-facing programs.

Validation layer
Prioritize which programs should be tested first and how meaningful signal should be recognized.

Current stack modes

The current integrated stack modes are:

default_safe_stack
Conservative interpretation and reinforcement of the dominant repair-compatible basin.

balanced_analysis_stack
Strongest current compromise between movement and stability for intermediate states.

boundary_probe_stack
Used to interrogate ambiguity-rich frontier behavior and transition logic.

maximum_rescue_probe_stack
Most aggressive rescue-oriented mode; informative, but not the default operating mode.

External validation status

External validation now exists in a first meaningful form.

Dataset B provides the strongest first-pass external support.
Dataset C serves as supportive triangulation, but is currently best framed as supportive_mixed rather than a co-equal benchmark.
What this means:

the architecture is not only an internal sandbox reading
dominant basin logic has first-pass external support
intermediate / frontier-like structure also has first-pass external support
external support exists, but identical geometry is not claimed
Intervention-facing layer

The architecture is currently translated into four intervention-facing programs:

default_safe_translation_program
First-line program for preserving or reinforcing a strong repair-compatible basin.

balanced_state_transition_program
Best current second-line program for moving an intermediate state upward without losing too much stability.

boundary_probe_program
Used for probing ambiguity-rich transition behavior and frontier structure.

maximum_rescue_program
Upper-bound rescue-oriented logic for cases where lower-risk programs may be insufficient.

Validation order

The current validation-preparation order is:

default_safe_translation_program
balanced_state_transition_program
boundary_probe_program
maximum_rescue_program
This order is intentional. Conservative dominant-basin reinforcement should be tested before more aggressive rescue logic.

Current status

Current project status:

first wedge built
v1 strategically complete
external validation first version completed
intervention translation layer built
validation-preparation layer built
platform / founder layer built
application-specific packaging built
The next real phase is experimental validation design, not more internal polishing.

Guardrails

This project should be read ambitiously, but also carefully.

What it does support:

a serious first wedge into neural state control
a coherent state-to-architecture-to-programs framework
meaningful first-pass external support
a real intervention-facing and validation-facing logic layer
What it does not yet support:

proof of general neural state control
proof of therapeutic efficacy
a finished therapy
a finished company or product
a claim that all ambiguity has already been resolved
Long-term direction

The long-term direction is broader than remyelination alone.

This project starts with repair because repair provides a tractable first wedge. But the deeper ambition is to move toward a broader framework for:

richer recovery
stronger resilience
cognition-relevant improvement
and, eventually, more serious forms of neural state guidance and human enhancement
That long-term direction remains future-facing. The current project should be understood as the first real wedge into it.

Documentation

For more detail, see:

docs/PROJECT_OVERVIEW.md
docs/SYSTEM_STACKS.md
docs/INTERVENTION_LAYER.md
docs/EXTERNAL_VALIDATION.md
docs/PLATFORM_THESIS.md
docs/RESULTS_INDEX.md
docs/REVIEWER_SUMMARY.md
docs/FOUNDER_SUMMARY.md
Current reading: a serious first computational wedge into programmable neurorepair, with broader implications for neural state control.

Why this matters

Modern neuroscience can measure cells, circuits, and molecular states at extraordinary resolution, but still lacks principled frameworks for understanding what actually controls transitions between neural states.

As a result, many interventions remain blunt relative to the complexity of the systems they are trying to affect. We can often describe dysfunction in great detail without understanding which molecular control points govern movement between damaged, adaptive, and repair-supporting states.

Programmable Neurorepair is an attempt to help close that gap.

Current focus: oligodendrocyte repair dynamics

The first module focuses on oligodendrocyte-lineage dynamics during demyelination and remyelination.

Using single-cell transcriptomic datasets, the framework models transitions between:

precursor-like oligodendrocyte states
mature oligodendrocyte repair states
This allows the system to identify molecular control points associated with the probability of cells entering a remyelinating state.

Repair-state signature

The current repair-state program includes genes strongly associated with mature oligodendrocyte function and remyelination:

Mal
Cldn11
Plp1
Mog
Mobp
Mbp
Mag
Cnp
Abca2
Tspan2
Ptgds
Myrf
These genes define the mature repair-state signature used by the engine to classify cellular states and model repair-associated transitions.

Candidate molecular control layers

Initial analyses highlight several mechanistically distinct candidate layers associated with remyelinating states:

Flagship repair-state lever

Tspan2
Repair architecture / support layer

Gjc2
Fa2h
Aspa
Abca2
Signaling and control candidates

Ptgds
Ptprd
Together, these candidates suggest that remyelination may be decomposed into multiple functional layers rather than explained by a single marker or pathway.

Current status

Early computational framework, already implemented across multiple independent datasets.

The first wedge has already produced a visible evidence layer rather than only a conceptual project description. Current outputs include repair-state structure, a curated mature repair-state signature, candidate control-layer separation, transition-oriented logic, cross-dataset directional support, and intervention-oriented prioritization.

Current evidence

Evidence artifacts

Dataset roles
Repair signature genes
Candidate control layers
Transition logic summary
Current outputs snapshot
Current candidate ranking (CSV)
Repair signature (CSV)
Current operational status

state-structure derivation implemented
mature repair-state signature derived
candidate control-layer separation implemented
transition-oriented logic implemented
cross-dataset directional support established
intervention-oriented prioritization implemented
Operational significance

Programmable Neurorepair is not only arguing that neural state transitions should be modeled differently. It already contains the first operational layers of that approach: state-structure derivation, repair-state definition, candidate control-layer separation, and transition-oriented intervention logic.

Evidence table

Component	Current evidence
Repair-state structure	oligodendrocyte-lineage progression modeled across datasets
Repair-state signature	curated mature repair-state program derived
Candidate prioritization	leverage / support / signaling layers identified
Transition logic	state-shift / repair-probability modeling implemented
Cross-dataset support	directional consistency across distinct biological contexts
Long-term vision

Programmable Neurorepair is designed as the first module of a broader platform for understanding and guiding neural cell-state transitions across the central nervous system.

Remyelination is the initial tractable test case, but the larger objective is to extend this framework toward additional neural systems and state dynamics, including neural adaptation, plasticity, and other forms of coordinated biological reorganization.

The long-term goal is to build computational systems capable of identifying molecular control points that govern neural plasticity, repair, and adaptation—and eventually make neural state transitions more predictable and guideable.

Repository structure

figures/ — visual evidence layer
results/ — model outputs and tables
docs/ — project-level documentation
