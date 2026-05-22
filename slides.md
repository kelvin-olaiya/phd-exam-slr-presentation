---
layout: intro
theme: seriph
title: Human-Robot Interaction in Computer Science
transition: fade-out
mdc: true
---

<div class="cover-kicker">Systematic literature review protocol proposal</div>

# Human-Robot Interaction in Computer Science

## Computer science methods, platforms, and evaluation patterns in modern HRI

---
layout: default
class: agenda-slide
---

# Review Frame

<div class="thesis-card">
  <strong>Thesis</strong>
  <p>This review will clarify how computer science methods shape HRI systems across robotic platforms, autonomy architectures, evaluation practices, and emerging foundation-model workflows.</p>
</div>

<div class="agenda-grid">
  <div>
    <span>01</span>
    <strong>Scope</strong>
    <p>Define HRI as a computational and embodied interaction problem.</p>
  </div>
  <div>
    <span>02</span>
    <strong>Protocol</strong>
    <p>Set PICOC, search sources, criteria, and scoring rules.</p>
  </div>
  <div>
    <span>03</span>
    <strong>Extraction</strong>
    <p>Map platforms, methods, domains, evaluation, and autonomy roles.</p>
  </div>
  <div>
    <span>04</span>
    <strong>Outcomes</strong>
    <p>Deliver a coding schema, taxonomy, and evidence gap map.</p>
  </div>
</div>

---
class: emphasis-slide
---

## Motivation & Scope

<div class="lead">
Human-Robot Interaction (HRI) studies how humans and embodied robots perceive, communicate, coordinate, and act together. This protocol focuses on the <strong>computer science perspective</strong>: algorithms, architectures, and evaluation methods behind those interactions.
</div>

<div class="scope-grid">
  <div>
    <strong>Timespan</strong>
    <p>The 2020-2026 period captures the shift from classical ML and modular autonomy toward LLM/VLM-mediated planning, dialogue, perception, and adaptation.</p>
  </div>
  <div>
    <strong>Concrete example</strong>
    <p>A service robot that uses speech, vision-language grounding, task planning, and safety checks to help a human complete a shared task.</p>
  </div>
  <div>
    <strong>Out of scope</strong>
    <p>Purely psychological, sociological, design-only, or non-embodied AI studies without a clear HRI/robotic system component.</p>
  </div>
</div>

---
class: genai-slide
---

## Why foundation models matter

<div class="model-shift">
  <div>
    <carbon-idea />
    <strong>Language as interface</strong>
    <p>LLMs make task specification, clarification, and dialogue policies more flexible than scripted interaction.</p>
  </div>
  <div>
    <carbon-image-search />
    <strong>Grounded perception</strong>
    <p>VLMs connect language to objects, scenes, affordances, and human actions in shared environments.</p>
  </div>
  <div>
    <carbon-decision-tree />
    <strong>Planning bridge</strong>
    <p>Foundation models can translate intent into task plans, while classical robotics still handles constraints, motion, and safety.</p>
  </div>
</div>

--- 

## PICOC

<div class="picoc-cards">
  <div class="picoc-card">
    <div class="picoc-title"><carbon-user-multiple />Population</div>
    <p>Studies of physical robotic systems (humanoids, cobots, mobile/service robots) and related HRI/CS literature from 2020-2026. Simulation-only work is included only when it targets embodied robotic interaction.</p>
  </div>

  <div class="picoc-card">
    <div class="picoc-title"><carbon-machine-learning-model />Intervention</div>
    <p>Computational methods for HRI, including classical ML, deep learning, reinforcement learning, and foundation models (LLMs, VLMs), applied to perception, planning, dialogue, control, and adaptation.</p>
  </div>

  <div class="picoc-card">
    <div class="picoc-title"><carbon-compare />Comparison</div>
    <p>Contrasts modern data-driven and generative-AI HRI methods with traditional baselines, and distinguishes simulation-only studies from real-world deployments.</p>
  </div>

  <div class="picoc-card">
    <div class="picoc-title"><carbon-chart-evaluation />Outcome</div>
    <p>Evaluation criteria across system performance, interaction quality, and human-centered outcomes such as trust, workload, safety, predictability, and legibility.</p>
  </div>

  <div class="picoc-card picoc-card-wide">
    <div class="picoc-title"><carbon-earth />Context</div>
    <p>Categorises study settings (industrial, service, healthcare, hazardous) and evaluation modalities (lab, field, simulation) to assess validity and generalizability of HRI findings.</p>
  </div>
</div>

---
class: rq-slide
---

## Research Questions

<div class="rq-groups">
  <span>Platforms & domains</span>
  <span>Methods & evaluation</span>
  <span>Limitations & gaps</span>
</div>

<div class="rq-cards">
  <div class="rq-card"><span>01</span><p>Which robotic platforms, system classes, and HRI taxonomies are most frequently studied in primary HRI research?</p></div>
  <div class="rq-card"><span>02</span><p>Which computational approaches are used at the levels of perception, planning, dialogue, control, and adaptation?</p></div>
  <div class="rq-card"><span>03</span><p>How do learning-based and AI-driven HRI approaches compare with traditional methodologies on outcome metrics and engineering trade-offs?</p></div>
  <div class="rq-card"><span>04</span><p>What evaluation metrics and assessment frameworks are used in HRI studies?</p></div>
  <div class="rq-card"><span>05</span><p>In which application domains and operational contexts are HRI systems developed and evaluated?</p></div>
  <div class="rq-card"><span>06</span><p>What are the recurring limitations, ethical concerns, and open research gaps in HRI studies?</p></div>
</div>

---
layout: two-cols-header
class: criteria-slide
---


## Inclusion / Exclusion criteria

::left::

### Include

**Studies that are:**
- Primary HRI / robotics / CS empirical studies
- Full-text, English, **2020-2026**
- Defined method + empirical results
- Peer-reviewed archival papers
- Preprints only if no reviewed version exists

::right::

### Exclude

**Studies that are:**
- Non-primary (editorials, position papers, templates, surveys)
- Not full-text or not in English
- Books, chapters, or monographs
- Duplicate reports (keep most complete/latest)
- Non-embodied AI without robotic interaction

::bottom::

<div class="criteria-bottom">

<p><strong>Peer-reviewed scope:</strong> major archival venues such as <strong>ICRA, IROS, RSS, CoRL, ACM/IEEE HRI, RO-MAN, RA-L, T-RO, IJRR, Science Robotics</strong>.</p>

<p><strong>Window rationale:</strong> 2020-2026 captures modern learning-based HRI and the foundation-model shift. <strong>Additional rule:</strong> backward/forward snowballing may add relevant primary studies; surveys and taxonomies are used only as mapping sources.</p>

</div>

---

## Quality assessment

<div class="rubric-note">
  Score each criterion as <strong>0</strong> absent, <strong>1</strong> partial, or <strong>2</strong> adequate. Low-scoring studies remain visible in the map but are flagged for sensitivity analysis rather than automatically removed.
</div>

<div class="quality-grid">
  <div class="quality-card">
    <div class="quality-title"><carbon-search />Research clarity</div>
    <p>The study should state clear research questions, hypotheses, or objectives.</p>
  </div>
  <div class="quality-card">
    <div class="quality-title"><carbon-data-structured />Method detail</div>
    <p>The paper must sufficiently describe its research design, such as experimental setup, dataset, and task conditions.</p>
  </div>
  <div class="quality-card quality-card-wide">
    <div class="quality-title"><carbon-chart-error-bar />Evaluation fit</div>
    <p>The evaluation should be appropriate for the stated objectives, including suitable baselines or ablation/benchmarking procedures where relevant.</p>
  </div>
  <div class="quality-card">
    <div class="quality-title"><carbon-deployment-pattern />Deployment context</div>
    <p>The study should report relevant details about datasets, simulation environments, or real-world deployment conditions.</p>
  </div>
  <div class="quality-card">
    <div class="quality-title"><carbon-checkmark-outline />Evidence alignment</div>
    <p>Results should be interpreted in a way that is consistent with the presented evidence.</p>
  </div>
  <div class="quality-card">
    <div class="quality-title"><carbon-code />Artifacts</div>
    <p>When applicable the study should provide artifacts such as code, parameter settings, datasets, and prompts.</p>
  </div>
  <div class="quality-card">
    <div class="quality-title"><carbon-warning-alt />Validity threats</div>
    <p>The study should acknowledge limitations, biases, or internal/external validity threats.</p>
  </div>
</div>

---
class: search-slide
---

## Sources extraction and databases

```txt
("human-robot interaction" OR HRI OR "human robot collaboration")
AND
(robot* OR humanoid OR cobot* OR "mobile robot*" OR "service robot*")
AND
("machine learning" OR "deep learning" OR "reinforcement learning" 
 OR "large language model*" OR LLM OR "vision-language model*" OR VLM 
 OR "foundation model*" OR "generative AI" OR diffusion)
AND
(planning OR "motion planning" OR manipulation OR "task planning" 
 OR "social robotics" OR "cognitive robotics")
AND
(simulation OR "user study" OR "real-world" OR deployment OR experiment*)
```

<ul class="source-grid">
  <li>
    <div class="source-icon"><carbon-catalog /></div>
    <strong>Scopus</strong>
  </li>
  <li>
    <div class="source-icon"><carbon-chip /></div>
    <strong>IEEE Xplore</strong>
  </li>
  <li>
    <div class="source-icon"><carbon-cics-program /></div>
    <strong>ACM Digital Library</strong>
  </li>
</ul>

<div class="search-result-note">
  <strong>Early search check:</strong> Scopus 659, IEEE Xplore 461, ACM Digital Library 2685. ACM likely needs query refinement.
</div>

Deduplication is performed at **record-level** and **study-level**. Backward snowballing scans references of included papers; forward snowballing checks later citing primary studies for high-relevance additions.

---
class: pipeline-slide
---

## Review pipeline

```mermaid
flowchart LR
  A[Database search] --> B[Record deduplication]
  B --> C[Title and abstract screening]
  C --> D[Full-text assessment]
  D --> E[Quality scoring]
  E --> F[Data extraction]
  F --> G[Synthesis and gap map]
  D --> H[Backward snowballing]
  D --> I[Forward snowballing]
  H --> C
  I --> C
```

---
class: extraction-slide
---

## Data extraction

**Extraction dimensions:**

<ol class="dimension-grid">
  <li><strong>Application Domain:</strong> industrial/collaborative, service/hospitality, social/assistive, healthcare, hazardous.</li>
  <li><strong>AI / ML & Foundation-Model Stack:</strong> classical ML/DL, RL/IL for control, LLM/VLM, hybrid architectures.</li>
  <li><strong>Robotic Platforms:</strong> humanoid/anthropomorphic, manipulators/cobots, mobile/ground robots</li>
  <li><strong>Robotic Focus Area:</strong> task/motion planning, manipulation, physical interaction, language grounding.</li>
  <li><strong>Evaluation Setting:</strong> simulation-only, real robot without participants, lab study, field deployment.</li>
  <li><strong>Interaction Paradigm:</strong> teleoperation/direct control, shared autonomy, mixed initiative, dialogue, grounded instruction.</li>
  <li><strong>Autonomy / HITL Structure:</strong> human as operator, advisor, teacher, supervisor, collaborator, or beneficiary.</li>
</ol>

---
class: extraction-table-slide
---

## Draft extraction table

| Field | Example value |
|---|---|
| Platform | mobile service robot, cobot arm, humanoid |
| AI method | LLM planner, VLM grounding, RL controller |
| Technical layer | perception, planning, dialogue, control, adaptation |
| Evaluation setting | simulation, lab study, real robot, field deployment |
| Metrics | success rate, latency, recovery, trust, workload |
| Evidence quality | baseline, ablation, participants, artifacts |

---
class: taxonomy-slide
---

## Taxonomy preview

<div class="taxonomy-grid">
  <div><strong>Domain</strong><p>industrial, service, healthcare, hazardous, social/assistive</p></div>
  <div><strong>Platform</strong><p>humanoid, manipulator/cobot, mobile robot, multi-robot system</p></div>
  <div><strong>Method</strong><p>classical ML, DL, RL/IL, LLM, VLM, diffusion, hybrid stack</p></div>
  <div><strong>Interaction</strong><p>teleoperation, shared autonomy, dialogue, instruction following, collaboration</p></div>
  <div><strong>Evaluation</strong><p>simulation, benchmark, lab user study, real-world deployment</p></div>
  <div><strong>Autonomy role</strong><p>operator, teacher, supervisor, collaborator, beneficiary</p></div>
</div>

---
class: synthesis-slide
---

## Planned synthesis

<div class="synthesis-grid">
  <div><carbon-chart-column /> <strong>Frequency mapping</strong><p>Count platforms, domains, methods, evaluation settings, and outcome metrics.</p></div>
  <div><carbon-map /> <strong>Evidence map</strong><p>Cross-tabulate method families against robotic focus areas and deployment maturity.</p></div>
  <div><carbon-text-link-analysis /> <strong>Narrative synthesis</strong><p>Explain recurring design patterns, trade-offs, and limitations across study clusters.</p></div>
  <div><carbon-warning-square /> <strong>Gap example</strong><p>LLM-based planners may be common in demos but under-evaluated in long-running real-world HRI deployments.</p></div>
</div>

---
layout: center
class: outcomes-slide
---

## Expected outcomes

<ul class="outcome-row">
  <li>
    <div class="outcome-icon"><carbon-document-requirements /></div>
    <strong>Protocol</strong>
    <p>Reproducible review protocol plus a screening and quality-scoring rubric.</p>
  </li>
  <li>
    <div class="outcome-icon"><carbon-tree-view-alt /></div>
    <strong>Coding schema</strong>
    <p>Extraction spreadsheet and controlled vocabulary for platforms, methods, metrics, and contexts.</p>
  </li>
  <li>
    <div class="outcome-icon"><carbon-idea /></div>
    <strong>Gap analysis</strong>
    <p>Evidence map identifying underexplored method-domain pairs and weak deployment evidence.</p>
  </li>
</ul>

---
class: validity-slide
---

## Threats to validity & bias control

<ul class="risk-grid">
  <li><span>01</span><strong>Construct coverage</strong><p>Risk: PICOC may oversimplify HRI metrics. Mitigation: code system, interaction, and human-centered outcomes separately.</p></li>
  <li><span>02</span><strong>Selection bias</strong><p>Risk: databases may miss niche venues. Mitigation: use backward and forward snowballing from included studies.</p></li>
  <li><span>03</span><strong>Terminology drift</strong><p>Risk: LLM/VLM/foundation-model terms change quickly. Mitigation: record aliases and update search strings during refinement.</p></li>
  <li><span>04</span><strong>Publication bias</strong><p>Risk: positive and fashionable results dominate. Mitigation: track baselines, failures, limitations, and deployment maturity.</p></li>
  <li><span>05</span><strong>External validity</strong><p>Risk: papers may overrepresent lab settings. Mitigation: separate simulation, lab, real-robot, and field evidence.</p></li>
  <li><span>06</span><strong>Fast-moving field</strong><p>Risk: AI literature may become outdated during review. Mitigation: freeze search date and report late-breaking studies separately.</p></li>
</ul>

---
layout: center
class: conclusion-slide
---

## Conclusion

<div class="conclusion-panel">
  <strong>Core takeaway</strong>
  <p>This protocol frames HRI as an embodied computer science problem: methods, platforms, autonomy structures, and evaluation practices must be mapped together to understand the field.</p>
</div>

<div class="conclusion-grid">
  <div><carbon-document /> <span>Protocol</span><p>Refine query strings, screening rules, and quality scoring.</p></div>
  <div><carbon-table /> <span>Evidence base</span><p>Extract platforms, methods, metrics, contexts, and deployment maturity.</p></div>
  <div><carbon-map /> <span>Synthesis</span><p>Produce a taxonomy and gap map for future related-work writing.</p></div>
</div>


