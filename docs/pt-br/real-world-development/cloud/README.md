---
slug: pt-br/real-world-development/cloud
title: "Agente de nuvem do GitHub Copilot"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

O [agente de nuvem do GitHub Copilot](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent) permite que o GitHub Copilot trabalhe de forma assíncrona na nuvem. Você atribui o trabalho no GitHub, e o agente de nuvem o executa em segundo plano — explora o repositório, faz alterações e abre um pull request — enquanto você pode cuidar de outras tarefas.

Nestes exercícios, você adicionará instruções personalizadas que o agente de nuvem seguirá e, depois, atribuirá a ele uma issue do GitHub para implementar. Você revisará e usará agentes personalizados para orientar a abordagem, acompanhará e direcionará as sessões no painel de agentes e terminará revisando os pull requests do agente e iterando sobre os resultados.

## Exercícios

| Exercício | Tópico | Descrição |
|----------|-------|-------------|
| [0. Pré-requisitos][ex0] | Configuração | Crie seu repositório e Codespace |
| [1. Instruções personalizadas][ex1] | Contexto | Adicione instruções personalizadas para o agente de nuvem |
| [2. Agente de nuvem][ex2] | Agente assíncrono | Atribua issues ao agente de nuvem do Copilot |
| [3. Agentes personalizados][ex3] | Agentes especializados | Revise e use agentes personalizados |
| [4. Gerenciar agentes][ex4] | Monitoramento | Monitore e direcione as sessões do agente |
| [5. Iterar][ex5] | Revisão | Revise pull requests, itere sobre o trabalho do Copilot e escolha os próximos passos |

## Pré-requisitos

Antes de participar deste workshop, verifique se você tem:

- [ ] Uma conta do GitHub com um plano **Copilot Student, Pro, Pro+, Business ou Enterprise** ativo
- [ ] O agente de nuvem do Copilot habilitado para sua conta ou organização

> [!TIP]
> Não tem um plano pago? Estudantes elegíveis podem obter o GitHub Copilot gratuitamente pelo [GitHub Education][callout-student-plan-education]. O plano **Copilot Student** inclui o agente, o protocolo de contexto de modelo (MCP), revisão de código e recursos do Copilot CLI usados neste workshop — assim, você pode concluir todos os ambientes com ele.

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> O agente de nuvem está disponível nos planos **Copilot Student, Pro, Pro+, Business e Enterprise**, mas não no Copilot Free. No Copilot Business ou Enterprise, um administrador precisa habilitá-lo para a organização.

> [!NOTE]
> Este ambiente não aborda o protocolo de contexto de modelo (MCP). Para explorar o uso de servidores MCP com o Copilot, consulte o [ambiente de CLI](../cli/) ou o [ambiente do VS Code](../vscode/).

## Começar

**[Comece pelo Exercício 0: Pré-requisitos →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
