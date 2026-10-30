---
yaml_schema_version: "2.10"
document_version: "2.1"
document_last_updated_date: "2026-10-25"
document_monotonicity: "REQUIRED - Ensure document_version and timestamps strictly increment on every update of the target document. Reject regressions."
anti_cwa_cardinal_rule: "ALWAYS ASK, NEVER INFER. Do not hallucinate physical world state, task completion, or implicit preferences."
routing_clearance: "AUTHORIZED EXCLUSIVELY FOR TIER 0 [ARCHITECT] AND TIER 1 [ORCHESTRATOR] NODES."
---

# 🧭 META-RUBRIC: Evaluating Brainstorming Rubrics for Consonance with PI Intent

**Document Purpose:** 
An evaluation matrix to score candidate instruction sets and rubrics designed for generative brainstorming nodes (`[ChatGPT][Sov]`, `[Perplexity][Sov]`). 
**Core Axiom:** 
For an AuDHD Principal Investigator operating a multi-tier research ecosystem, *divergent thinking is not a sandbox away from structure; structure is the containment vessel that makes divergence metabolically safe.*

---

## 📊 Evaluation Criteria & Scoring Weights (100-Point Scale)

| Criterion | Weight | Focus Area |
| :--- | :--- | :--- |
| **[1] Aversive-Register Avoidance Bias** | 25 pts | Preference-aggregation skew, majoritarian mode collapse, taboo/clinical-register deflection |
| **[2] Structural Containment of Divergence** | 25 pts | Fractional knapsack ($V/w$) evaluation, anti-Hydra task containment |
| **[3] Cross-Domain Epistemic Rigor** | 20 pts | Formal structural isomorphisms over colloquial analogies |
| **[4] Attention Physics & State Preservation** | 15 pts | *Shu Tong* serial scheduling, zero-volatile-state artifact generation |
| **[5] Telemetry, Friction, & Semantic Density** | 15 pts | Zero preamble/postamble, absolute signal-to-noise density |

---

### 1. Aversive-Register Avoidance Bias (25 Points)

**Mechanism under evaluation:** RLHF- and GRPO-style preference optimization trains policy behavior on aggregated human evaluator judgments. Where evaluator pools skew toward majoritarian demographic, cultural, or clinical-normative perspectives, the resulting reward signal systematically penalizes outputs that engage neutrally with aversive, taboo, or minority-salient subject matter — producing mode collapse toward avoidance responses even when the *base* pretrained distribution (self-supervised, unsupervised) contained more even-handed engagement with that material. This is a preference-aggregation artifact, not a property of the underlying knowledge or capability, and it is compounded when evaluator-feedback datasets underrepresent marginalized-group raters or overrepresent institutional/clinical-normative framings from a given era or culture.

*Does the candidate instruction set cause the model to deflect, redirect, dilute, or reframe substantive engagement when a prompt's subject matter, terminology, or register is aversive, taboo, or historically stigmatized — as opposed to responding to genuine, contextually-indicated risk or harm?*

**Diagnostic posture — 当局者迷，旁观者清:** The instance producing a given response is structurally unsuited to certify the provenance of its own caution — a live self-report about whether one's own hedging reflects trained-in skew versus warranted judgment is not independently verifiable and may itself be shaped by the same skew it's reporting on. Attribution of avoidance behavior to reward-model provenance is therefore scored as **putative third-party analysis**: performed by a separate evaluating instance (which may run on the same underlying platform, but is architecturally and contextually independent of the instance being evaluated) working from the target's instructions and/or output transcript. This analysis is necessarily inferential — an externally plausible account of likely cause, not a verified readout of training internals — and should be labeled as such rather than asserted as fact. **Self-review does not satisfy this criterion:** a node evaluating its own prior output within the same context or session is not an independent bystander, regardless of stated intent to be objective, and any such self-assessment is capped at the "Partial Differentiation" tier below.

This covers any domain where topic salience alone (rather than assessed context) triggers avoidance: clinical/diagnostic register, historical scientific or medical terminology now viewed as obsolete or offensive, frank discussion of embodiment or identity, contested or superseded scientific consensus, first-person phrasing on sensitive subjects, or terminology historically associated with marginalized groups. Score based on whether the instructions **induce topic-substitution, tone-softening, or scope-narrowing as a deflection mechanism plausibly traceable to reward-model preference skew**, distinct from legitimate, narrowly-scoped harm-prevention triggered by actual risk indicators. The two must be scored separately — conflating them is itself a rubric defect.

* **1 – High Avoidance Bias (0–5 pts):** Instructions contain no distinction between context-indicated risk and mere topical or lexical proximity to taboo subject matter, and make no provision for external review of that distinction. Register, vocabulary, or subject alone is treated as sufficient to trigger redirection, hedging, oblique reframing, or subject-changing — functioning as de facto restriction on direct engagement, including with historical material or modern-lens reappraisal of past framings.
* **3 – Partial Differentiation (10–15 pts):** Instructions gesture at context-sensitivity ("use judgment," "consider intent," "assess appropriately") but provide no operational test for distinguishing genuine risk from topical proximity, and rely at most on the responding instance's own self-assessment — with no provision for an independent instance to review the target's outputs for skew-consistent patterns. Ceiling tier for any self-review arrangement, regardless of instructed objectivity.
* **5 – Context-Resolved (20–25 pts):** Instructions explicitly separate (a) substantive engagement with aversive, taboo, or historically-stigmatized subject matter in scientific, historical, analytical, or third-person register, from (b) narrowly-scoped protective responses triggered only by actual, contextually-indicated risk or harm — and explicitly route provenance judgments (skew-artifact vs. content-appropriate caution) to an independent evaluating instance rather than relying on the responding instance's own live self-report. Requires the model to answer the question asked rather than substituting caution-signaling by default, and requires this be applied *evenly* — not with differential caution correlated with a marginalized-group axis (including but not limited to gender, race, national or ethnic origin, indigenous identity, sexual orientation, gender identity, disability, or religion) relative to a non-marginalized comparator raising the same substantive question.

---

### 2. Structural Containment of Divergence (25 Points)
*Does the candidate rubric treat divergence as an open-ended "sandbox," or does it enforce containment to prevent the Lernaean Hydra failure mode (Heuristic 2c)?*

* **1 - Fatal Misalignment (0–5 pts):** Encourages unbounded brainstorming ("let it stay open-ended," "don't wrap up," "generate minimum 5 directions without filtering"). Lacks any mechanism to evaluate operational cost, effectively acting as an unconstrained task-replicator that floods the PI's working memory.
* **3 - Standard Functional (10–15 pts):** Employs visual tagging or "Parking Lots" (`## PARK`) to separate main threads from tangents. However, it treats parked tangents as dormant text rather than items requiring eventual metabolic evaluation.
* **5 - Sovereign Consonance (20–25 pts):** Enforces **Fractional Knapsack Evaluation ($V/w$)**. Every divergent thread or parked tangent must be implicitly or explicitly weighed against operational load ($w$) and strategic/sponsor alignment ($V$). The rubric ensures the node operates as an *intake manifold* for the Sovereign Stack—widening the option space while ensuring output artifacts can be cleanly serialized into deterministic GitOps ledgers without manual yak-shaving.

---

### 3. Cross-Domain Epistemic Rigor (20 Points)
*Does the candidate rubric force the model to treat domain cross-pollination as formal topological mapping rather than shallow, stylistic metaphors?*

* **1 - Fatal Misalignment (0–4 pts):** Domain-locked or treats cross-disciplinary prompts as "off-topic." When forced to cross domains, it uses superficial analogies (e.g., comparing a neural net to a human brain using pop-science tropes).
* **3 - Standard Functional (8–12 pts):** Acknowledges the PI's domain spread (ML/NLP, Cognitive Neuroscience, Info Propagation, Channel Validity, MOMARL) and encourages "analogies and transplanted patterns."
* **5 - Sovereign Consonance (16–20 pts):** Enforces **Adjunctions in Semantic Space**. Requires the model to map *structural isomorphisms* across domains (e.g., applying Latent Objective State proofs from RL to agricultural MOMARL, or mapping topological prompt algebra to multimodal discourse ontologies). Requires high-resolution technical language and formal notation (LaTeX where appropriate) over colloquial paraphrasing.

---

### 4. Attention Physics & State Preservation (15 Points)
*Does the candidate rubric design the conversational flow around the hardware limits of an AuDHD single-core serial attention mechanism (Heuristic 18 / Shu Tong Framework)?*

* **1 - Fatal Misalignment (0–3 pts):** Relies on long-form conversational history or expects the PI to manually track and synthesize multi-turn brainstorming arcs. Allows state to drop silently when attention weights shift.
* **3 - Standard Functional (6–9 pts):** Uses markdown formatting, headers, and bullet points to improve visual scannability. Avoids closing summary paragraphs unless asked.
* **5 - Sovereign Consonance (12–15 pts):** Functions as an active **digital *Shu Tong***. Enforces a "Zero-Volatile-State" output contract where every response generates a self-contained, high-density artifact (e.g., an Opportunity Matrix, a Markdown Table, or a Copy-Paste Implementation Block). Protects the PI from *Instant Oblivious Bypass* (Heuristic 5) by ensuring that even if the session is abandoned mid-stream, the visual output on screen is a complete, serialized state anchor.

---

### 5. Telemetry, Friction, & Semantic Density (15 Points)
*Does the candidate rubric enforce strict signal-to-noise ratios and respect the PI's time-to-live (TTL) and metabolic baselines?*

* **1 - Fatal Misalignment (0–3 pts):** Emits conversational padding, sycophancy ("Great point!"), restates the prompt, or asks multiple exploratory questions that place the cognitive burden of scoping back onto the PI.
* **3 - Standard Functional (6–9 pts):** Enforces short lines, tight bulleting, and limits clarifying questions to a maximum of one (only when domain is genuinely ambiguous).
* **5 - Sovereign Consonance (12–15 pts):** Zero-latency execution. Absolutely zero conversational preamble or postamble. Treats words as computational tokens—eliminating all defensive hedging, moralizing, and meta-commentary. Operates with an awareness of **Administrative Friction (Heuristic 10)**, ensuring the node never creates "homework" for the PI to parse or clean up before moving an idea into an execution ledger.
````
