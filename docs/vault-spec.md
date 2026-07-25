# Vault Specification

## Purpose

This document defines the implementation contract for the Knowledge Operating System.

Its purpose is to describe how a compliant implementation should be generated from the repository specifications.

The repository itself is the canonical source of truth.

This document defines **how to implement** those specifications, not the specifications themselves.

---

# Repository Specifications

The repository is intentionally divided into independent specifications.

Each document has a single responsibility and should remain the canonical source for its domain.

| Document | Responsibility |
|-----------|----------------|
| README.md | Project vision and repository overview |
| knowledge-model.md | Knowledge entities, relationships and lifecycle |
| architecture.md | Conceptual architecture of the Knowledge OS |
| conventions.md | Documentation standards and writing conventions |
| template-spec.md | Canonical document template specification |
| vault-layout.md | Canonical directory structure and ownership |
| vault-spec.md | Implementation contract |
| security-model.md | Security principles and implementation constraints |
| agent-protocol.md | AI collaboration protocol |
| implementation-guide.md | Execution workflow for AI agents |

Specifications must complement each other.

No document should duplicate information maintained elsewhere.

---

# Objectives

A compliant implementation must:

- organize project knowledge consistently;
- preserve canonical sources of truth;
- support long-term documentation;
- remain predictable for both humans and AI agents;
- minimize ambiguity;
- remain independent of any specific implementation platform.

---

# Design Principles

## Knowledge before folders

Folders define ownership.

Knowledge is connected through relationships.

Navigation should be driven by documentation and links rather than directory traversal.

---

## One Source of Truth

Every concept must have one canonical document.

Other documents should reference that source instead of duplicating information.

---

## Progressive Knowledge

Knowledge evolves over time.

Implementations should preserve this evolution instead of replacing historical states.

---

## Deterministic Implementation

Every implementation must be generated exclusively from the repository specifications.

An implementation must never invent:

- folder structures;
- document types;
- metadata;
- naming conventions;
- documentation standards.

If any required information is missing or contradictory, implementation must stop and request clarification.

---

## Technology Independence

The Knowledge Operating System is independent from any implementation platform.

The specifications must remain valid regardless of whether the implementation targets:

- Obsidian
- VS Code
- Notion
- GitHub
- Cursor
- Claude Code
- Antigravity
- Any future platform

Platform-specific adaptations belong to the implementation, not to the architecture.

---

# Knowledge Lifecycle

Knowledge naturally evolves through successive maturity stages.

```text
Inbox
    ↓
Working Notes
    ↓
Structured Documentation
    ↓
Permanent Knowledge
    ↓
Archive
```

Implementations should preserve this lifecycle whenever possible.

---

# Implementation Process

Every implementation must follow the same workflow.

## Step 1 — Read the Repository

Read the repository README.

Understand the project's philosophy before implementing anything.

---

## Step 2 — Read the Knowledge Model

Understand:

- knowledge entities;
- relationships;
- ownership;
- lifecycle.

---

## Step 3 — Read the Architecture

Understand:

- conceptual organization;
- navigation principles;
- documentation domains.

---

## Step 4 — Read the Conventions

Understand:

- naming rules;
- metadata;
- document standards;
- linking conventions.

---

## Step 5 — Read the Template Specification

Understand:

- available document types;
- template selection rules;
- template lifecycle.

Templates must never be recreated by inference.

---

## Step 6 — Read the Vault Layout

Understand:

- directory hierarchy;
- folder ownership;
- indexes;
- implementation structure.

---

## Step 7 — Read the Security Model

Verify implementation constraints and prohibited behaviors.

---

## Step 8 — Read the Agent Protocol

Understand how AI agents are expected to collaborate during implementation.

---

## Step 9 — Generate the Knowledge OS

Generate the implementation strictly according to the repository specifications.

Do not introduce undocumented folders, files or conventions.

---

## Step 10 — Validate the Implementation

Before considering the implementation complete, verify that:

- every required directory exists;
- every required template exists;
- every required index exists;
- every document follows repository conventions;
- navigation is internally consistent;
- canonical sources remain unique;
- internal links are valid.

Only after successful validation should the implementation be considered complete.

---

# Implementation Constraints

An implementation must never:

- invent architecture;
- invent folder structures;
- invent documentation standards;
- duplicate canonical information;
- rename official document types;
- modify repository specifications without explicit authorization.

Whenever conflicting specifications are found, implementation must stop and request clarification.

---

# Evolution

The implementation process should remain stable even as the repository evolves.

New specifications may be added over time without changing the overall implementation workflow.

Tool-specific adaptations may evolve independently from the Knowledge Operating System architecture.