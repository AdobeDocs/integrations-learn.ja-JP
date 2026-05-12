---
title: Adobe [!DNL Analytics] とカスタマージャーニー [!DNL Analytics] をExperience [!DNL Platform] Edge チュートリアルと統合する
description: AEP Web SDK、AEP Mobile SDK、またはEdge Network Server APIを使用して、Adobe [!DNL Analytics] をお客様のジャーニー [!DNL Analytics] と統合する方法について説明します。
solution: Customer Journey Analytics, Analytics
feature: Integrations
topic: Integrations
role: Developer
level: Experienced
index: true
kt: null
thumbnail: 13728
last-substantial-update: 2023-04-11T00:00:00.000Z
badgeIntegration: label="統合" type="positive"
exl-id: e39dac5d-6ad5-47c8-94e8-070011233161
TQID: https://experienceleague.adobe.com/ClZddWXeWp51gWTBjRDQBZ2xNiO1bTRq-AoAdmucNEg
product_v2:
  - id: e55547f1-a1ff-40c6-8978-026e40ab7fa4
  - id: e98b7246-966c-4318-9e95-cad2f7a17dc7
feature_v2:
  - id: b3f03848-ae12-48b2-8aab-cad18567eb32
  - id: e75a4a9c-d354-4ca4-9b02-1afeca73fa5e
  - id: eb9732ab-8232-4b21-bc4c-89de86dbe4d7
  - id: fd307ce7-56f5-4ee3-af68-a7833ff6e85e
subfeature_v2:
  - id: e6c28e30-8689-4bf4-8fa8-561343d308a9
role_v2:
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
source-git-commit: 2a324011b3d235db3d4642c2797c4fa107267e6a
workflow-type: tm+mt
source-wordcount: 413
ht-degree: 16%

---

# Adobe [!DNL Analytics]とカスタマージャーニー [!DNL Analytics]をExperience [!DNL Platform] Edge チュートリアルと統合する

<ol>
    <li>取り込むデータの<a href="https://experienceleague.adobe.com/ja?lang=ja#dashboard/learning" _target="_blank" rel="noopener noreferrer"> スキーマ </a>を作成します。</li>
    <li>取り込むデータの<a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html?lang=ja" _target="_blank" rel="noopener noreferrer"> データセット </a>を作成します。</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=ja" _target="_blank" rel="noopener noreferrer">取り込んだデータを統合プロファイルに結合できるように、スキーマ </a>で正しいIDとID名前空間を設定します。</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=ja" _target="_blank" rel="noopener noreferrer"> プロファイル </a>のスキーマとデータセットを有効にします。</li>
    <li>次のいずれかの方法を使用して、データをExperience [!DNL Platform]に取り込みます。</li>
        <ul>
            <li>[!DNL Platform] Web SDKを体験：</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html?lang=ja" _target="_blank" rel="noopener noreferrer">チュートリアル</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/web-sdk/overview.html?lang=ja" _target="_blank" rel="noopener noreferrer">チェックリスト</a></li>
                </ul>
            <li>[!DNL Platform] Mobile SDKを体験：</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/create-mobile-properties.html?lang=ja" _target="_blank" rel="noopener noreferrer">チュートリアル</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/mobile-sdk/overview.html?lang=ja" _target="_blank" rel="noopener noreferrer">チェックリスト</a></li>
                </ul></li>
            <li>Edge Network Server API:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/experience-platform/edge-network-server-api/interacting-other-adobe-solutions/interacting-adobe-analytics.html?lang=ja" _target="_blank" rel="noopener noreferrer">チュートリアル</a></li>
                </ul>
       </ul>
    <li><i> （オプション） </i>。 複数のデータセットを使用する場合は、個人IDをつなぎ合わせて<a href="https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/combined-dataset.html?lang=ja" _target="_blank" rel="noopener noreferrer">結合データセットを生成</a>します。 1つの[!DNL Analytics] データセットを使用している場合、またはお客様のジャーニー [!DNL Analytics]で使用する予定のすべてのデータセットに共通のIDが存在する場合は、この手順をスキップしてください。</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=ja" _target="_blank" rel="noopener noreferrer">お客様のジャーニー [!DNL Analytics]で接続</a>を作成します。</li>
    <li>顧客ジャーニー [!DNL Analytics]で<a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/basic-configuration-for-data-views.html?lang=ja" _target="_blank" rel="noopener noreferrer"> データビューを作成</a>、<a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configuring-component-settings-in-data-views.html?lang=ja" _target="_blank" rel="noopener noreferrer"> コンポーネント設定</a>および<a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/formatting-metrics-in-data-views.html?lang=ja" _target="_blank" rel="noopener noreferrer">形式の指標</a>を設定します。
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/workspace-projects/build-a-new-project.html?lang=ja" _target="_blank" rel="noopener noreferrer">カスタマージャーニー [!DNL Analytics]でプロジェクトを作成します。</a></li>
</ol>

>[!NOTE]
>
>Adobe [!DNL Analytics] ソースコネクタの標準ワークフローステップでは、[!DNL Analytics]から「そのまま」データを取り込むために使用するスキーマとデータセットを作成します。 したがって、最初の2つのステップはシステムによって処理されます。 マッピングワークフローでは、カスタム属性を作成する必要があります。したがって、手順の順序に完全に従ってください。
