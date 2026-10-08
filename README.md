# Paper Reading

Interactive paper explainers focused on motion generation, retargeting, and humanoid robotics.

## Online

- [Paper Reading index](https://xander-2077.github.io/paper_reading/)
- [Shooting for Contact](https://xander-2077.github.io/paper_reading/shooting-for-contact/)
- [Kimodo](https://xander-2077.github.io/paper_reading/kimodo/)
- [Humanoid HOI research map](https://xander-2077.github.io/paper_reading/humanoid-hoi/)

## Current notes

### Humanoid HOI research map

A searchable research map with 118 papers, deduplicated by arXiv ID:

- 51 core HOI papers and 67 related-method candidates;
- 12 priority readings and a 10-paper Majid Khadiv spotlight, both subsets of the full index;
- contact planning, physically feasible retargeting, whole-body manipulation, and demonstration expansion;
- cross-paper reading links, publication status, and distinctions between humanoid hardware, quadrupeds, manipulators, and simulation;
- links back to the Kimodo and Shooting for Contact explainers.

Checked through **2026-10-08**. Original abstracts or selected paper sections were checked for 22 entries; the other 96 remain preliminary reading candidates. One workshop lead is listed separately and excluded from the paper count. Dates distinguish arXiv submission days from ID-derived months and publication status. Reading recommendations are editorial judgments, not reproduced experimental results.

The page contains only research notes and public paper metadata. It is self-contained HTML with embedded data and does not load external scripts, fonts, or data APIs.

Primary sources: [TUM author page](https://www.ce.cit.tum.de/en/aipd/members/majid-khadiv/), arXiv, IEEE, PMLR, and official workshop listings. Each entry links to its public source.

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
