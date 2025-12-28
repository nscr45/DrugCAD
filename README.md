# DrugCAD – AI-Driven Interactive Drug Design

DrugCAD is an AI-enabled, CAD-style tool for **de novo drug design**. It lets you visually assemble molecular building blocks (scaffolds, side chains, linkers, functional groups) and gives **real-time feedback** on whether the designed molecule is chemically valid and potentially drug-like (stability, ADMET, toxicity, synthetic feasibility).

Researchers can use DrugCAD to quickly explore candidate molecules **before** committing to expensive wet-lab experiments.

---

## Features

- **Drag-and-drop molecular design** (CAD-like experience)
- **Real-time chemical validation**
  - Valency and bonding rules
  - 3D geometry sanity checks
  - Lipinski’s Rule of Five
- **AI property prediction**
  - Stability score
  - ADMET / bioavailability (where models are trained)
  - Toxicity risk
  - Synthetic accessibility estimate
- **Export & integration**
  - Export SMILES and structure files
  - Designed for extension with additional models and rules

> Status: Early-stage research prototype under active development.

---

## Project Structure

```text
drugcad/
├── components.json               # Core component library (scaffolds, groups, linkers)
├── component_index.json          # Searchable index of components
├── 10_known_drugs.csv            # Example dataset of known drugs
├── validator.py                  # Core validation engine (Lipinski, basic checks)
├── test_week1.py                 # Initial tests for the validator
├── WEEK_1_ACTION_PLAN.md         # Week 1 development plan / roadmap (internal docs)
├── QUICK_REFERENCE.md            # Commands & code snippets (internal docs)
├── drug_design_research_roadmap.md  # Full 8‑month research roadmap
└── README.md                     # Main project description


