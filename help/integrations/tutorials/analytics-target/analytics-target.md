---
title: 統合  [!DNL Analytics]  チュートリアル  [!DNL Target]
description: AdobeをAdobeと統合する方法  [!DNL Analytics]  説明し  [!DNL Target] す。
solution: Analytics, Target
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
exl-id: 4ab6c61f-f14e-408a-a700-53f7b3d0600a
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 1%

---

# [!DNL Analytics] と [!DNL Target] の統合


## 統合値と設定

以下のビデオでは、この統合を使用することの価値と、統合の設定に関する詳細を示しています。

>[!NOTE]
>
>これらのビデオでは、[!DNL Target] at.js および appMeasurement.js の実装と検証 [!DNL Analytics] ついて説明します。 両方のツールで必要なライブラリバージョンについては、[ ドキュメント ](https://experienceleague.adobe.com/docs/target/using/integrate/a4t/a4timplementation.html?lang=ja) を参照してください。

### A4T の設定（[!DNL Target] の場合は [!DNL Analytics]）

このビデオでは、開発者向けに、次の方法を説明します。

* SDID を使用して [!DNL Analytics] 要求と [!DNL Target] 要求をバインドする方法を説明する
* Adobe[!DNL Target] （A4T）を使用したAdobe[!DNL Analytics] の実装要件の説明

>[!VIDEO](https://video.tv.adobe.com/v/35146/?quality=12&learn=on)

### [!DNL Analytics] as a Data Source for [!DNL Target] の使用

このビデオでは、ビジネス実務担当者向けに、次の内容を説明します。

* A4T の概要と用途
* A4T の仕組み
* A4T を使用するための前提条件は何ですか？

>[!VIDEO](https://video.tv.adobe.com/v/17384/?quality=12&learn=on)


## よくあるユースケース

以下のビデオでは、A4T 経由で統合する場合の様々な機能、アクティビティタイプ、メリットを示します。

### Analysis Workspaceの [!DNL Analytics] for [!DNL Target] （A4T）パネル

この [!DNL Analytics] for [!DNL Target] （A4T）パネルを使用すると、Analysis Workspaceでリフトと信頼度を使用して、アクティビティ [!DNL Target] エクスペリエンスのAdobeを分析できます。

>[!VIDEO](https://video.tv.adobe.com/v/37247/?quality=12&learn=on)

### A4T パネルを使用した自動 [!DNL Target] 動アクティビティの分析

このビデオでは、[!DNL Analytics] for [!DNL Target] パネルを使用して自動 [!DNL Target] テストの結果を視覚化する方法を説明します。

>[!VIDEO](https://video.tv.adobe.com/v/333270/?quality=12&learn=on)

また、「自動配分」と「自動ターゲット」アクティビティに関する A4T レポートをAnalysis Workspaceで設定する方法の詳細を示す、2 つのステップバイステップのチュートリアルもあります。

## Analysis Workspaceでの自動配分アクティビティ用 A4T レポートの設定 {#a4t-auto-allocate}

自動配分アクティビティは、複数のエクスペリエンスの中から勝者を特定し、より多くのトラフィックをその勝者に自動的に再配分します。その間もテストによる学習は続けられます。 自動配分のための [!DNL Analytics] for [!DNL Target] （A4T）統合により、レポートデータをAdobe[!DNL Analytics] で確認できるほか、[!DNL Analytics] で定義されたカスタムイベントや指標を最適化することもできます。

<a href="https://experienceleague.adobe.com/docs/target-learn/tutorials/integrations/set-up-a4t-reports-in-analysis-workspace-for-auto-allocate-activities.html?lang=ja" class="spectrum-Button spectrum-Button--primary spectrum-Button--sizeM" target="_blank">
  <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 自動配分アクティビティ用の A4T レポートの設定 </span>
</a>

## Analysis Workspaceでの自動 [!DNL Target] 動アクティビティ用 A4T レポートの設定 {#a4t-auto-target}

自動 [!DNL Target] 動アクティビティ用の [!DNL Analytics] for [!DNL Target] （A4T）統合では、Adobe[!DNL Target] アンサンブル機械学習（ML）アルゴリズムを使用して、Adobeと目標指標を使用しながら、プロファイル、行動、コンテキストに基づいて各訪問者に最適なエクスペリエンスを選 [!DNL Analytics] します。

Adobe[!DNL Analytics]Analysis Workspaceには豊富な分析機能が備わっていますが、実験アクティビティ（手動 A/B テストと自動配分）とパーソナライゼーションアクティビティ（自動 [!DNL Target]）の違いにより、自動 [!DNL Target] 分アクティビティを正しく解釈するには、[!DNL Target] のパネルのデフォルト [!DNL Analytics] ードにいくつかの変更を加える必要があります。

<a href="https://experienceleague.adobe.com/docs/target-learn/tutorials/integrations/set-up-a4t-reports-in-analysis-workspace-for-auto-target-activities.html?lang=ja" class="spectrum-Button spectrum-Button--primary spectrum-Button--sizeM" target="_blank">
  <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 自動 [!DNL Target] 動アクティビティ用の A4T レポートの設定 </span>
</a>
