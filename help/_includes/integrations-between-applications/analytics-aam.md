---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '390'
ht-degree: 0%

---


# [!DNL Analytics]とAudience Managerの統合

{{analytics-description}}

{{audience-manager-description}}

この統合を有効にすると、Adobe [!DNL Analytics] データをサーバーサイドでAudience Managerに転送することにより、Audience Managerはデータの主要なソースの1つ、つまりオンライン顧客行動データを提供します。 このデータを、ファーストパーティのCRM データやサードパーティのパートナーデータなどの他のデータと組み合わせることで、優れた顧客セグメントを構築できます。 さらに、Audience Managerのセグメントは、訪問者をさらに分析するために、web ページに返送されます。 これらの価値あるユースケースは、どちらも次に示します。

Adobe [!DNL Analytics]とAudience Managerを連携する主な利点は次のとおりです。

+ **高度なセグメンテーション**: Adobe [!DNL Analytics]とAudience Managerのデータを組み合わせて、マーケティングキャンペーンで正確にパーソナライズされたオーディエンスセグメントを作成できます。
+ **統合顧客プロファイル**: データソースを統合して、インタラクションと行動を理解し、包括的な顧客プロファイルを作成します。
+ **広告効果の向上**: Adobe [!DNL Analytics]とAudience Managerの統合によるデータドリブン型ターゲティングで、広告を最適化します。
+ **データ主導の意思決定**: Adobe [!DNL Analytics]とAudience Manager データを結合し、詳細なインサイトを通じて選択肢に情報を提供します。
+ **パーソナライズされたエクスペリエンス**：コンテンツとオファーをカスタマイズし、両方のプラットフォームを使用して顧客接点をまたいで顧客インタラクションを強化します。

全体として、この統合は貴重なデータとオーディエンスのインサイトを。 これにより、顧客の好みや行動をより深く理解しながら、よりターゲットを絞った適切なマーケティング施策を展開できるようになります。

## 共通の統合

<table>
    <thead>
        <tr>
            <th>Experience Cloud製品</th>
            <th>を使用して統合</th>
            <th>使用するタイミング</th>
            <th>よくあるユースケース</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <a href="/docs/analytics-learn/tutorials/integrations/audience-manager/enable-server-side-forwarding-in-adobe-launch.html" target="_blank" rel="noreferrer">[!DNL Analytics]さんがAudience Manager</a>にデータを送信しています
            </td>
            <td>サーバーサイド転送が有効になっているAdobe [!DNL Analytics] タグ拡張機能またはAppMeasurement.js</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Adobe [!DNL Analytics] データをAudience Managerに送信して、他のAdobe Experience Cloudの宛先、ピープルベースの宛先、またはAudience Managerでサポートされているその他のデバイスベースの宛先やカスタムの宛先と共有できるセグメントを作成する場合。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>[!DNL Analytics]で収集された行動属性を含む広告プラットフォームにセグメントを共有します。</li>
                    <li>[!DNL Analytics]個のデータでセグメントを強化し、オンサイトのターゲティングで使用する価値の高いクロスチャネルセグメントを作成します。</li>
                    <li>電子メールなどのハッシュ化された識別子にキーオフされたセグメントに[!DNL Analytics]個のデータをレイヤー化して、ソーシャルメディアプラットフォームで使用します。</li>
                </ul>
            </td>
        </tr>        
        <tr>
            <td>
                <a href="https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html?lang=ja" target="_blank" rel="noreferrer">Audience Managerが[!DNL Analytics]</a>にデータを送り返しています
            </td>
            <td>サーバーサイド転送が有効になっているAdobe [!DNL Analytics] タグ拡張機能またはAppMeasurement.js</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Audience Managerから[!DNL Analytics]までのセグメントを共有して、オーディエンスの発見、セグメンテーション、最適化に活用する場合。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>[!DNL Analytics]件のレポートで、サードパーティプロバイダーからのデモグラフィックデータを含むAudience Manager セグメントを使用します。</li>
                    <li>[!DNL Analytics]件のレポートに広告サーバーからのキャンペーンデータを含むAudience Manager セグメントを使用します。</li>
                    <li>[!DNL Analytics]件のレポートにオンボーディングされたCRM データを含むAudience Manager セグメントを使用します。</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
