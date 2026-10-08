# Paper Reading

Interactive paper explainers focused on motion generation, retargeting, and humanoid robotics.

## Online

- [Paper Reading index](https://xander-2077.github.io/paper_reading/)
- [Shooting for Contact](https://xander-2077.github.io/paper_reading/shooting-for-contact/)
- [Kimodo](https://xander-2077.github.io/paper_reading/kimodo/)
- [Humanoid HOI research map](https://xander-2077.github.io/paper_reading/humanoid-hoi/)

## Current notes

### Humanoid HOI research map

A unified, searchable research pool with **155 works** (154 papers and one workshop lead), re-screened on **2026-10-08**:

- **43 core HOI papers**, narrowed from 118 using direct contact, object dynamics, whole-body coordination, and interaction-control contributions;
- **34 related applications** and **78 supporting methods**, retained in the same pool with a per-paper classification reason;
- **12 priority readings**, selected for complementary research questions rather than author or ingestion date;
- all 155 entries have concise **task / method / experiments** summaries;
- original abstracts and relevant method/experiment passages checked for **154 papers**; the workshop entry has a verified public abstract/listing but unconfirmed experimental details;
- hardware filters distinguish humanoid experiments, upper-body/wheeled/other platforms, simulation, trajectory replay, and unknown evidence.

Success rates are attributed to their experimental setting. For example, Weave is simulation-only; CoorDex's hardware visualization replays trajectories on a different hand configuration. A humanoid-hardware tag alone does not imply autonomous closed-loop whole-body manipulation. Results have not been independently reproduced.

The candidate sources include 2,778 deduplicated arXiv records, journal alerts, and existing author notes. Every author, including Majid Khadiv, shares the same screening criteria. This revision re-audits the complete existing pool rather than creating a new-source section.

Deduplication uses arXiv IDs and confirmed work-level relationships: withdrawn HumanoidUMI (2606.27239) is merged into BifrostUMI (2605.03452); the same-titled behavior-system thesis (2606.26425) and short paper (2609.01518) share one record with both sources. Distinct papers with the same short name remain separate. Each card links to the original abstract and experimental text and records its checked version.

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
