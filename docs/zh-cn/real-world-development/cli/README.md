---
slug: zh-cn/real-world-development/cli
title: "GitHub Copilot CLI"
description: "学习 Copilot CLI 模式、自定义配置、MCP 工具和拉取请求自动化，同时为 Tailspin Toys 创建、验证并交付两项更改。"
authors:
  - geektrainer
lastUpdated: 2026-09-18
---

**[GitHub Copilot CLI][about-copilot-cli]** 将 GitHub Copilot 作为智能体式编码助手引入终端。它可以探索代码库、生成代码、运行命令并连接外部工具——全部通过命令行完成，无需切换到图形化编辑器即可保持工作流畅。

本研讨会将通过 Tailspin Toys 的完整工作流展开：

1. 在 GitHub Codespaces 中准备项目、安装 Copilot CLI 并熟悉环境。
2. 小幅修改星级评分，在浏览器中审查，并手动合并第一个拉取请求 (PR)。
3. 从筛选议题开始，在 Plan 模式中确定方案，在 Autopilot 模式中实现，然后在 Interactive 模式中审查。
4. 更新存储库指令，并将其应用到筛选功能的开发中。
5. 自定义现有的 `quality-checks` 技能，并用它运行项目检查。
6. 添加 Playwright 模型上下文协议 (MCP) 服务器，并用它在浏览器中探索筛选功能。
7. 创建质量保证 (QA) 自定义智能体，用于审查需求、覆盖率和验证证据。
8. 审查完整的筛选更改，并在筛选 PR 中使用 Agent Merge。
9. 探索用于上下文、模型、共享和可选云委托的实用斜杠命令。

为保持研讨会重点清晰，你将创建两个 PR：一个用于星级评分，另一个用于筛选，并包含指令更新、技能更新、QA 配置和测试。筛选与质量工作共用一个会话和分支，这样你可以在探索各项工具时延续已有工作。

## 课程

| 课程 | 主题 | 说明 |
| ------ | ----- | ----------- |
| [0. 先决条件][ex0] | 设置 | 创建存储库和 Codespace |
| [1. 安装 Copilot CLI][ex1] | 安装 | 安装并验证 Copilot CLI，然后熟悉环境 |
| [2. 添加星级评分：快速取得第一个成果][ex2] | 首次更改 | 显示现有评分和评分为空时的备用文本，然后合并第一个 PR |
| [3. 智能体模式：Plan 和 Autopilot][ex3] | 智能体模式 | 根据议题规划功能，使用 Autopilot 实现，然后在 Interactive 模式中审查 |
| [4. 使用自定义指令引导 Copilot][ex4] | 上下文 | 查看并更新指令，然后将其应用到筛选功能 |
| [5. 自定义并使用质量检查技能][ex5] | 可重复检查 | 查看现有技能、更改报告格式并运行技能 |
| [6. 使用 Playwright MCP 验证功能][ex6] | 浏览器观察 | 在 CLI 中配置 MCP 并检查筛选行为 |
| [7. 创建并使用 QA 智能体][ex7] | 需求与覆盖率 | 创建并选择专用配置，然后收集最终验证证据 |
| [8. 创建并合并功能 PR][ex8] | 审查与合并 | 审查完整更改、创建 PR 并使用 Agent Merge |
| [9. GitHub Copilot CLI 斜杠命令][ex9] | CLI 功能 | 探索上下文、模型、共享和可选的云智能体委托 |
| [10. 回顾与后续步骤][ex10] | 总结 | 回顾工作流、可复用的自定义配置和其他资源 |
| [可选：集成 Foundry][foundry] | 托管智能体 | 准备模型、部署基于目录的智能体，并将其连接到网站 |

## 先决条件

参加本研讨会之前，请确保具备以下条件：

- [ ] 拥有有效的 **Copilot Student、Pro、Pro+、Business 或 Enterprise** 计划的 GitHub 帐户
- [ ] 有权创建存储库和 Codespace
- [ ] 熟悉基本的终端或命令行操作

> [!TIP]
> 没有付费计划？通过验证的学生可从 [GitHub Education][student-plan] 免费获取 GitHub Copilot。**Copilot Student** 计划包含本研讨会使用的智能体、MCP、代码审查和 Copilot CLI 功能。

> [!NOTE]
> 如果你使用 Copilot Business 或 Copilot Enterprise，请确认管理员已启用 Copilot CLI。

## 开始

**[从先决条件开始 →][ex0]**

[about-copilot-cli]: https://docs.github.com/copilot/concepts/agents/about-copilot-cli
[student-plan]: https://github.com/education/students
[ex0]: 0-prerequisites/
[ex1]: 1-install-copilot-cli/
[ex2]: 2-add-star-rating/
[ex3]: 3-agent-modes/
[ex4]: 4-custom-instructions/
[ex5]: 5-agent-skills/
[ex6]: 6-mcp-playwright/
[ex7]: 7-qa-agent/
[ex8]: 8-create-pull-request/
[ex9]: 9-cli-power-tools/
[ex10]: 10-review/
[foundry]: 8-foundry-agent/
