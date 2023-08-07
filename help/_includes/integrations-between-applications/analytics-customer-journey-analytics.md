---
source-git-commit: 94b074c17e976e4f4acbb1ff41aacfc9bf74744c
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 2%

---


# 統合Adobe [!DNL Analytics] 顧客ジャーニー [!DNL Analytics]

{{analytics-description}}

{{customer-journey-analytics-description}}

統合Adobe [!DNL Analytics] 顧客ジャーニー [!DNL Analytics] は、主なメリットを提供します。

+ **包括的なインサイト** を顧客の行動や好みに追加します。
+ **シームレスなクロスチャネルトラッキング** 全体的な見方を示す
+ **統合されたデータとレポート** を使用して正確な分析を行うことができます。
+ **パーソナライゼーションの強化** 顧客エンゲージメントの向上
+ **リアルタイムデータインサイト** 迅速な意思決定を可能にします。

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
            <td rowspan="2">[!DNL Analytics] および顧客ジャーニー [!DNL Analytics]</td>
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-source-connector.md" target="_blank" rel="noreferrer">エクスペリエンス [!DNL Platform] ソースコネクタ</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>Adobeを実装済みのお客様に推奨されるアプローチ [!DNL Analytics]を使用し、このデータを Experience に最もすばやく取り込む方法を求めている [!DNL Platform] 顧客ジャーニーで使用する [!DNL Analytics].</li>
                    <li>顧客プロファイルに対するデータの可用性がデータ収集時から 2 ～ 30 分になり、データレイクへの可用性が最大 90 分になる場合。</li>
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
            <td><a href="../../integrations/tutorials/analytics-cja/experience-platform-edge.md" target="_blank" rel="noreferrer">エクスペリエンス [!DNL Platform] Edge</a></td>
            <td>
                <ul style="margin-top: 0;">
                    <li>新しい [!DNL Analytics] 実装を使用するか、長期戦略を実装する場合に使用します。</li>
                    <li>デバイスからエクスペリエンスに直接データを送信 [!DNL Platform] AEP Web SDK、AEP Mobile SDK、または Edge Network Server API を使用する。</li>
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
    </tbody>          
</table>
