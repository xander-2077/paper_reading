# Paper Reading

Interactive paper explainers focused on motion generation, retargeting, and humanoid robotics.

## Online

- [Paper Reading index](https://xander-2077.github.io/paper_reading/)
- [Shooting for Contact](https://xander-2077.github.io/paper_reading/shooting-for-contact/)
- [Kimodo](https://xander-2077.github.io/paper_reading/kimodo/)
- [Humanoid HOI research map](https://xander-2077.github.io/paper_reading/humanoid-hoi/)

## Current notes

### Humanoid HOI research map

A unified, searchable research pool with **174 works** (173 papers and one workshop lead), last updated on **2026-10-11**:

- **45 core HOI papers**, using the stricter contact, object dynamics, whole-body coordination, and interaction-control criteria established on October 8;
- **38 related applications** and **91 supporting methods**, retained in the same pool with a per-paper classification reason;
- **12 priority readings**, selected for complementary research questions rather than author or ingestion date;
- all 174 entries have concise **task / method / experiments** summaries;
- original abstracts and relevant method/experiment passages checked for **173 papers**; the workshop entry has a verified public abstract/listing but unconfirmed experimental details;
- hardware filters distinguish humanoid experiments, other platforms and localization-only evaluation, simulation, trajectory replay, and unknown evidence.

The October 11 update rechecked unread research mail across all folders, fetched one new October 10 digest, screened all 20 previously unseen papers, and added nine to the same pool: three related applications and six supporting methods. No new work met the stricter core criteria, so the 45 core papers and 12 priority readings remain unchanged. VioLA, Being-M0.7, and HWAM have humanoid hardware evidence; Dex-One2Many, OmniHOI, and SkillWeave use arm–hand hardware; GNR, Solo to Ensemble, and ManiUnit provide simulation evidence. All nine summaries state task, method, experimental results, hardware scope, and classification reason. Majid Khadiv's existing papers continue under the same standard.

VioLA's zero-shot claim means no task-specific fine-tuning: task families overlap training, with episodes, environment, and object instances held out. Being-M0.7's hardware comparison comprises 15 trials and ties GR00T-N1.6. OmniHOI reports seven open-loop hardware demonstrations without an aggregate hardware success rate. GNR's reported successes and contact-force data are simulation results.

Success rates are attributed to their experimental setting. Workhorse's reported success rates are simulation-only despite its G1 hardware demonstrations. HULK's small-sample hardware completion rates and separate maximum-load sweeps are distinguished. ResGAC is categorized as a supporting pose-tracking interface, not external-force feedback control. A humanoid-hardware tag alone does not imply autonomous closed-loop whole-body manipulation. Results have not been independently reproduced.

The candidate sources include 2,818 deduplicated arXiv records, journal alerts, and existing author notes. The complete pool was re-screened on October 8; new entries were checked on October 9 or October 11. Each card retains its own verification date and version.

Deduplication uses arXiv IDs and confirmed work-level relationships: withdrawn HumanoidUMI (2606.27239) is merged into BifrostUMI (2605.03452); the same-titled behavior-system thesis (2606.26425) and short paper (2609.01518) share one record with both sources. Distinct papers with the same short name remain separate. Each card links to the original abstract and experimental text.

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
