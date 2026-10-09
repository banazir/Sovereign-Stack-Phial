---
yaml_schema_version: "2.9"
document_version: "1.0"
document_last_updated_date: "2026-10-08"
routing_clearance: "GENERAL - CLEARED FOR ALL KDD LAB PERSONNEL."
---
# SOVEREIGN STACK (PHIAL): SPILLOVER ROUTING MATRIX
**Status:** ACTIVE
**Purpose:** 3-Tier dimension table mapping primary lab compute nodes to their designated Secondary (Cloud/Bridge) and Tertiary (Sovereign Local) fallback platforms to mitigate token caps and context limits.

<details>
<summary><h3>Anthropic Claude Nodes (Research & Engineering)</h3></summary>

| Primary Node | Secondary (Cloud / Bridge) | Tertiary (Sovereign Local) | Trigger Condition & Strengths |
| :--- | :--- | :--- | :--- |
| 🖋️ `[Claude] Research Coordinator` | `[Perplexity] 01_lifecycle` | `[Self-Hosted] 02_general_assistant` | Claude usage limit/Retrieval need. Perplexity handles live DB sync; local Llama drafts offline. |
| 🔬 `[Claude] Critical Review` | `[ChatGPT] Agile Sandbox` | `[Self-Hosted] 01_general_reasoning` | Claude safety filter on harsh critiques. DeepSeek ensures deep CoT. |
| 🏗️ `[Claude] Requirements-to-Spec` | `[ChatGPT] Agile Sandbox` | `[Self-Hosted] 02_general_assistant` | Claude refusal on rigid specs. GPT-5 bypasses constraints; Llama-3 enforces structural formatting. |
| 🧱 `[Claude] Spec-to-Code` | ChatGPT (Adv. Data Analysis) | `[Self-Hosted] 03_coding_math` | Cloud API limit or sensitive code. Qwen 2.5-Coder runs locally for fully private implementation. |
| 🔍 `[Claude] Spec/Code-to-Verifier` | ChatGPT (Adv. Data Analysis) | `[Self-Hosted] 03_coding_math` | Context window limit on large diffs. Qwen 2.5 secures code compilation. |

</details>

<details>
<summary><h3>Perplexity Sonar Nodes (Literature)</h3></summary>

| Primary Node | Secondary (Cloud / Bridge) | Tertiary (Sovereign Local) | Trigger Condition & Strengths |
| :--- | :--- | :--- | :--- |
| 📖 `[Perplexity] 01_lifecycle` | Gemini Advanced (Search) | `[Self-Hosted] 10_rag_retrieval` | Perplexity rate-limits/context windows. Gemini handles massive context search; local Jina searches local lab ontology. |
| 📋 `[Perplexity] 02_systems_auditor` | `[Claude] Research Coordinator` | `[Self-Hosted] 01_general_reasoning` | Engineering documentation deep-dives. DeepSeek-R1 CoT parsing of local architectural specifications. |

</details>

<details>
<summary><h3>Microsoft Copilot (Free) Nodes</h3></summary>

| Primary Node | Secondary (Cloud / Bridge) | Tertiary (Sovereign Local) | Trigger Condition & Strengths |
| :--- | :--- | :--- | :--- |
| ⚡ `[Free Copilot] 11_sandbox` | `[ChatGPT] (Free Tier)` | `[Self-Hosted] 02_general_assistant` | Fast, non-sensitive text transformations. Llama 3.3 for local offline shaping. |

</details>

<details>
<summary><h3>K-State Self-Hosted Nodes (GPU Cluster)</h3></summary>

| Primary Node | Secondary (Cloud / Bridge) | Tertiary (Sovereign Local) | Trigger Condition & Strengths |
| :--- | :--- | :--- | :--- |
| 👑 `[Self-Hosted] Sovereign Core` | Claude API / Grok API | N/A (Graceful degradation) | Complete local hardware failure or OS Jetsam crash. Spillover forces fallback to standard Tier 2 bridging. |
| 🧠 `[Self-Hosted] 01_reasoning` | Gemini Advanced / AI Studio | Local CPU Offload | DeepSeek VRAM OOM. Fallback to system RAM/CPU processing. |
| 💻 `[Self-Hosted] 03_coding` | `[Claude] Impl. Agent` | Local CPU Offload | Qwen 2.5 context limit. CPU handles incremental local compilation. |
| 🔠 `[Self-Hosted] 09_doc_ocr` | `[Free Copilot] 11_sandbox` | Local CPU Offload | Llama Vision context limit. CPU parses structured PDFs offline. |
| 🗄️ `[Self-Hosted] 10_rag` | `[Perplexity] 01_lifecycle` | Local BM25/Lexical | Jina vector database scale limit. Lexical search handles local strings. |

</details>
