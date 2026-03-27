---
title: 大規模なパーソナライゼーションを実現するアプリケーション統合
description: カスタマージャーニーのあらゆる瞬間にパーソナライズされた体験を。
exl-id: 6d18813d-950c-40ae-8d5b-80bf389358fc
source-git-commit: fc60646e49dcd32f833669e05e82397386eb68d9
workflow-type: tm+mt
source-wordcount: '610'
ht-degree: 1%

---

# Personalizationの大量運用

競争の激しいデジタル主導の今日の状況では、顧客は自身の好みやニーズに合わせた体験を期待するようになっています。 「Adobe Adobe Experience Cloudの機能を活用することで、広範な顧客データを収集、分析し、行動、興味関心、嗜好に関する貴重なインサイトを獲得できます」。 顧客を詳細に把握することで、さまざまな顧客接点をまたいで、パーソナライズされたエクスペリエンスを容易に提供し、有意義で魅力的なインタラクションを実現できます。 Adobe Experience Cloudを活用することで、パーソナライゼーションの可能性を最大限に引き出し、顧客とのつながりを強化し、ロイヤルティを育み、ビジネスの成長を促進できます。

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
        ユーザーに基づいて署名用のコミュニケーションドキュメントを生成します
        選択/環境設定：
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            AEMのデータに基づいて動的に生成されたNDAを提示する
            Formsへの署名用の送信
          </li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-acrobat-sign.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM FormsとSign</a
        >
      </td>
    </tr>
    <tr>
      <td rowspan="2"><strong>データ分析とレポート</strong></td>
      <td>
        デジタルエクスペリエンスからの行動データの分析<br />Adobeの使用
        カスタマージャーニーのAnalysis Workspaceの[!DNL Analytics]行動データ
        [!DNL Analytics]。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>コンバージョンの上位/下位のパスを分析</li>
          <li>チャネルのエンゲージメントとコンバージョンを分析</li>
          <li>最も閲覧されたコンテンツを把握</li>
          <li>上位の製品カテゴリと製品について</li>
          <li>
            ツール使用分析を実施して、セルフサービス体験を最適化する
          </li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-customer-journey-analytics.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics]とお客様のジャーニー[!DNL Analytics]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        パーソナライゼーション活動のレポート <br />最適化の分析
        Adobe [!DNL Target]と次の機能を利用して、A/B テストを含むテスト結果を行います。
        Adobe [!DNL Analytics]を通じて包括的なレポートを作成しています。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>豊富な分析レポートでA/B テストの結果を表示したい</li>
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
        Adobe Experience Manager Sitesのネイティブ機能を活用して、動的コンテンツでメール配信をパーソナライズし
        Adobe [!DNL Target]の機能。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>顧客のメールにパーソナライズされたオファーを追加する</li>
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
        <strong> パーソナライゼーションと広告プラットフォームのオーディエンスを拡大</strong>
      </td>
      <td>
        Audience Manager セグメントを使用して、Real-Time CDPで次のオーディエンスを作成します
        パーソナライゼーションとリマーケティング戦術での利用：
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            匿名のデジタルオーディエンスのターゲティングとパーソナライゼーションを
            web サイト、モバイルアプリ、サポートされている広告チャネル
          </li>
          <li>
            に基づいて、ランディングページと事前認証エクスペリエンスを最適化します
            既知のデバイスおよび行動特性
          </li>
          <li>
            Audience Managerのサードパーティデータネットワークを活用して、さらなる進化を遂げましょう
            ターゲティング用にオーディエンスを絞り込み、拡大
          </li>
          <li>RTCDPへのAudience Manager セグメントの共有</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/aam/aam-rtcdp.md"
          target="_blank"
          rel="noopener noreferrer"
          >Audience ManagerとReal-Time Customer Data [!DNL Platform]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        [!DNL Analytics] データを使用して、パーソナライゼーションまたはパーソナライゼーションで使用するオーディエンスを作成する
        リマーケティング戦術：
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>
            デジタルオーディエンスのターゲティングとパーソナライゼーションをデバイスまたは
            サポートされている広告チャネル：
          </li>
          <li>
            既知の顧客ランディングページと匿名の顧客体験を最適化
            暗黙的なパーソナライゼーションを可能にします。
          </li>
          <li>電子メールやSMSなどの既知のチャネルに対してオーディエンスをアクティベートできます。</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/analytics/analytics-customer-journey-analytics.md"
          target="_blank"
          rel="noopener noreferrer"
          >[!DNL Analytics]とリアルタイム顧客データ [!DNL Platform]</a
        >
      </td>
    </tr>
    <tr>
      <td rowspan="3"><strong>web エクスペリエンスのパーソナライズ</strong></td>
      <td>
        シングルページアプリケーション（SPA）エクスペリエンスを効果的にカスタマイズ
        Adobe [!DNL Target]とAEM ヘッドレスを組み合わせて使用しています。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>SPAおよびモバイルアプリのパーソナライゼーション</li>
          <li>パーソナライズされたAPI応答：</li>
          <li>[!DNL Target]コンテンツ配信を自動化。</li>
          <li>A/B テストのバリエーション：</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM ヘッドレスおよび[!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        AEM Sitesを効果的に活用して、カスタマイズされたweb サイト体験を提供する
        Adobe [!DNL Target]を追加します。
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>AEMのweb サイトのパーソナライゼーション：</li>
          <li>A/B テストのバリエーション：</li>
          <li>利用者の行動にもとづく行動ターゲティング。</li>
          <li>複数のシステムからのユーザーデータをつなぎ合わせることで、既知顧客のパーソナライゼーションを実現し、顧客の全体像を提供します。</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/experience-manager/experience-manager-target.md"
          target="_blank"
          rel="noopener noreferrer"
          >AEM Sitesと[!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td>
        AEMとAdobe [!DNL Target]の統合に関する実用的なヒント
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>スケーラブルなPersonalizationでのエクスペリエンスフラグメントの使用</li>
          <li>ContextHub セグメントをターゲットオーディエンスにミラーリングする</li>
          <li>エクスペリエンスフラグメントをターゲット対応にする</li>
          <li>ローンチワークフローへのターゲット検証の構築</li>
          <li>Dynamic Media + Target for Visual Personalizationの組み合わせ</li>
          <li>Author for Edge Delivery</li>
        </ul>
      </td>
      <td>
        <a
          href="https://experienceleague.adobe.com/ja/perspectives/personalization-that-scales-practical-tips-for-aem-adobe-target-integration"
          target="_blank"
          rel="noopener noreferrer"
          >AEM Sitesと[!DNL Target]</a
        >
      </td>
    </tr>    
    <tr>
      <td><strong>Personalise digital experiences</strong></td>
      <td>
        リアルタイム顧客プロファイルと一元管理された[!DNL Platform] セグメントの使用
        webやモバイルなどのデジタルチャネルごとにメッセージをパーソナライズできます
      </td>
      <td>
        <ul style="margin-top: 0;">
          <li>既知の訪問者に対するコンテンツのパーソナライゼーション</li>
          <li>ロイヤルティ向上</li>
          <li>解約リスクのある顧客を特定してエンゲージ</li>
          <li>リアルタイムのオファーパーソナライゼーション</li>
        </ul>
      </td>
      <td>
        <a
          href="../integrations-between-applications/rtcdp/rtcdp-target.md"
          target="_blank"
          rel="noopener noreferrer"
          > リアルタイム顧客データ [!DNL Platform]および[!DNL Target]</a
        >
      </td>
    </tr>
    <tr>
      <td><strong>リードジェネレーションの強化</strong></td>
      <td>
        リアルタイム顧客プロファイルと一元管理された[!DNL Platform] セグメントの使用
        webやモバイルなどのデジタルチャネルごとにメッセージをパーソナライズできます
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
          > リアルタイム顧客データ [!DNL Platform]および[!DNL Target]</a
        >
      </td>
    </tr>
  </tbody>
</table>
