---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 1%

---


# Adobe [!DNL Analytics] とカスタマージャーニー [!DNL Analytics] の統合

{{analytics-description}}

{{customer-journey-analytics-description}}

Adobe [!DNL Analytics] とカスタマージャーニー [!DNL Analytics] の統合には、次のような主なメリットがあります。

+ 顧客の行動や好みに関する **包括的なインサイト**。
+ **シームレスなクロスチャネルトラッキング** で全体像を把握
+ 正確な分析のための **統合されたデータとレポート**。
+ **パーソナライゼーションの強化** と顧客エンゲージメントの向上。
+ アジャイルな意思決定を可能にする **リアルタイムデータインサイト**。

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
            <td rowspan="2">[!DNL Analytics] およびカスタマージャーニー [!DNL Analytics]</td>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] ソースコネクタ</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>既にAdobe[!DNL Analytics] を実装していて、このデータを Experience [!DNL Platform] に取り込んでカスタマージャーニー[!DNL Analytics] ークフローで最速で使用したい場合は、このアプローチをお勧めします。</li>
                    <li>顧客プロファイルへのデータの可用性がデータ収集時から 2～30 分の場合、データレイクへの可用性は最大 90 分である場合。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>簡単なユーザーインターフェイスで開始されるワークフロー。</li>
                    <li>[!DNL Analytics] prop と eVar を新しい XDM フィールドにコピーするユーザーインターフェイスのマッピング。</li>
                    <li>リアルタイム顧客プロファイルおよび顧客ジャーニー[!DNL Analytics] ールから価値を得る最速の方法。</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-edge.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] Edge</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>新規の [!DNL Analytics] 実装または長期戦略を実装する場合に推奨されるアプローチ。</li>
                    <li>AEP Web SDK、AEP Mobile SDK またはEdge Networkサーバー API を使用して、デバイスから Experience [!DNL Platform] に直接データを送信します。</li>
                </ul>
            </td>
            <td>
                <ul style="margin-top: 0;">
                    <li>は、ユースケースをサポートするために使用するために収集されたデータを最高レベルで制御できます。</li>
                    <li>クライアントサイドのデータは、XDM フィールドに簡単にマッピングできます。</li>
                    <li>リアルタイム顧客プロファイルでデータをすばやく利用できます。</li>
                </ul>
            </td>
        </tr>  
    </tbody>          
</table>
