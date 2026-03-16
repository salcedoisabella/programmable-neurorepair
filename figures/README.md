# Figures

This folder contains the visual layer of the Programmable Neurorepair engine.

The purpose of this layer is to make the logic of the framework interpretable at a glance: how neural cell states are organized, how repair-associated programs emerge, and which molecular control points appear most relevant.

## Figure logic

```mermaid
flowchart TD
    A[Single-cell datasets] --> B[State mapping]
    B --> C[Repair-state structure]
    C --> D[Candidate control nodes]
    D --> E[Intervention and transition modeling]
