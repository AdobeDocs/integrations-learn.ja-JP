---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 1%

---


# Adobe [!DNL Analytics]をお客様のジャーニー [!DNL Analytics]と統合する

{{analytics-description}}

{{customer-journey-analytics-description}}

Adobe [!DNL Analytics]をお客様のジャーニー [!DNL Analytics]と統合すると、主なメリットが得られます。

+ 顧客の行動や好みに関する包括的なインサイト **を**&#x200B;提供しています。
+ **包括的なビューのためのシームレスなクロスチャネルトラッキング**。
+ 正確な分析のための&#x200B;**統合データとレポート**。
+ **強化されたパーソナライゼーション**&#x200B;と顧客エンゲージメントの向上。
+ アジャイルな意思決定のための&#x200B;**リアルタイムデータインサイト**。

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
            <td rowspan="2">[!DNL Analytics] 顧客ジャーニーが向上し [!DNL Analytics]</td>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] ソースコネクタ</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>既にAdobe [!DNL Analytics]を実装しており、このデータをExperience [!DNL Platform]に取り込み、カスタマージャーニー [!DNL Analytics]で使用する場合に推奨されるアプローチです。</li>
                    <li>顧客プロファイルへのデータの可用性が、データ収集時から2 ～ 30分の間である可能性があり、データレイクへの可用性が最大90分である場合。</li>
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
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-edge.md" target="_blank" rel="noreferrer">[!DNL Platform] Edgeを体験</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>新しい[!DNL Analytics]実装の場合や、長期的な戦略を実装する場合に推奨されるアプローチ。</li>
                    <li>AEP Web SDK、AEP Mobile SDK、またはEdge Network Server APIを使用して、デバイスからExperience [!DNL Platform]にデータを直接送信します。</li>
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
    </tbody>          
</table>
