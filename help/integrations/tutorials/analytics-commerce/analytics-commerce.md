---
title: ' [!DNL Analytics] と [!DNL Commerce]  チュートリアルの統合'
description: ' [!DNL Analytics] と [!DNL Commerce]の統合方法について説明します。'
solution: Analytics, Commerce
feature: Integrations
topic: Integrations
role: Leader, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: null
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="統合" type="positive"
exl-id: ef50b6b3-1e2b-4fe9-98d5-555bc14ae8d6
source-git-commit: 7fffc0b887164645ab16fe94d2f82a657fcc9d64
workflow-type: tm+mt
source-wordcount: '932'
ht-degree: 2%

---

# [!DNL Analytics]と[!DNL Commerce]の統合

## 初期オンボーディング

これらの手順は、Adobe [!DNL Commerce] Cloudでホストされているプロジェクト用です。 セルフホスティングの手法は、ビジネスニーズによって異なります。しかし、全体的なプロセスは類似している必要があります。

1. ローカル環境でコードをチェックアウトする
1. コンポーザーとインストールモジュールの使用
1. ここで個々の指示に従い、完了したら戻って残りの手順を完了します
   [Experience [!DNL Platform]  コネクタ &#x200B;](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/fundamentals/install.html?lang=ja){target="_blank"}をインストールして設定します


1. composer.jsonをコミットし、クラウド上の場合はcomposer.lock ファイルをコミットします
1. モジュールがステージング環境または実稼動環境にあることを確認します
これを行うには、Adobe [!DNL Commerce]の管理セクションにログインし、システム/サービスの下でこれらの新しいセクションを探します
   ![&#x200B; エクスペリエンス [!DNL Platform] コネクタ拡張機能](./assets/analytics-commerce/admin-view-experience-platform-commector-extension.png)

1. Adobe [!DNL Commerce] バックオフィス内から資格情報を使用してモジュールを設定します。
   * 最初に、以下に示すように、[!DNL Commerce] サービスコネクタの設定を行います。
     ![[!DNL Commerce] サービスコネクタの設定](./assets/analytics-commerce/commerce-services-connector-setup.png)
   * 次に、次に示すように、Experience [!DNL Platform] コネクタの設定を行います。
     ![&#x200B; エクスペリエンス [!DNL Platform] コネクタ &#x200B;](./assets/analytics-commerce/experience-platform-connector.png)

オンボーディングプロセスの各フェーズと手順の詳細については、[Experience [!DNL Platform]  コネクタの概要](https://experienceleague.adobe.com/docs/commerce-merchant-services/experience-platform-connector/overview.html?lang=ja){target="_blank"}の手順に従ってください。 Experience [!DNL Platform] コネクタのチュートリアルでは、各セクションについて詳しく説明し、質問に答えることができます。 残りのクイック設定手順については、このチュートリアルを使用してください。

## Experience EdgeとAdobeの設定[!DNL Analytics]

1. お客様の組織がAdobe [!DNL Analytics]へのアクセス権を持っている（および持っている）ことを確認します。 これは、[Adobe Experience Cloudのホームページ &#x200B;](https://experience.adobe.com/)に移動し、上部ナビゲーションのアプリケーションスイッチャー（9つのドット）をクリックすることで確認できます。

1. Adobe [!DNL Analytics]で新しいレポートスイートを作成するか、[!DNL Commerce] データをプッシュするレポートスイートのIDを特定します。 詳しくは、[新しいレポートスイートの作成](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/analytics-basics/understanding-and-creating-report-suites.html?lang=ja)に関するチュートリアルをご覧ください。 以下のデータストリーム手順で、このレポートスイート IDが必要になります。

1. Experience [!DNL Platform]へのアクセス権がある場合は、[Adobe Experience [!DNL Platform]  インターフェイス &#x200B;](https://platform.adobe.com)に移動します。 そのインターフェイスにアクセスできない場合は、Adobe Experience [!DNL Platform] [Data Collection インターフェイス &#x200B;](https://experience.adobe.com/#/data-collection)で、次に示す必要なすべての手順を実行できます。

1. [!DNL Commerce]固有のフィールドグループを使用してXDM スキーマを作成または更新します。 スキーマの作成方法について詳しくは、[&#x200B; 「スキーマの作成」 &#x200B;](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=ja) チュートリアルを参照してください。
   * このスキーマは、以下のデータストリーム手順のオプションから選択する必要があります。 スキーマを作成するには、**データ管理**&#x200B;の下の左側の列で&#x200B;**スキーマ**&#x200B;を見つけます。 インターフェイスの右上にある「**スキーマを作成**」をクリックします。 XDM ExperienceEventを選択します。
   * 新しいスキーマを作成した後、[!DNL Commerce] フィールドグループを追加します。 UIの左側で、「フィールドグループ」を見つけて、**追加**&#x200B;をクリックします
      * 検索では、`ExperienceEvent Commerce`と入力してフィルタリングできます
      * チェックボックスをオンにして、**Adobe [!DNL Analytics] ExperienceEvent[!DNL Commerce]**&#x200B;を選択します
      * 次に、右上の&#x200B;**フィールドグループを追加**&#x200B;をクリックして保存し、続行します

1. オプションで（Experience [!DNL Platform] インターフェイスを使用している場合のみ） – 新しいデータセットを作成します
   * この手順を使用すると、[!DNL Commerce] データをExperience [!DNL Platform]に取り込むことができます（データをAdobe [!DNL Analytics]に取り込むとは別）。 Experience [!DNL Platform]へのアクセス権があり、Real-Time Customer Data [!DNL Platform]、カスタマージャーニー [!DNL Analytics]、Journey Optimizerなど、Experience [!DNL Platform]でサポートされているアプリケーションで[!DNL Commerce] データを使用することを計画している場合は、この手順を実行します。
   * 以下のデータストリーム手順のオプションから、このデータセットを選択する必要があります。
   * 左側のナビゲーションの左側の列&#x200B;**データ管理**&#x200B;の見出しの下で、**データセット**&#x200B;を選択します。
   * 右上の「**データセットを作成**」をクリックします。 「**スキーマからデータセットを作成**」オプションを選択します。
   * 最後の手順で作成したスキーマを検索して使用します

1. データストリームを作成して、[!DNL Commerce] データをAdobe [!DNL Analytics]に送信します
   * 左側の列の&#x200B;**データ収集**&#x200B;見出しの下で、**データストリーム**&#x200B;を選択します。
   * インターフェイスの右上にある「**新しいデータストリーム**」をクリックします。
   * 名前とオプションの説明を入力します。
   * 前の手順で作成/識別したスキーマを検索して選択します。
   * 必要に応じて詳細オプションを追加します。 詳細オプションについて詳しくは、[&#x200B; ドキュメント &#x200B;](https://experienceleague.adobe.com/docs/experience-platform/datastreams/configure.html?lang=ja)を参照してください。
   * **保存**&#x200B;をクリックして続行します。
   * 「**サービスを追加**」をクリックし、ドロップダウンフィールドで「**Adobe[!DNL Analytics]**」を選択します。
   * 「**レポートスイートを追加**」をクリックし、前の手順で作成または識別したレポートスイート IDを入力します。 複数のレポートスイートにデータを流し込む場合は、複数のレポートスイートを追加できます。
   * 必要に応じて、前の手順でデータセットを作成した場合は、ドロップダウンフィールドから&#x200B;**Adobe Experience[!DNL Platform]**&#x200B;を選択して、**Add Service**&#x200B;をもう一度クリックします。 「イベントデータセット」フィールドで、以前に作成したデータセットを選択します。
   * データストリームを保存します。

1. 最後に、[!DNL Commerce] データを表示するには、Adobe [!DNL Analytics]でAnalysis Workspaceに移動し、プロジェクトを作成し、レポートスイートを選択し、フリーフォームテーブルやその他のビジュアライゼーションを追加して、[!DNL Commerce] データをレポートおよび分析する必要があります。 次の図は、Analysis Workspaceで作成できるテーブルの一例を示しています。

   ![[!DNL Analytics] コマースデータのスクリーンショット &#x200B;](./assets/analytics-commerce/analytics-screenshot-commerce-items.png)

   ここでは、Analysis Workspaceを活用するための資料をいくつか紹介します。

   * [Analysis Workspaceの概要](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-overview.html?lang=ja)
   * [Workspaceプロジェクトをゼロから構築](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/building-a-workspace-project-from-scratch.html?lang=ja)
   * [Analysis Workspaceでのテーブル、ビジュアライゼーションおよびパネルの使用](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/using-tables-visualizations-and-panels.html?lang=ja)
   * [視覚化のユースケース](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/visualization-use-cases.html?lang=ja)

   さらに、Experience Leagueでは無料のコースを利用できます。 利用可能な[!DNL Analytics]件のコース [こちら](https://experienceleague.adobe.com/ja?lang=en&Solution=Analytics#courses)を参照してください。
