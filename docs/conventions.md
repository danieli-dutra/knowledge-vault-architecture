# Documentation Conventions

## Purpose

This document defines the standards for creating, maintaining and evolving documentation inside the Knowledge OS.

Its objective is to ensure consistency across all documentation, regardless of whether it is written by humans or AI agents.

Every document created within the Knowledge OS must follow these conventions.

---

# Documentation Principles

## Clarity over complexity

Documentation should prioritize readability.

A simple explanation is preferable to an exhaustive but confusing one.

---

## One responsibility per document

Every document should answer one primary question.

If a document starts answering multiple unrelated questions, it should be split.

---

## One source of truth

Information must exist in only one canonical location.

Other documents should reference that source instead of duplicating content.

---

## Progressive evolution

Documentation is expected to evolve.

Drafts become reviews.

Reviews become approved documentation.

Documentation should evolve instead of being rewritten from scratch.

---

# File Naming

File names should:

- be descriptive;
- remain stable over time;
- avoid abbreviations whenever possible;
- avoid dates unless they are intrinsic to the document.

Good examples:

Feature Authentication

Product Vision

Design Principles

Meeting Sprint Planning

Architecture Decisions

Avoid:

doc-final-v3

meeting-new

notes2

temp

---

# Writing Style

Documentation should be:

- objective;
- concise;
- technically accurate;
- written in complete sentences.

Avoid:

- unnecessary marketing language;
- excessive formatting;
- duplicated explanations.

---

# Document Lifecycle

Every document belongs to one lifecycle stage.

Available stages include:

- Draft
- Review
- Approved
- Archived

Status should reflect the maturity of the document rather than its importance.

---

# Metadata

Whenever supported by the implementation platform, documents should include metadata describing:

- title;
- owner;
- status;
- creation date;
- last updated;
- related domains;
- tags.

Metadata should remain standardized across the repository.

---

# Internal Links

Documents should reference related knowledge whenever possible.

Internal links should connect concepts instead of repeating explanations.

Links are preferred over duplication.

---

# Knowledge Ownership

Every document has one owner.

The owner is responsible for maintaining the canonical version of the information.

Ownership does not restrict collaboration.

---

# Versioning

Documentation should evolve through version control.

Historical context should be preserved.

Important decisions should never disappear without traceability.

---

# AI Collaboration

AI agents should:

- preserve document intent;
- avoid unnecessary rewrites;
- respect existing structure;
- follow official templates;
- request clarification whenever ambiguity exists.

AI should improve documentation, not replace project decisions.

---

# Forbidden Practices

The following practices should be avoided:

- duplicated documentation;
- orphan documents;
- undocumented decisions;
- inconsistent naming;
- multiple canonical sources;
- undocumented structural changes.

---

# Quality Checklist

Before considering a document complete, verify:

✓ Purpose is clear.

✓ Responsibility is well defined.

✓ Naming follows conventions.

✓ Related documents are linked.

✓ Duplicate information does not exist.

✓ Status reflects document maturity.

✓ Metadata is complete.

✓ Writing is technically consistent.