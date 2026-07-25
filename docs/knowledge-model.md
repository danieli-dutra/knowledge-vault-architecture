# Knowledge Model

## Purpose

This document defines the conceptual model of the Knowledge Operating System.

It describes the different types of knowledge that may exist within a software project, how they relate to each other and how they evolve over time.

This model serves as the semantic foundation for documentation, templates and AI-assisted knowledge management.

---

# Knowledge Philosophy

Knowledge is not a collection of files.

Knowledge is a network of concepts.

Each document represents a specific type of knowledge with a defined purpose, lifecycle and relationships.

The objective of the Knowledge OS is to preserve these relationships over time.

---

# Knowledge Entities

The Knowledge OS is composed of different knowledge entities.

Each entity represents a distinct type of information.

---

## Vision

### Purpose

Defines the long-term direction of the project.

### Answers

- Why does this project exist?
- What problem does it solve?
- What is the desired future?

### May Generate

- Strategy
- Product
- Research

---

## Strategy

### Purpose

Defines how the vision will be achieved.

### Answers

- What are our priorities?
- What should we build first?
- What should we avoid?

### May Generate

- Roadmaps
- Decisions
- Features

---

## Research

### Purpose

Collects information before decisions are made.

### Sources

- articles
- benchmarks
- experiments
- interviews
- documentation
- market analysis

### May Generate

- Decisions
- Architecture
- Features

---

## Decision

### Purpose

Records an important project decision.

### Answers

- What was decided?
- Why was it decided?
- What alternatives were rejected?

### May Generate

- Architecture
- Features
- Tasks

---

## Architecture

### Purpose

Defines how the system is organized.

### Includes

- components
- domains
- boundaries
- responsibilities
- relationships

### May Generate

- Technical documentation
- Features
- Tasks

---

## Feature

### Purpose

Describes a product capability.

### Answers

- What should be built?
- Why does it exist?
- Who benefits?

### May Generate

- Tasks
- UX
- Technical implementation

---

## Task

### Purpose

Represents executable work.

### Characteristics

- finite
- actionable
- measurable

Tasks should always reference the Feature or Decision that originated them.

---

## Meeting

### Purpose

Captures discussions and outcomes.

Meetings should summarize:

- participants
- context
- decisions
- action items

Meetings should never become the canonical source of project knowledge.

Important information must migrate to the appropriate document.

---

## Reference

### Purpose

Stores stable information intended for consultation.

Examples include:

- APIs
- Standards
- Guidelines
- External documentation

Reference documents rarely change.

---

## Archive

### Purpose

Preserves historical information.

Archived documents remain searchable but are no longer actively maintained.

Archive exists for traceability, not deletion.

---

# Knowledge Relationships

Knowledge entities naturally generate other entities.

Typical flow:

Vision

↓

Strategy

↓

Research

↓

Decision

↓

Architecture

↓

Feature

↓

Task

↓

Implementation

↓

Reference

↓

Archive

This flow is directional but not strictly linear.

Projects may iterate between stages.

---

# Knowledge Lifecycle

Every entity progresses through maturity stages.

Draft

↓

Review

↓

Approved

↓

Historical

↓

Archived

The lifecycle describes confidence, not importance.

---

# Ownership

Every knowledge entity has exactly one owner.

Ownership defines:

- maintenance
- canonical location
- responsibility

Multiple documents may reference the same entity.

Only one document owns it.

---

# AI Classification

AI agents should classify documents according to this model before creating new documentation.

Whenever possible, existing entities should be updated instead of creating duplicates.

If an entity cannot be classified, the agent should request clarification.

---

# Model Evolution

The Knowledge Model is expected to evolve.

New entity types may be introduced as the Knowledge OS grows.

Existing entities should remain stable whenever possible to preserve long-term consistency.

Changes to this model should be treated as architectural decisions.