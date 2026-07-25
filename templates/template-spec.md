# Template Specification

## Purpose

This document defines the standards for document templates used within the Knowledge Operating System.

Templates provide consistent structures for documenting different knowledge entities while allowing the system to evolve incrementally.

A template is the canonical starting point for creating a document of a specific knowledge type.

---

# Design Principles

Templates should be:

- Simple
- Reusable
- Consistent
- Evolvable

Templates should never become unnecessarily complex.

Each template exists to improve consistency, not bureaucracy.

---

# Relationship with the Knowledge Model

Every template represents one Knowledge Entity defined in `knowledge-model.md`.

A template should never introduce a new knowledge entity that is not defined by the Knowledge Model.

---

# Relationship with Conventions

Templates define document structure.

Conventions define writing standards.

Templates must follow all rules established in `conventions.md`.

---

# Canonical Templates

The `/templates` directory contains the canonical template for each supported knowledge entity.

Each template file represents the official structure for that document type.

Agents should always prefer existing templates over creating new document structures.

---

# Template Lifecycle

Templates evolve as the project matures.

A template may begin as a minimal placeholder and gradually become more detailed through real project usage.

Templates should evolve based on actual documentation needs rather than anticipated scenarios.

---

# Creating New Templates

A new template should only be introduced when:

- a recurring documentation pattern is identified;
- no existing template adequately represents the knowledge;
- the new template aligns with the Knowledge Model.

Templates should not be created preemptively.

---

# Updating Templates

Existing templates may evolve when:

- documentation patterns become stable;
- recurring improvements are identified;
- project practices change.

Template evolution should preserve consistency whenever possible.

Breaking structural changes should be treated as architectural decisions.

---

# Template Selection

Before creating a new document, an AI agent should:

1. Identify the Knowledge Entity.
2. Locate the corresponding template.
3. Use the canonical template.
4. Populate only the information required for that document.

If no appropriate template exists, the agent should request approval before introducing a new one.

---

# Placeholder Templates

Some templates may intentionally remain minimal until real project needs emerge.

A placeholder template indicates that:

- the document type is officially recognized;
- its detailed structure has not yet been defined.

This approach encourages organic evolution based on practical experience.

---

# AI Collaboration

AI agents should never invent new document structures when a canonical template already exists.

If improvements are identified, agents should propose updates instead of modifying templates autonomously.

---

# Future Evolution

The template system is expected to grow alongside the Knowledge Operating System.

Templates should evolve incrementally, reflecting validated documentation practices rather than hypothetical future requirements.

The objective is to maintain a library of simple, reliable and reusable document structures.