---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '302'
ht-degree: 1%

---


# 統合Adobe [!DNL Analytics] とリアルタイムの顧客データ [!DNL Platform]

{{analytics-description}}

{{real-time-cdp-description}}

統合Adobe [!DNL Analytics] とAdobeのリアルタイム顧客データ [!DNL Platform] (Real-Time CDP) は、顧客体験やマーケティング活動の強化を目指す企業に、いくつかのメリットを提供できます。 主な利点を次に示します。

+ **オーディエンスのターゲティングとパーソナライゼーションの強化**：デバイスおよびチャネルでの正確なマーケティング、最適化されたエンゲージメントのためのカスタマイズされたメッセージ。
+ **ランディングページの最適化の改善**：デバイスと行動に基づいてカスタマイズされたエクスペリエンスで、ユーザーの満足度とコンバージョンを向上。
+ **シームレスなオーディエンスのアクティベーション**：顧客プロファイルを利用し、優先チャネルを通じて効果的なターゲティングをおこない、関連するメッセージを配信します。

組み合わせAdobe [!DNL Analytics] Real-Time CDPや企業は、マーケティング活動を次のレベルに進め、パーソナライズされたエクスペリエンスを提供し、顧客エンゲージメントを向上させ、様々なデジタルタッチポイントをまたいでコンバージョンを最適化できます。

<table>
    <thead>
        <tr>
            <th>Experience Cloud</th>
            <th>統合の条件</th>
            <th>使用するタイミング</th>
            <th>よくあるユースケース</th>
        </tr>
    </thead>
    <tr>
        <td rowspan="2">[!DNL Analytics] Real-Time CDPと</td>
        <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-source-connector.md" target="_blank" rel="noreferrer">エクスペリエンス [!DNL Platform] ソースコネクタ</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>Adobeを実装済みのお客様に推奨されるアプローチ [!DNL Analytics]を使用し、このデータを Experience に最もすばやく取り込む方法を求めている [!DNL Platform] を使用して、リアルタイム顧客プロファイルで使用できます。</li>
                <li>リアルタイム顧客プロファイルに対するデータの可用性がデータ収集時から 2 ～ 30 分になり、データレイクに対する可用性が最大 90 分になる場合。</li>
            </ul>
        </td>
        <td>
            <ul style="margin-top: 0;">
                <li>簡単な、ユーザーインターフェイスによって開始されたワークフロー。</li>
                <li>コピーするユーザーインターフェイスのマッピング [!DNL Analytics] prop および eVar を新しい XDM フィールドに追加します。</li>
                <li>リアルタイムの顧客プロファイルと顧客ジャーニーから最速で価値を得る方法 [!DNL Analytics].</li>
            </ul>
        </td>
    </tr>
    <tr>
       <td><a href="../../integrations/tutorials/analytics-rtcdp/experience-platform-edge.md" target="_blank" rel="noreferrer">エクスペリエンス [!DNL Platform] Edge</a></td>
        <td>
            <ul style="margin-top: 0;">
                <li>新しい [!DNL Analytics] 実装を使用するか、長期戦略を実装する場合に使用します。</li>
                <li>デバイスからエクスペリエンスに直接データを送信 [!DNL Platform] AEP Web SDK、AEP Mobile SDK、または Edge Network Server API を使用する。</li>
                <li>新規のお客様または既存のお客様で、 [!DNL Analytics] リアルタイム顧客プロファイルでのデータの可用性が、同じページおよび次のページのパーソナライゼーションの使用例をサポートする。</li>
            </ul>
        </td>
        <td>
            <ul style="margin-top: 0;">
                <li>収集したデータを使用して、使用事例をサポートするための最大レベルの制御を提供します。</li>
                <li>クライアント側のデータは、XDM フィールドに簡単にマッピングできます。</li>
                <li>リアルタイム顧客プロファイルに対するデータの可用性を最も迅速に実現します。</li>
            </ul>
        </td>
    </tr>            
</table>
