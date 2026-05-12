---
title: Experience [!DNL Platform] Edge チュートリアルで [!DNL Analytics] とReal-Time Customer Data [!DNL Platform] を統合する
description: AEP Web SDK、AEP Mobile SDK、またはEdge Network Server APIを使用して、Adobe [!DNL Analytics] とReal-Time Customer Data [!DNL Platform] を統合する方法について説明します。
solution: Real-Time Customer Data Platform, Analytics
feature: Integrations
topic: Integrations
role: Developer
level: Experienced
index: true
kt: 13732
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00.000Z
badgeIntegration: label="統合" type="positive"
exl-id: 07c2c329-0810-4f66-a91a-e315695f3fb4
TQID: https://experienceleague.adobe.com/K1CpRtUekl5jQNDMGswJpexC9fv9uVmgraLlNFXUIr8
product_v2: id: e55547f1-a1ff-40c6-8978-026e40ab7fa4id: fdddec33-c9cb-4459-b8b6-2664395a6f10
feature_v2: id: eb9732ab-8232-4b21-bc4c-89de86dbe4d7id: fd307ce7-56f5-4ee3-af68-a7833ff6e85e
subfeature_v2: id: e6c28e30-8689-4bf4-8fa8-561343d308a9
role_v2: id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
topic_v2: id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
source-git-commit: 2a324011b3d235db3d4642c2797c4fa107267e6a
workflow-type: tm+mt
source-wordcount: 317
ht-degree: 10%

---

# Adobe [!DNL Analytics]とReal-Time Customer Data [!DNL Platform]をExperience [!DNL Platform] Edge チュートリアルと統合する

<ol>
    <li>取り込むデータの<a href="https://experienceleague.adobe.com/?lang=ja#dashboard/learning" _target="_blank" rel="noopener noreferrer"> スキーマ </a>を作成します。</li>
    <li>取り込むデータの<a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html" _target="_blank" rel="noopener noreferrer"> データセット </a>を作成します。</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">取り込んだデータを統合プロファイルに結合できるように、スキーマ </a>で正しいIDとID名前空間を設定します。</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=ja" _target="_blank" rel="noopener noreferrer"> プロファイル </a>のスキーマとデータセットを有効にします。</li>
    <li>次のいずれかの方法を使用して、データをExperience [!DNL Platform]に取り込みます。</li>
        <ul>
           <li>[!DNL Platform] Web SDKを体験：</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html?lang=ja" _target="_blank" rel="noopener noreferrer">チュートリアル</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/web-sdk/overview.html" _target="_blank" rel="noopener noreferrer">チェックリスト</a></li>
                </ul>
            <li>[!DNL Platform] Mobile SDKを体験：</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/create-mobile-properties.html" _target="_blank" rel="noopener noreferrer">チュートリアル</a></li>
                    <li><a href="https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/mobile-sdk/overview.html" _target="_blank" rel="noopener noreferrer">チェックリスト</a></li>
                </ul></li>
            <li>Edge Network Server API:</li>
                <ul>
                    <li><a href="https://experienceleague.adobe.com/docs/experience-platform/edge-network-server-api/interacting-other-adobe-solutions/interacting-adobe-analytics.html" _target="_blank" rel="noopener noreferrer">チュートリアル</a></li>
                </ul>
       </ul>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-segments.html" _target="_blank" rel="noopener noreferrer"> エクスペリエンス [!DNL Platform]でセグメントを作成します。</a> セグメントがバッチ（データコネクタ）とストリーミング（Edgeネットワーク）のどちらとして評価されるかを自動的に判断します。</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html" _target="_blank" rel="noopener noreferrer">プロファイル属性とオーディエンスメンバーシップを目的の宛先と共有するための宛先を設定します。</a></li>
</ol>

>[!NOTE]
>
>Adobe [!DNL Analytics] ソースコネクタの標準ワークフローステップでは、[!DNL Analytics]から「そのまま」データを取り込むために使用するスキーマとデータセットを作成します。 したがって、最初の2つのステップはシステムによって処理されます。 マッピングワークフローでは、カスタム属性を作成する必要があります。したがって、手順の順序に完全に従ってください。
