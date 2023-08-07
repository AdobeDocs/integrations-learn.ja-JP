---
title: 統合 [!DNL Analytics] およびリアルタイムの顧客データ [!DNL Platform] エクスペリエンス [!DNL Platform] ソースコネクタのチュートリアル
description: Adobeの統合方法 [!DNL Analytics] とリアルタイムの顧客データ [!DNL Platform] エクスペリエンスの使用 [!DNL Platform] ソースコネクタ。
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
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '218'
ht-degree: 19%

---


# 統合Adobe [!DNL Analytics] およびリアルタイムの顧客データ [!DNL Platform] エクスペリエンス [!DNL Platform] ソースコネクタ

<ol>
    <li>取り込むデータの <a href="https://experienceleague.adobe.com/?lang=ja#dashboard/learning" _target="_blank" rel="noopener noreferrer">スキーマを作成</a> します。</li>
    <li>取り込むデータの <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html?lang=ja" _target="_blank" rel="noopener noreferrer">データセットを作成</a> します。</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">スキーマでの正しい ID と ID 名前空間の設定</a> 取り込んだデータを統合プロファイルに確実に結び付けることができるようにするため。</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=ja" _target="_blank" rel="noopener noreferrer">プロファイルのスキーマとデータセットの有効化</a>.</li>
    <li>取り込み [!DNL Analytics] を使用して Experience Platform にデータを取り込む <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=ja" _target="_blank" rel="noopener noreferrer">Adobe [!DNL Analytics] ソースコネクタ</a>.</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/audiences/create-audiences.html" _target="_blank" rel="noopener noreferrer">エクスペリエンスでのセグメントの作成 [!DNL Platform].</a> セグメントがバッチ（データコネクタ）とストリーミング（Edge ネットワーク）のどちらで評価されるかは、システムによって自動的に判断されます。</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/create-destinations-and-activate-data.html" _target="_blank" rel="noopener noreferrer">目的の宛先に対して、プロファイル属性とオーディエンスメンバーシップを共有するための宛先を設定します。</a></li>   
</ol>

>[!NOTE]
>
>Adobeの標準ワークフローステップ [!DNL Analytics] ソースコネクタ：データの取り込みに使用するスキーマとデータセットの作成 [!DNL Analytics] 「現状」 したがって、最初の 2 つの手順はシステムによって処理されます。 マッピングワークフローでは、カスタム属性を作成する必要があります。したがって、手順の順序に完全に従います。
