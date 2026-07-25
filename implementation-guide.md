# Implementation Guide

## Purpose

This document provides the implementation entry point for the current project.

Its purpose is to define how the Knowledge Operating System should be instantiated without modifying the repository specifications.

Repository specifications remain the canonical source of truth.

This document defines only the implementation scope for this project.

---

# Current Objective

Implement the first Knowledge OS instance for the **Junta.ai** project using **Obsidian** as the implementation platform.

The objective is to instantiate the repository specifications without extending, redesigning or modifying them.

Obsidian is an implementation platform, not part of the Knowledge OS architecture.

---

# Reading Order

Before any implementation begins, review the repository specifications in the following order.

1. README.md
2. docs/knowledge-model.md
3. docs/architecture.md
4. docs/conventions.md
5. docs/template-spec.md
6. docs/vault-layout.md
7. docs/vault-spec.md
8. docs/security-model.md
9. docs/agent-protocol.md

Only after every specification has been reviewed may implementation begin.

---

# Implementation Scope

The first implementation should instantiate the repository specifications for the Junta.ai project.

This includes:

- creating the directory structure;
- generating required indexes;
- creating the official templates;
- organizing canonical documentation;
- establishing navigation;
- configuring metadata where specified.

The implementation must strictly follow the repository specifications.

---

# Out of Scope

The implementation must not:

- redesign the Knowledge Operating System;
- introduce undocumented directories;
- create undocumented document types;
- modify repository specifications;
- infer missing architecture;
- introduce project workflows not defined by the specifications.

Missing information should be reported rather than implemented.

---

# Implementation Principles

The implementation should prioritize:

- consistency;
- predictability;
- traceability;
- maintainability;
- strict compliance with repository specifications.

Whenever multiple implementation approaches are possible, choose the simplest approach that fully complies with the documented specifications.

---

# Validation

Before considering the implementation complete, verify that:

- every repository specification has been respected;
- the directory structure matches the Vault Layout;
- canonical documents remain unique;
- required templates exist;
- required indexes exist;
- navigation is consistent;
- metadata follows repository conventions;
- internal links are valid.

Implementation is complete only after successful validation.

---

# Expected Deliverable

The final deliverable should be a functional Knowledge OS instance for the Junta.ai project implemented as an Obsidian Vault.

The resulting vault should faithfully represent the repository specifications while remaining maintainable and extensible.

---

# Conflict Resolution

If implementation conflicts with any repository specification:

1. stop the implementation;
2. identify the conflicting specifications;
3. explain the conflict;
4. request clarification before continuing.

Specification compliance always takes precedence over speculative implementation.

---

# Completion

Upon completion, provide a summary including:

- implemented components;
- validation results;
- unresolved questions;
- recommendations for future improvements.

Repository specifications must never be modified during implementation.