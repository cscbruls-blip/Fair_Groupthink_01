# FAIR Theory: Groupthink: A Theory of Interdependent Symptom Escalation

**Authors:** Laurine van ’t Hullenaar, Cindy Bruls, Joris Muijs (Group Keep Calm)  
**Concept DOI:**  DOI: 10.5072/zenodo.649591

## Overview & Purpose
This repository archives a formalized, time-sliced Directed Acyclic Graph (DAG) of **Interdependent Symptom Escalation in Groupthink**, reframing Janis (1971) from a static checklist of group states into a dynamic causal process.

## Scope and Boundaries
The theory applies to **small, interdependent decision-making groups with identity investment** that meet repeatedly over a decision cycle. Large or loosely connected groups and groups without identity investment fall outside the scope of this theory.

## X-Interoperability & Constructs
The model is specified in plain-text DOT/dagitty format (`theory.txt`) across an initial phase (`_t0`) and an escalation phase (`_t1`):
- **Exogenous mechanism:** `concurrence_seeking` (dominant mode of thinking overriding realistic appraisal of alternatives).
- **Central drivers (`_t0` -> `_t1`):** `morality`, `rationalization`, and `pressure` (highest out-degree in the symptom network).
- **Peripheral symptoms (`_t0` -> `_t1`):** `invulnerability`, `stereotypes`, `self_censorship`, `unanimity`, and `mindguards`.
- **Endogenous outcome:** `defective_decision_making` (e.g., considering too few alternatives and failing to re-examine the preferred option).

This specification supports causal inference (variable selection), simulation-based evaluation (e.g., single-symptom interventions), and empirical longitudinal testing.

## Citation & License
Licensed under **CC0** (public domain) to maximize reuse. Please cite the Zenodo Concept DOI above and the underlying theoretical basis (Janis, 1971) when reusing or extending this theory.
'

writeLines(readme_text, file.path(project_path, "README.md"))# FAIR theory: Groupthink: A Theory of Interdependent Symptom Escalation

# Description

This is a FAIR theory, see Van Lissa et al., in preparation.

# Interoperability

Explain what the theory can be reused for, and how.

# Contributing

If you want to contribute to this project, please get involved. You can do so in three ways:

1. **To discuss the current implementation and discuss potential changes**, file a 'GitHub' issue
2. **To directly propose changes**, send a pull request containing the proposed changes
3. **To create a derivative theory**, please fork the repository

If you fork the repository, please cite this repository (see below), and add it as a related work (below and by adding the appropriate metadata on 'Zenodo').

By participating in this project, you agree to abide by the [Contributor Covenant](https://www.contributor-covenant.org/version/2/0/code_of_conduct.html).

## Related works

Optionally, cite the canonical reference for the theory implemented in this repository here. This is redundant with adding the cross-reference in 'Zenodo', but may be useful nonetheless.

## Citing this work

See this project's 'Zenodo' page for the preferred citation.
