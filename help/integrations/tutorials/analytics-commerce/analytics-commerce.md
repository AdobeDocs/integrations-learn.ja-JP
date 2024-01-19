---
title: 統合 [!DNL Analytics] 次を使用 [!DNL Commerce] チュートリアル
description: ' [!DNL Analytics] と [!DNL Commerce] を統合する方法について説明します。'
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
ht-degree: 3%

---

# [!DNL Analytics] と [!DNL Commerce] の統合

## 初回オンボーディング

これらの手順はAdobe用です [!DNL Commerce] クラウドがホストするプロジェクト。 自己ホスト型は、ある程度異なる場合がありますが、全体的なプロセスは同じである必要があります。

1. ローカル環境でコードを確認する
1. コンポーザーとインストールモジュールの使用
1. ここで示す個々の手順に従い、完了したら戻って残りの手順を完了します。
   [エクスペリエンスのインストールと設定 [!DNL Platform] コネクタ](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/fundamentals/install.html){target="_blank"}


1. composer.json をコミットし、クラウド上の場合は composer.lock ファイルをコミットします。
1. モジュールがステージング環境または実稼動環境にあることを確認します。確認するには、Adobeの admin セクションにログインします [!DNL Commerce] 新しいセクションを探すには、 System > Services を選択します。
   ![エクスペリエンス [!DNL Platform] コネクタ拡張](./assets/analytics-commerce/admin-view-experience-platform-commector-extension.png)

1. Adobe内からの資格情報を使用してモジュールを設定します。 [!DNL Commerce] バックオフィス。
   * 1 つ目の [!DNL Commerce] サービスコネクタの設定（下図を参照）。
     ![[!DNL Commerce] Services Connector の設定](./assets/analytics-commerce/commerce-services-connector-setup.png)
   * 次に、エクスペリエンス [!DNL Platform] コネクタ設定を表示します（下図を参照）。
     ![エクスペリエンス [!DNL Platform] コネクタ](./assets/analytics-commerce/experience-platform-connector.png)

オンボーディングプロセスの各フェーズと手順の詳細については、 [エクスペリエンス [!DNL Platform] コネクタの概要](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/overview.html?lang=ja){target="_blank"}. エクスペリエンス [!DNL Platform] コネクタのチュートリアルでは、各節について詳しく説明し、必要な質問に答えます。 このチュートリアルを使用して、残りのクイックセットアップ手順を実行します。

## Experience Edge とAdobeの設定 [!DNL Analytics]

1. 組織がAdobeへのアクセス権を持っている（および持っている）ことを確認します。 [!DNL Analytics]. これは、 [Adobe Experience Cloudホームページ](https://experience.adobe.com/) をクリックし、上部のナビゲーションでアプリケーション切り替えボタン（9 つのドット）をクリックします。

1. Adobeでの新しいレポートスイートの作成 [!DNL Analytics]または、プッシュするレポートスイートの ID を特定します。 [!DNL Commerce] データをに送信します。 詳しくは、 [新しいレポートスイートの作成](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/analytics-basics/understanding-and-creating-report-suites.html?lang=ja). このレポートスイート ID は、以下のデータストリーム手順で必要になります。

1. 次に移動： [Adobe体験 [!DNL Platform] インターフェイス](https://platform.adobe.com) Experience にアクセスできる場合 [!DNL Platform]. そのインターフェイスにアクセスできない場合は、Adobeエクスペリエンスで以下に示す必要な手順をすべて実行できます [!DNL Platform] [データ収集インターフェイス](https://experience.adobe.com/#/data-collection).

1. で XDM スキーマを作成または更新します。 [!DNL Commerce] — 特定のフィールドグループ。 スキーマの作成方法について詳しくは、 [「スキーマの作成」](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=ja) チュートリアル
   * このスキーマは、以下のデータストリーム手順のオプションから選択する必要があります。 スキーマを作成するには、左の列のを見て、 **データ管理** 検索 **スキーマ**. インターフェイスの右上で、 **スキーマを作成**. 「XDM ExperienceEvent」を選択します。
   * 新しいスキーマを作成した後、 [!DNL Commerce] フィールドグループを使用します。 UI の左側で、フィールドグループを探し、 **追加**
      * 検索では、 `ExperienceEvent Commerce`
      * を選択します。 **Adobe [!DNL Analytics] ExperienceEvent[!DNL Commerce]** ボックスをオンにして
      * 次に、「 **フィールドグループを追加** 右上で保存して続行する

1. オプション（エクスペリエンスにいる場合のみ） [!DNL Platform] インターフェイス ) — 新しいデータセットの作成
   * この手順では、 [!DNL Commerce] データを Experience に送信 [!DNL Platform] ( データをAdobeに移行するのとは別に ) [!DNL Analytics]) をクリックします。 エクスペリエンスへのアクセス権がある場合は、この手順を実行します。 [!DNL Platform]を使用し、 [!DNL Commerce] エクスペリエンス内のデータ [!DNL Platform] — リアルタイム顧客データなどのサポート対象のアプリケーション [!DNL Platform]、顧客ジャーニー [!DNL Analytics]、またはJourney Optimizer
   * このデータセットは、以下のデータストリーム手順のオプションから選択する必要があります。
   * 左の列の下 **データ管理** 左側のナビゲーションの見出しで、「 **データセット**.
   * クリック **データセットを作成** を右上に表示します。 を選択します。 **スキーマからデータセットを作成** オプション。
   * 前の手順で作成したスキーマを検索して使用します。

1. データストリームを作成し、 [!DNL Commerce] データからAdobe [!DNL Analytics]
   * の下 **データ収集** 左の列の見出しで、「 」を選択します。 **データストリーム**.
   * クリック **新規データストリーム** をクリックします。
   * 名前と説明（オプション）を入力します。
   * 前の手順で作成または識別したスキーマを見つけて選択します。
   * 必要に応じて、詳細設定オプションを追加します。 アドバンスオプションの詳細については、 [ドキュメント](https://experienceleague.adobe.com/docs/experience-platform/datastreams/configure.html?lang=ja).
   * クリック **保存** をクリックして続行します。
   * クリック **サービスを追加** を選択します。 **Adobe[!DNL Analytics]** 」と入力します。
   * クリック **レポートスイートの追加** をクリックし、前の手順で作成または識別したレポートスイート ID を入力します。 データを複数のレポートスイートに表示する場合は、複数のレポートスイートを追加できます。
   * （オプション）前の手順でデータセットを作成した場合は、 **サービスを追加** 再び選択 **Adobe体験[!DNL Platform]** 」をクリックします。 「イベントデータセット」フィールドで、以前に作成したデータセットを選択します。
   * データストリームを保存します。

1. 最後に、 [!DNL Commerce] データを使用する場合は、AdobeでAnalysis Workspaceに移動する必要があります [!DNL Analytics]、プロジェクトを作成、レポートスイートを選択、フリーフォームテーブルやその他のビジュアライゼーションを追加して、レポートおよび分析します [!DNL Commerce] データ。 次の図は、Analysis Workspaceで作成できるテーブルの例を示しています。

   ![[!DNL Analytics] 一部のコマースデータのスクリーンショット](./assets/analytics-commerce/analytics-screenshot-commerce-items.png)

   以下に、Analysis Workspaceでの作業に役立つその他のリソースを示します。

   * [Analysis Workspace の概要](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-overview.html)
   * [Workspace プロジェクトを一から作成する](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/building-a-workspace-project-from-scratch.html)
   * [Analysis Workspace でのテーブル、ビジュアライゼーション、パネルの使用](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/using-tables-visualizations-and-panels.html)
   * [ビジュアライゼーションの使用例](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/visualization-use-cases.html)

   また、無料コースもExperience League。 詳しくは、 [!DNL Analytics] 利用可能なコース [ここ](https://experienceleague.adobe.com/?lang=en&amp;Solution=Analytics#courses).
