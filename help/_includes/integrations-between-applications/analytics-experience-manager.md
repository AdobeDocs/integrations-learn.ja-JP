---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '242'
ht-degree: 2%

---


# [!DNL Analytics] とExperience Managerの統合

{{analytics-description}}

{{experience-manager-description}}

Adobe [!DNL Analytics] とAdobe Experience Managerの統合には、次のような利点があります。

+ **正確なセグメント化**：キャンペーンでパーソナライズされたオーディエンスセグメントのAdobe[!DNL Analytics] とAudience Managerを結合する。
+ **包括的な顧客** プロファイル：データソースを統合し、インタラクションと行動を統一された形で把握します。
+ **最適化された広告ターゲティング**：広告のターゲティングとAudience Managerから得られるデータ駆動型のターゲティングにより、Adobeの効 [!DNL Analytics] を高めます。
+ **十分な情報に基づいた意思決定**：より優れた選択肢を実現するために、結合されたAdobe[!DNL Analytics] とAudience Managerデータから得られる詳細なインサイト。
+ **パーソナライズされたエクスペリエンス**：両方のプラットフォームの機能を活用して、タッチポイントをまたいでパーソナライズされたコンテンツとオファーを提供します。

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
            <td rowspan="2">[!DNL Analytics] （AEM Sitesを使用）</a></td>
            <td><a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/experience-platform/analytics-using-web-sdk.html?lang=ja" target="_blank" rel="noreferrer">Experience [!DNL Platform] Web SDK タグ拡張機能または alloy.js</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Adobe [!DNL Analytics] でAEM web 分析データについてレポートする場合は、将来、他のExperience Cloudアプリケーションと統合する立場をとってください。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                  <li>Web サイトトラフィックのトラッキング。</li>
                  <li>マーケティングキャンペーンの監視。</li>
                  <li>Web サイトのパフォーマンスの最適化。</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/analytics/collect-data-analytics.html?lang=ja" target="_blank" rel="noreferrer">Adobe [!DNL Analytics] タグ拡張機能またはAppMeasurement.js</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Experience Cloud[!DNL Analytics] ークフローでAEM web 分析データをレポートし、他のAdobeアプリケーションでそのデータを使用する予定がない場合</li>
                    <li>AEM コアコンポーネントを追跡可能な web サイト要素に使用する場合。</li>
                    <li>最小限の設定と実装が必要な場合。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                  <li>Web サイトトラフィックのトラッキング。</li>
                  <li>マーケティングキャンペーンの監視。</li>
                  <li>Web サイトのパフォーマンスの最適化。</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-and-analytics/introduction.html?lang=ja" target="_blank" rel="noreferrer">[!DNL Analytics] Cloud ServiceとしてのAEM Forms</a></td>
            <td>Experience [!DNL Platform] Web SDK タグ拡張機能</td>
            <td>
              <ul style="margin-top: 0;">
                <li>Adobe [!DNL Analytics] でデジタルフォーム分析データをレポートする場合は、将来、他のExperience Cloudアプリケーションと統合できるようになります。</li>
              </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                  <li>フォーム送信を追跡します。</li>
                  <li>フォームフィールドのエラーの監視</li>
                  <li>送信されたフォームフィールド値に関するレポート。</li>
                </ul>
            </td>
        </tr>
    </tbody>          
</table>
