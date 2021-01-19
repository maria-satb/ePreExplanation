# ePre研修に関する概要

# そもそもEpre研修とはなにか
## E-preの目的
自走できるエンジニアを短期間で育成し、「アプリ開発人材」として社内で活躍する人を増やすことを目的とした研修。
自社で開発できる、自走できるエンジニアが少ないという現状があり、自走できるエンジニアの要員を育成するという大きな目的がある。
今回の研修では、「モバイルアプリ開発エンジニア」の内製要員を増強を目的とした研修である。

## 参加者が期待できること
* 「アプリ開発のための学び方」を短期間で身につけることができる
* モダンな開発を体系的に学べる
* クリーンなコーディングを学べる
* 「アプリ開発人財」として登録され、社内のアプリ開発プロジェクトに参画し活躍できる

## 組織が期待できること
* モバイルアプリ開発エンジニアを内製要員として確保し「サービス化」を推し進めることができる

## 本研修の参加者
別資料「参加者一覧」参照のこと

## 本研修のカリキュラム概要
![カリキュラム](https://i.gyazo.com/d83025daa94f8fdb08bbeeeb90f0083d.png)

### サーバーサイドの利用言語：GO言語
Googleが開発したプログラミング言語。
「シンプルかつ高速な処理が可能なプログラミング言語」で学習難易度が低く、構造がシンプルなため、「誰が読んでも分かるプログラムを書きやすい」という特徴がある。

![GOロゴ](https://upload.wikimedia.org/wikipedia/commons/thumb/2/23/Go_Logo_Aqua.svg/144px-Go_Logo_Aqua.svg.png)
![GOロゴ](https://i.gyazo.com/6d706bdbbb3934fd184f415842f8b94f.png)

### データベース：PostgreSQL

### モバイルアプリの利用言語：Swift
iPhoneやiPad、MacなどのApple社製品向けのアプリ開発が可能なプログラミング言語。
開発にはXcodeという開発アプリを使う。
SwiftもGO言語同様、コードが読みやすい、書きやすいという特徴がある。

![GOロゴ](https://i.gyazo.com/3a2ec527e0495d78890baf2c99c950b2.png)

## カリキュラム詳細
3ヶ月のカリキュラム
別資料「カリキュラム」参照のこと

## 一日の流れ
![カリキュラム](https://i.gyazo.com/f5420a94aadb4652806f7b7cf8265643.png)

## 講義形式
Zoomによる完全リモートでの講義。

講師：千葉・外出先(都内？)・アメリカ・ポーランド

受講生：原宿・大阪・松山・自宅

10月のGO言語、データーベースは、一から講義形式でレクチャーを行ない、午後に演習問題を解いていく形式で進めた。
11月のSwiftについては、簡単なレクチャーの後はひたすら演習問題となり、教えてもらうのではなく自分で調べる形式で進めた。

## 講義や演習で使ったアプリやツール
### slack
講師への質問や受講生同士のコミュニケーションはSlackを使ってやり取りを行った。
* 勤怠連絡
* 全体向けの連絡
* 講義に関する質疑応答
* 講義の動画をまとめたチャネル
* チーム開発用のグループ
* iOSビギナーズチャンネル

### scrapbox
情報共有ができるツール。
研修では、ノート代わりに利用していた。
無料だと非公開か全公開の2つの公開設定を選べる。

安斎のノート
https://scrapbox.io/mobileAppLearning/

佐藤さんのノート
https://scrapbox.io/EPreTrainingProgram/

### skitch
ノート作成でよく利用していたMac用のスクリーンショット&画像加工アプリ。
任意の場所をスクリーンショット保存し、スクリーンショットに書き込みがかんたんにできる。

サンプル

![イメージ](https://i.gyazo.com/90917d33dc6399cfd20691427dbcc16f.png)

### draw.io
フローチャートやERD図を簡単に作れるツール。

サンプル

![イメージ](https://i.gyazo.com/504dccc52f1f1a35992e74d60149de83.png)

### gitとgithub、fork
今回の演習開発では以下の方法でソース管理を行った。

①課題がアップされているGitHubのリポジトリから、GitHubの自分のリポジトリに持ってくる（フォーク）

②①でコピーした自分のリポジトリのソースコードを、MacBookにダウンロード（クローン）

③MacBook上で開発、開発内容はGitでバージョン管理

④完成したソースコードをコミットし、GitHubの自分のリポジトリにアップロード（プッシュ）

⑤自分のリポジトリに反映されたソースコードを、大元のリポジトリの方にプルリクエストし、コードレビューを講師に依頼する。


基本的に課題はこの流れで行うことで、GitHubやGitの簡単な操作や使い方を学んだ。

### VSCode、XCode
実際にコーディングで利用したアプリ。
VSCodeはGO言語の開発で利用、XCodeはSwiftの開発で利用した。

###  postico
今回の演習で利用した、PostgreSQLのデータをGUIでいじれるソフト。

### postman
APIを開発する際に多用したアプリ。
Postmanを利用すると簡単にAPIリクエストを送信して、レスポンスを取得できるので、API開発に重宝した。

## 今回の研修でできるようになったこと
### 最終演習で行ったこと
3ヶ月の研修の成果として最終演習を通じ、モバイル側からリクエストを送信するとサーバ側での処理結果が返ってくる、という一連の動作について実装した。
演習問題に費やせる時間が個人によって異なったため最終演習のレベル感が人によって大きく異なったが、クライアントのリクエストに応じてDBの検索や更新ができるような機能の実装ができるようになった。

![簡単なシステム構成](https://i.gyazo.com/e4b854b407b848ea7a1e032c9a6bdbeb.png)

### 研修によってその他に得たもの
* コーディングの際に不明点が出た際の調べる力が身についた。
    * 公式ドキュメントを参照する癖をつける
    * Googleは日本語サイトではなくGoogleUSAを利用する（公式ドキュメントが埋もれるため）
    * 1年以上前の記事は参考にしない

* クリーンコーディングの実践
みんなにとって理解しやすいコードはクリーンコードと呼ばれるが、課題はこのクリーンコードを意識して実装するように指導を受けた。
他人のコードをレビューする機会があるため、このへんは興味があったが、研修を受講する前よりは、良いコードがどういうものなのかの理解が深まった気がする。

     * 一貫性
同じような処理は同じような方法で書く。

    * 簡潔性
コードは短いほうがバグが少ない。

    * 命名規則
名前は丁寧に、読んだら何をする変数なのかがわかるようにする。

    * 関数と関数型のスタイル
引数は少ない方がよい。副作用がなく、明確な戻り値がある方が良い。

   * コメント
原則コメントは書かない。（個人的には衝撃）
コメントを書かなくても読めばわかるように書くのがモダンなプログラミング言語の特徴。

   * コードの構造
インデントを整える。
何もかもをmainで書かず、モジュール化を心がける。
似たような処理はコピー作成せず1つの処理でまとめる。
1つの関数では1つの役割のみとする。

* クリーンアーキテクチャという考え方についてを参考までに講師より教えてもらった。
研修ではクリーンアーキテクチャというキーワードと簡単な概念の説明はあったものの、実際の演習問題に活かすところまでは行かず。
今後設計に携わるなら一度目を通したほうがいいという情報だけ。

* GO言語、Swiftをひととおり使えるようになったが
実際にサーバーサイドとモバイルの両方を経験し、基本的な実装ができるようになったが、自分の作りたい機能を実装できるようになるには実装経験を積まなければならないということを改めて実感した。

書籍

https://www.kadokawa.co.jp/product/301806000678/


## 実際に研修で作ったアプリのデモ
佐藤さんによるデモ

https://github.com/KAZZ5630/stocktaking_iOS_swift

## 最後にE-Preを通じて感じた感想
### 安斎コメント
* 一通りコーディングすることでサーバ側とモバイル側がどう連携しているのか理解できて非常にためになった。
他の人のコードで何をしているのかをイメージしやすくなった。

* 業務都合による離脱影響が大きく、後半は辛かった
GO言語は結構しっかり講義をしてもらえたため、業務都合で講義が受けられなかった場合でも、録画された動画を見れば大体の内容が理解でき、後追いで演習問題も苦戦することがなかった。
Swiftについては自主的に必要な機能を調べて進めていくスタイルだったので、業務都合で時間が取れないとひたすら演習が遅れていくという状況が続いたことから、十分にSwiftの勉強ができなかったのが心残り。
最後の演習もSwiftの理解を深めるため、サーバーサイドとのAPI連携は最低限として、Swiftでの開発にほとんどの時間を費やした。

* 日本語のドキュメントが少なく調査に苦戦
GOもSwiftも公式ドキュメントが英語のみなので、翻訳サイトを駆使したり英語を読み解くのが大変だった。
また概念の説明があっても実際どう使うかについて、公式ドキュメントだと説明が少なく、調査に時間を要することも多かった。

### 佐藤さんコメント
* 直近の業務ではスクリプト言語しか触っていなかったのに、自力でサーバー側もiOSも作り上げられたのは自分でも驚き。
* 自学自習スタイルで三か月間、試行錯誤する時間が取れたことで、iOS開発なら自走できるのではないかと思えるようになっている。
* 時間がたくさんある中で、（業務と違って納期と報告資料作成に追われることなく）自分が気になったところをしっかり突き詰めることができ、とても満足している。
