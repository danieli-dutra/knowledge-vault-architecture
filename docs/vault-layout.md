# Vault Layout

## Purpose

This document defines the canonical directory structure of a Knowledge Operating System.

Its purpose is to establish predictable ownership of information without prescribing project-specific content.

The layout complements the Knowledge Model by defining where knowledge is stored.

---

# Design Principles

The directory structure exists to organize ownership.

It must never become the primary navigation mechanism.

Knowledge is primarily connected through:

- links;
- indexes;
- canonical references.

Folders provide physical organization.

Documentation provides logical organization.

---

# Canonical Layout

Every Knowledge OS implementation should follow the same high-level structure.

```text
/
├── Home
├── Knowledge
├── Work
├── References
├── Templates
└── Archive
```

Additional folders may exist only when explicitly defined by project specifications.

---

# Directory Responsibilities

## Home

Entry point of the Knowledge OS.

Contains:

- home page;
- navigation indexes;
- project overview.

This directory should remain small.

---

## Knowledge

Contains permanent project knowledge.

Typical contents include:

- Vision
- Strategy
- Architecture
- Decisions
- Features
- Research

Knowledge stored here should represent canonical information.

---

## Work

Contains active work.

Typical contents include:

- Tasks
- Working Notes
- Drafts
- Temporary documentation

Documents may eventually evolve into permanent knowledge.

---

## References

Contains external or supporting information.

Typical contents include:

- documentation;
- specifications;
- standards;
- third-party references;
- imported material.

Reference documents should not become canonical project knowledge.

---

## Templates

Contains every official template defined by the repository.

Only approved templates belong here.

Templates should remain implementation-independent.

---

## Archive

Contains inactive knowledge.

Examples include:

- completed initiatives;
- obsolete documentation;
- historical decisions;
- deprecated material.

Archived information should remain accessible.

---

# Ownership Rules

Every document must have exactly one canonical location.

Documents should not exist in multiple directories.

If a document changes purpose over time, it should move rather than be duplicated.

---

# Lifecycle Mapping

Knowledge naturally progresses through the directory structure.

```text
Work
    ↓
Knowledge
    ↓
Archive
```

References and Templates exist outside this lifecycle.

---

# Navigation

Navigation should rely primarily on:

- index documents;
- links;
- canonical references.

Users should never be required to browse folders in order to discover information.

---

# Implementation Constraints

An implementation must never:

- invent additional top-level directories;
- duplicate canonical documents across directories;
- use folders as the primary navigation mechanism;
- introduce undocumented ownership rules.

Whenever a different directory structure is required, it must be explicitly defined by project-specific specifications.

---

# Extensibility

Projects may introduce additional directories when required.

Additional directories must:

- have a clearly defined responsibility;
- avoid overlapping ownership;
- remain consistent with the Knowledge Model;
- be documented before implementation.

The canonical layout should remain recognizable regardless of project-specific extensions.