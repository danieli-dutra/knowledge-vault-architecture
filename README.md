# Knowledge Vault OS

> An open specification for organizing project knowledge into a structured, navigable and AI-ready knowledge system.

Modern software projects accumulate knowledge everywhere.

Requirements live in documents.
Architecture is discussed in meetings.
Product decisions happen in chat.
Research is stored in random notes.
Implementation lives in code.

Over time, valuable knowledge becomes fragmented, difficult to discover and almost impossible to reuse.

Knowledge Vault OS provides an open specification for organizing that knowledge into a single source of truth designed for both humans and AI agents.

---

# Why?

Traditional documentation answers:

> "Where is this document?"

Knowledge Vault OS answers:

> "Where does this knowledge belong?"

Instead of organizing documentation by folders or files, it organizes knowledge by purpose.

This makes information easier to discover, maintain and reuse throughout the entire product lifecycle.

---

# Core Principles

- Single Source of Truth
- Knowledge Before Implementation
- Canonical Documentation
- Decision Traceability
- Human + AI Collaboration
- Technology Agnostic
- Structured Navigation
- Continuous Evolution

---

# Repository Structure

```
knowledge-vault-os/
│
├── docs/
│   └── specifications/
│
├── vault/
│
├── LICENSE
└── README.md
```

The repository contains the specification and a reference implementation of the Knowledge Vault.

---

# Reference Vault Structure

```
vault/
│
├── Home.md
├── Index/
│   ├── Knowledge Index.md
│   ├── Work Index.md
│   ├── References Index.md
│   └── Templates Index.md
│
├── Knowledge/
│   ├── Vision/
│   ├── Strategy/
│   ├── Architecture/
│   ├── Decisions/
│   ├── Features/
│   └── Research/
│
├── Work/
│   ├── Tasks/
│   ├── Meetings/
│   └── Drafts/
│
├── References/
│   ├── Specifications/
│   ├── Standards/
│   └── External/
│
└── Templates/
```

This structure serves as the reference implementation of the Knowledge Vault OS specification.

---

# Specification

The specification defines where knowledge belongs.

Instead of creating folders like:

```
docs/
notes/
old-docs/
misc/
```

Knowledge Vault OS organizes information into predictable knowledge domains.

Every document has a single responsibility and a clear location.

This makes navigation easier for both humans and AI agents.

---

# Getting Started

## 1. Clone the repository

```bash
git clone https://github.com/<your-user>/knowledge-vault-os.git
```

---

## 2. Open the Reference Vault

Open the `vault/` folder directly with Obsidian.

```
knowledge-vault-os/
└── vault/
```

The `vault/` directory is the reference implementation of the specification.

---

## 3. Start from Home

The entry point of every vault is:

```
Home.md
```

From there you can navigate through the entire knowledge system using indexes and wikilinks.

---

## 4. Create the canonical documents

Before documenting implementation details, define the project's foundations.

Recommended order:

1. Product Vision
2. Product Strategy
3. Architecture
4. Features
5. Decisions

These documents become the project's single source of truth.

---

# How to Use

Knowledge Vault OS is not a note-taking system.

It is a knowledge architecture.

Whenever new information appears, ask:

> Where does this knowledge belong?

Examples:

| Information | Destination |
|-------------|-------------|
| Product purpose | Vision |
| Business goals | Strategy |
| System design | Architecture |
| Functional requirements | Features |
| Technical decisions | Decisions |
| User interviews | Research |
| Meeting notes | Work / Meetings |
| Temporary ideas | Work / Drafts |
| External standards | References |

Following this principle keeps the knowledge base organized as the project grows.

---

# Designed for AI

Knowledge Vault OS was designed so humans and AI agents share the same knowledge structure.

Benefits include:

- Predictable document locations
- Better context retrieval
- Reduced information fragmentation
- Faster onboarding
- Traceable architectural decisions
- Reusable institutional knowledge
- AI-friendly documentation

---

# Roadmap

- [ ] Specification v1.0
- [ ] Templates
- [ ] Reference Vault
- [ ] Migration Guide
- [ ] AI Integration Guide
- [ ] MCP Best Practices
- [ ] Community Examples

---

# Contributing

Contributions are welcome.

If you'd like to improve the specification, templates or documentation, feel free to open an Issue or Pull Request.

Please read the specification before proposing structural changes.

---

# License

This project is licensed under the MIT License.
