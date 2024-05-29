---
nav_title: ユーザーインストールについて理解する
article_title: ユーザーインストールについて理解する 
page_order: 7
page_type: reference
description: "この記事では、ユーザーインストール (インストールアトリビューションのトラッキング) と、キャンペーン内でこの情報を使用するさまざまな方法について説明します。"
tool:
  - Campaigns
  - Segments
---

# ユーザーインストールについて理解する

> インストールアトリビューションのトラッキングは、ユーザーとの初期関係を改善する理想的な方法です。ユーザーがアプリをインストールする方法、場所、そしてその理由を知ることで、ユーザーの特性を把握し、どのようにアプリを紹介すべきかをよりよく理解することができます。 

Braze 自体はインストールアトリビューションのトラッキングを提供しませんが、Branch や AppsFlyer などの[サービス]({{site.baseurl}}/partners/message_orchestration/attribution)と統合すると、インストールデータをシームレスに取得することができます。

## ユーザーのセグメント化

ユーザーがアプリをインストールしたら、以下の[インストールアトリビューションフィルター][2]に基づいて、セグメント化を開始できます。例えば、旅行アプリは、ビーチバケーションの割引に関連する広告から来たユーザーを、「ビーチ大好き」セグメントに追加できます。同様に、音楽アプリは、インストールに至った広告に表示された音楽のジャンルに基づいて、ユーザーをセグメント化することができます。

## ベストプラクティス

### パーソナライズされたオンボーディング

これで、ユーザーに関する詳細情報が得られたので、オンボーディングプロセスをカスタマイズできます。これは、メッセージ内の画像を好みに合わせて変更するといったシンプルなものから、インストールにつながる可能性のある広告ごとにユーザーオンボーディングを作成する複雑なプロセスまでさまざまです。ユーザーの行動を考慮に入れることが可能なメッセージの包括的なシーケンスをスケールアウトするには、[キャンバス][5] のドキュメントを参照してください。

### 広告からの参照データ

ユーザーは、プロモーションオファーやプレゼントによってアプリに惹きつけられるかもしれません。インストールアトリビューションデータを使用すると、割引コードを含むキャンペーンを送信したり、これらのプロモーションのためにインストールしたユーザーのみにオファーを送信したりできます。同様の方法で、広告に特定の製品 (動画アプリの場合は特定の映画、e コマースアプリの場合はセールなど) に関する情報が含まれている場合、キャンペーンを使ってユーザーをアプリの適切なページに送ることができます。

## 広告の効果を評価する

インストールアトリビューションデータは、さまざまなマーケティングキャンペーンの有効性を評価する際に役立ちます。どの広告やキャンペーンが最も多くのインストールにつながり、どの広告の効果が低いかを調べることで、最も魅力的な広告にリソースを集中させることができます。

[2]: {{site.baseurl}}/user_guide/engagement_tools/segments/segmentation_filters/#install-attribution
[3]: {% image_buster /assets/img_archive/install_onboarding.png %}
[5]: {{site.baseurl}}/developer_guide/rest_api/messaging/#canvas