---
slug: ja-jp/real-world-development/cloud
title: "GitHub Copilot クラウドエージェント"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

[GitHub Copilot クラウドエージェント](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent)を使うと、GitHub Copilot がクラウドで非同期に作業できます。GitHub で作業を割り当てると、クラウドエージェントはバックグラウンドでリポジトリを調査し、変更を加えてプルリクエストを作成します。その間、開発者はほかの作業を進められます。

各演習では、クラウドエージェントが従うカスタム指示を追加した後、GitHub Issue を割り当てて実装を任せます。カスタムエージェントを確認して使い、作業の進め方を調整します。エージェントのダッシュボードからセッションを監視して指示を出し、最後にプルリクエストをレビューして結果を改善します。

## 演習

| 演習 | トピック | 説明 |
|----------|-------|-------------|
| [0. 前提条件][ex0] | セットアップ | リポジトリと Codespace を作成する |
| [1. カスタム指示][ex1] | コンテキスト | クラウドエージェントが従うカスタム指示を追加する |
| [2. クラウドエージェント][ex2] | 非同期エージェント | GitHub Issue を Copilot クラウドエージェントに割り当てる |
| [3. カスタムエージェント][ex3] | 専門エージェント | カスタムエージェントを確認して使う |
| [4. エージェントの管理][ex4] | 監視 | エージェントのセッションを監視して指示を出す |
| [5. イテレーション][ex5] | レビュー | プルリクエストをレビューし、Copilot の作業を改善して次の手順を選ぶ |

## 前提条件

このワークショップに参加する前に、次の条件を満たしていることを確認してください。

- [ ] 有効な **Copilot Student、Pro、Pro+、Business、または Enterprise** プランの GitHub アカウント
- [ ] アカウントまたは組織で有効になっている Copilot クラウドエージェント

> [!TIP]
> 有料プランをお持ちでない場合、対象となる学生は [GitHub Education][callout-student-plan-education] を通じて GitHub Copilot を無料で利用できます。**Copilot Student** プランには、このワークショップで使うエージェント、モデルコンテキストプロトコル (MCP)、コードレビュー、Copilot CLI の機能が含まれているため、すべての環境を完了できます。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> クラウドエージェントは **Copilot Student、Pro、Pro+、Business、Enterprise** で利用できます。Copilot Free は対象外です。Copilot Business または Enterprise の場合、組織の管理者が有効にする必要があります。

> [!NOTE]
> この環境ではモデルコンテキストプロトコル (MCP) を扱いません。Copilot で MCP サーバーを使う方法については、[CLI 環境](../cli/)または [VS Code 環境](../vscode/)を参照してください。

## 開始する

**[演習 0: 前提条件から始める →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
