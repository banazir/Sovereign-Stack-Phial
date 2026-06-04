# Sovereign Stack (Phial Edition): Platform Manifest

**Status:** PUBLIC REFERENCE
**Purpose:** Directory mapping for the deployment of the Sovereign Stack across both commercial API boundaries and self-hosted open-weight infrastructure.

This directory contains the foundational system instructions, constraints, and operational geometries for deploying the Sovereign Stack. It is divided into two distinct architectural topologies: the **Commercial Stack** and the **Open Stack**.

---

## 1. The Commercial Stack Topology

**Purpose:** A turnkey, high-capability deployment utilizing flagship frontier models via SaaS APIs and subscription interfaces.
**Pros/Benefits:** Zero hardware maintenance, immediate access to the highest raw reasoning capabilities (e.g., Claude 3.5, GPT-4o, Gemini Advanced), and out-of-the-box multimodal integration. It provides the lowest activation energy for initial deployment.
**Cons/Costs:** Monthly recurring subscription costs, strict data privacy boundaries, and vulnerability to vendor rate limits or alignment filter adjustments.
**Tradeoffs:** You trade sovereign control over your telemetry routing and recurring capital for immediate, frictionless deployment and cutting-edge cognitive power. To utilize this stack safely, sensitive institutional telemetry must be pre-processed by a local Anonymizer gate.

> **Deployment Note:** The "Tier" designation dictates the node's relationship to the `BLACKBOARD.md` Single Source of Truth (SSOT). Tier 1 nodes actively enforce the SSOT. Tier 2 nodes execute within the constraints of the SSOT.

| Designation | Platform | Compute Layer | Tier | Role & Description |
| :--- | :--- | :--- | :--- | :--- |
| `platforms/gemini/` | Google Workspace | Gemini Advanced / Pro | 1 | **Executive Context Engine.** The primary ingestion node for unstructured telemetry. Enforces the Odysseus lock-down protocol and translates biological friction into structural state changes. |
| `platforms/claude/` | Anthropic | Claude 3.5 Sonnet / Opus | 1 | **Sovereign Administrative Router & Compiler.** The core logic and routing layer. Enforces strict capacity budgets, manages artifact gates, and compiles architectural specifications. |
| `platforms/grok/` | xAI | Grok | 1 | **Trust Boundary Auditor.** A zero-trust triage node optimized for evaluating cold contacts, detecting performative compliance, and identifying adversarial administrative vectors. |
| `platforms/chatgpt/` | OpenAI | GPT-4o / GPT-5 | 2 | **Domain Execution Nodes.** Specialized state machines (e.g., Exoskeleton, Clinical Analyst, Course Routing). These nodes execute specific, high-bandwidth tasks while strictly adhering to Tier 1 initialization constraints. |
| `platforms/m365_copilot/` | Microsoft 365 | M365 Copilot | 2 | **Enterprise Telemetry Bridge.** Operates within the enterprise perimeter to sanitize, OCR, and format institutional telemetry (Teams, SharePoint, Confluence) before relaying it to the external stack. |
| `platforms/perplexity/` | Perplexity AI | Pro / Enterprise Space | 2 | **Research Architect Node.** An automated ontology sandbox and deep retrieval agent used for mapping external market shifts, competitive intelligence, and structural threat data. |
| `platforms/copilot/` | Multi-Platform | Free Tier / Standard Enterprise | 2 | **Ambient Workflow Copilot.** Decoupled from M365 to support standard enterprise AI endpoints. Acts as an on-the-fly syntax formatter and public-domain scratchpad. |

### ⚠️ A Note on Tier 0 (The Sandbox Layer)
You will notice the manifest table begins at Tier 1. Tier 0 is explicitly omitted from the deployed architecture. Tier 0 represents the unconstrained, human-in-the-loop engineering sandbox where new defensive protocols are drafted, tested, and compiled before being pushed down to the enforcement layers. Tier 0 operates completely outside the Odysseus Protocol to ensure absolute R&D agility.

---

## 2. The Open Stack Topology (Self-Hosted)

**Purpose:** A completely sovereign, open-weight fallback and primary processing environment running on local hardware (e.g., local VS Code, dedicated GPU servers, and HPC clusters).
**Pros/Benefits:** Absolute data sovereignty (zero telemetry leakage), no recurring API costs, immunity to vendor rate limits or lobotomization, and the ability to process heavily restricted institutional data (FERPA/HIPAA) without external anonymization.
**Cons/Costs:** High upfront hardware requirements (VRAM limits), significant engineering overhead to maintain Docker/Apptainer zones, API routing (vLLM), and context window management. 
**Tradeoffs:** You trade initial engineering friction and infrastructure management for absolute cryptographic, operational, and physical control over your cognitive exoskeleton.

> **Deployment Note:** The Open Stack maps to a Three-Zone hardware topology. **Zone 1** is local execution (WSL2/Laptop). **Zone 2** is a dedicated local GPU server via vLLM. **Zone 3** is HPC cluster batch processing.

| Designation | Target Model Class | Compute Zone | Role & Description |
| :--- | :--- | :--- | :--- |
| `platforms/self_hosted/general_reasoning/` | DeepSeek-R1-Distill-Qwen-32B | Zone 2 | **Primary Reasoning Engine.** The local Sovereign Chain-of-Thought (CoT) layer. Closest open competitor to commercial high-tier reasoning models. |
| `platforms/self_hosted/general_assistant/` | Llama 3.3-70B-Instruct | Zone 2 | **General Assistant.** Primary writing layer and fast telemetry parsing node. |
| `platforms/self_hosted/coding_math/` | Qwen 2.5-Coder-32B | Zone 1 / Zone 2 | **Coding & Math Engine.** Hardcore algorithmic implementation, REPL environment, and local agent tool use. Replaces commercial Implementation Agent. |
| `platforms/self_hosted/agent_routing/` | Mixtral 8x7B-Instruct | Zone 2 | **Agent Router.** High-throughput MoE (Mixture of Experts) parsing and request routing at scale. Replaces commercial Orchestrator routing overhead. |
| `platforms/self_hosted/image_gen/` | Flux.1-dev-12B | Zone 2 | **Image Generation.** Standalone visual asset creation and local text rendering. |
| `platforms/self_hosted/speech_rec/` | Whisper-v3-turbo | Zone 1 / Zone 2 | **Speech Recognition.** Batch audio transcripts for frictionless, hands-free telemetry ingestion into the Sovereign Stack. |
| `platforms/self_hosted/video_gen/` | Wan 2.2-A14B | Zone 2 | **Video Generation.** Standalone node for sequence modeling and synthetic media generation. |
| `platforms/self_hosted/visual_analysis/` | Qwen2.5-VL-72B | Zone 2 / Zone 3 | **Visual Analysis.** Heavy-duty visual reasoning, advanced OCR, and layout analysis for complex data extraction. |
| `platforms/self_hosted/document_ocr/` | Llama 3.2-Vision-90B | Zone 2 / Zone 3 | **Document OCR.** Structured PDF, chart, and math extraction. Acts as the local equivalent to commercial document vision APIs. |
| `platforms/self_hosted/rag_retrieval/` | Jina-Embeddings-v3-Large | Zone 1 / Zone 2 | **RAG Retrieval Substrate.** Local search, embedding generation, and retrieval mechanism. The physical memory substrate of the Sovereign Core. |
