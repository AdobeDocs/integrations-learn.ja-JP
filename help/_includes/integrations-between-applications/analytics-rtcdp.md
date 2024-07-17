---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '305'
ht-degree: 0%

---


# Adobe[!DNL Analytics] と Real-Time Customer Data [!DNL Platform] の統合

{{analytics-description}}

{{real-time-cdp-description}}

Adobe[!DNL Analytics] とAdobeの Real-time Customer Data [!DNL Platform] （Real-Time CDP）の統合は、カスタマーエクスペリエンスとマーケティング活動の強化を検討している企業に対して、いくつかのメリットを提供できます。 主な利点は次のとおりです。

+ **オーディエンスのターゲティングとパーソナライゼーションの強化**：デバイスとチャネルに関する正確なマーケティング、エンゲージメントを最適化するためのカスタマイズされたメッセージ。
+ **ランディングページの最適化の向上**：デバイスと行動に基づいてエクスペリエンスをカスタマイズし、ユーザーの満足度とコンバージョンを向上させます。
+ **シームレスなオーディエンスのアクティベーション**：顧客プロファイルを利用して、好みのチャネルを通じた効果的なターゲティングや、関連するメッセージの配信を行います。

Adobe [!DNL Analytics] とReal-Time CDPを組み合わせることで、企業はマーケティング活動を次のレベルに進め、パーソナライズされたエクスペリエンスを提供し、顧客エンゲージメントを向上させ、様々なデジタルタッチポイントをまたいでコンバージョンを最適化できます。

<table>
    <thead>
        <tr>
            <th>Experience Cloudアプリケーション</th>
            <th>を使用した統合</th>
            <th>使用するタイミング</th>
            <th>よくあるユースケース</th>
        </tr>
    </thead>
    <tr>
        <td rowspan="2">[!DNL Analytics] （Real-Time CDPを使用）</td>
        <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-source-connector.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] ソースコネクタ</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>既にAdobe[!DNL Analytics] を実装していて、このデータを Experience [!DNL Platform] に取り込んでリアルタイム顧客プロファイルで使用する最速の方法を希望するお客様に推奨されるアプローチです。</li>
                <li>リアルタイム顧客プロファイルへのデータの可用性がデータ収集時から 2～30 分の間である場合、データレイクへの可用性は最大 90 分です。</li>
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
       <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-edge.md" target="_blank" rel="noreferrer">Experience [!DNL Platform] Edge</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>新規の [!DNL Analytics] 実装または長期戦略を実装する場合に推奨されるアプローチ。</li>
                <li>AEP Web SDK、AEP Mobile SDK またはEdge Networkサーバー API を使用して、デバイスから Experience [!DNL Platform] に直接データを送信します。</li>
                <li>リアルタイム顧客プロファイルへの [!DNL Analytics] データの可用性を必要とする新規または既存のお客様は、同じページおよび次のページのパーソナライゼーションのユースケースをサポートできます。</li>
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
</table>
