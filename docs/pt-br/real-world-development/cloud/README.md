---
slug: pt-br/real-world-development/cloud
title: "Agente na nuvem do GitHub Copilot"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

O [**agente na nuvem do GitHub Copilot**](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent) permite que o GitHub Copilot trabalhe de forma assíncrona na nuvem. Você atribui uma tarefa no GitHub, e o agente na nuvem a assume em segundo plano: explora o repositório, faz alterações e abre um pull request enquanto você pode cuidar de outras atividades.

Nestes exercícios, você adicionará instruções personalizadas para o agente na nuvem e, em seguida, atribuirá um issue do GitHub para que ele implemente o trabalho. Você revisará e usará agentes personalizados para orientar a abordagem, monitorará e direcionará sessões pelo painel de agentes e, por fim, revisará os pull requests e iterará sobre os resultados.

## Exercícios

| Exercício | Tópico | Descrição |
|----------|-------|-------------|
| [0. Pré-requisitos][ex0] | Configuração | Crie seu repositório e um codespace |
| [1. Instruções personalizadas][ex1] | Contexto | Adicione as instruções personalizadas que o agente na nuvem seguirá |
| [2. Agente na nuvem][ex2] | Agente assíncrono | Atribua issues ao agente na nuvem do Copilot |
| [3. Agentes personalizados][ex3] | Agentes especializados | Revise e use agentes personalizados |
| [4. Gerenciar agentes][ex4] | Monitoramento | Monitore e direcione sessões do agente |
| [5. Iteração][ex5] | Revisão | Revise PRs, itere sobre o trabalho do Copilot e escolha as próximas etapas |

## Pré-requisitos

Antes de participar deste workshop, verifique se você tem:

- [ ] Uma conta do GitHub com um plano **Copilot Student, Pro, Pro+, Business ou Enterprise** ativo
- [ ] O agente na nuvem do Copilot habilitado para sua conta ou organização

> [!TIP]
> Você não tem um plano pago? Estudantes verificados podem obter o GitHub Copilot gratuitamente pelo [GitHub Education][callout-student-plan-education]. O plano **Copilot Student** inclui os recursos de agente, MCP, revisão de código e Copilot CLI usados neste workshop — assim, você pode concluir todos os ambientes.

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> O agente na nuvem está disponível nos planos **Copilot Student, Pro, Pro+, Business e Enterprise**, mas não no Copilot Free. No Copilot Business ou Enterprise, um administrador precisa habilitar o agente para a organização.

> [!NOTE]
> Este ambiente não aborda MCP. Para explorar o uso de servidores MCP com o Copilot, consulte o [ambiente de CLI][cli] ou o [ambiente de VS Code][vscode].

## Comece

**[Comece pelo exercício 0: Pré-requisitos →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
[cli]: ../cli/
[vscode]: ../vscode/
