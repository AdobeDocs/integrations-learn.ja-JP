---
title: 統合 [!DNL Analytics] および顧客ジャーニー [!DNL Analytics] エクスペリエンス [!DNL Platform] ソースコネクタのチュートリアル
description: Adobeの統合方法 [!DNL Analytics] 顧客ジャーニー [!DNL Analytics] エクスペリエンスの使用 [!DNL Platform] ソースコネクタ。
solution: Customer Journey [!DNL Analytics], [!DNL Target]
feature: Integrations
topic: Integrations
role: Leader, Architect, Admin, Developer
level: Beginner
index: true
hidefromtoc: true
kt: 13727
thumbnail: null
last-substantial-update: 2023-04-11T00:00:00Z
badgeIntegration: label="統合" type="positive"
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '274'
ht-degree: 18%

---


# 統合Adobe [!DNL Analytics] および顧客ジャーニー [!DNL Analytics] エクスペリエンス [!DNL Platform] ソースコネクタ

<ol>
    <li>取り込むデータの <a href="https://experienceleague.adobe.com/?lang=ja#dashboard/learning" _target="_blank" rel="noopener noreferrer">スキーマを作成</a> します。</li>
    <li>取り込むデータの <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/create-datasets-and-ingest-data.html?lang=ja" _target="_blank" rel="noopener noreferrer">データセットを作成</a> します。</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/identities/label-ingest-and-verify-identity-data.html?lang=en" _target="_blank" rel="noopener noreferrer">スキーマでの正しい ID と ID 名前空間の設定</a> 取り込んだデータを統合プロファイルに確実に結び付けることができるようにするため。</li> 
    <li><a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html?lang=ja" _target="_blank" rel="noopener noreferrer">プロファイルのスキーマとデータセットの有効化</a>.</li>
    <li>データを Experience に取り込む [!DNL Platform] の使用 <a href="https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=ja" _target="_blank" rel="noopener noreferrer">Adobe [!DNL Analytics] ソースコネクタ</a></li>
    <li><i>(オプション)</i>. 複数のデータセットを使用する場合は、ユーザー ID を <a href="https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/combined-dataset.html" _target="_blank" rel="noopener noreferrer">組み合わせデータセットを生成する</a>. 単一の [!DNL Analytics] データセット、または顧客ジャーニーで使用する予定のすべてのデータセットに共通の識別子が存在する場合。 [!DNL Analytics]、この手順をスキップします。</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=ja" _target="_blank" rel="noopener noreferrer">接続の作成</a> 顧客ジャーニー [!DNL Analytics].</li>
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/basic-configuration-for-data-views.html" _target="_blank" rel="noopener noreferrer">データビューの作成</a>, <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configuring-component-settings-in-data-views.html" _target="_blank" rel="noopener noreferrer">コンポーネント設定の指定</a>、および <a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/formatting-metrics-in-data-views.html" _target="_blank" rel="noopener noreferrer">指標の形式</a> 顧客ジャーニー [!DNL Analytics].
    <li><a href="https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/workspace-projects/build-a-new-project.html" _target="_blank" rel="noopener noreferrer">顧客ジャーニーでのプロジェクトの作成 [!DNL Analytics].</a></li>
</ol>

>[!NOTE]
>
>Adobeの標準ワークフローステップ [!DNL Analytics] ソースコネクタ：データの取り込みに使用するスキーマとデータセットの作成 [!DNL Analytics] 「現状」 したがって、最初の 2 つの手順はシステムによって処理されます。 マッピングワークフローでは、カスタム属性を作成する必要があります。したがって、手順の順序に完全に従います。
