---
title: GenStudio for Performance MarketingとAEM Assetsの設定
description: Adobe GenStudioとGenStudio for Performance MarketingおよびAEM Assetsを連携させ、コンテンツ制作を効率化して、ブランドの一貫性を確保しましょう。
solution: Experience Manager, Experience Manager as a Cloud Service, GenStudio for Performance Marketing
version: Experience Manager as a Cloud Service
feature-set: Experience Manager Assets, GenStudio for Performance Marketing
topic: Content Supply Chain
role: User
level: Intermediate
doc-type: Article
duration: 416
last-substantial-update: 2024-11-19T00:00:00Z
index: true
hidefromtoc: false
jira: KT-16484
exl-id: b63cfe6e-a530-4ca4-9e8e-16c54478054f
source-git-commit: 2d898df7e49f6a14c162973145592f0d3fdd1646
workflow-type: tm+mt
source-wordcount: '372'
ht-degree: 16%

---

# GenStudio for Performance MarketingとAEM Assetsの設定

[‹ AEM AssetsとGenStudio for Performance Marketingに戻る概要](./overview.md)

Adobe GenStudioとAEM Assets as a Cloud ServiceおよびGenStudio for Performance Marketingの使用を開始するには、必要な製品がプロビジョニング、有効化、設定されていることを確認します。 具体的には、次のアクセス権が必要です。

* AEM Assets as a Cloud Service
* AEM Assets Content Hub
* パフォーマンスマーケティング用の GenStudio

これらの製品を統合するために、利用可能であること、設定してユーザーがアクセスできることを確認する以外に、追加の設定は必要ありません。

## ガイドの設定

これらのAdobe製品がまだ設定および有効になっていない場合は、次のガイドを参照して詳細な設定手順を確認してください。

<!--
CARDS 

* https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view
   {title=Set up AEM Assets}
* https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/content-hub/set-up
   {title=Enable AEM Assets Content Hub}
* https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/get-started
   {title=Set up GenStudio for Performance Marketing}
   {image=https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/media_1dd8829962c9e37e1251f3d2d92f5d72c8a58cdaf.png?width=2000&format=webply&optimize=medium}

-->
<!-- START CARDS HTML - DO NOT MODIFY BY HAND -->
<div class="columns">
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Set up AEM Assets">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view" title="AEM Assetsの設定" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view./media_1e4b209baa6169af9b0aefff8a2f1f39816aa6b42.png?width=400&format=png&optimize=medium" alt="AEM Assetsの設定"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view" target="_blank" rel="referrer" title="AEM Assetsの設定">AEM Assetsの設定</a>
                    </p>
                    <p class="is-size-6">AssetsビューでAEM Assets as a Cloud Serviceを操作する方法について、製品に関する知識を深めることを目的とした厳選されたビデオプレイリストをご確認ください。</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">詳細情報</span>
                </a>
            </div>
        </div>
    </div>
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Enable AEM Assets Content Hub">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-learn/assets/content-hub/set-up" title="AEM Assets Content Hubを有効にする" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3433513/?format=jpeg&nocache=1733417775065" alt="AEM Assets Content Hubを有効にする"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-learn/assets/content-hub/set-up" target="_blank" rel="referrer" title="AEM Assets Content Hubを有効にする">AEM Assets Content Hubを有効にする</a>
                    </p>
                    <p class="is-size-6">AEM as a Cloud ServiceでAdobe Experience Manager Assets Content Hubを設定する方法について説明します。</p>
                </div>
                <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-learn/assets/content-hub/set-up" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">所要時間</span>
                </a>
            </div>
        </div>
    </div>
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Set up GenStudio for Performance Marketing">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/get-started" title="GenStudio for Performance Marketingの設定" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/media_1dd8829962c9e37e1251f3d2d92f5d72c8a58cdaf.png?width=400&format=webply&optimize=medium" alt="GenStudio for Performance Marketingの設定"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/get-started" target="_blank" rel="referrer" title="GenStudio for Performance Marketingの設定">GenStudio for Performance Marketingの設定</a>
                    </p>
                    <p class="is-size-6">パフォーマンスマーケティング用の GenStudio の使用を開始して、ブランドに合わせた新しいマーケティングコンテンツを生成する方法について説明します。</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/get-started" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">詳細情報</span>
                </a>
            </div>
        </div>
    </div>
</div>
<!-- END CARDS HTML - DO NOT MODIFY BY HAND -->

<br/>
<br/>
