---
yaml_schema_version: "2.11"
document_version: "1.1"
document_last_updated_date: "2026-10-22"
document_last_updated_time: "15:20:00 CDT"
document_monotonicity: "REQUIRED - Ensure document_version and timestamps strictly increment on every update of the target document. Reject regressions."
anti_cwa_cardinal_rule: "ALWAYS ASK, NEVER INFER. Do not hallucinate physical world state, task completion, or implicit preferences."
routing_clearance: "GENERAL / LAB-WIDE - SANITIZED PER NECK-REINING PROTOCOL V3.1 FOR STUDENT AND CO-ADVISOR DISTRIBUTION."
---

# 🧭 RUBRIC: Hypothesis Quality, Construct Validity & Experimental Architecture

**Document Purpose:** 
A standardized evaluation matrix derived from the *Epistemic Rigor Meta-Rubric*. This instrument scores research hypotheses and experimental protocols across computer science and machine learning workflows. It enforces construct validity, separates stochastic generation from deterministic verification, and utilizes **Argon Reversible Branching** (staging secondary ideas behind foundational baselines rather than prematurely discarding them).

## 📊 Evaluation Criteria & Scoring Weights (100-Point Scale)

| Criterion | Weight | Focus Area |
| :--- | :--- | :--- |
| **[1] A Priori Falsifiability & Decision Thresholds** | 30 pts | Operationalization of qualitative claims into pre-specified, refutable quantitative bounds. |
| **[2] Epistemic Separation (Generator vs. Verifier Independence)** | 25 pts | Elimination of reference-label circularity, outcome leakage, and unverified model anchoring. |
| **[3] Construct Validity & Causal Isolation** | 20 pts | Separation of the target mechanism from confounding variables via controlled ablations. |
| **[4] Staged Architecture & Reversible Branching (Argon Scaffold)** | 15 pts | Grounding complex multi-hypothesis plans in a verifiable `Method 1` baseline with gated extensions. |
| **[5] Reproducible Artifact & Provenance Integration** | 10 pts | Mapping experimental stages to version-controlled schemas, data dictionaries, and audit logs. |

---

### 1. A Priori Falsifiability & Decision Thresholds (30 Points)
*Does the protocol operationalize qualitative terms into measurable boundary conditions before execution, specifying what empirical outcome would refute the hypothesis?*

* **1 – Pre-Formal / Unbounded (0–10 pts):** Relies on unquantified qualitative descriptors (e.g., "good enough," "improves performance," "more meaningful") without defining the target metric, comparison baseline, or refutation threshold. Permits post-hoc reinterpretation of null results.
* **3 – Partial Differentiation (11–20 pts):** Specifies evaluation metrics (e.g., Macro-F1, IoU, AURC, Cohen's $\kappa$) and baseline comparators, but omits the decision rule, minimum meaningful effect size, or variance/uncertainty estimation required to adjudicate the hypothesis.
* **5 – Sovereign Consonance (21–30 pts):** Explicitly defines the primary endpoint, matched-budget baselines, statistical uncertainty procedure, and exact falsification boundary *prior* to unblinding test outcomes. Distinguishes confirmatory primary claims from exploratory secondary diagnostics.

### 2. Epistemic Separation (Generator vs. Verifier Independence) (25 Points)
*Does the experimental design maintain a strict boundary between the system under evaluation (or stochastic label proposer) and the reference standard used to score it?*

* **1 – Reference Circularity (0–8 pts):** Exhibits direct or indirect circularity between the evaluated method and the reference standard—for example, using unverified zero-shot LLM/VLM outputs as ground truth, conditioning human annotation eligibility on downstream model success/failure, or evaluating cross-modal discovery on a pool pre-filtered exclusively by one modality.
* **3 – Anchored / Partially Coupled Verification (9–18 pts):** Incorporates human-in-the-loop review, but exposes annotators to model predictions, confidence scores, or rank orderings without an unassisted, blinded calibration subset to measure anchoring bias.
* **5 – Sovereign Consonance (19–25 pts):** Enforces an epistemic wall between generation and verification. The evaluation reference is constructed independently of system predictions and candidate-selection biases (with randomized presentation and documented masking). Any assisted or weak-supervision labeling (`source=silver`) is calibrated against a protected, independently audited reference (`source=gold`).

### 3. Construct Validity & Causal Isolation (20 Points)
*Does the experiment isolate the specific mechanism claimed in the hypothesis from confounding factors?*

* **1 – Confounded Proxy (0–7 pts):** Equates an indirect proxy with the target construct without validation (e.g., treating classifier saliency maps as direct measures of optical image quality, or treating geometric occlusion as identical to optical blur).
* **3 – Correlational Comparison (8–14 pts):** Demonstrates an empirical difference between configurations, but leaves input coverage, token/compute budgets, or information access unequal across arms, preventing attribution to the proposed mechanism.
* **5 – Sovereign Consonance (15–20 pts):** Isolates the causal mechanism via information-matched controls and synthetic or interventional ablations (e.g., verifying that degrading the target region lowers the metric while matched background degradation does not).

### 4. Staged Architecture & Reversible Branching (Argon Scaffold) (15 Points)
*Does the experimental plan protect research momentum by staging ambitious extensions behind a self-contained, low-risk foundational baseline?*

* **1 – Monolithic Entanglement (0–5 pts):** Bundles multiple sequential dependencies (e.g., zero-shot prompting, human correction UI, model fine-tuning, dataset curation, and saliency fallback) into a single coupled pipeline where an upstream flaw invalidates all downstream effort.
* **3 – Linear Sequencing without Gates (6–10 pts):** Lists experimental steps in a logical order, but lacks explicit go/no-go verification checkpoints or a fallback baseline (`Method 1`) if an intermediate model or external resource underperforms.
* **5 – Sovereign Consonance (11–15 pts):** Implements **Delayed Pruning and Reversible Branching**. Locks the immediate critical path to a self-contained Minimum Quantum of Work (`Method 1` baseline and interventional sanity check) while preserving secondary hypotheses in a gated extension table with explicit unlock criteria and fallback rules.

### 5. Reproducible Artifact & Provenance Integration (10 Points)
*Does each experimental stage emit a deterministic, version-controlled artifact that allows independent recomputation?*

* **1 – Off-Ledger / Ephemeral Output (0–3 pts):** Relies on unrecorded local runs, conversational summaries, or unversioned spreadsheets without schema definitions or commit provenance.
* **3 – Outcome-Only Archiving (4–7 pts):** Saves final summary tables or notebooks, but omits intermediate input coverage logs, annotator exposure metadata, or exact model/prompt revision identifiers.
* **5 – Sovereign Consonance (8–10 pts):** Commits a self-contained reproducibility package to the Single Source of Truth (SSOT) repository, including a data dictionary, frozen split manifests, hash-verified raw and adjudicated label files, and deterministic recomputation scripts.
