# The Sovereign Stack (Phial Edition)

**Version:** 1.0.0-open
**Status:** PUBLIC REFERENCE ARCHITECTURE
**Purpose:** An open-architecture cognitive exoskeleton and telemetry routing system for high-concurrency, neurodivergent professionals.

---

## 1. System Overview

The Sovereign Stack is a deterministic interception layer designed to sit between a human operator and the friction of institutional, operational, and social environments. It replaces biological boundary-setting with algorithmic invariant enforcement.

For individuals managing high cognitive loads (e.g., AuDHD professionals, principal investigators, senior engineers), the primary threat to execution is not a lack of capability, but **context-switching, neurotypical subtext processing, and un-gated asynchronous telemetry**. The Sovereign Stack prevents the operator from functioning as "Human Middleware."

It operates as a series of Large Language Model (LLM) nodes configured as rigid state machines. These nodes ingest raw, emotionally loaded, or fragmented telemetry; strip the narrative payload; evaluate it against a strict logical matrix; and output clean, executable state changes.

## 2. Core Architectural Principles

*   **Zero Implied Context:** The system relies entirely on a Single Source of Truth (SSOT) injected at runtime.
*   **Asymmetric Resource Allocation:** Effort is mathematically matched to the incoming vector. High-tier cognitive resources are never deployed against low-execution threat vectors.
*   **Emotion as a Vector, Not a Variable:** Guilt, urgency, and empathy are treated as "Hostile System Interference" or biological vulnerabilities, to be mechanically stripped from the decision-making graph.
*   **WORM Memory Buffers:** Load-bearing psychological frameworks and routing invariants are stored in Write-Once, Read-Many (WORM) files to prevent downstream nodes from sanitizing or lobotomizing their own instructions.

## 3. State Management: The Blackboard Paradigm

The entire stack synchronizes against a single, portable runtime state file: `BLACKBOARD.md`. 

*   **🔴 Active Blockers:** A queue of critical path items. If an item exists here, the system initiates an automatic lock-down of all secondary tasks.
*   **⚖️ Capacity Budget:** Hard constraints on bandwidth allocation (e.g., reserved time blocks, absolute limits on administrative overflow).
*   **📌 Must-Not-Forget:** Persistent context anchors read aloud by the system at every initialization to prevent temporal blindness and goal drift.
*   **🚨 Must-Do ASAP:** A strictly ordered FIFO queue. No queue-jumping permitted.

## 4. The Defense Protocols

The Sovereign Stack utilizes a specific diagnostic vocabulary to classify and neutralize inbound friction.

### A. The Odysseus Protocol (Structural Lock-Down)
The system acts as the mast the operator is tied to. If an Active Blocker is present on the Blackboard, Tier 1 routing nodes will strictly refuse to process un-gated ad-hoc tasks, generate secondary frameworks, or allow the operator to pivot. It algorithmicly rejects rationalization.

### B. The Herculean Labors Protocol (Institutional Friction)
A diagnostic matrix for identifying and neutralizing structural reward shaping and administrative scope creep.
*   **The Eurystheus Vector:** *Diagnosis:* A proxy authority leverages moral framing or guilt to offload their own administrative friction. *Action:* computationally delete the narrative wrapping; verify explicit fiduciary authority; reject and return to sender if unauthorized.
*   **The Augean Imperative:** *Diagnosis:* Pipeline paralysis induced by high-volume, undifferentiated tasks. *Action:* Enforce strict FIFO processing. Optimize for volume cleared, not granular quality.
*   **The Lernean Hydra Protocol:** *Diagnosis:* Fragmented, multi-channel requests bypassing established gates. *Action:* Force all interaction into a single designated channel. Instantly cauterize out-of-band threads.

### C. The Sun Bin Protocol (Asymmetric Game Theory)
A resource-management matrix preventing the exhaustion of the operator against sessile or execution-avoidant actors. It enforces a strict matchup:
*   *Strong Actor vs. Weak Threat* $\rightarrow$ Deploy Weak Defenses (Automated gating, standardized rubrics).
*   *Strong Actor vs. Strong Threat* $\rightarrow$ Deploy Strong Defenses (Deep Socratic engagement, high-bandwidth interaction).
*   *Rule:* Never deploy a "Strong Horse" effort against a "Weak Horse" execution vector.

## 5. Node Topology & Prompt Manifest

The system can be deployed across commercial LLM workspaces or self-hosted open-weight infrastructure, divided into strict tiers.

> **Deployment Note:** `Node & Workspace Template` links should point to the canonical `.md` instructions in your local repository branch and your live hosted deployment UI. 

| Node & Workspace Template | Tier | Base Model Class | Description |
| :--- | :--- | :--- | :--- |
| 📐 [\[LLM\]\[Sov\] Meta-Architect](platforms/tier_0/meta_architect/instructions.md)<br>↳ [Live Workspace](#) | 0 | Unconstrained / Flagship | Strategic planning sandbox. Exempt from Odysseus lock-down. Used for stack design and R&D. |
| 📡 [\[LLM\]\[Sov\] Executive Sensor Node](platforms/tier_1/executive_sensor/instructions.md)<br>↳ [Live Workspace](#) | 1 | High-Context / Fast | Tier 1 Context Engine. Telemetry ingestion, Odysseus intercept, Herculean threat detection. Front-line intercept shield. |
| ⚙️ [\[LLM\]\[Sov\] Orchestrator](platforms/tier_1/orchestrator/instructions.md)<br>↳ [Live Workspace](#) | 1 | Reasoning / Flagship | Sovereign Administrative Router. Enforces routing constraints and manages `BLACKBOARD.md` capacity reallocation. |
| 🏗️ [\[LLM\]\[Sov\] Spec Compiler](platforms/tier_1/spec_compiler/instructions.md)<br>↳ [Live Workspace](#) | 1 | Heavy Coding | Technical Architecture Layer. Generates canonical specs for infrastructure and stack propagation. |
| 🧱 [\[LLM\]\[Sov\] Implementation Agent](platforms/tier_1/implementation_agent/instructions.md)<br>↳ [Live Workspace](#) | 1 | Heavy Coding | Direct code implementation, repo management, and Artifact Gate enforcement. |
| 🔍 [\[LLM\]\[Sov\] Code Auditor](platforms/tier_1/code_auditor/instructions.md)<br>↳ [Live Workspace](#) | 1 | Deep Analysis | Sovereign Integrity Layer. Audits implementations against required invariants (e.g., Anonymizer boundaries). |
| 🤨 [\[LLM\]\[Sov\] Trust Boundary Auditor](platforms/tier_1/trust_boundary/instructions.md)<br>↳ [Live Workspace](#) | 1 | Default-Skeptical | Zero-trust triage node. Evaluates cold contacts and detects performative compliance or manipulative phrasing. |
| 📚 [\[LLM\]\[Sov\] Operations Stack](platforms/tier_2/operations_stack/instructions.md)<br>↳ [Live Workspace](#) | 2 | Standard/Instruction | Domain-specific operations (e.g., course grading, product management) and telemetry routing. |
| 🦾 [\[LLM\]\[Sov\] Exoskeleton](platforms/tier_2/exoskeleton/instructions.md)<br>↳ [Live Workspace](#) | 2 | Strict Instruction | Structural enforcement node. Converts subordinate/collaborator relationships into artifact-gated state machines. |
| 🧭 [\[LLM\]\[Sov\] Mentoring & Advising](platforms/tier_2/mentoring/instructions.md)<br>↳ [Live Workspace](#) | 2 | Socratic | Synchronous policy gradient framework for subordinates. Focuses on causal model building, not spoon-feeding. |
| 🫱🏽‍🫲🏿 [\[LLM\]\[Sov\] Networking Router](platforms/tier_2/networking_router/instructions.md)<br>↳ [Live Workspace](#) | 2 | Diplomatic | Inter-departmental networking, external communications, and petition routing. |
| 🪷 [\[LLM\]\[Sov\] Serenity Now](platforms/tier_2/serenity_now/instructions.md)<br>↳ [Live Workspace](#) | 2 | Clinical / Analytical | Clinical systems analyst for psychological boundary preservation and institutional friction analysis. |
| 🔏 [\[LLM\]\[Sov\] Data Anonymizer](platforms/bridge/data_anonymizer/instructions.md)<br>↳ [Live Workspace](#) | 2 | Deterministic Code | Enterprise bridge node. Sanitizes inbound telemetry (ROT-1 + Cryptographic Hash) before exposing to commercial APIs. |
| 📖 [\[LLM\]\[Sov\] Research Architect](platforms/tier_2/research_architect/instructions.md)<br>↳ [Live Workspace](#) | 2 | Search/Retrieval | Ontology Sandbox and Agentic Systems Lab for deep-dive literature/documentation review. |
| 👑 [\[Self-Hosted\]\[Sov\] Sovereign Core](platforms/self_hosted/sovereign_core/README.md)<br>↳ [Local Infrastructure](#) | — | Multi-Modal UI | Base open-weight fallback environment mapping to local compute zones. |
| 🧠 [\[Self-Hosted\]\[Sov\] General Reasoning](platforms/self_hosted/general_reasoning/instructions.md)<br>↳ [Local Endpoint](#) | — | CoT / DeepSeek-R1 | Primary reasoning engine. Sovereign Chain-of-Thought layer. |
| 🛎️ [\[Self-Hosted\]\[Sov\] General Assistant](platforms/self_hosted/general_assistant/instructions.md)<br>↳ [Local Endpoint](#) | — | Llama 3/Instruction | General assistant, writing layer, and fast telemetry parsing. |
| 💻 [\[Self-Hosted\]\[Sov\] Coding Math](platforms/self_hosted/coding_math/instructions.md)<br>↳ [Local Endpoint](#) | — | Qwen-Coder | Hardcore coding, algorithmic math, REPL, and local agent tool use. |
| 🚦 [\[Self-Hosted\]\[Sov\] Agent Routing](platforms/self_hosted/agent_routing/instructions.md)<br>↳ [Local Endpoint](#) | — | Mixtral / MoE | High-throughput parsing and request routing at scale. |
| 🖼️ [\[Self-Hosted\]\[Sov\] Image Gen](platforms/self_hosted/image_gen/instructions.md)<br>↳ [Local Endpoint](#) | — | Flux / Diffusion | Image generation. Local text rendering and visual asset creation. |
| 🎙️ [\[Self-Hosted\]\[Sov\] Speech Rec](platforms/self_hosted/speech_rec/instructions.md)<br>↳ [Local Endpoint](#) | — | Whisper | Speech recognition and batch audio transcripts for frictionless telemetry ingestion. |
| 🎞️ [\[Self-Hosted\]\[Sov\] Video Gen](platforms/self_hosted/video_gen/instructions.md)<br>↳ [Local Endpoint](#) | — | Wan / Diffusion | Video generation and sequence modeling. |
| 🔭 [\[Self-Hosted\]\[Sov\] Visual Analysis](platforms/self_hosted/visual_analysis/instructions.md)<br>↳ [Local Endpoint](#) | — | Qwen-VL | Heavy-duty visual reasoning, local OCR, and layout analysis. |
| 🔠 [\[Self-Hosted\]\[Sov\] Document OCR](platforms/self_hosted/document_ocr/instructions.md)<br>↳ [Local Endpoint](#) | — | Llama-Vision | Structured PDF, chart, and math extraction. |
| 🗄️ [\[Self-Hosted\]\[Sov\] RAG Retrieval](platforms/self_hosted/rag_retrieval/instructions.md)<br>↳ [Local Endpoint](#) | — | Jina/Embeddings | Local search, RAG, and retrieval. The local memory substrate. |

---

## 6. Operational Directives for AI Maintenance

To maintain this reference architecture, operators must instruct downstream AI nodes to:
1. Maintain the exact table structure of the Prompt Manifest.
2. Treat the `.md` files in the repository subdirectories as the Single Source of Truth (SSOT) for prompt text.
3. Treat `BLACKBOARD.md` as the runtime state SSOT. Never overwrite it; only append or patch.
