---
title: 統合  [!DNL Analytics]  チュートリアル  [!DNL Commerce]
description: ' [!DNL Commerce] と統合する方法  [!DNL Analytics]  説明します。'
solution: Analytics, Commerce
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: null
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="統合" type="positive"
exl-id: ef50b6b3-1e2b-4fe9-98d5-555bc14ae8d6
source-git-commit: 46803595cf8e199e0c331ea8b82f7fe4a2afc801
workflow-type: tm+mt
source-wordcount: '821'
ht-degree: 0%

---

# [!DNL Analytics] と [!DNL Commerce] の統合

## 初期オンボーディング

これらの手順は、Cloud でホストされるプロジェクト [!DNL Commerce]Adobeするためのものです。 自己ホスト型は、ある程度異なる場合がありますが、全体的なプロセスは似たものになります。

1. ローカル環境でコードをチェックアウトします。
1. Composer の使用とモジュールのインストール
1. ここで個々の指示に従い、完了したら戻って残りの手順を完了します
   [Experience [!DNL Platform] connector のインストールと設定 ](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/fundamentals/install.html){target="_blank"}


1. composer.json をコミットし、cloud の場合は composer.lock ファイル
1. モジュールがステージング環境または実稼動環境（あるいはその両方）にあることを確認します。
これをおこなうには、Adobe[!DNL Commerce] の管理者セクションにログインし、システム/サービスでこれらの新しいセクションを探します
   ![Experience [!DNL Platform] コネクタ拡張機能 ](./assets/analytics-commerce/admin-view-experience-platform-commector-extension.png)

1. バックオフィスのAdobeー内から、資格情報を使用してモジュール [!DNL Commerce] 設定します。
   * まず、以下に示すように、[!DNL Commerce] サービスコネクタの設定を選択します。

     ![[!DNL Commerce] Services コネクタのセットアップ ](./assets/analytics-commerce/commerce-services-connector-setup.png)
   * 次に、以下に示すように、Experience [!DNL Platform] コネクタの設定を行います。

     ![Experience [!DNL Platform] コネクタ ](./assets/analytics-commerce/experience-platform-connector.png)

オンボーディングプロセスの各フェーズと手順について詳しくは、[Experience [!DNL Platform] connector の概要 ](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/overview.html){target="_blank"} の説明に従ってください。 Experience [!DNL Platform] コネクタのチュートリアルでは、各セクションについて詳しく説明し、質問があれば回答します。 残りのクイックセットアップ手順については、このチュートリアルを使用します。

## Experience EdgeとAdobe [!DNL Analytics] の設定

1. 組織がAdobe [!DNL Analytics] へのアクセス権を持っている（またあなたが）ことを確認します。 これは、[Adobe Experience Cloud ホームページに移動し ](https://experience.adobe.com/) 上部のナビゲーションにあるアプリ切り替えボタン（9 つのドット）をクリックして確認できます。

1. Adobe [!DNL Analytics] で新しいレポートスイートを作成するか、データのプッシュ先となるレポートスイートの ID[!DNL Commerce] 特定します。 詳しくは、[ 新しいレポートスイートの作成 ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/analytics-basics/understanding-and-creating-report-suites.html) に関するチュートリアルをご覧ください。 このレポートスイート ID は、以下のデータストリーム手順で必要になります。

1. Experience [!DNL Platform] へのアクセス権がある場合は、[AdobeExperience [!DNL Platform]  インターフェイス ](https://platform.adobe.com) に移動します。 そのインターフェイスにアクセスできない場合は、Adobe Experience [!DNL Platform] [ データ収集インターフェイス ](https://experience.adobe.com/#/data-collection) で、以下に示す必要なすべての手順を実行できます。

1. [!DNL Commerce] 固有のフィールドグループを使用して XDM スキーマを作成または更新します。 スキーマの作成方法について詳しくは、[ 「スキーマの作成」 ](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=ja) チュートリアルを参照してください。
   * 以下のデータストリーム手順のオプションから、このスキーマを選択する必要があります。 スキーマを作成するには、**データ管理** の下の左列を見て、**スキーマ** を見つけます。 インターフェイスの右上で、「**スキーマを作成**」をクリックします。 XDM ExperienceEvent を選択します。
   * 新しいスキーマを作成したら、[!DNL Commerce] のフィールドグループを追加します。 UI の左側で、「フィールドグループ」を見つけて、「**追加**」をクリックします
      * 検索では、`ExperienceEvent Commerce` と入力してフィルタリングできます。
      * チェックボックスをオンにして、**Adobe[!DNL Analytics]ExperienceEvent[!DNL Commerce]** を選択します
      * 次に、右上の **フィールドグループを追加** をクリックして、保存して続行します

1. オプション（Experience [!DNL Platform] インターフェイスにいる場合のみ） – 新しいデータセットを作成します
   * この手順では、[!DNL Commerce] のデータを Experience [!DNL Platform] に取り込むことができます（データをAdobe [!DNL Analytics] に取り込むのとは別に）。 この手順を実行するのは、Experience [!DNL Platform] へのアクセス権を持ち、Experience [!DNL Platform] をサポートするアプリケーション（Real-time Customer Data [!DNL Platform]、カスタマージャーニー [!DNL Analytics]、Journey Optimizerなど）で [!DNL Commerce] データを使用する予定がある場合です。
   * 以下のデータストリーム手順のオプションから、このデータセットを選択する必要があります。
   * 左側のナビゲーションの左列 **データ管理** 見出しの下で、「**データセット**」を選択します。
   * 右上の **データセットを作成** をクリックします。 「**スキーマからデータセットを作成**」オプションを選択します。
   * 前の手順で作成したスキーマを検索して使用します

1. データストリームを作成し、[!DNL Commerce] データをAdobe[!DNL Analytics] に送信します。
   * 左側の列の「**データ収集**」見出しの下で、「**データストリーム**」を選択します。
   * インターフェイスの右上にある **新規データストリーム** をクリックします。
   * 名前と説明（オプション）を入力します。
   * 前の手順で作成または識別したスキーマを検索して選択します。
   * 必要な詳細オプションを追加します。 詳細設定オプションについて詳しくは、[ ドキュメント ](https://experienceleague.adobe.com/docs/experience-platform/datastreams/configure.html?lang=ja) を参照してください。
   * 「**保存**」をクリックして続行します。
   * **サービスを追加** をクリックし、ドロップダウンフィールドで **Adobe[!DNL Analytics]** を選択します。
   * 「**レポートスイートを追加**」をクリックし、前の手順で作成または識別したレポートスイート ID を入力します。 データを複数のレポートスイートに送りたい場合は、複数のレポートスイートを追加できます。
   * オプションで、前の手順でデータセットを作成した場合は、**サービスを追加** を再度クリックし、ドロップダウンフィールドから **Adobeエクスペリエンス[!DNL Platform]** を選択します。 「イベントデータセット」フィールドで、前に作成したデータセットを選択します。
   * データストリームを保存します。

1. 最後に、[!DNL Commerce] データを表示するには、Adobe[!DNL Analytics] でAnalysis Workspaceに移動し、プロジェクトを作成し、レポートスイートを選択し、フリーフォームテーブルやその他のビジュアライゼーションを追加して、[!DNL Commerce] データのレポートと分析を行う必要があります。 次の画像は、Analysis Workspaceで作成できるテーブルの例を示しています。

   一部 ![[!DNL Analytics] コマースデータのスクリーンショット ](./assets/analytics-commerce/analytics-screenshot-commerce-items.png)

   Analysis Workspaceでの作業に役立つその他のリソースを次に示します。

   * [Analysis Workspace の概要](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-overview.html)
   * [Workspace プロジェクトを一から作成する ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/building-a-workspace-project-from-scratch.html)
   * [Analysis Workspaceでのテーブル、ビジュアライゼーション、パネルの使用 ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/using-tables-visualizations-and-panels.html)
   * [ ビジュアライゼーションの使用例 ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/visualization-use-cases.html)

   さらに、Experience Leagueで利用できる無料コースがあります。 ご利用 [!DNL Analytics] きるコースを [ こちら ](https://experienceleague.adobe.com/?lang=en&amp;Solution=Analytics#courses) ご覧ください。
