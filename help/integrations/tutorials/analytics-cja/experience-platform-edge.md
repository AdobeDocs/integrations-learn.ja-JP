---
title: Adobeお  [!DNL Analytics]  び顧客ジャーニーと Experience [!DNL Analytics] 2&rbrace;Edge チュートリアルの統合 [!DNL Platform]
description: AEP Web SDK [!DNL Analytics] AEP Mobile SDK、またはEdge Networkサーバー API を使用して、Adobeをカスタマージャーニー [!DNL Analytics]  統合する方法について説明します。
solution: Customer Journey [!DNL Analytics], [!DNL Analytics]
feature: Integrations
topic: Integrations
role: Developer
level: Experienced
index: true
hidefromtoc: true
kt: null
thumbnail: 13728
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="統合" type="positive"
exl-id: e39dac5d-6ad5-47c8-94e8-070011233161
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '236'
ht-degree: 3%

---

# Experience [!DNL Platform] Edge チュートリアルを使用したAdobe[!DNL Analytics] ースとカスタマージャーニー[!DNL Analytics] ールの統合

<ol>
    <li>取り込むデータの <a href="https://experienceleague.adobe.com/ja?lang=ja#dashboard/learning" _target="_blank" rel="noopener noreferrer"> スキーマを作成 </a> します。</li>
    <li>取り込むデータの <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html?lang=ja" _target="_blank" rel="noopener noreferrer"> データセットを作成 </a> します。</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=ja" _target="_blank" rel="noopener noreferrer"> スキーマ上で正しい ID と ID 名前空間を設定して </a> 取り込まれたデータが統合プロファイルにステッチできることを確認します。</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=ja" _target="_blank" rel="noopener noreferrer"> プロファイルのスキーマとデータセットを有効にします </a>。</li>
    <li>次のいずれかの方法を使用して、Experience [!DNL Platform] にデータを取り込みます。</li>
        <ul>
            <li>Experience [!DNL Platform] Web SDK:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html?lang=ja" _target="_blank" rel="noopener noreferrer">チュートリアル</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/web-sdk/overview.html?lang=ja" _target="_blank" rel="noopener noreferrer">Checklist</a></li>
                </ul>
            <li>Experience [!DNL Platform] Mobile SDK:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/create-mobile-properties.html?lang=ja" _target="_blank" rel="noopener noreferrer">チュートリアル</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/mobile-sdk/overview.html?lang=ja" _target="_blank" rel="noopener noreferrer">Checklist</a></li>
                </ul></li>
            <li>Edge Networkサーバー API:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/experience-platform/edge-network-server-api/interacting-other-adobe-solutions/interacting-adobe-analytics.html" _target="_blank" rel="noopener noreferrer">チュートリアル</a></li>
                </ul>
       </ul>
    <li><i> （オプション） </i>. 複数のデータセットを使用する場合は、ユーザー ID をステッチして <a href="https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/combined-dataset.html?lang=ja" _target="_blank" rel="noopener noreferrer"> 結合されたデータセットを生成 </a> します。 1 つの [!DNL Analytics] データセットを使用する場合、または顧客ジャーニー[!DNL Analytics] で使用するすべてのデータセットに共通の ID が存在する場合、この手順はスキップします。</li>
    <li>カスタマージャーニー[!DNL Analytics] ージで <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=ja" _target="_blank" rel="noopener noreferrer"> 接続を作成 </a> します。</li>
    <li>カスタマージャーニー [!DNL Analytics] ークフローで <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/basic-configuration-for-data-views.html?lang=ja" _target="_blank" rel="noopener noreferrer"> データビューの作成 </a>、<a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configuring-component-settings-in-data-views.html?lang=ja" _target="_blank" rel="noopener noreferrer"> コンポーネント設定の指定 </a>、および <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/formatting-metrics-in-data-views.html?lang=ja" _target="_blank" rel="noopener noreferrer"> フォーマット指標 </a> を行います。
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/workspace-projects/build-a-new-project.html?lang=ja" _target="_blank" rel="noopener noreferrer">顧客ジャーニー[!DNL Analytics] でプロジェクトを作成します。</a></li>
</ol>

>[!NOTE]
>
>ソースコネクタ [!DNL Analytics]Adobeの標準的なワークフロー手順では、「そのまま」のデータの取り込みに使用するスキーマ [!DNL Analytics] データセットを作成します。 したがって、最初の 2 つの手順はシステムで処理されます。 マッピングワークフローでは、カスタム属性の作成が必要なため、一連の手順に完全に従ってください。
