---
title: 大規模なパーソナライゼーションのためのアプリケーション統合
description: パーソナライズされたエクスペリエンスをすべての瞬間の一部にします。
exl-id: 6d18813d-950c-40ae-8d5b-80bf389358fc
source-git-commit: 132c892723d29d415d07093ef8514ff8c9b7b1db
workflow-type: tm+mt
source-wordcount: '533'
ht-degree: 1%

---

# 大規模なPersonalization

今日の競争の激しいデジタル主導の状況の中で、お客様は独自の好みやニーズに合わせたエクスペリエンスを期待するようになっています。 Adobe Experience Cloudの機能を活用することで、お客様の幅広いデータを収集および分析し、行動、興味、好みに関する貴重なインサイトを提供できます。 この深い理解により、様々なタッチポイントをまたいでパーソナライズされたエクスペリエンスの配信が容易になり、有意義で魅力的なインタラクションを実現できます。 Adobe Experience Cloudの機能を活用することで、パーソナライゼーションの可能性を最大限に引き出し、お客様とのつながりを強化し、ロイヤルティを育成し、ビジネスの成長を促進します。

<table>
 <thead>
    <tr>
      <th>ユースケース</th>
      <th>説明</th>
      <th>例</th>
      <th>アプリケーション</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>パーソナライズされたPDF ドキュメントの作成</strong></td>
      <td>
        ユーザーに基づいて署名するための通信ドキュメントを生成します
        選択/環境設定。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            AEMのデータに基づいて動的に生成された機密保持契約書（NDA）を提示
            署名用のForms送信
          </li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-acrobat-sign.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM Formsと署名 </a
        >
      </td>
    </tr>
    <tr>
      <td rowspan="2"><strong>データ分析とレポート</strong></td>
      <td>
        デジタルエクスペリエンスからの行動データの分析 <br />Adobeの使用
        カスタマージャーニーでのAnalysis Workspaceの行動データの [!DNL Analytics] り込み
        [!DNL Analytics]。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>上位/下位の変換パスを分析</li>
          <li>チャネルエンゲージメントとコンバージョンの分析</li>
          <li>上位に表示されたコンテンツの理解</li>
          <li>上位の製品カテゴリと製品について</li>
          <li>
            ツールの使用状況の分析を実行して、セルフサービスエクスペリエンスを最適化する
          </li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-customer-journey-analytics.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics] およびカスタマージャーニー [!DNL Analytics]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        パーソナライゼーションアクティビティ <br /> 最適化の分析のレポート
        Adobe [!DNL Target] を利用した A/B テストを含むテスト結果
        Adobe [!DNL Analytics] を通じて包括的なレポートを生成する。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>リッチ分析レポートでの A/B テスト結果の表示</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics] および [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td><strong>メール配信のパーソナライズ</strong></td>
      <td>
        を活用して、動的コンテンツでメール配信をパーソナライズします。
        Adobe [!DNL Target] の機能。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>パーソナライズされたオファーを顧客のメールに追加</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/campaign//campaign-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Campaign] および [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <strong> パーソナライゼーションと広告プラットフォームのオーディエンスを拡張 </strong>
      </td>
      <td>
        Audience Manager セグメントを使用した、Real-Time CDPでのオーディエンスの作成により、次のことを行えます
        パーソナライゼーションおよびリマーケティング戦術での使用。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            で匿名のデジタルオーディエンスのターゲティングとパーソナライゼーションを実行する
            web サイト、モバイルアプリ、またはサポートされている広告チャネル上
          </li>
          <li>
            に基づいてランディングページと事前認証エクスペリエンスを最適化
            既知のデバイスと行動特性
          </li>
          <li>
            Audience Managerのサードパーティデータネットワークを活用して、さらに詳しく
            ターゲティングのためのオーディエンスの調整と拡張
          </li>
          <li>Audience Manager セグメントのRTCDPへの共有</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/aam/aam-rtcdp.md"
          target="_blank"
          rel="noopener noreferrer"
          >Audience Managerおよび Real-Time Customer Data [!DNL Platform]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        [!DNL Analytics] パーソナライゼーションで使用するオーディエンスを作成するために、または
        リマーケティング戦術。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            デバイスでデジタルオーディエンスのターゲティングとパーソナライゼーションを実行または
            サポートされる広告チャネル。
          </li>
          <li>
            既知の顧客ランディングページと匿名エクスペリエンスの最適化
            デバイスと行動の属性に基づいています。
          </li>
          <li>メールや SMS など、既知のチャネルに対してオーディエンスをアクティブ化します。</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-customer-journey-analytics.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics] および Real-Time Customer Data [!DNL Platform]</a
        >
      </td>
    </tr>
    <tr>
      <td rowspan="2"><strong>Web エクスペリエンスのパーソナライズ</strong></td>
      <td>
        単一ページアプリケーション（SPA）エクスペリエンスの効果的なカスタマイズ
        Adobe [!DNL Target] と組み合わせたAEM ヘッドレスの利用。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>SPA とモバイルアプリのパーソナライズ機能</li>
          <li>パーソナライズされた API の応答。</li>
          <li>[!DNL Target]ed コンテンツ配信。</li>
          <li>A/B テストのバリエーション。</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM ヘッドレスと [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        AEM Sitesを有効活用してカスタマイズされた web サイトエクスペリエンスを提供
        とAdobe [!DNL Target] を使用してパーソナライズ機能を実行できます。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>AEM web サイトのパーソナライズ機能。</li>
          <li>A/B テストのバリエーション。</li>
          <li>ユーザー行動に基づく行動ターゲティング。</li>
          <li>複数のシステムのユーザーデータを結び付けて、顧客の 360 度のビューを提供する、既知のユーザーのパーソナライゼーション。</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM Sitesと [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td><strong>デジタルエクスペリエンスのパーソナライズ</strong></td>
      <td>
        リアルタイム顧客プロファイルと一元的に管理される [!DNL Platform] セグメントの使用
        web、モバイルおよびその他のデジタルチャネルをまたいでメッセージングをパーソナライズするには、次の手順を実行します
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>既知の訪問者に対するコンテンツのパーソナライゼーション</li>
          <li>ロイヤルティのサインアップと参加の増加</li>
          <li>チャーンのリスクがある顧客の特定と関与</li>
          <li>リアルタイムオファーのパーソナライゼーション</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/rtcdp/rtcdp-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >Real-Time Customer Data [!DNL Platform] and [!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td><strong>リードジェネレーションの強化</strong></td>
      <td>
        リアルタイム顧客プロファイルと一元的に管理される [!DNL Platform] セグメントの使用
        web、モバイルおよびその他のデジタルチャネルをまたいでメッセージングをパーソナライズするには、次の手順を実行します
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>既知の訪問者に対するコンテンツのパーソナライゼーション</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/rtcdp/rtcdp-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >Real-Time Customer Data [!DNL Platform] and [!DNL Target]</a
        >
      </td>
    </tr>
  </tbody>
</table>
