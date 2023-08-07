---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '373'
ht-degree: 3%

---


# [!DNL Analytics] とAudience Managerの統合

{{analytics-description}}

{{audience-manager-description}}

転送Adobeによるこの統合の有効化 [!DNL Analytics] データは、Audience Managerに対してサーバー側で提供され、Audience Managerは、主なデータソースの 1 つであるオンライン顧客行動データを提供します。 その後、このデータを他のデータ（ファーストパーティの CRM データやサードパーティのパートナーデータなど）と組み合わせて、リッチな顧客セグメントを作成できます。 さらに、Audience Managerセグメントが応答で Web ページに送り返され、訪問者の分析がさらに進められます。 これらの有用な使用例の両方を以下に示します。

統合の主なメリットAdobe [!DNL Analytics] Audience Managerは次のとおりです。

+ **セグメント化の強化**：結合Adobe [!DNL Analytics] マーケティングキャンペーンでパーソナライズされた正確なオーディエンスセグメントのための&amp;Audience Managerデータ。
+ **統合された顧客プロファイル**：データソースを統合して、インタラクションと行動を理解し、包括的な顧客プロファイルを作成します。
+ **広告効果の向上**:Adobeのデータ駆動型ターゲティングによる広告の最適化 [!DNL Analytics] とAudience Managerの統合。
+ **データ駆動型の意思決定**：詳細なインサイト、結合Adobeを通じて選択肢に情報を提供 [!DNL Analytics] &amp;Audience Managerデータ。
+ **パーソナライズされたエクスペリエンス**：両方のプラットフォームを使用して、コンテンツとオファーを調整し、複数のタッチポイントをまたいで顧客のインタラクションを強化します。

全体的に、この統合により、貴重なデータとオーディエンスのインサイトが統合されます。 これにより、企業は、よりターゲットを絞り込んだ関連性の高いマーケティングキャンペーンを作成し、顧客の好みや行動をより深く理解することができます。

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
            <td>
                <a href="/docs/analytics-learn/tutorials/integrations/audience-manager/enable-server-side-forwarding-in-adobe-launch.html" target="_blank" rel="noreferrer">[!DNL Analytics] データをAudience Managerに送信中</a>
            </td>
            <td>Adobe [!DNL Analytics] サーバー側転送が有効になっている tags 拡張機能またはAppMeasurement.js</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>送信するAdobe [!DNL Analytics] 他のAdobe Experience Cloudの宛先、ユーザーベースの宛先、Audience Managerでサポートされているその他のデバイスベースの宛先やカスタムの宛先と共有できるセグメントを作成するためのデータをAudience Managerに送信する方法について説明します。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>収集された行動属性を含む広告プラットフォームに対してセグメントを共有する [!DNL Analytics].</li>
                    <li>次を使用したセグメントのエンリッチメント [!DNL Analytics] オンサイトターゲティングで使用する、価値の高いクロスチャネルセグメントを作成するためのデータ。</li>
                    <li>レイヤーイン [!DNL Analytics] ソーシャルメディアプラットフォームで使用する、電子メールなどのハッシュ化された識別子でキーオフにされたセグメントへのデータ。</li>
                </ul>
            </td>
        </tr>        
        <tr>
            <td>
                <a href="https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html?lang=ja" target="_blank" rel="noreferrer">Audience Managerがにデータを送り返す [!DNL Analytics]</a>
            </td>
            <td>Adobe [!DNL Analytics] サーバー側転送が有効になっている tags 拡張機能またはAppMeasurement.js</td>
            <td>
                <ul style="margin-top: 0;">
                    <li>セグメントをAudience Managerからに共有する場合 [!DNL Analytics] を使用して、audience discovery、segmentation、および optimization に通知します。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Audience Managerセグメントを使用して、 [!DNL Analytics] レポート。</li>
                    <li>広告サーバーのAudience Managerデータを含むキャンペーンセグメントを [!DNL Analytics] レポート。</li>
                    <li>オンボードの CRMAudience Managerを含むデータセグメントを [!DNL Analytics] レポート。</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
