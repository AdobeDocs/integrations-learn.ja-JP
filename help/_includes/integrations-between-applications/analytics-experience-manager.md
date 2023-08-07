---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 10%

---


# [!DNL Analytics] とExperience Managerの統合

{{analytics-description}}

{{experience-manager-description}}

統合Adobe [!DNL Analytics] とAdobe Experience Managerには、次のようないくつかの利点があります。

+ **正確なセグメント化**：結合Adobe [!DNL Analytics] キャンペーンでパーソナライズされたオーディエンスセグメントの&amp;Audience Manager。
+ **包括的な顧客** プロファイル：データソースを統合して、インタラクションと行動を統一的に理解します。
+ **最適化された広告ターゲティング**:Adobeのデータ駆動型ターゲティングにより、広告の効果を高める [!DNL Analytics] &amp;Audience Manager。
+ **情報に基づく意思決定**：結合されたAdobeからの詳細なインサイト [!DNL Analytics] およびAudience Managerデータを利用して選択を改善。
+ **パーソナライズされたエクスペリエンス**：両方のプラットフォームの機能を活用し、タッチポイントをまたいでパーソナライズされたコンテンツとオファー。

## 一般的な統合

<table>
    <thead>
        <tr>
            <th>Experience Cloud</th>
            <th>統合の条件</th>
            <th>使用するタイミング</th>
            <th>よくあるユースケース</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2">[!DNL Analytics] AEM Sitesと</a></td>
            <td><a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/experience-platform/analytics-using-web-sdk.html" target="_blank" rel="noreferrer">エクスペリエンス [!DNL Platform] Web SDK タグ拡張機能または alloy.js</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>AdobeでAEM Web 分析データをレポートする場合 [!DNL Analytics]を使用し、将来他のExperience Cloud・アプリケーションと統合するように配置します。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                  <li>Web サイトトラフィックの追跡。</li>
                  <li>マーケティングキャンペーンの監視.</li>
                  <li>Web サイトのパフォーマンスを最適化する。</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/analytics/collect-data-analytics.html?lang=ja" target="_blank" rel="noreferrer">Adobe [!DNL Analytics] tags 拡張機能またはAppMeasurement.js</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>AdobeでAEM Web 分析データをレポートする場合 [!DNL Analytics]など ) を使用している場合は、他のExperience Cloud・アプリケーションでデータを使用する予定はありません。</li>
                    <li>追跡可能な Web サイト要素にAEMコアコンポーネントを使用する場合。</li>
                    <li>最小限の設定と実装が必要な場合。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                  <li>Web サイトトラフィックの追跡。</li>
                  <li>マーケティングキャンペーンの監視.</li>
                  <li>Web サイトのパフォーマンスを最適化する。</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-and-analytics/introduction.html?lang=ja" target="_blank" rel="noreferrer">[!DNL Analytics] AEM FormsをCloud Service</a></td>
            <td>エクスペリエンス [!DNL Platform] Web SDK タグ拡張機能</td>
            <td>
              <ul style="margin-top: 0;">
                <li>デジタルフォーム分析データをAdobeでレポートする場合 [!DNL Analytics]を使用し、将来他のExperience Cloud・アプリケーションと統合するように配置します。</li>
              </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                  <li>フォームの送信を追跡します。</li>
                  <li>フォームフィールドのエラーを監視する。</li>
                  <li>送信済みフォームフィールドの値に関するレポート。</li>
                </ul>
            </td>
        </tr>
    </tbody>          
</table>
