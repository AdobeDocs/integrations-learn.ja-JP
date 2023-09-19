---
source-git-commit: ed53392381fa568de8230288e6b85c87540222cf
workflow-type: tm+mt
source-wordcount: '424'
ht-degree: 100%

---
# 記事のコントリビューション

アドビのコミュニティはもとより、ドキュメントチーム外部のアドビ従業員からのコントリビューションもお待ちしています。

## アドビのオープンソースの行動規範

このプロジェクトでは、[アドビのオープンソースの行動規範](code-of-conduct.md)または [.NET Foundation Code of Conduct](https://dotnetfoundation.org/code-of-conduct)（英語）を採用しています。詳しくは、[コントリビューション](contributing.md)の記事を参照してください。

## アドビのコンテンツへのコントリビューションについて

[アドビドキュメントのコントリビューターガイド](https://experienceleague.adobe.com/docs/contributor/contributor-guide/introduction.html?lang=ja)を参照してください。

コントリビューションの方法は、誰がどのような変更をコントリビューションするかに応じて異なります。

### 軽微な変更

軽微な変更をコントリビューションする場合には、目的の記事にアクセスし、**Edit** リンクをクリックしてください。当該記事の GitHub ソースが開きます。その後、GitHub UI を使用して更新を行います。詳しくは、全般的な事項について説明した[アドビドキュメントのコントリビューターガイド](https://experienceleague.adobe.com/docs/contributor/contributor-guide/introduction.html?lang=ja)を参照してください。

このリポジトリー内のドキュメントやコード例に対して提案される軽微な変更や補足説明には、アドビの利用規約が適用されます。

### コミュニティメンバーによる大幅な変更または新しい記事

アドビコミュニティのメンバーが新しい記事を作成したり、大幅な変更をコントリビューションしたりする場合は、Git リポジトリーの「Issues」タブを使用してイシューを送信し、ドキュメントチームとのやり取りを開始してください。計画に同意したら、アドビ従業員と協力し、公開リポジトリーと非公開リポジトリー内の作業結果を組み合わせて新しいコンテンツを取り込むのを手伝う必要があります。

<!--
If you submit a pull request with significant changes to documentation and code examples, you'll see a message in the pull request asking you to submit an online contribution license agreement (CLA). We need you to complete the online form before we can review your pull request.
-->

### アドビ従業員による大幅な変更

Adobe Experience Cloud ソリューションの製品チームに所属するテクニカルライター、プログラムマネージャー、開発者が業務の一環として技術的記事にコントリビューションしたり、技術的記事を作成したりする場合は、`https://git.corp.adobe.com/AdobeDocs` の非公開リポジトリーを使用してください。

<!--Employees from other parts of the Adobe world should use the public repo for minor updates.-->

## ツールとセットアップ

コミュニティのコントリビューターは、基本的な編集をするときには GitHub の UI を使用し、大きな変更を加えるときにはリポジトリーをフォークします。

詳しくは、[アドビドキュメントのコントリビューターガイド](https://experienceleague.adobe.com/docs/contributor/contributor-guide/introduction.html?lang=ja)を参照してください。

## Markdown を使用してトピックをフォーマットする方法

このリポジトリーの記事はいずれも GitHub Flavored Markdown（GFM）を使用して書かれています。Markdown について詳しくない場合は、以下を参照してください。

* [Markdown の基本](https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/)（英語）
* [印刷可能な Markdown のクイックリファレンス](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)（英語）

## ラベル

公開リポジトリーでは、プルリクエストに以下のような自動ラベルが割り当てられ、プルリクエストワークフローの管理とプルリクエストの処理状況の把握に役立ちます。

* **Change sent to author**：保留中のプルリクエストの通知が作成者に送信されました。
* **ready- to- merge**：プルリクエストレビューチームによるレビューの準備ができました。