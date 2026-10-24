---
title: "実践的な開発"
slug: ja-jp/real-world-development
authors:
  - geektrainer
lastUpdated: 2026-09-16
---

現実的なシナリオ、完成したアプリケーション、共有バックログを使って、ソフトウェア開発ライフサイクル全体で GitHub Copilot を活用します。変更を計画し、コードを作成し、動作をテストし、プルリクエストをレビューし、エージェントで作業を管理する流れを段階的に実践します。

## シナリオ

架空の企業 Tailspin Toys で新たに開発者として働きます。同社は、開発者をテーマにしたボードゲームのクラウドファンディングを提供しています。チームのバックログは GitHub Issue として登録済みで、すぐに作業を始められます。フィルタリングやページネーションなどの機能開発に加え、アクセシビリティやコーディング規約などの品質改善も含まれています。

## 作業環境を選ぶ

GitHub Copilot は、開発者が作業する環境で利用できます。自分の開発方法に合った環境を選びましょう。各ワークショップには独自のセットアップがあり、同じ Tailspin Toys のシナリオを使用します。

### [GitHub Copilot CLI（コマンドラインインターフェイス）][cli]

ターミナルでエージェント型アシスタントを使います。Plan モードと Autopilot モード、指示、スキル、カスタムエージェント、Playwright のモデルコンテキストプロトコル (MCP)、Agent Merge、便利なスラッシュコマンドを扱います。

### [GitHub Copilot app][app]

エージェントの並列セッションを実行し、セッションモードを切り替え、Canvas で共同作業し、デスクトップアプリから GitHub Issue とプルリクエストを管理します。

### [GitHub Copilot クラウドエージェント][cloud]

非同期エージェントに GitHub Issue を割り当て、作業を誘導し、進捗を監視して、エージェントが作成したプルリクエストをレビューします。

### [Visual Studio Code][vscode]

Visual Studio Code と GitHub Codespaces で GitHub Copilot を使います。エディターを離れずに、Copilot Chat のエージェントモード、MCP サーバー、カスタムエージェントを扱います。

[cli]: cli/
[app]: app/
[cloud]: cloud/
[vscode]: vscode/
