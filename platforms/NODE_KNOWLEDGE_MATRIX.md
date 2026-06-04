# 🧠 SOVEREIGN STACK: NODE KNOWLEDGE MATRIX
**Status:** REFERENCE TEMPLATE
**Purpose:** Denormalized map illustrating which persistent files and context boundaries should be loaded into which Sovereign Stack LLM nodes. 
**Update Protocol:** Any modification to a base `.md` file in the repository requires a sync update to the deployed nodes listed below to prevent memory desynchronization.

---

## The Synchronization Matrix

| Platform Tier | Node Template | Role/Function | Required Context Files (Repository Path) | Injection Method |
| :--- | :--- | :--- | :--- | :--- |
| **Tier 1** | ⚙️ `[Sov] Orchestrator` | Logistics, SSOT constraint enforcement | `reference/BLACKBOARD.md`<br>`reference/active_roster.md`<br>`templates/feature_vector.md` | Workspace Knowledge Upload |
| **Tier 1** | 🏗️ `[Sov] Spec Compiler` | Technical Architecture & scripting | `reference/BLACKBOARD.md`<br>`protocols/06_sun_bin_protocol.md` | Workspace Knowledge Upload |
| **Tier 1** | 🧱 `[Sov] Implementation Agent` | Code implementation & Artifact Gates | Base Instructions Only (Target Codebase via Chat) | Workspace Knowledge Upload |
| **Tier 1** | 🔍 `[Sov] Code Auditor` | Sovereign Integrity & Validation | Base Instructions Only (Target Codebase via Chat) | Workspace Knowledge Upload |
| **Tier 1** | 🤨 `[Sov] Trust Boundary Auditor` | Zero-trust evaluation | Base Instructions Only (Target Inbound Comms via Chat) | Workspace Context |
| **Tier 2** | 📚 `[Sov] Operations Stack` | Domain management & telemetry | Domain Docs, SOPs (As needed per project) | Custom Instructions / Uploads |
| **Tier 2** | 🦾 `[Sov] Exoskeleton` | Structural boundary enforcement | `reference/active_roster.md` (via Addendum) | Custom Instructions |
| **Tier 2** | 🧭 `[Sov] Mentoring/Advising` | Socratic policy gradient framework | `reference/active_roster.md` (via Addendum)<br>`templates/feature_vector.md` | Custom Instructions / Uploads |
| **Tier 2** | 🫱🏽‍🫲🏿 `[Sov] Networking Router` | Petition routing & comms | Base Instructions Only (Target Petitions via Chat) | Custom Instructions |
| **Tier 2** | 🪷 `[Sov] Serenity Now` | Clinical boundary/friction analysis | `protocols/WORM_manifest.md` | Custom Instructions / Uploads |
| **Tier 1 (Sensor)** | 📡 `[Sov] Executive Sensor Node` | Telemetry Ingestion / Odysseus Intercept | `BLACKBOARD.md` (Runtime)<br>`protocols/00` to `06`<br>`reference/active_roster.md` | Manifest Compiler Script (Paste into UI) |
| **Tier 0** | 📐 `[Sov] Meta-Architect` | Meta-architecture sandbox | `reference/BLACKBOARD.md`<br>`platforms/NODE_KNOWLEDGE_MATRIX.md` | Direct Context Window Paste |
| **Bridge** | 🔏 `[Sov] Data Anonymizer` | Enterprise sanitation bridge | Regex Target List, Entity Dictionaries | Local Script / Protected Notebook |
| **Tier 2** | 📖 `[Sov] Research Architect` | Ontology Sandbox / IR queries | Base Instructions Only | Workspace Context |
| **Self-Hosted** | 👑 `[Sov] Sovereign Core` | Open-weight fallback environment | TBD per Zone Configuration | Local File System (RAG/API) |
