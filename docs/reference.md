# さくらのAI Engine のドキュメント

このアプリが使っている AI のサービス「さくらのAI Engine」の公式ページへのリンク集です。もっと知りたくなったときや、06 の発展課題で別のモデルや機能を試したくなったときに開いてください。

リンク先は 2026年10月19日に確認しました。ページの場所は変わることがあります。

## まず読むなら

| ページ | 書いてあること |
|---|---|
| [さくらのAI Engine（サービス紹介）](https://ai.sakura.ad.jp/sakura-ai/ai-engine/) | どんなサービスか、料金プラン |
| [利用手順](https://manual.sakura.ad.jp/cloud/ai-engine/02-howto.html) | 申し込み、アカウントトークン（この講座でいう「キー」）の作り方、API の住所、curl での動作確認 |
| [サービス基本情報](https://manual.sakura.ad.jp/cloud/ai-engine/01-basics.html) | できること（チャット、文字起こし、音声合成、RAG）、料金の考え方、注意事項 |

## API の説明書

| ページ | 書いてあること |
|---|---|
| [API ドキュメント（推論 API）](https://manual.sakura.ad.jp/api/cloud/portal/ai-engine-inference-api/index.html) | API の住所ごとに、送るデータと返ってくるデータの形。このアプリが使う `/v1/chat/completions` もここにあります |

02 でのぞき窓に出ていた `model`、`messages`、`temperature`、`max_tokens` は、この説明書の「Chat completions」の部分に書かれている項目です。説明書には、このアプリで使っていない項目（`stream` など）も載っています。

## 画面で試す・管理する

| ページ | 書いてあること |
|---|---|
| [Playground](https://manual.sakura.ad.jp/cloud/ai-engine/playground.html) | プログラムを書かずに、ブラウザの画面でモデルとプロンプトを試す方法 |
| [操作ガイド](https://manual.sakura.ad.jp/cloud/ai-engine/03-operation-guide.html) | コントロールパネルの操作方法 |
| [コントロールパネル](https://secure.sakura.ad.jp/ai/?gastep=ai-engine/) | トークンの作成・削除、利用状況の確認（さくらインターネットのアカウントが必要） |

Playground で同じ言葉を試すと、このアプリを通したときと結果を比べられます。プロンプトは、のぞき窓の「AI への指示（system）を読みやすくしたもの」からコピーできます。

## 困ったとき・規約

| ページ | 書いてあること |
|---|---|
| [メンテナンス・障害情報](https://help.sakura.ad.jp/status/) | サービスが止まっていないか。画面に「AI のサーバーにつながりませんでした」が続くときに確認します |
| [提供するモデルのライセンス表示](https://manual.sakura.ad.jp/cloud/ai-license.html) | 各モデルの利用条件 |
| [サービス約款](https://www.sakura.ad.jp/corporate/agreement/) | 利用規約 |
