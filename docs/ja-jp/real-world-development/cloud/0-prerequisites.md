---
title: "演習 0: 前提条件"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

Copilot クラウド エージェントの演習を始める前に、必要なものを準備します。Tailspin Toys リポジトリのコピーを作成し、[codespace][codespaces] を起動します。この環境で指示ファイルを編集し、クラウド エージェントの作業をレビューします。

## ワークショップ用リポジトリを設定する

コードを作成するためのリポジトリのコピーとして、[テンプレート][template-repository]からインスタンスを作成します。新しいインスタンスにはワークショップに必要なファイルがすべて含まれ、演習を進める間に使用します。

1. 新しいブラウザー ウィンドウで、[Tailspin Toys テンプレート][tailspin-template]に移動します。
2. ワークショップ リポジトリのページで **Use this template** ボタンを選択し、**Create a new repository** を選択してリポジトリのコピーを作成します。

    ![Use this template ボタン](../../../_images/ex0-use-template.png)

3. GitHub または Microsoft が主催するイベントでワークショップに参加する場合は、メンターの指示に従います。それ以外の場合は、GitHub Copilot にアクセスできる組織に新しいリポジトリを作成します。

    ![リポジトリ テンプレートの設定を入力する画面](../../../_images/ex0-repository-settings.png)

4. 後で参照するため、作成したリポジトリのパス (**organization-or-user-name/repository-name**) を控えておきます。

## codespace を作成する

次に、codespace を使って演習を進めます。

[GitHub Codespaces][codespaces] は、ブラウザーで直接コードの作成、実行、デバッグができるクラウド ベースの開発環境です。複数のプログラミング言語、拡張機能、ツールに対応する、フル機能の IDE を利用できます。

1. 作成したリポジトリに移動します。
2. 緑色の **Code** ボタンを選択します。

    ![Code ボタンを選択する](../../../_images/ex0-code-button.png)

3. **Codespaces** タブを選択し、**+** ボタンを選択して新しい Codespace を作成します。

    ![新しい codespace を作成する](../../../_images/ex0-create-codespace.png)

codespace の作成には数分かかりますが、すべてのサービスを手動でインストールするよりもはるかに短時間で済みます。待っている間に GitHub Copilot の他の機能を確認してみましょう。次のステップで紹介します。

> [!CAUTION]
> 今後の演習で codespace に戻ります。今はブラウザーのタブで開いたままにしてください。

> [!NOTE]
> このワークショップは、codespace またはローカルの [dev container][dev-containers] 内で実行できるように構成されています。どちらの環境にも、スムーズに進めるために必要な前提条件がすべてインストールされています。ローカルで実行する場合は、クローンしたリポジトリを VS Code で開き、プロンプトが表示されたら **Reopen in Container** を選択します。codespace と同じ dev container が VS Code によってビルドされます。

[codespaces]: https://github.com/features/codespaces
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers

## まとめ

ワークショップ用リポジトリのコピーを作成し、codespace の作成を開始しました。この環境で Copilot クラウド エージェントと作業します。

## 次のステップ

クラウド エージェントが従うカスタム指示を追加します。[演習 1 - カスタム指示][next-lesson]に進みます。

## リソース

- [GitHub Codespaces の概要][codespaces]
- [テンプレートからリポジトリを作成する][template-repository]
- [Codespaces の使用を開始する][codespaces-quickstart]

[tailspin-template]: https://github.com/github-samples/tailspin-toys
[template-repository]: https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-template-repository
[codespaces-quickstart]: https://docs.github.com/codespaces/getting-started/quickstart
[next-lesson]: ../1-custom-instructions/
