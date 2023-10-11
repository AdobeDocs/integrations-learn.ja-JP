---
title: カスタマージャーニーのアプリケーション統合
description: すべてのソースからデータを取り出して、パーソナライズされたクロスチャネルジャーニーを作成し、リアルタイムの顧客プロファイルを作成します。
exl-id: eb653b89-db0f-433a-8641-bbeb32197096
source-git-commit: 509b227f360718e81fb19d3a4d30aebf9de49e5a
workflow-type: tm+mt
source-wordcount: '286'
ht-degree: 2%

---

# カスタマージャーニー

すべてのソースからデータを取り出して、パーソナライズされたクロスチャネルジャーニーを作成し、リアルタイムの顧客プロファイルを作成します。


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
  <td><strong>ブランドアセットを使用したマーケティング販促物の作成</strong><br></td>
  <td>AEMとAdobeを使用して、電子メールマーケティングのコンテンツとテンプレートを作成および監視します [!DNL Campaign].</td>
  <td>
    <ul style="margin-top: 0;">
      <li>AEMで作成したマーケティングメールの送信</li>
    </ul>    
  </td>
  <td><a href="../integrations-between-applications/experience-manager/experience-manager-campaign.md">[!DNL Campaign] およびAEM</a></td>
</tr>

<tr>
  <td><strong>顧客データのキャプチャ</strong><br></td>
 <td>ネイティブを拡張 [!DNL Campaign] マーケティングキャンペーンのターゲティングとパーソナライゼーションをおこなうために顧客データをキャプチャする機能。</td>
  <td>
    <ul style="margin-top: 0;">
      <li>プロファイルを作成し、追加情報を収集します。 </li>
      <li>購読</li>
    </ul>
  </td>
  <td><a href="../integrations-between-applications/experience-manager/experience-manager-campaign.md">AEM Formsと [!DNL Campaign] 標準</a></td>
</tr>

<tr>
  <td><strong>リードの生成</strong><br></td>
  <td>フォーム送信からキャプチャしたデータを、リードジェネレーション、顧客セグメント化、パーソナライズされたマーケティングキャンペーンに使用します。</td>
    <td>
    <ul style="margin-top: 0;">
      <li>リードジェネレーション用に、Web およびモバイルデバイス用の動的でインタラクティブなフォームをデザインして公開します。</li>
    </ul>
  </td>
  <td><a href="../integrations-between-applications/experience-manager/experience-manager-marketo.md">Marketo EngageとForms</td>
</tr>

<tr>
  <td><strong>トランザクションメッセージの調整</strong><br></td>
  <td>リアルタイムイベントデータを使用したトリガートランザクションメッセージ。</td>
  <td>
    <ul style="margin-top: 0;">
      <li>登録や買い物かごのチェックアウト確認などの確認 E メール </li>
      <li>買い物かごの放棄</li>
    </ul>
  </td>
  <td><a href="../integrations-between-applications/campaign/campaign-analytics.md">[!DNL Campaign] and [!DNL Analytics]</a></td>
</tr>

<tr>
  <td><strong>マーケティングキャンペーン用のオーディエンスの拡大</strong><br></td>
  <td>オーディエンスとプロファイルデータでマーケティングキャンペーンを強化する。</td>
  <td>
    <ul style="margin-top: 0;">
      <li>AEP データでマーケティングキャンペーンを強化して、オーディエンスのセグメント化を実現</li>
    </ul>
  </td>
 <td><a href="../integrations-between-applications/campaign/campaign-rtcdp.md">[!DNL Campaign] v8 およびリアルタイム顧客データ [!DNL Platform]</a></td>
</tr>

<tr>
  <td><strong>E メール配信をパーソナライズ</strong><br></td>
  <td>Adobeの機能を活用して、動的コンテンツを使用して E メール配信をパーソナライズ [!DNL Target].</td>
  <td>
    <ul style="margin-top: 0;">
      <li>顧客の E メールにパーソナライズされたオファーを追加</li>
    </ul>
  </td>
  <td><a href="../integrations-between-applications/campaign/campaign-target.md">[!DNL Campaign] and [!DNL Target]</a></td>
</tr>

<tr>
  <td><strong>デジタルエクスペリエンスのパーソナライズ</strong><br></td>
  <td>リアルタイムの顧客プロファイルを使用し、一元的に管理 [!DNL Platform] web、モバイル、その他のデジタルチャネルをまたいでメッセージをパーソナライズするセグメント。</td>
  <td>
    <ul style="margin-top: 0;">
      <li>既知の訪問者に対するコンテンツのパーソナライゼーション</li>
      <li>ロイヤリティのサインアップと参加を増やす</li>
      <li>チャーンのリスクがある顧客を特定し、惹きつける</li>
      <li>リアルタイムオファーパーソナライズ機能</li>
    </ul>
  </td>
  <td><a href="../integrations-between-applications/rtcdp/rtcdp-target.md">リアルタイム顧客データ [!DNL Platform] および [!DNL Target]</a></td>
</tr>

<tr>
  <td><strong>リードジェネレーションの強化</strong><br></td>
  <td>リアルタイムの顧客プロファイルを使用し、一元的に管理 [!DNL Platform] Web、モバイル、その他のデジタルチャネルをまたいでメッセージをパーソナライズするセグメント</td>
  <td>
    <ul style="margin-top: 0;">
      <li>既知の訪問者に対するコンテンツのパーソナライゼーション</li>
    </ul>
  </td>
  <td><a href="../integrations-between-applications/rtcdp/rtcdp-target.md">リアルタイム顧客データ [!DNL Platform] および [!DNL Target]</a></td>
</tr>
</tbody>
</table>
