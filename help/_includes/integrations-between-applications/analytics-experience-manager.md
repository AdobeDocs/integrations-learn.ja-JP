---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '279'
ht-degree: 10%
---

# [!DNL Analytics]とExperience Managerの統合

{{analytics-description}}

{{experience-manager-description}}

Adobe [!DNL Analytics]とAdobe Experience Managerを統合すると、次のようなメリットが得られます。

+ **正確なセグメンテーション**: Adobe [!DNL Analytics]とAudience Managerを統合して、キャンペーンでパーソナライズされたオーディエンスセグメントを実現します。
+ **包括的な顧客** プロファイル：インタラクションと行動の統合的な理解のためにデータソースを統合します。
+ **広告ターゲティングの最適化**: Adobe [!DNL Analytics]およびAudience Managerのデータドリブン型ターゲティングで、広告の効果を向上させます。
+ **情報に基づいた意思決定**：より良い選択肢のために、結合されたAdobe [!DNL Analytics]とAudience Manager データから詳細なインサイトを得ることができます。
+ **パーソナライズされたエクスペリエンス**：両方のプラットフォームの機能を活用して、顧客接点をまたいでパーソナライズされたコンテンツとオファー。

## 共通の統合

<table>
    <thead>
        <tr>
            <th>Experience Cloud アプリケーション</th>
            <th>を使用して統合</th>
            <th>使用するタイミング</th>
            <th>よくあるユースケース</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2">[!DNL Analytics] AEM Sitesで実現</a></td>
            <td><a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/experience-platform/analytics-using-web-sdk.html?lang=ja" target="_blank" rel="noreferrer">[!DNL Platform]個のWeb SDK タグ拡張機能またはalloy.jsを体験</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Adobe [!DNL Analytics]でAEM web分析データをレポートする場合、将来的に他のExperience Cloud アプリケーションと統合できる位置に置きます。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                  <li>web サイトのトラフィックの追跡：</li>
                  <li>マーケティング施策の監視：</li>
                  <li>web サイトパフォーマンスの最適化。</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/analytics/collect-data-analytics.html?lang=ja" target="_blank" rel="noreferrer">Adobe [!DNL Analytics] tags拡張機能またはAppMeasurement.js</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Adobe [!DNL Analytics]のAEM web Analytics データについてレポートする場合で、他のExperience Cloud アプリケーションでデータを使用することを計画していない場合</li>
                    <li>AEMのコアコンポーネントを使用して、追跡可能なweb サイト要素を実行する場合。</li>
                    <li>設定や実装を最小限に抑えたいとき。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                  <li>web サイトのトラフィックの追跡：</li>
                  <li>マーケティング施策の監視：</li>
                  <li>web サイトパフォーマンスの最適化。</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-and-analytics/introduction.html?lang=ja" target="_blank" rel="noreferrer">[!DNL Analytics] AEM Forms as Cloud Serviceを組み合わせることで</a></td>
            <td>エクスペリエンス [!DNL Platform] Web SDK タグ拡張機能</td>
            <td>
              <ul style="margin-top: 0;">
                <li>Adobe [!DNL Analytics]でデジタルフォーム分析データをレポートする場合、将来的に他のExperience Cloud アプリケーションと統合できる状態になります。</li>
              </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                  <li>フォーム送信を追跡：</li>
                  <li>フォームフィールドエラーの監視：</li>
                  <li>送信されたフォームフィールド値に関するレポート。</li>
                </ul>
            </td>
        </tr>
    </tbody>          
</table>
