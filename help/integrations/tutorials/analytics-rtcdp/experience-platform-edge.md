---
title: Experience [!DNL Platform] Edge チュートリアルで [!DNL Analytics] とReal-Time Customer Data [!DNL Platform] を統合する
description: AEP Web SDK、AEP Mobile SDK、またはEdge Network Server APIを使用して、Adobe [!DNL Analytics] とReal-Time Customer Data [!DNL Platform] を統合する方法について説明します。
solution: Real-Time Customer Data Platform, Analytics
feature: Integrations
topic: Integrations
role: Developer
level: Experienced
index: true
hidefromtoc: true
kt: 13732
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="統合" type="positive"
exl-id: 07c2c329-0810-4f66-a91a-e315695f3fb4
source-git-commit: 7fffc0b887164645ab16fe94d2f82a657fcc9d64
workflow-type: tm+mt
source-wordcount: '317'
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
