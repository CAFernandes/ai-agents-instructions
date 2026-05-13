# AI Agents Instructions

Biblioteca para centralizar e padronizar instruções de agentes de IA para engenharia de software.

Library to centralize and standardize AI agent instructions for software engineering.

## Objetivo | Purpose

Este repositório organiza instruções prontas para uso com GitHub Copilot, Claude Code e outras ferramentas de IA para programação.

This repository provides production-ready instructions to use with GitHub Copilot, Claude Code, and other coding AI tools.

## Quick Start

1. Escolha um agente na pasta docs.
2. Copie o conteúdo do documento para a sua configuração de agente ou prompt de sistema.
3. Ajuste regras específicas do seu projeto.
4. Execute a revisão ou geração com o agente selecionado.

1. Pick an agent from the docs folder.
2. Copy the document content into your agent configuration or system prompt.
3. Adapt project-specific rules.
4. Run your review or generation flow with the selected agent.

## Catálogo de agentes | Agent Catalog

### Agentes existentes | Existing

- Agent Architecture Guardian: Protege arquitetura, boundaries e modularidade.
- Agent Code Quality Guardian: Garante qualidade de código, legibilidade e redução de dívida técnica.

### Novos agentes | New

- Agent Security Sentinel: Foco em vulnerabilidades, autenticação, segredos e validação de entrada.
- Agent Test Strategy Architect: Foco em estratégia de testes, cobertura e confiabilidade de suíte.
- Agent Performance Optimizer: Foco em latência, uso de memória e eficiência algorítmica.
- Agent Documentation Guardian: Foco em documentação técnica, onboarding e runbooks.
- Agent DevOps Guardian: Foco em CI/CD, IaC, deploy safety e operação.
- Agent Observability Architect: Foco em logs, métricas, tracing e alertas acionáveis.
- Agent Product Thinking Agent: Foco em trade-offs, escopo, valor e viabilidade técnico-produto.
- Agent Compliance Governance Guard: Foco em conformidade, governança e rastreabilidade.

## Estrutura do repositório | Repository Structure

docs/
- Agent Architecture Guardian.md
- Agent Code Quality Guardian.md
- Agent Security Sentinel.md
- Agent Test Strategy Architect.md
- Agent Performance Optimizer.md
- Agent Documentation Guardian.md
- Agent DevOps Guardian.md
- Agent Observability Architect.md
- Agent Product Thinking Agent.md
- Agent Compliance Governance Guard.md
- Agent Template.md

## Como usar | How To Use

### GitHub Copilot

- Use o conteúdo do agente como base para arquivos de instrução do seu projeto.
- Combine um agente de governança com um agente especializado para revisões mais precisas.

- Use an agent document as the base for your project instruction files.
- Combine one governance agent with one specialist agent for more precise reviews.

### Claude Code

- Cole o conteúdo do agente no contexto de sistema ou no início da sessão.
- Mantenha apenas os blocos relevantes para reduzir ruído e custo de contexto.

- Paste the agent content into the system context or at the beginning of the session.
- Keep only relevant sections to reduce noise and context cost.

### Outras AIs | Other AIs

- Use as seções de objetivo, gatilhos, responsabilidades e restrições como núcleo do prompt.
- Preserve o formato de saída definido para facilitar automação.

- Use objective, triggers, responsibilities, and constraints sections as your prompt core.
- Preserve the expected output format for easier automation.

## Convenções de qualidade | Quality Conventions

- Preferir soluções simples e incrementais.
- Evitar overengineering e abstrações prematuras.
- Explicar riscos e impactos de manutenção.
- Indicar ações priorizadas por severidade.

- Prefer simple and incremental solutions.
- Avoid overengineering and premature abstractions.
- Explain risk and long-term maintenance impact.
- Provide prioritized actions by severity.

## Contribuição | Contributing

Para criar um novo agente:

1. Use Agent Template.md como base.
2. Nomeie no padrão Agent [Especialidade] [Papel].md.
3. Mantenha versão bilíngue PT-BR + EN.
4. Inclua seções de objetivo, quando atuar, regras e formato de saída.
5. Revise consistência com os demais agentes.

To create a new agent:

1. Use Agent Template.md as baseline.
2. Name it with Agent [Specialty] [Role].md.
3. Keep bilingual PT-BR + EN sections.
4. Include objective, trigger moments, rules, and output format.
5. Review consistency with existing agents.

## Próximos passos sugeridos | Suggested Next Steps

- Adicionar exemplos práticos por stack (Node.js, Python, Java, Go).
- Criar versão compacta de cada agente para uso em contexto curto.
- Adicionar automação para validação de estrutura dos documentos.

- Add stack-specific examples (Node.js, Python, Java, Go).
- Create compact versions of each agent for short-context usage.
- Add automation to validate agent document structure.
