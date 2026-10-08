# Paper Reading

Interactive paper explainers focused on motion generation, retargeting, and humanoid robotics.

## Online

- [Paper Reading index](https://xander-2077.github.io/paper_reading/)
- [Shooting for Contact](https://xander-2077.github.io/paper_reading/shooting-for-contact/)
- [Kimodo](https://xander-2077.github.io/paper_reading/kimodo/)
- [Humanoid HOI research map](https://xander-2077.github.io/paper_reading/humanoid-hoi/)

## Current notes

### Humanoid HOI research map

A unified, searchable research pool with **155 works** (154 papers and one workshop lead):

- 118 core HOI works and 37 related-method references, screened using the same relevance criteria;
- 20 priority readings, with all authors sharing the same topic filters and relevance ranking;
- contact representations, whole-body manipulation, physically feasible retargeting, data generation, and perception-driven control;
- explicit distinctions between humanoid hardware, upper-body and wheeled platforms, manipulators, and simulation.

The full candidate pool includes 2,778 deduplicated arXiv records, journal alerts, and existing author research notes. Ingestion date does not affect the reading rank. Checked through **2026-10-08 18:00 CST**: original abstracts or selected paper sections were checked for 60 entries; 95 remain preliminary candidates or leads. Relevance labels and verification depth are separate dimensions. Results have not been reproduced.

Deduplication uses arXiv IDs and confirmed work-level relationships: withdrawn HumanoidUMI (2606.27239) is merged into BifrostUMI (2605.03452); the same-titled behavior-system thesis (2606.26425) and short paper (2609.01518) share one record with both sources. The workshop lead is part of the same pool and clearly labeled as awaiting detailed verification. Dates distinguish arXiv submission days, ID-derived months, workshop years, and journal publication dates.

The page contains only research notes and public paper metadata. It is self-contained HTML and loads no external scripts, fonts, or data APIs. Sources link to arXiv, IEEE, TUM, PMLR, and author/project pages; mailbox contents and identifiers are not published.

### Kimodo: Scaling Controllable Human Motion Generation

The explainer covers:

- the human motion generation to humanoid reference-motion pipeline;
- controllable pose-space diffusion and Kimodo's two-stage denoiser;
- motion representation, constraints, training, scaling, and ablations;
- the boundary between kinematic generation and physical robot control;
- a paper-to-code audit of what the public repository implements.

Sources: [paper](https://arxiv.org/abs/2603.15546) · [code](https://github.com/nv-tlabs/kimodo)

### Shooting for Contact

An interactive walkthrough of contact-implicit multiple shooting for dynamic motion retargeting.
