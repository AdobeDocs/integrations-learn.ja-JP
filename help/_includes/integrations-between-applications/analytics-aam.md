---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---


# [!DNL Analytics] とAudience Managerの統合

{{analytics-description}}

{{audience-manager-description}}

この統合を有効にすると、Adobe[!DNL Analytics] データサーバーサイドをAudience Managerに転送することで、Audience Managerはオンラインの顧客行動データなどの主要なデータソースの 1 つを得ることができます。 その後、このデータをファーストパーティの CRM データやサードパーティのパートナーデータなどの他のデータと組み合わせて、豊富な顧客セグメントを作成できます。 さらに、さらに詳細な訪問者分析のために、Audience Managerセグメントが応答の web ページに送り返されます。 これらの貴重なユースケースの両方について、以下で説明します。

Adobe[!DNL Analytics] とAudience Managerを統合する主なメリットは次のとおりです。

+ **セグメント化の強化**:Adobe[!DNL Analytics] とAudience Managerデータを組み合わせて、マーケティングキャンペーンで正確にパーソナライズされたオーディエンスセグメントを得ます。
+ **統合された顧客プロファイル**：データソースを統合してインタラクションと行動を把握し、包括的な顧客プロファイルを作成します。
+ **広告効果の向上**:Adobeの [!DNL Analytics] ールとAudience Managerの統合により、データに基づくターゲティングで広告を最適化します。
+ **データに基づく意思決定**：詳細なインサイトを通じて選択肢に情報を提供し、Adobe[!DNL Analytics] とAudience Managerデータを結合します。
+ **エクスペリエンスのパーソナライズ**：両方のプラットフォームを使用して、コンテンツとオファーをカスタマイズし、タッチポイントをまたいで顧客インタラクションを強化します。

全体的に、この統合により、貴重なデータとオーディエンスのインサイトが得られます。 これにより、企業は顧客の好みや行動をより深く理解しながら、よりターゲットを絞った関連性の高いマーケティングキャンペーンを作成できます。

## 一般的な統合

<table>
    <thead>
        <tr>
            <th>Experience Cloudアプリケーション</th>
            <th>を使用した統合</th>
            <th>使用するタイミング</th>
            <th>よくあるユースケース</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                Audience Managerにデータを送信できませ <a href="/docs/analytics-learn/tutorials/integrations/audience-manager/enable-server-side-forwarding-in-adobe-launch.html" target="_blank" rel="noreferrer">[!DNL Analytics] でした </a>
            </td>
            <td>サーバーサイド転送 [!DNL Analytics] 有効なタグ拡張機能またはAppMeasurement.js のAdobe</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Adobe[!DNL Analytics] データをAudience Managerに送信して、他のAdobe Experience Cloudの宛先、人物ベースの宛先、またはAudience Managerがサポートするその他のデバイスベースやカスタムの宛先と共有できるセグメントを作成する場合。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>[!DNL Analytics] で収集された行動属性を含む広告プラットフォームにセグメントを共有します。</li>
                    <li>[!DNL Analytics] データを使用してセグメントを強化し、オンサイトターゲティングで使用する高価値のクロスチャネルセグメントを作成します。</li>
                    <li>ソーシャルメディアプラットフォームで使用するために、ハッシュ化された識別子（電子メールなど）をキーにキーにセグメントにデータを [!DNL Analytics] り込みます。</li>
                </ul>
            </td>
        </tr>        
        <tr>
            <td>
                <a href="https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html" target="_blank" rel="noreferrer">[!DNL Analytics]</a> へのデータの返送Audience Manager
            </td>
            <td>サーバーサイド転送 [!DNL Analytics] 有効なタグ拡張機能またはAppMeasurement.js のAdobe</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Audience Manager間でセグメントを共有して、オーディエンスの検出、セグメント化および最適化を知 [!DNL Analytics] せたい場合。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>[!DNL Analytics] レポートには、サードパーティプロバイダーのデモグラフィックデータを含んだAudience Managerセグメントを使用します。</li>
                    <li>広告サーバーのキャンペーンデータをレポートに含めたAudience Managerセグメント [!DNL Analytics] 使用します。</li>
                    <li>[!DNL Analytics] レポートにオンボードされた CRM データを含むAudience Managerセグメントを使用します。</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
