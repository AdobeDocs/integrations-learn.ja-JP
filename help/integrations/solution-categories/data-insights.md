---
title: データインサイトとアクティベーションのアプリケーション統合
description: 組織全体でオンラインおよびオフラインのデータインサイトを使用して、任意のチャネルでリアルタイムのパーソナライゼーションを推進します。
exl-id: 9f22085a-306e-48e8-9b86-6429d851df58
source-git-commit: 509b227f360718e81fb19d3a4d30aebf9de49e5a
workflow-type: tm+mt
source-wordcount: '541'
ht-degree: 1%

---

# データインサイトとアクティベーション

組織全体でオンラインおよびオフラインのデータインサイトを使用して、任意のチャネルでリアルタイムのパーソナライゼーションを推進します。

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
  <!--  ROW 2  -->
 <tr>
   <td rowspan="8"><b>データ分析とレポート</b></td>

<!--  ROW 2a  -->
<td>Adobe[!DNL Target] を使用し、Adobe[!DNL Analytics] を通じて包括的なレポートを生成することで、A/B テストを含む最適化テストの結果を分析します。</td>
   <td><ul style="margin-top: 0;">
        <li>リッチ分析レポートで A/B テスト結果を表示します。</li>
       </ul></td>
   <td><a href="../integrations-between-applications/target/target-analytics.md" target="_blank" rel="noopener noreferrer">[!DNL Target] and [!DNL Analytics]</a></td>
  </tr>

<!--  ROW 2b  -->
<tr>
   <td>Audience Managerセグメントデータを [!DNL Analytics] に送信して、より深いオーディエンス分析、検出および最適化を行います。</td>
    <td><ul style="margin-top: 0;">
        <li>ユーザーをより深く分析するために、サードパーティセグメントデータを [!DNL Analytics] に送信します。</li>
        <li>CRM データを [!DNL Analytics] に送信して、ユーザー分析に含めます。</li>
       </ul></td>
   <td><a href="../integrations-between-applications/aam/aam-analytics.md" target="_blank" rel="noopener noreferrer">Audience Managerと [!DNL Analytics]</a></td>
 </tr>

<!--  ROW 2c -->
<tr>
   <td>パーソナライゼーションと広告プラットフォームのオーディエンスを拡張します。</td>
    <td><ul style="margin-top: 0;">
        <li>サーバーサイド転送を使用して [!DNL Analytics] データをAudience Managerに送信し、セグメントを作成します。</li>
       </ul></td>
   <td><a href="../integrations-between-applications/aam/aam-analytics.md" target="_blank" rel="noopener noreferrer">Audience Managerと [!DNL Analytics]</a></td>
 </tr>

<!--  ROW 2d  -->
<tr>
   <td>AEM Formsと [!DNL Analytics] を使用して、デジタルフォームに対するユーザーエンゲージメントをトラッキング、分析およびレポートします。 </td>
   <td><ul style="margin-top: 0;">
        <li>入力済みのフォームフィールドやエラーが発生したフォームフィールドなど、フォーム送信のディメンションと指標に関するレポート。</li>
       </ul></td>
   <td><a href="../integrations-between-applications/experience-manager/experience-manager-analytics.md" target="_blank" rel="noopener noreferrer">AEM Formsと [!DNL Analytics]</a></td>
 </tr>

<!--  ROW 2e  -->
<tr>
   <td>包括的なレポートとインサイトを実現するAdobe[!DNL Analytics] を使用して、AEM Sites web サイト上でのユーザーアクティビティをトラッキング、分析およびレポートします。</td>
   <td><ul style="margin-top: 0;">
        <li>サイトページの主要指標を追跡、分析およびレポートします。</li>
        <li>[!DNL Analytics] レポートを使用して、ユーザーエクスペリエンスとコンテンツ戦略に関するデータ駆動型の決定を行います。</li>
        <li>上位および下位の変換パスを分析します。</li>
       </ul></td>
   <td><a href="../integrations-between-applications/experience-manager/experience-manager-analytics.md" target="_blank" rel="noopener noreferrer">AEM Sitesと [!DNL Analytics]</a></td>
 </tr>

<!--  ROW 2f  -->
<tr>
   <td>プレクリック指標 [!DNL Campaign] コンバージョン率を使用して、Adobeおよびメールマーケティングキャンペーンに関する包括的なインサイトを得ます。</td>
   <td><ul style="margin-top: 0;">
        <li>メールキャンペーンのクリック後のコンバージョン指標を追跡、分析、レポートします。</li>
        <li>キャンペーンを [!DNL Analytics] で収集された他のディメンションにドリルダウンします。</li>
        <li>事前クリックおよび事後クリックのキャンペーン指標を 1 つのレポートに表示します。</li>
       </ul></td>
   <td><a href="../integrations-between-applications/campaign/campaign-analytics.md" target="_blank" rel="noopener noreferrer">[!DNL Campaign] and [!DNL Analytics]</a></td>
 </tr>

<!--  ROW 2g  -->
<tr>
   <td>選択した主要指標 [!DNL Commerce] ディメンションを使用して、Adobeとストアパフォーマンスに関する包括的なインサイトを得ます。</td>
   <td><ul style="margin-top: 0;">
        <li>コマースアクティビティに関するデータインサイトとレポート。</li>
        <li>選択した主要指標 [!DNL Commerce] ディメンションを使用して、Adobeとストアパフォーマンスに関する包括的なインサイトを得ます。</li>
       </ul></td>
   <td><a href="../integrations-between-applications/commerce/commerce-analytics.md" target="_blank" rel="noopener noreferrer">[!DNL Commerce] and [!DNL Analytics]</a></td>
 </tr>

<!--  ROW 2h  -->
<tr>
   <td>カスタマージャーニー[!DNL Analytics] ークフロー [!DNL Analytics]Analysis WorkspaceでAdobeと行動データを使用します。</td>
   <td><ul style="margin-top: 0;">
        <li>チャネルエンゲージメントとコンバージョンを分析します。</li>
        <li>上位の製品カテゴリと製品について説明します。</li>
        <li>ツールの使用状況の分析を実行して、セルフサービスエクスペリエンスを最適化します。</li>
       </ul></td>
   <td><a href="../integrations-between-applications/analytics/analytics-customer-journey-analytics.md" target="_blank" rel="noopener noreferrer">[!DNL Analytics] およびカスタマージャーニー [!DNL Analytics]</a></td>
 </tr>


<!--  Row 3  -->
<tr>
  <td rowspan="5"><b>パーソナライゼーションとマーケティングのためのオーディエンスの拡張</b></td>
 </tr>

<!--  ROW 3a  -->
<tr>
  <td>マルチチャネルデータソースを使用して、パーソナライゼーションやリマーケティング戦術に使用するオーディエンスを作成します。</td>
  <td><ul style="margin-top: 0;"><li>宛先に配信するためのReal-Time CDPへのオーディエンスセグメントの送信</li>
     </ul></td>
  <td><a href="../integrations-between-applications/rtcdp/rtcdp-cja.md" target="_blank" rel="noopener noreferrer">カスタマージャーニー[!DNL Analytics] とリアルタイムのカスタマーデータ [!DNL Platform]</a></td>
 </tr>

<!--  ROW 3c  -->
<tr>
  <td>オーディエンスとプロファイルデータでマーケティングキャンペーンを強化します。</td>
  <td><ul style="margin-top: 0;">
        <li>オーディエンスのセグメント化に使用する AEP データでマーケティングキャンペーンを強化します。</li>
      </ul></td>
   <td><a href="../integrations-between-applications/campaign/campaign-rtcdp.md">[!DNL Campaign] v8 およびリアルタイムの顧客データ [!DNL Platform]</a></td>
 </tr>

<!--  ROW 3d  -->
<tr>
  <td>パーソナライゼーションやリマーケティングに使用するオーディエンスをReal-Time CDPで作成するには、Audience Managerセグメントを使用します。</td>
  <td><ul style="margin-top: 0;">
        <li>Web サイト、モバイルアプリ、またはサポートされている広告チャネルで、匿名のデジタルオーディエンスのターゲティングとパーソナライゼーションを実行します。</li>
        <li>既知のデバイスと行動特性に基づいて、ランディングページと事前認証エクスペリエンスを最適化します。</li>
        <li>Audience Managerのサードパーティデータネットワークを活用して、ターゲティング用のオーディエンスをさらに絞り込み、拡張します。</li>
      </ul></td>
  <td><a href="../integrations-between-applications/aam/aam-rtcdp.md" target="_blank" rel="noopener noreferrer">Audience Managerおよびリアルタイムの顧客データ [!DNL Platform]</a></td>
 </tr>

<!--  ROW 3e  -->
<td>パーソナライゼーションやリマーケティング戦術で使用するオーディエンスを作成するために、[!DNL Analytics] のデータを使用します。</td>
   <td><ul style="margin-top: 0;"><li>デバイスまたはサポートされている広告チャネルで、デジタルオーディエンスのターゲティングとパーソナライゼーションを実行します。</li>
           <li>デバイスと行動属性に基づいて、既知の顧客ランディングページと匿名エクスペリエンスを最適化します。</li>
           <li>メールや SMS など、既知のチャネルに対してオーディエンスをアクティブ化します。</li>
        </ul></td>
   <td><a href="../integrations-between-applications/analytics/analytics-rtcdp.md" target="_blank" rel="noopener noreferrer">[!DNL Analytics] およびリアルタイムの顧客データ [!DNL Platform]</a></td>


<!--  ROW 4  -->
<tr>
   <td><b>マーケティング画像の使用状況とパフォーマンスの測定</b></td>
   <td>AEM AssetsとAdobe [!DNL Analytics] を統合して、マーケティング画像の効果をトラッキングおよび分析します。</td>
   <td><ul style="margin-top: 0;"><li>アセットのパフォーマンスの追跡と分析。</li>
           <li>ユーザーエンゲージメントを分析します。</li>
           <li>コンテンツ戦略を最適化します。</li>
        </ul></td>
   <td><a href="../integrations-between-applications/experience-manager/experience-manager-analytics.md" target="_blank" rel="noopener noreferrer">AEM Assetsと [!DNL Analytics]</a></td>
 </tr>
 </tbody>
 </table>
