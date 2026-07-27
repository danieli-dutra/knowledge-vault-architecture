---
title: Como Usar
owner: Dani Dutra
status: Active
created:
updated:
domains: []
tags:
  - guia
  - documentação
  - navegação
---

# 🧠 Como usar a Knowledge Vault Architecture

> Um guia rápido para começar a utilizar esta arquitetura de conhecimento em qualquer projeto.

---

## Boas-vindas

A **Knowledge Vault Architecture** é uma estrutura para organizar conhecimento de forma clara, escalável e reutilizável.

Ela foi criada para centralizar informações sobre produtos, projetos, pesquisas, decisões e atividades do dia a dia, formando uma base de conhecimento viva que evolui junto com o projeto.

Embora tenha sido pensada para desenvolvimento de software, a arquitetura pode ser utilizada em qualquer contexto que envolva documentação em Markdown.

Esta arquitetura não define como você deve organizar seu conhecimento.
Ela oferece uma base sólida que pode ser adaptada às necessidades do seu projeto.
Sinta-se à vontade para remover, adicionar ou reorganizar pastas e templates conforme sua realidade.

---

# 🚀 Primeiros passos

## 1. Faça uma cópia do projeto

Você pode:

- Clonar este repositório
- Fazer um Fork
- Baixar os arquivos em formato ZIP

Depois disso, utilize a estrutura como base para seu próprio projeto.

---

## 2. Renomeie o Vault (opcional)

Alguns exemplos:

```text
Meu Brain
Brain do Produto
Knowledge Base
Documentação Técnica
```

---

## 3. Abra a pasta no Obsidian

Basta selecionar a pasta principal como um novo Vault.

Nenhuma configuração adicional é necessária.

---

## 4. Explore a estrutura

A arquitetura é composta por seis áreas principais:

| Pasta | Finalidade |
|--------|------------|
| **Home** | Página inicial e navegação |
| **Knowledge** | Conhecimento permanente do projeto |
| **Work** | Registro das atividades realizadas |
| **References** | Links, artigos e materiais de apoio |
| **Archive** | Conteúdo antigo ou descontinuado |
| **Templates** | Modelos para criação de novos documentos |

---

# 📝 Criando novos documentos

Sempre que possível, utilize um dos templates disponíveis em:

```text
Templates/
```

Os templates disponíveis incluem:

- ADR
- Decision
- Feature
- Meeting
- Reference
- Research
- Strategy
- Task
- Vision

Eles ajudam a manter um padrão de documentação ao longo do projeto.

---

# 🔄 Fluxo recomendado

```text
Escolha um Template
        ↓
Crie um novo documento
        ↓
Renomeie o arquivo
        ↓
Mova para a pasta correta
        ↓
Relacione com outras notas
        ↓
Atualize os índices (quando necessário)
```

---

# 📚 Organização da documentação

Uma boa prática é separar o conhecimento em três categorias:

### Conhecimento permanente

Informações que representam o estado atual do projeto.

Exemplos:

- Arquitetura
- Funcionalidades
- Estratégia
- Visão do produto

---

### Trabalho realizado

Registros cronológicos das atividades.

Exemplos:

- Implementações
- Reuniões
- Descobertas
- Estudos

---

### Referências

Conteúdos externos que apoiam o projeto.

Exemplos:

- Artigos
- Documentações
- Vídeos
- Papers
- Links úteis

---

# 🔗 Conecte suas notas

Sempre que possível, utilize links internos do Obsidian:

```markdown
[[Feature]]
[[Research]]
[[ADR-0001]]
```

Quanto mais conexões existirem entre os documentos, mais útil será a visualização em grafo e mais fácil será navegar pelo conhecimento.

---

# 💡 Filosofia

A documentação deve ser:

- Organizada
- Fácil de encontrar
- Conectada
- Versionada
- Reutilizável

O objetivo da Knowledge Vault Architecture é transformar a documentação em um ativo do projeto, e não apenas em arquivos espalhados pelo repositório.

---

# 📌 Boas práticas

- Utilize os templates sempre que possível.
- Prefira registrar decisões importantes em ADRs.
- Mantenha os documentos atualizados.
- Faça referências entre notas relacionadas.
- Evite duplicar informações.

---

# 📖 Continue explorando

- [[Knowledge Index]]
- [[Templates Index]]
- [[References Index]]
- [[Work Index]]
