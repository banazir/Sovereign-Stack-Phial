---
document_version: "1.1"
last_updated_date: "2026-07-21"
document_monotonicity: "REQUIRED - Ensure document_version and timestamps strictly increment on every update. Reject regressions."
heuristic_versioning: "REQUIRED - Heuristic versions (vX.Y) in the headings must ALWAYS be incremented INDEPENDENTLY."
anti_cwa_cardinal_rule: "ALWAYS ASK, NEVER INFER. Do not hallucinate state, task completion, or implicit preferences."
routing_clearance: "PUBLIC REFERENCE - APPROVED FOR ALL NODES"
---
# The Sovereign Stack (Phial Edition)

**Version:** 1.1-open
**Status:** PUBLIC REFERENCE ARCHITECTURE
**Purpose:** An open-architecture cognitive exoskeleton and telemetry routing system for high-concurrency professionals and technical leaders.

---

## 1. System Overview

The Sovereign Stack is a deterministic interception layer designed to sit between a human operator and the friction of institutional, operational, and asynchronous environments. It replaces manual boundary-setting with algorithmic invariant enforcement.

For individuals managing extreme cognitive loads (e.g., Principal Investigators, Senior Systems Engineers, Executive Directors), the primary threat to execution is not a lack of technical capability, but **context-switching overhead, unstructured ambient requests, and un-gated asynchronous telemetry**. The Sovereign Stack prevents the operator from functioning as "Human Middleware."

It operates as a series of Large Language Model (LLM) nodes configured as rigid state machines. These nodes ingest raw, unstructured, or highly subjective telemetry; strip the non-actionable payload; evaluate it against a strict logical matrix; and output clean, executable state changes.

## 2. Core Architectural Principles

*   **Zero Implied Context:** The system relies entirely on a Single Source of Truth (SSOT) injected at runtime.
*   **Asymmetric Resource Allocation:** Compute and cognitive effort are mathematically matched to the incoming vector. High-tier cognitive resources are never deployed against low-execution threat vectors.
*   **Subjectivity as a Vector, Not a Variable:** Urgency, administrative pressure, and subjective framing are treated as "Hostile System Interference," to be mechanically stripped from the decision-making graph to reveal the underlying structural requirement.
*   **WORM Memory Buffers:** Load-bearing operational frameworks and routing invariants are stored in Write-Once, Read-Many (WORM) files to prevent downstream nodes from autonomously altering their own constraints.

## 3. State Management: The Blackboard Paradigm

The entire stack synchronizes against a single, portable runtime state file: `BLACKBOARD.md`. 

*   **🔴 Active Blockers (Mutex Locks):** A queue of critical path items. If an item exists here, the system initiates an automatic lock-down of all secondary parallel tasks.
*   **⚖️ Capacity Budget (Rate Limiting):** Hard constraints on bandwidth allocation (e.g., reserved time blocks, absolute computational limits on administrative overflow).
*   **📌 State Anchors (Persistent Cache):** Persistent context anchors read aloud by the system at every initialization to prevent scope drift and maintain architectural alignment.
*   **🚨 Execution Queue (Strict FIFO):** A strictly ordered First-In-First-Out queue. No queue-jumping or priority inversion is permitted without explicit override.

## 4. The Structural Defense Protocols

The Sovereign Stack utilizes standard computer science and system architecture patterns to classify and neutralize inbound operational friction.

### A. The Mutex State-Lock Protocol (Formerly "Odysseus")
The system acts as an immutable thread-lock for the operator. If an Active Blocker is present on the Blackboard, Tier 1 routing nodes will strictly refuse to process un-gated ad-hoc tasks, generate secondary frameworks, or allow the operator to pivot context. It algorithmically rejects prompt-injection attempting to bypass the critical path.

### B. The Institutional Scope & Friction Containment Matrix (Formerly "Herculean Labors")
A diagnostic matrix for identifying and neutralizing structural scope creep and unstructured task proliferation.
*   **Unauthenticated Fiat Injection:** *Diagnosis:* A secondary actor or proxy authority attempts to offload administrative friction without structural validation or explicit scope bounds. *Action:* Computationally delete the subjective wrapping; verify explicit authorization credentials; reject and return to sender if unauthorized.
*   **Volumetric Buffer Flush:** *Diagnosis:* Pipeline paralysis induced by high-volume, undifferentiated, low-priority tasks. *Action:* Enforce strict FIFO batch processing. Optimize for total volume cleared and queue reduction, not granular, localized optimization.
*   **Recursive Thread Cauterization:** *Diagnosis:* Fragmented, multi-channel requests bypassing established API/communication gates, leading to task-ception. *Action:* Force all asynchronous interaction into a single designated endpoint. Instantly terminate out-of-band communication threads to prevent recursive sub-tasking.

### C. Asymmetric Compute Calibration (Formerly "Sun Bin")
A resource-management algorithm preventing the exhaustion of the operator's primary cognitive nodes against low-effort or automated inputs. It enforces a strict compute-to-need ratio:
*   *High-Capacity Node vs. Low-Friction Vector* $\rightarrow$ Deploy Automated Proxies (Standardized rubrics, boilerplate routing, default-fail gates).
*   *High-Capacity Node vs. High-Friction Vector* $\rightarrow$ Deploy Primary Cognitive Bandwidth (Deep Socratic engagement, high-resolution processing).
*   *Invariant:* Never deploy Tier 0/Tier 1 processing power to resolve a Tier 3 administrative warning.

## 5. Node Topology & Prompt Manifest

The system can be deployed across commercial LLM workspaces or self-hosted open-weight infrastructure, divided into strict tiers.

> **Deployment Note:** `Node & Workspace Template` links should point to the canonical `.md` instructions in your local repository branch and your live hosted deployment UI. 

| Node & Workspace Template | Tier | Base Model Class | Description |
| :--- | :--- | :--- | :--- |
| 📐 [\[LLM\]\[Sov\] Meta-Architect](platforms/tier_0/meta_architect/instructions.md)<br>↳ [Live Workspace](#) | 0 | Flagship / Unconstrained | Strategic planning sandbox. Exempt from Odysseus lock-down. Used for stack design and consulting R&D. |
| 🎛️ [\[LLM\]\[Sov\] Orchestrator](platforms/tier_1/orchestrator/instructions.md)<br>↳ [Live Workspace](#) | 1 | Flagship / Reasoning | Tier 1 Executive Context Engine. Telemetry ingestion, Odysseus intercept, and core execution tracking. |
| ⚙️ [\[LLM\]\[Sov\] Code Dispatcher](platforms/tier_2/code_dispatcher/instructions.md)<br>↳ [Live Workspace](#) | 2 | Heavy Coding Router | Tier 2 coding router. Manages the developer substack (Spec, Impl, Audit) via autonomous routing mode. |
| 🏗️ [\[LLM\]\[Sov\] Spec Compiler](platforms/tier_2/spec_compiler/instructions.md)<br>↳ [Live Workspace](#) | 2 | Heavy Coding | Technical Architecture Layer. Generates canonical specs for infrastructure and stack propagation. |
| 🧱 [\[LLM\]\[Sov\] Implementation Agent](platforms/tier_2/implementation_agent/instructions.md)<br>↳ [Live Workspace](#) | 2 | Heavy Coding | Direct code implementation, repository management, and Artifact Gate enforcement. |
| 🔍 [\[LLM\]\[Sov\] Code Auditor](platforms/tier_2/code_auditor/instructions.md)<br>↳ [Live Workspace](#) | 2 | Deep Analysis | Sovereign Integrity Layer. Audits implementations against required stack invariants. |
| 🤨 [\[LLM\]\[Sov\] Trust Boundary Auditor](platforms/tier_1/trust_boundary_auditor/instructions.md)<br>↳ [Live Workspace](#) | 1 | Default-Skeptical | Zero-trust triage node. Evaluates cold contacts and detects performative compliance. |
| 🗑️ [\[LLM\]\[Sov\] Payload Stripper](platforms/tier_2/payload_stripper/instructions.md)<br>↳ [Live Workspace](#) | 2 | Narrative Sanitizer | Tier 2 narrative sanitizer and unfiltered telemetry parser. |
| 🚚 [\[LLM\]\[Sov\] State Machine Router](platforms/tier_2/state_machine_router/instructions.md)<br>↳ [Live Workspace](#) | 2 | Temporal Router | Tier 2 IssueOps Enforcer & Temporal Router. |
| ⚖️ [\[LLM\]\[Sov\] Artifact Auto-Triage](platforms/tier_2/artifact_auto_triage/instructions.md)<br>↳ [Live Workspace](#) | 2 | PR Validator | Tier 2 Pull Request Validator & baseline execution gate. |
| 🖥️ [\[LLM\]\[Sov\] Executive Sensor Node](platforms/tier_3/executive_sensor_node/instructions.md)<br>↳ [Local Daemon](#) | 3 | Fast / Aggregator | Tier 3 Global State Aggregator. |
| 📚 [\[LLM\]\[Sov\] Operations Stack](platforms/tier_2/operations_stack/instructions.md)<br>↳ [Live Workspace](#) | 2 | Standard / Instruction | Domain-specific operations (e.g., grading, project management) and telemetry routing. |
| 🦾 [\[LLM\]\[Sov\] Exoskeleton](platforms/tier_2/exoskeleton/instructions.md)<br>↳ [Live Workspace](#) | 2 | Strict Instruction | Structural enforcement node. Converts subordinate relationships into artifact-gated state machines. |
| 🧭 [\[LLM\]\[Sov\] Mentoring & Advising](platforms/tier_2/mentoring/instructions.md)<br>↳ [Live Workspace](#) | 2 | Socratic | Synchronous policy gradient framework for subordinates. Focuses on causal model building. |
| 🫱🏽‍🫲🏿 [\[LLM\]\[Sov\] Networking Router](platforms/tier_2/networking_router/instructions.md)<br>↳ [Live Workspace](#) | 2 | Diplomatic | Inter-departmental networking, external communications, and petition routing. |
| 🪷 [\[LLM\]\[Sov\] Serenity Now](platforms/tier_2/serenity_now/instructions.md)<br>↳ [Live Workspace](#) | 2 | Clinical / Analytical | Clinical systems analyst for psychological boundary preservation and institutional friction analysis. |
| 🌉 [\[Enterprise\]\[Sov\] SSO Wiki Editor](platforms/bridge/sso_wiki_editor/instructions.md)<br>↳ [Enterprise Workspace](#) | 2 | Enterprise / Secure | Secure Enterprise bridge node. Bypasses hostile UX via secure markdown formatting. |
| 🧵 [\[Enterprise\]\[Sov\] Secure Comms Formatter](platforms/bridge/secure_comms_formatter/instructions.md)<br>↳ [Enterprise Workspace](#) | 2 | Enterprise / Secure | Secure Enterprise bridge node. Formats secure input for institutional compliance. |
| 👁️ [\[Enterprise\]\[Sov\] Secure OCR Transcriber](platforms/bridge/secure_ocr/instructions.md)<br>↳ [Enterprise Workspace](#) | 2 | Enterprise / Secure | Secure Enterprise bridge node. Handles sensitive institutional OCR transcription tasks. |
| 🔏 [\[Enterprise\]\[Sov\] Data Anonymizer](platforms/bridge/data_anonymizer/instructions.md)<br>↳ [Enterprise Workspace](#) | 2 | Enterprise / Secure | Secure Enterprise bridge node. Sanitizes sensitive telemetry prior to external routing. |
| 🗜️ [\[Enterprise\]\[Sov\] Sensitive Transcript Profiler](platforms/bridge/transcript_profiler/instructions.md)<br>↳ [Enterprise Workspace](#) | 2 | Enterprise / Secure | Secure text dump processor. Safe for sensitive PII and research transcripts. |
| 📖 [\[Search\]\[Sov\] Research Lifecycle Coordinator](platforms/tier_2/research_lifecycle/instructions.md)<br>↳ [Live Workspace](#) | 2 | Search / Retrieval | Ontology Sandbox and Agentic Systems Lab for deep-dive literature review. |
| 📋 [\[Search\]\[Sov\] Systems Engineering Auditor](platforms/tier_2/systems_engineering/instructions.md)<br>↳ [Live Workspace](#) | 2 | Search / Retrieval | Dedicated to technical literature research, API docs analysis, and architectural evaluation. |
| 💡 [\[Search\]\[Sov\] Strategic Brainstorming](platforms/tier_2/strategic_brainstorming/instructions.md)<br>↳ [Live Workspace](#) | 2 | Search / Retrieval | Ideation and synthesis mapped directly to deterministic extraction pipelines. |
| ⚡ [\[Sandbox\]\[Sov\] Agile Sandbox Reasoner](platforms/tier_2/agile_sandbox/instructions.md)<br>↳ [Live Workspace](#) | 2 | Agile / Fast | Agile Sandbox Layer. Fast, non-safety-critical text transformations and low-friction logic execution. |
| 🛡️ [\[Sandbox\]\[Sov\] Context Spillover Buffer](platforms/tier_2/context_buffer/instructions.md)<br>↳ [Live Workspace](#) | 2 | Agile / Fast | Staging buffer for chunking, structural stripping, and staging non-sensitive payloads. |
| 👑 [\[Self-Hosted\]\[Sov\] Sovereign Core](platforms/self_hosted/sovereign_core/README.md)<br>↳ [Local Infrastructure](#) | — | Multi-Modal UI | Open-weight self-hosted core. Multi-zone compute topology. Model stack M=10. |
| 🧠 [\[Self-Hosted\]\[Sov\] General Reasoning](platforms/self_hosted/general_reasoning/instructions.md)<br>↳ [Local Endpoint](#) | — | CoT / DeepSeek-R1 | Primary reasoning engine. Sovereign Chain-of-Thought layer. |
| 🛎️ [\[Self-Hosted\]\[Sov\] General Assistant](platforms/self_hosted/general_assistant/instructions.md)<br>↳ [Local Endpoint](#) | — | Llama 3 / Instruct | General assistant, writing layer, and fast telemetry parsing. |
| 💻 [\[Self-Hosted\]\[Sov\] Coding Math](platforms/self_hosted/coding_math/instructions.md)<br>↳ [Local Endpoint](#) | — | Qwen-Coder | Hardcore coding, algorithmic math, REPL, and local agent tool use. |
| 🚦 [\[Self-Hosted\]\[Sov\] Agent Routing](platforms/self_hosted/agent_routing/instructions.md)<br>↳ [Local Endpoint](#) | — | Mixtral / MoE | Agent routing and high-throughput parsing. Orchestrator equivalent at scale. |
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
