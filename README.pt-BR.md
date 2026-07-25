[🇺🇸 English](README.md) | 🇧🇷 Português

# Knowledge Vault Architecture

> Uma arquitetura aberta para construir sistemas de conhecimento estruturados, navegáveis e preparados para IA.

O **Knowledge Vault Architecture** é uma arquitetura reutilizável para organização do conhecimento em projetos de software.

Em vez de tratar a documentação como um conjunto de arquivos isolados, o Knowledge Vault Architecture entende o conhecimento como um ativo arquitetural compartilhado entre pessoas e agentes de IA durante todo o ciclo de vida de um projeto.

O objetivo é simples:

> Construir uma única fonte de verdade que permaneça organizada, reutilizável e escalável ao longo do tempo.

---

# Por que este projeto existe?

Projetos de software modernos acumulam conhecimento em diversos lugares.

- Notion
- Google Docs
- GitHub Issues
- Conversas com IA
- PDFs
- Anotações locais
- Atas de reunião
- Arquivos de design
- Código-fonte

Com o passar do tempo, esse conhecimento se torna fragmentado, duplicado e, muitas vezes, perdido.

O Knowledge Vault Architecture propõe uma abordagem diferente.

Em vez de organizar documentos por pastas ou ferramentas, ele organiza o conhecimento por responsabilidade.

Cada decisão importante, pesquisa, funcionalidade, reunião ou artefato arquitetural possui um local previsível dentro do sistema de conhecimento.

O conhecimento deixa de ser um subproduto da documentação e passa a fazer parte da arquitetura do projeto.

---

# Princípios

## Documentação é um Produto

A documentação deve ser projetada, versionada e mantida com o mesmo cuidado dedicado ao desenvolvimento de software.

---

## IA Auxilia, Não Substitui

Agentes de IA colaboram organizando, mantendo e implementando o sistema de conhecimento.

A responsabilidade por visão, estratégia, arquitetura e tomada de decisões permanece com as pessoas.

---

## O Conhecimento Possui um Ciclo de Vida

Ideias evoluem.

Pesquisas evoluem.

Arquiteturas evoluem.

O Knowledge Vault preserva essa evolução em vez de reescrever continuamente a história do projeto.

---

## Fonte Única da Verdade

Cada conceito possui um único documento canônico.

Os demais documentos devem referenciá-lo, evitando duplicação de informação.

---

## Estrutura Possibilita Automação

Estruturas previsíveis permitem que pessoas e agentes de IA naveguem, recuperem e mantenham o conhecimento de forma consistente.

---

## Independente de Tecnologia

O Knowledge Vault Architecture define uma arquitetura.

Ele não depende de nenhuma plataforma específica.

A mesma especificação pode ser implementada utilizando ferramentas como:

- Obsidian
- Notion
- VS Code
- GitHub
- Futuras plataformas

O Obsidian é apenas a implementação de referência atual.

---

# Estrutura do Repositório

```
knowledge-vault-architecture/
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

O repositório contém tanto a especificação quanto uma implementação de referência.

---

# Implementação de Referência

O repositório inclui um Knowledge Vault completo como exemplo de implementação.

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

Essa estrutura demonstra como a arquitetura pode ser aplicada em um projeto real.

---

# Especificações do Repositório

O Knowledge Vault Architecture é composto por documentos independentes.

Cada documento possui uma única responsabilidade.

| Documento | Responsabilidade |
|------------|------------------|
| README.md | Visão geral do projeto |
| knowledge-model.md | Modelo de conhecimento e ciclo de vida |
| architecture.md | Arquitetura conceitual |
| conventions.md | Convenções de documentação |
| template-spec.md | Templates canônicos |
| vault-layout.md | Estrutura padrão do Vault |
| vault-spec.md | Especificação do Vault |
| security-model.md | Princípios de segurança |
| agent-protocol.md | Protocolo de colaboração com IA |
| implementation-guide.md | Guia da implementação de referência |

Em conjunto, esses documentos definem como uma implementação do Knowledge Vault deve ser construída.

---

# Primeiros Passos

## 1. Clone o repositório

```bash
git clone https://github.com/<seu-usuario>/knowledge-vault-architecture.git
```

---

## 2. Abra o Vault

Abra a pasta `vault/` utilizando o Obsidian.

```
knowledge-vault-architecture/
└── vault/
```

Esse Vault representa a implementação de referência da arquitetura.

---

## 3. Comece pelo Home

Toda implementação começa em:

```
Home.md
```

A partir dele é possível navegar por todo o sistema utilizando índices e wikilinks.

---

## 4. Construa os documentos fundamentais

Antes de documentar detalhes técnicos, recomenda-se criar os documentos canônicos do projeto.

Ordem sugerida:

1. Visão do Produto
2. Estratégia do Produto
3. Arquitetura
4. Funcionalidades
5. Decisões

Esses documentos tornam-se a fonte oficial de conhecimento do projeto.

---

# Como Utilizar

O Knowledge Vault Architecture **não é um sistema de anotações**.

Ele é uma arquitetura para organização do conhecimento.

Sempre que surgir uma nova informação, pergunte:

> A qual responsabilidade esse conhecimento pertence?

| Informação | Destino |
|------------|----------|
| Propósito do produto | Vision |
| Estratégia de negócio | Strategy |
| Arquitetura do sistema | Architecture |
| Funcionalidades | Features |
| Decisões arquiteturais | Decisions |
| Pesquisas | Research |
| Reuniões | Work / Meetings |
| Ideias temporárias | Work / Drafts |
| Referências externas | References |

Seguindo esse princípio, a base de conhecimento permanece organizada à medida que o projeto evolui.

---

# Projetado para IA

O Knowledge Vault Architecture foi concebido para que pessoas e agentes de IA compartilhem a mesma estrutura de conhecimento.

Entre os benefícios estão:

- Estrutura previsível
- Melhor recuperação de contexto
- Redução da fragmentação de informação
- Onboarding mais rápido
- Rastreabilidade de decisões arquiteturais
- Reutilização do conhecimento institucional
- Documentação preparada para IA
- Evolução consistente do projeto

---

# Projeto de Referência

A primeira implementação completa do Knowledge Vault Architecture foi desenvolvida para o projeto **Junta.ai**.

Entretanto, a metodologia é independente e pode ser utilizada em qualquer projeto de software.

---

# Roadmap

## Versão 1.0

- [x] Especificação da Arquitetura
- [x] Templates Canônicos
- [x] Implementação de Referência
- [ ] Revisão da Documentação
- [ ] Lançamento Oficial da v1.0

---

## Versão 1.1

- [ ] Guia de Migração
- [ ] Guia de Integração com IA
- [ ] Boas Práticas para MCP

---

## Futuro

- [ ] Exemplos da Comunidade
- [ ] Novas Implementações de Referência
- [ ] Site Oficial

---

# Contribuindo

Contribuições são bem-vindas.

Caso queira melhorar a especificação, os templates ou a documentação, fique à vontade para abrir uma Issue ou um Pull Request.

Antes de propor mudanças estruturais, recomenda-se a leitura das especificações do projeto.

---

# Licença

Este projeto está licenciado sob a licença MIT.
