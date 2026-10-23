---
yaml_schema_version: "2.2"
document_version: "2.1"
document_last_updated_date: "2026-10-22"
document_last_updated_time: "20:28:44 CDT"
document_monotonicity: "REQUIRED - Ensure document_version and timestamps strictly increment on every update of the target document to maintain forward progression."
heuristic_versioning: "REQUIRED - Increment heuristic versions (vX.Y) independently. Log minor additions as X.(Y+1). Log authorized title changes as (X+1).Y and retain the previous title as a synonym."
anti_cwa_cardinal_rule: "MAINTAIN EXPLICIT STATE. Ground all responses in provided physical world state and task completion data. Pause execution and prompt the PI for boolean confirmation to resolve undefined variables."
routing_clearance: "INTERNAL - AUTHORIZED FOR TIER 1 AND TIER 2 NODES"
# VALID ENUMS FOR ROUTING_CLEARANCE:
# "TIER 0 / TIER 1 AUTHORIZED"
# "INTERNAL - AUTHORIZED FOR TIER 1 AND TIER 2 NODES"
# "GENERAL - AUTHORIZED FOR ALL NODES"
---


# SOVEREIGN STACK: Reference Manifest (Memory)

**Status:** ACTIVE SSOT  
**Location:** `Mithril_Shirt/reference/README.md`  
**Purpose:** Canonical Ledger Gamut for the Sovereign Stack. This directory contains all *non‑volatile memory*, *immutable constraints*, and *identity documents* that every compute node must read to understand the PI’s environment, the lab’s structure, and the repository’s ontology.

---

# 🧭 Ledger Gamut Ontology (from `stack_architecture.md`)

The `/reference/` directory is the **Ledger Gamut** — the domain of *state*, *identity*, and *immutable constraints*. Artifacts placed here describe **what *is*** rather than **what executes***.

Ledger artifacts include:

- System identity documents  
- Immutable operational envelopes  
- Historical records  
- Telemetry ledgers  
- Incident dockets  
- Canonical lab protocols  
- Structural ontologies  

Execution logic, templates, and tools belong elsewhere (`/platforms/`, `/templates/`, `/tools/`).

---

# 🏗️ Tripartite Memory Structure

The Sovereign Stack divides reference memory into three operational zones.

---

## 🗄️ 1. THE ARCHIVE  
**Static & Immutable Protocols.**  
These files represent the *law* of the lab — structural documents, historical records, canonical procedures, and all immutable identity documents.

Archive subdirectories:

- [`architecture`](architecture)  
- [`ideas`](ideas)  
- [`incidents`](incidents)  
- [`kdd-lab-wiki`](kdd-lab-wiki)  
- [`personal_concepts`](personal_concepts)  
- [`rubrics`](rubrics)  

### 📁 System Identity (Archive Subsection) — ⚙️ [`systems`](systems)

System identity documents are immutable descriptions of physical and virtual machines. They belong in **THE ARCHIVE** because they define *state of the world*, not runtime behavior.

- 💻 **Computers** — [`systems/computers`](systems/computers)  
  Personal or workstation machines with BIOS, OS, WDAC posture, installation constraints, and user‑level operational envelopes.

- 🖥️ **Servers** — [`systems/servers`](systems/servers)  
  Institutional or lab‑managed servers, HPC nodes, and shared infrastructure with centralized administration and persistent host identity.

- ☁️ **Cloud Systems** — [`systems/cloud`](systems/cloud)  
  Virtualized or ephemeral compute nodes provisioned via API (AWS, Azure, GCP, OpenCloud VMs). Identity is defined by IAM roles, region/zone, and service tier rather than hardware.

### 📁 Application Notes (Archive Subsection) — 🧩 [`apps`](apps)

Application notes are *cross‑system operational knowledge* about runtimes, toolchains, and application‑level constraints.  
They belong in **THE ARCHIVE** because they describe *immutable knowledge* about tools, not live state.

Examples include:

- Node.js portable runtime notes  
- Playwright/Chromium deterministic rendering notes  
- rclone configuration  
- Browser DOM‑capture workflows  
- Cloud orchestration tools (OpenCloud, Slurm CLI clients, etc.)

---

## ⚡ 2. THE STATE — [`state`](state)

**Live Data, Telemetry, & Runtime Reality.**  
This is the dynamic SSOT for the PI and the lab. Compute nodes query this directory to understand the exact operational reality at the present moment.

Subdirectories include:

- [`state/academics`](state/academics)  
- [`state/ledgers`](state/ledgers)  
- [`state/outreach`](state/outreach)  
- [`state/personnel`](state/personnel)  
- [`state/pi_vitals`](state/pi_vitals)  
- [`state/spillover`](state/spillover)  
- [`state/tickets`](state/tickets)

---

## 🧬 3. THE MOLD — [`templates`](templates)

**Schemas, Forms, and Bureaucratic Execution.**  
Role‑based templates that enforce standardization across artifact generation. These are empty molds consumed by compute nodes and humans.

Subdirectories include:

- [`templates/advisor_mentor`](templates/advisor_mentor)  
- [`templates/kstate_faculty`](templates/kstate_faculty)  
- [`templates/pi_director`](templates/pi_director)  
- [`templates/stack_architect`](templates/stack_architect)  
- [`templates/sysadmin_infra`](templates/sysadmin_infra)

---

# 📚 Reference Directory Table of Contents (Subdirectories Only)

- [`architecture`](architecture)  
- [`ideas`](ideas)  
- [`incidents`](incidents)  
- [`kdd-lab-wiki`](kdd-lab-wiki)  
- [`personal_concepts`](personal_concepts)  
- [`rubrics`](rubrics)  
- [`state`](state)  
  - [`state/academics`](state/academics)  
  - [`state/ledgers`](state/ledgers)  
  - [`state/outreach`](state/outreach)  
  - [`state/personnel`](state/personnel)  
  - [`state/pi_vitals`](state/pi_vitals)  
  - [`state/spillover`](state/spillover)  
  - [`state/tickets`](state/tickets)  
- [`systems`](systems)  
  - [`systems/cloud`](systems/cloud)  
  - [`systems/computers`](systems/computers)  
  - [`systems/servers`](systems/servers)  
- [`apps`](apps)  
- [`templates`](templates)
