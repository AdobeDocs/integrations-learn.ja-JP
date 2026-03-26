---
title: Experience [!DNL Platform]  ソースコネクタを使用した [!DNL Analytics] およびReal-Time Customer Data [!DNL Platform] の統合チュートリアル
description: Experience [!DNL Platform]  ソースコネクタを使用してAdobe [!DNL Analytics] とReal-Time Customer Data [!DNL Platform] を統合する方法について説明します。
solution: Real-Time Customer Data Platform, Analytics
feature: Integrations
topic: Integrations
role: Leader, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: 13728
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="統合" type="positive"
exl-id: 1e27555d-e609-4a04-91ca-9518898ad699
source-git-commit: 7fffc0b887164645ab16fe94d2f82a657fcc9d64
workflow-type: tm+mt
source-wordcount: '248'
ht-degree: 13%

---

# Adobe [!DNL Analytics]とReal-Time Customer Data [!DNL Platform]をExperience [!DNL Platform] ソースコネクタと統合

<ol>
    <li>取り込むデータの<a href="https://experienceleague.adobe.com/?lang=ja#dashboard/learning" _target="_blank" rel="noopener noreferrer"> スキーマ </a>を作成します。</li>
    <li>取り込むデータの<a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html" _target="_blank" rel="noopener noreferrer"> データセット </a>を作成します。</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">取り込んだデータを統合プロファイルに結合できるように、スキーマ </a>で正しいIDとID名前空間を設定します。</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=ja" _target="_blank" rel="noopener noreferrer"> プロファイル </a>のスキーマとデータセットを有効にします。</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=ja" _target="_blank" rel="noopener noreferrer">Adobe [!DNL Analytics] ソースコネクタ </a>を使用して、[!DNL Analytics] データをExperience Platformに取り込みます。</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/audiences/create-audiences.html" _target="_blank" rel="noopener noreferrer"> エクスペリエンス [!DNL Platform]でセグメントを作成します。</a> セグメントがバッチ（データコネクタ）とストリーミング（Edgeネットワーク）のどちらとして評価されるかを自動的に判断します。</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html" _target="_blank" rel="noopener noreferrer">プロファイル属性とオーディエンスメンバーシップを目的の宛先と共有するための宛先を設定します。</a></li>   
</ol>

>[!NOTE]
>
>Adobe [!DNL Analytics] ソースコネクタの標準ワークフローステップでは、[!DNL Analytics]から「そのまま」データを取り込むために使用するスキーマとデータセットを作成します。 したがって、最初の2つのステップはシステムによって処理されます。 マッピングワークフローでは、カスタム属性を作成する必要があります。したがって、手順の順序に完全に従ってください。
