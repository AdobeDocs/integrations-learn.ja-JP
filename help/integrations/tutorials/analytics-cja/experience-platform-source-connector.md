---
title: Experience [!DNL Platform]  ソースコネクタを使用した [!DNL Analytics] および顧客ジャーニー [!DNL Analytics] の統合チュートリアル
description: Experience [!DNL Platform]  ソースコネクタを使用してAdobe [!DNL Analytics] をお客様のジャーニー [!DNL Analytics] と統合する方法について説明します。
solution: Customer Journey Analytics, Target
feature: Integrations
topic: Integrations
role: Leader, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: 13727
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="統合" type="positive"
exl-id: f0dbd59d-d5e5-40e6-b4a4-e4789e7dd7e3
source-git-commit: 7fffc0b887164645ab16fe94d2f82a657fcc9d64
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 19%

---

# Adobe [!DNL Analytics]とカスタマージャーニー [!DNL Analytics]をExperience [!DNL Platform] ソースコネクタと統合

<ol>
    <li>取り込むデータの<a href="https://experienceleague.adobe.com/?lang=ja#dashboard/learning" _target="_blank" rel="noopener noreferrer"> スキーマ </a>を作成します。</li>
    <li>取り込むデータの<a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html" _target="_blank" rel="noopener noreferrer"> データセット </a>を作成します。</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">取り込んだデータを統合プロファイルに結合できるように、スキーマ </a>で正しいIDとID名前空間を設定します。</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=ja" _target="_blank" rel="noopener noreferrer"> プロファイル </a>のスキーマとデータセットを有効にします。</li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=ja" _target="_blank" rel="noopener noreferrer">Adobe [!DNL Analytics] ソースコネクタ </a>を使用して、Experience [!DNL Platform]にデータを取り込みます</li>
    <li><i> （オプション） </i>。 複数のデータセットを使用する場合は、個人IDをつなぎ合わせて<a href="https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/combined-dataset.html" _target="_blank" rel="noopener noreferrer">結合データセットを生成</a>します。 1つの[!DNL Analytics] データセットを使用している場合、またはお客様のジャーニー [!DNL Analytics]で使用する予定のすべてのデータセットに共通のIDが存在する場合は、この手順をスキップしてください。</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=ja" _target="_blank" rel="noopener noreferrer">お客様のジャーニー [!DNL Analytics]で接続</a>を作成します。</li>
    <li>顧客ジャーニー [!DNL Analytics]で<a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/basic-configuration-for-data-views.html" _target="_blank" rel="noopener noreferrer"> データビューを作成</a>、<a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configuring-component-settings-in-data-views.html" _target="_blank" rel="noopener noreferrer"> コンポーネント設定</a>および<a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/formatting-metrics-in-data-views.html" _target="_blank" rel="noopener noreferrer">形式の指標</a>を設定します。
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/workspace-projects/build-a-new-project.html?lang=ja" _target="_blank" rel="noopener noreferrer">カスタマージャーニー [!DNL Analytics]でプロジェクトを作成します。</a></li>
</ol>

>[!NOTE]
>
>Adobe [!DNL Analytics] ソースコネクタの標準ワークフローステップでは、[!DNL Analytics]から「そのまま」データを取り込むために使用するスキーマとデータセットを作成します。 したがって、最初の2つのステップはシステムによって処理されます。 マッピングワークフローでは、カスタム属性を作成する必要があります。したがって、手順の順序に完全に従ってください。
