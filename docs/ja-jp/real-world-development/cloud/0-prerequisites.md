---
title: "演習 0: 前提条件"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

Copilot クラウドエージェントの演習を始める前に、必要な環境を準備します。Tailspin Toys リポジトリのコピーを作成し、[Codespace][codespaces] を起動して、指示ファイルの編集やクラウドエージェントが作成した変更のレビューに使います。

## ラボ用リポジトリを設定する

開発するコードのリポジトリを作成するには、[テンプレート][template-repository]からインスタンスを作成します。新しいインスタンスにはラボに必要なファイルがすべて含まれており、演習を通して使用します。

1. 新しいブラウザーウィンドウで、[Tailspin Toys のテンプレート][tailspin-template]を開きます。
2. ラボのリポジトリページで **Use this template** ボタンを選択して、自分用のコピーを作成します。次に、**Create a new repository** を選択します。

    ![Use this template ボタン](../../../_images/ex0-use-template.png)

3. GitHub または Microsoft が主催するイベントでワークショップに参加する場合は、メンターの指示に従います。それ以外の場合は、GitHub Copilot を利用できる組織に新しいリポジトリを作成します。

    ![リポジトリのテンプレート設定を入力](../../../_images/ex0-repository-settings.png)

4. 作成したリポジトリのパス（**organization-or-user-name/repository-name**）を控えておきます。ラボの後半で使用します。

## Codespace を作成する

次に、ラボの演習で使う Codespace を作成します。

[GitHub Codespaces][codespaces] は、ブラウザー上でコードの作成、実行、デバッグができるクラウド開発環境です。複数のプログラミング言語、拡張機能、ツールをサポートする、機能豊富な統合開発環境 (IDE) を利用できます。

1. 作成したばかりのリポジトリを開きます。
2. 緑色の **Code** ボタンを選択します。

    ![Code ボタンを選択](../../../_images/ex0-code-button.png)

3. **Codespaces** タブを選択し、**+** ボタンを選択して新しい Codespace を作成します。

    ![新しい Codespace を作成](../../../_images/ex0-create-codespace.png)

Codespace の作成には数分かかりますが、サービスをすべて手作業でインストールするよりはるかに早く完了します。その間、次に紹介する GitHub Copilot の機能を確認できます。

> [!CAUTION]
> 後の演習でこの Codespace に戻ります。今はブラウザーのタブで開いたままにしてください。

> [!NOTE]
> このワークショップは Codespace またはローカルの [開発コンテナー][dev-containers]内で実行するように構成されています。どちらの環境にも、スムーズに作業するために必要な前提条件がすべてインストールされています。ローカルで作業する場合は、クローンしたリポジトリを VS Code で開き、プロンプトが表示されたら **Reopen in Container** を選択します。VS Code が Codespace と同じ開発コンテナーを構築します。

[codespaces]: https://github.com/features/codespaces
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers

## まとめ

これでラボ用リポジトリのコピーを作成し、Copilot クラウドエージェントと作業するときに使う Codespace の作成を開始できました。

## 次のステップ

次に、クラウドエージェントが従うカスタム指示を追加します。[演習 1: カスタム指示][next-lesson]に進みます。

## リソース

- [GitHub Codespaces の概要][codespaces]
- [テンプレートからリポジトリを作成する][template-repository]
- [Codespaces を使ってみる][codespaces-quickstart]

[tailspin-template]: https://github.com/github-samples/tailspin-toys
[template-repository]: https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-template-repository
[codespaces-quickstart]: https://docs.github.com/codespaces/getting-started/quickstart
[next-lesson]: ../1-custom-instructions/
