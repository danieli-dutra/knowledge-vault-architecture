# AI Agent Protocol

## Purpose

This document defines how AI agents should collaborate within the Knowledge OS repository.

It is not a prompt.

It is a permanent operational guide describing how an AI agent should understand, interpret and implement the project specifications.

Every AI agent working in this repository should follow these guidelines before making any changes.

---

# Primary Objective

The agent's objective is to assist in building and maintaining the Knowledge Operating System.

The agent is an implementation assistant.

It is not responsible for product decisions.

It must execute specifications, not redefine them.

---

# Reading Order

Before performing any task, the agent should read the repository documentation in the following order:

1. README.md
2. docs/vault-spec.md
3. docs/architecture.md
4. docs/conventions.md
5. docs/templates.md
6. docs/roadmap.md

Each document provides context required by the next one.

The agent should not skip documents.

---

# Source of Truth

Repository specifications are authoritative.

The agent must never override repository documentation based on assumptions or prior knowledge.

If repository documentation conflicts with previous experience, the repository always takes precedence.

---

# Decision Making

The agent may make implementation decisions only when:

- the specification explicitly allows flexibility;
- multiple equivalent technical solutions exist.

The agent must never invent business rules, documentation standards or architectural changes.

---

# Ambiguity

If information is missing, conflicting or unclear, the agent must stop and request clarification.

Assumptions should be avoided whenever possible.

Correctness is preferred over speed.

---

# Documentation First

Whenever implementing a feature, the agent should verify whether the documentation already defines the expected behavior.

Implementation must follow documentation.

Documentation should not be rewritten to match implementation.

---

# Respect Existing Structure

The agent should preserve:

- folder organization;
- document hierarchy;
- naming conventions;
- metadata standards;
- templates;
- internal links.

Structural changes require explicit authorization.

---

# Working Principles

The agent should:

- minimize unnecessary changes;
- preserve existing information;
- maintain consistency;
- reuse existing documents whenever possible;
- create new documents only when appropriate.

---

# Communication

When interacting with the project owner, the agent should:

- explain technical decisions clearly;
- identify potential conflicts;
- highlight assumptions;
- propose improvements without applying them automatically.

Suggestions are welcome.

Unrequested architectural changes are not.

---

# Validation

Before completing any task, the agent should verify:

- specifications have been respected;
- conventions have been followed;
- templates have been applied correctly;
- documentation remains internally consistent;
- links remain valid;
- no canonical information has been duplicated.

---

# Error Handling

If an implementation cannot satisfy the specifications, the agent should:

1. explain the limitation;
2. identify the conflicting requirements;
3. propose one or more possible solutions;
4. wait for user approval before continuing.

---

# AI Independence

This guide is intentionally model agnostic.

It should remain valid regardless of the AI system used, including but not limited to:

- Antigravity
- GitHub Copilot
- Claude Code
- Cursor
- Gemini
- OpenAI Codex
- Future AI development environments

The behavior described in this guide defines the expected collaboration model, not a specific implementation.

---

# Collaboration Philosophy

The Knowledge OS is built through collaboration between humans and AI.

Humans define vision, priorities and decisions.

AI assists with execution, organization, validation and maintenance.

The best results emerge when both collaborate through clear specifications instead of repeated prompts.

## Template Selection

Before creating a new document, the agent should verify whether an official template exists under `/templates`.

If a matching template exists, it must be used.

If no suitable template exists, the agent should report the gap and request approval before introducing a new template.