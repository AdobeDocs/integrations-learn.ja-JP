---
title: リアルタイム顧客データ  [!DNL Analytics] Experience [!DNL Platform] source コネクタを使用した統合  [!DNL Platform]  リアルタイム顧客データのチュートリアル
description: Experience [!DNL Platform] source コネクタを使用してAdobe [!DNL Analytics]  リアルタイム顧客データ  [!DNL Platform]  統合する方法について説明します。
solution: Real-Time Customer Data [!DNL Platform], [!DNL Analytics]
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: 13728
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="統合" type="positive"
exl-id: 1e27555d-e609-4a04-91ca-9518898ad699
source-git-commit: d35dc06c56c117cffe70542b6713f275877e4879
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 2%

---

# Adobe[!DNL Analytics] と Real-time Customer Data [!DNL Platform] を Experience [!DNL Platform] ソースコネクタに統合する

<ol>
    <li>取り込むデータの <a href="https://experienceleague.adobe.com/?lang=ja#dashboard/learning" _target="_blank" rel="noopener noreferrer"> スキーマを作成 </a> します。</li>
    <li>取り込むデータの <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html" _target="_blank" rel="noopener noreferrer"> データセットを作成 </a> します。</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer"> スキーマ上で正しい ID と ID 名前空間を設定して </a> 取り込まれたデータが統合プロファイルにステッチできることを確認します。</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=ja" _target="_blank" rel="noopener noreferrer"> プロファイルのスキーマとデータセットを有効にします </a>。</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=ja" _target="_blank" rel="noopener noreferrer">Adobe [!DNL Analytics] ソースコネクタ </a> を使用して、[!DNL Analytics] データを Experience Platform に取り込みます。</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/audiences/create-audiences.html" _target="_blank" rel="noopener noreferrer">Experience [!DNL Platform] でセグメントを作成します。</a> セグメントをバッチ（データコネクタ）とストリーミング（Edge Network）のどちらで評価するかを自動で判断します。</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html" _target="_blank" rel="noopener noreferrer">目的の宛先にプロファイル属性とオーディエンスメンバーシップを共有するための宛先を設定します。</a></li>   
</ol>

>[!NOTE]
>
>ソースコネクタ [!DNL Analytics]Adobeの標準的なワークフロー手順では、「そのまま」のデータの取り込みに使用するスキーマ [!DNL Analytics] データセットを作成します。 したがって、最初の 2 つの手順はシステムで処理されます。 マッピングワークフローでは、カスタム属性の作成が必要なため、一連の手順に完全に従ってください。
