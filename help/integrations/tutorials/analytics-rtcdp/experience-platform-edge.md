---
title: Experience [!DNL Analytics] 2&rbrace;Edge チュートリアルを使用したリアルタイム顧客データ  [!DNL Platform]  の統合 [!DNL Platform]
description: AEP Web SDK [!DNL Analytics] AEP Mobile SDK、またはEdge Networkサーバー API を使用して、Adobe [!DNL Platform]  リアルタイム顧客データ）を統合する方法を説明します。
solution: Real-Time Customer Data [!DNL Platform], [!DNL Analytics]
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
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 3%

---

# Experience [!DNL Platform] Edge チュートリアルを使用した、Adobe[!DNL Analytics] ータと Real-time Customer Data [!DNL Platform] の統合

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
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-segments.html?lang=ja" _target="_blank" rel="noopener noreferrer">Experience [!DNL Platform] でセグメントを作成します。</a> セグメントをバッチ（データコネクタ）とストリーミング（Edge Network）のどちらで評価するかを自動で判断します。</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html?lang=ja" _target="_blank" rel="noopener noreferrer">目的の宛先にプロファイル属性とオーディエンスメンバーシップを共有するための宛先を設定します。</a></li>
</ol>

>[!NOTE]
>
>ソースコネクタ [!DNL Analytics]Adobeの標準的なワークフロー手順では、「そのまま」のデータの取り込みに使用するスキーマ [!DNL Analytics] データセットを作成します。 したがって、最初の 2 つの手順はシステムで処理されます。 マッピングワークフローでは、カスタム属性の作成が必要なため、一連の手順に完全に従ってください。
