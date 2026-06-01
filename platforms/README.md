# Sovereign Stack (Phial Edition): Platform Manifest

**Status:** PUBLIC REFERENCE
**Purpose:** Directory mapping for the turnkey commercial deployment of the Sovereign Stack.

This directory contains the foundational system instructions for deploying the Sovereign Stack across standard, commercially available API and subscription LLM platforms. 

## Commercial Stack Topology

> **Deployment Note:** The "Tier" designation dictates the node's relationship to the `BLACKBOARD.md` Single Source of Truth (SSOT). Tier 1 nodes actively enforce the SSOT. Tier 2 nodes execute within the constraints of the SSOT.

| Designation | Platform | Compute Layer | Tier | Role & Description |
| :--- | :--- | :--- | :--- | :--- |
| `platforms/gemini/` | Google Workspace | Gemini Advanced / Pro | 1 | **Executive Context Engine.** The primary ingestion node for unstructured telemetry. Enforces the Odysseus lock-down protocol and translates biological friction into structural state changes. |
| `platforms/claude/` | Anthropic | Claude 3.5 Sonnet / Opus | 1 | **Sovereign Administrative Router & Compiler.** The core logic and routing layer. Enforces strict capacity budgets, manages artifact gates, and compiles architectural specifications. |
| `platforms/grok/` | xAI | Grok | 1 | **Trust Boundary Auditor.** A zero-trust triage node optimized for evaluating cold contacts, detecting performative compliance, and identifying adversarial administrative vectors. |
| `platforms/chatgpt/` | OpenAI | GPT-4o / GPT-5 | 2 | **Domain Execution Nodes.** Specialized state machines (e.g., Exoskeleton, Clinical Analyst, Course Routing). These nodes execute specific, high-bandwidth tasks while strictly adhering to Tier 1 initialization constraints. |
| `platforms/m365_copilot/` | Microsoft 365 | M365 Copilot | 2 | **Enterprise Telemetry Bridge.** Operates within the enterprise perimeter to sanitize, OCR, and format institutional telemetry (Teams, SharePoint, Confluence) before relaying it to the external stack. |
| `platforms/perplexity/` | Perplexity AI | Pro / Enterprise Space | 2 | **Research Architect Node.** An automated ontology sandbox and deep retrieval agent used for mapping external market shifts, competitive intelligence, and structural threat data. |
| `platforms/copilot/` | Multi-Platform | Free Tier / Standard Enterprise | 2 | **Ambient Workflow Copilot.** Decoupled from M365 to support standard enterprise AI endpoints (Gemini, ChatGPT, or built-in IDE/browser tools). Acts as an on-the-fly syntax formatter and micro-task executor. |

### ⚠️ A Note on Tier 0 (The Sandbox Layer)
You will notice the manifest table begins at Tier 1. Tier 0 is explicitly omitted from the deployed architecture. Tier 0 represents the unconstrained, human-in-the-loop engineering sandbox (this meta-architecture thread) where new defensive protocols are drafted, tested, and compiled before being pushed down to the enforcement layers. Tier 0 operates completely outside the Odysseus Protocol to ensure absolute R&D agility.

---
*For self-hosted, open-weight deployments, refer to the advanced architectural documentation (Not included in the Phial release).*