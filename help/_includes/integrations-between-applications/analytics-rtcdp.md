---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '319'
ht-degree: 0%

---


# Adobe [!DNL Analytics]とReal-Time Customer Data [!DNL Platform]の統合

{{analytics-description}}

{{real-time-cdp-description}}

Adobe [!DNL Analytics]とAdobe Real-Time Customer Data [!DNL Platform] （Real-Time CDP）を統合すると、顧客体験とマーケティング活動を強化したい企業にとって、いくつかのメリットが得られます。 主な利点は次のとおりです。

+ **強化されたオーディエンスターゲティングとパーソナライゼーション**：デバイスとチャネルでの正確なマーケティング、エンゲージメントを最適化するためのカスタマイズされたメッセージ。
+ **ランディングページの最適化**&#x200B;の改善：デバイスと行動に基づいてカスタマイズされたエクスペリエンスを提供して、ユーザー満足度とコンバージョンを向上させます。
+ **シームレスなオーディエンスのアクティベーション**：顧客プロファイルを活用して、好みのチャネルを通じて効果的にターゲティングし、関連性の高いメッセージを配信します。

Adobe [!DNL Analytics]とReal-Time CDPを組み合わせることで、企業はマーケティング活動を次のレベルに引き上げ、パーソナライズされた体験の提供、顧客エンゲージメントの向上、さまざまなデジタル接点をまたいだコンバージョンの最適化を実現できます。

<table>
    <thead>
        <tr>
            <th>Experience Cloud アプリケーション</th>
            <th>を使用して統合</th>
            <th>使用するタイミング</th>
            <th>よくあるユースケース</th>
        </tr>
    </thead>
    <tr>
        <td rowspan="2">[!DNL Analytics] Real-Time CDPで実現</td>
        <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] ソースコネクタ</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Adobe [!DNL Analytics]を既に実装しており、このデータをExperience [!DNL Platform]に取り込み、リアルタイム顧客プロファイルで使用する最速の方法を必要とするお客様に推奨されるアプローチです。</li>
                <li>リアルタイム顧客プロファイルへのデータの可用性が、データ収集時から2～30分の範囲で設定でき、データレイクへの可用性が最大90分の場合。</li>
            </ul>
        </td>
        <td>
            <ul style="margin-top: 0;">
                <li>わかりやすいユーザーインターフェイスによるワークフローで。</li>
                <li>ユーザーインターフェイスをマッピングして[!DNL Analytics]個のpropとeVarを新しいXDM フィールドにコピーします。</li>
                <li>リアルタイム顧客プロファイルと顧客ジャーニー [!DNL Analytics]から価値を得る最速の方法です。</li>
            </ul>
        </td>
    </tr>
    <tr>
       <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-edge.md" target="_blank" rel="noreferrer">[!DNL Platform] Edgeを体験</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>新しい[!DNL Analytics]実装の場合や、長期的な戦略を実装する場合に推奨されるアプローチ。</li>
                <li>AEP Web SDK、AEP Mobile SDK、またはEdge Network Server APIを使用して、デバイスからExperience [!DNL Platform]にデータを直接送信します。</li>
                <li>同じページと次のページのパーソナライゼーションのユースケースをサポートするために、Real-Time Customer Profileへの[!DNL Analytics]のデータ可用性を必要とする新規または既存の顧客。</li>
            </ul>
        </td>
        <td>
            <ul style="margin-top: 0;">
                <li>ユースケースのサポートに使用するために収集したデータを最大限に制御できます。</li>
                <li>クライアントサイドのデータをXDM フィールドに簡単にマッピングできます。</li>
                <li>リアルタイム顧客プロファイルへの最短のデータ可用性。</li>
            </ul>
        </td>
    </tr>            
</table>
