---
title: GenStudio for Performance MarketingとAEM Assetsのセットアップ
description: Adobe GenStudioをGenStudio for Performance MarketingとAEM Assetsで設定して、コンテンツ作成を効率化し、ブランドの一貫性を確保します。
solution: Experience Manager, GenStudio for Performance Marketing
version: Cloud Service
feature-set: Experience Manager Assets, GenStudio for Performance Marketing
topic: Content Supply Chain
role: User
level: Intermediate
doc-type: Article
duration: 416
last-substantial-update: 2024-11-19T00:00:00Z
index: true
hidefromtoc: true
jira: KT-16484
exl-id: b63cfe6e-a530-4ca4-9e8e-16c54478054f
source-git-commit: 8e3adf228592b60b2a226326e885f9e7359ff232
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 7%

---

# GenStudio for Performance MarketingとAEM Assetsのセットアップ

[‹ AEM AssetsとGenStudio for Performance Marketingの概要に戻る](./overview.md)

Adobe GenStudioをAEM Assets as a Cloud ServiceおよびGenStudio for Performance Marketingで使用するには、必要な製品がプロビジョニング、有効化、設定されていることを確認します。 特に、次の場所にアクセスする必要があります。

* AEM Assetsas a Cloud Service
* AEM AssetsContent Hub
* パフォーマンスマーケティング用の GenStudio

これらの製品を統合するために、追加の設定は必要ありません。使用できるようにして、ユーザーがセットアップしてアクセスできるようにします。

## 設定ガイド

これらのAdobe製品がまだ設定されておらず、有効になっていない場合、設定手順の詳細については次のガイドを参照してください。

<!-- CARDS 

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
                        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view" target="_blank" rel="referrer" title="AEM Assetsの設定">AEM Assetsのセットアップ </a>
                    </p>
                    <p class="is-size-6">商品に関する知識を高めることを目的として、厳選されたビデオプレイリストを使用して、Assets ビューでAEM Assets as a Cloud Serviceを操作する方法を説明します。</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/video-playlists/assets-view" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細情報 </span>
                </a>
            </div>
        </div>
    </div>
    <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Enable AEM Assets Content Hub">
        <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
            <div class="card-image">
                <figure class="image x-is-16by9">
                    <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/content-hub/set-up" title="AEM Assets Content Hubを有効にする" target="_blank" rel="referrer">
                        <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3433513/?format=jpeg&nocache=1733417775065" alt="AEM Assets Content Hubを有効にする"
                             style="width: 100%; aspect-ratio: 16 / 9; object-fit: cover; overflow: hidden; display: block; margin: auto;">
                    </a>
                </figure>
            </div>
            <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
                <div class="top-card-content">
                    <p class="headline is-size-6 has-text-weight-bold">
                        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/content-hub/set-up" target="_blank" rel="referrer" title="AEM Assets Content Hubを有効にする">AEM Assets Content Hubを有効にする </a>
                    </p>
                    <p class="is-size-6">AEM as a Cloud ServiceにAdobe Experience Manager Assets Content Hubをセットアップする方法について説明します。</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/content-hub/set-up" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> ウォッチ </span>
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
                        <a href="https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/get-started" target="_blank" rel="referrer" title="GenStudio for Performance Marketingの設定">GenStudio for Performance Marketingのセットアップ </a>
                    </p>
                    <p class="is-size-6">パフォーマンスマーケティング用の GenStudio の使用を開始して、ブランドに合わせた新しいマーケティングコンテンツを生成する方法について説明します。</p>
                </div>
                <a href="https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/user-guide/get-started" target="_blank" rel="referrer" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
                    <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細情報 </span>
                </a>
            </div>
        </div>
    </div>
</div>
<!-- END CARDS HTML - DO NOT MODIFY BY HAND -->

<br/>
<br/>
