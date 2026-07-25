# Knowledge Vault Architecture

> An open specification for building structured, navigable and AI-ready project knowledge systems.

Knowledge Vault OS is a reusable Knowledge Operating System designed to organize software project knowledge into a structured, maintainable and searchable system.

Instead of treating documentation as isolated files, Knowledge Vault OS treats knowledge as a first-class architectural asset shared by humans and AI agents throughout the entire software lifecycle.

The objective is simple:

> Build a single source of truth that remains organized, reusable and scalable over time.

---

# Why?

Modern software projects accumulate knowledge everywhere.

- Notion
- Google Docs
- GitHub Issues
- Chat conversations
- PDFs
- Local notes
- Meeting notes
- Design files
- Source code

As projects evolve, knowledge becomes fragmented, duplicated and eventually forgotten.

Knowledge Vault OS proposes a different approach.

Instead of organizing documentation by files or folders, it organizes knowledge by responsibility.

Every important decision, research document, feature, meeting and architectural artifact belongs to a predictable location inside the knowledge system.

Knowledge becomes part of the project's architecture.

---

# Core Principles

## Documentation is a Product

Documentation should be designed, versioned and maintained with the same level of care as software.

---

## AI Assists, Not Replaces

AI agents collaborate by organizing, maintaining and implementing knowledge.

Humans remain responsible for vision, strategy, architecture and decision making.

---

## Knowledge Has a Lifecycle

Ideas evolve.

Research evolves.

Architecture evolves.

The Knowledge Vault preserves this evolution instead of continuously rewriting history.

---

## Single Source of Truth

Every concept has one canonical location.

Every other document references it instead of duplicating information.

---

## Structure Enables Automation

Predictable structures allow humans and AI agents to navigate, retrieve and maintain project knowledge consistently.

---

## Technology Agnostic

Knowledge Vault OS defines an architecture.

It does not depend on any specific platform.

The same specification can be implemented using:

- Obsidian
- Notion
- VS Code
- GitHub
- Future knowledge platforms

Obsidian is the current reference implementation, not a requirement.

---

# Repository Structure

```
knowledge-vault-os/
│
├── docs/
│   └── specifications/
│
├── templates/
│
├── vault/
│
├── implementation-guide.md
│
├── LICENSE
└── README.md
```

The repository contains both the specification and a reference implementation.

---

# Reference Implementation

The repository includes a complete reference Knowledge Vault.

```
vault/
│
├── Home.md
│
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

This vault demonstrates how the specification can be applied in a real project.

---

# Repository Specifications

The Knowledge Vault OS specification is composed of independent documents.

Each document has a single responsibility.

| Document | Responsibility |
|----------|----------------|
| README.md | Repository overview |
| knowledge-model.md | Knowledge entities and lifecycle |
| architecture.md | Conceptual architecture |
| conventions.md | Documentation standards |
| template-spec.md | Canonical document templates |
| vault-layout.md | Canonical directory structure |
| vault-spec.md | Knowledge Vault specification |
| security-model.md | Security principles |
| agent-protocol.md | AI collaboration protocol |
| implementation-guide.md | Reference implementation guide |

Together these documents define how a Knowledge Vault should be implemented.

---

# Getting Started

## 1. Clone the repository

```bash
git clone https://github.com/<your-user>/knowledge-vault-os.git
```

---

## 2. Open the Reference Vault

Open the `vault/` directory using Obsidian.

```
knowledge-vault-os/
└── vault/
```

The vault is the reference implementation of the specification.

---

## 3. Start from Home

Every Knowledge Vault starts from:

```
Home.md
```

From there you can navigate the entire knowledge system using indexes and wikilinks.

---

## 4. Build the project foundations

Before documenting implementation details, create the project's canonical documents.

Recommended order:

1. Product Vision
2. Product Strategy
3. Architecture
4. Features
5. Decisions

These become the project's single source of truth.

---

# How to Use

Knowledge Vault OS is **not** a note-taking system.

It is a knowledge architecture.

Whenever new information appears, ask:

> Where does this knowledge belong?

| Information | Destination |
|-------------|-------------|
| Product purpose | Vision |
| Business strategy | Strategy |
| System architecture | Architecture |
| Functional requirements | Features |
| Architectural decisions | Decisions |
| Research | Research |
| Meetings | Work / Meetings |
| Temporary ideas | Work / Drafts |
| External references | References |

Following this principle keeps the knowledge base organized as the project evolves.

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
- Consistent project evolution

---

# Reference Project

The first complete implementation of Knowledge Vault OS was developed for the **Junta.ai** project.

The methodology itself is independent of any specific project and may be adopted by any software team.

---

# Roadmap

- [ ] Specification v1.0
- [ ] Templates
- [ ] Reference Implementation
- [ ] Migration Guide
- [ ] AI Integration Guide
- [ ] MCP Best Practices
- [ ] Community Examples

---

# Contributing

Contributions are welcome.

If you'd like to improve the specification, templates or documentation, feel free to open an Issue or Pull Request.

Please read the specifications before proposing structural changes.

---

# License

This project is licensed under the MIT License.
