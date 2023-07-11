# JS 応用カリキュラム

## はじめに

このカリキュラムでは JavaScript の基本を学習された方のカリキュラムです。
もう一歩踏み込んだ内容について機能単位で解説しながら進めていく JavaScript のエキスパートカリキュラムです。
モダンスタイルの基礎から現場での応用までを視野に入れた JavaScript を本質的に理解するためのきっかけとなることを望んでおります。

## カリキュラム作成の目的と目標

### 目的：JS への理解度の向上と概念的把握が目的です。

（このカリキュラムで扱った内容の応用が現場で求められるので、あくまでも知識をつけておく程度です。ただ、知っているのと知らないのとではこの先の技術への理解度が変わってくるのでなるべく網羅的に扱います。）

### 目標：このカリキュラムを経て Vue などのフレームワークに取り組んでもらいたいので基礎的な土台形成を目標としています。

全体を通して知らない単語が頻出します。なるべく噛み砕いて説明できるように心がけて作成してますが、限界はあるのでわからない単語は調べておくと話の流れが抽象的にならずに済むのでオススメです。
また、扱う内容全てが現場で求められるというわけではなく、一部が頻出したりしなかったりと現場によって様々です。

# 環境構築

### 手順

####　クローンとビルド
リポジトリのクローンを行う
クローンが完了したらフォルダのルートディレクトリに移動して「yarn」コマンドを実行
完了したら、package ディレクトリに移動してターミナルで「yarn」コマンドを実行
エラーなどが発生せず、success が表示されたら、「yarn dev」コマンドを実行し、下記リンクにアクセス
http://localhost:3000/introduction
ホーム画面が表示されたら成功です。各章を読んで課題に取り組んでください。

### よくあるエラー

本カリキュラムは React と Next を使用して組み立てております。
もし何かしらのエラーが出た場合は、エラーログを読んで対応してください。
あり得るエラーとしては、Node のバージョンエラー、React や Next がインストールされていない場合が想定されます。
それぞれ、エラーを読んでインストールすれば解決できる内容なので、焦らず対応してください。
本カリキュラムでは Node のバージョンは*19.8.1*を使用しています。
自分の Node のバージョンを調べる方法
「node -v」
上記コマンドを入力してバージョンをチェックしてください
おそらくカリキュラムの WebPack を受講されていれば Mac なら nodebrew Windows なら nvm-windows で管理しているかと思います。
それぞれでバージョンの上げ方が異なるので、以下を参考にバージョンを上げてください。
_nodebrew_
インストール可能な Node.js のバージョンを調べる
$ nodebrew ls-remote
出力されたバージョンの中から指定バージョンの Node.js をインストール
$ nodebrew install v19.8.1
インストールした Node.js のバージョンを切り替える
$ nodebrew use v19.8.1
有効なバージョンを確認
$ node -v
v19.8.1 と出力されていれば完了

_nvm-windows_
インストール可能なバージョンを調べる
$ nvm ls available
出力されたバージョンの中から指定バージョンの Node.js をインストール
$ nvm install 19.8.1
インストールした Node.js のバージョンを切り替える
$ nvm use 19.8.1
有効なバージョンを確認
$ node -v
v19.8.1 と出力されていれば完了

####　課題の提出方法
自分の名前のブランチを作成する　 ※必ず Main ブランチから派生させる　
ブランチはローマ字で姓・名で作成してください
各課題を取り組んでから作成したブランチにプッシュ
GitHub 上でプルリクエストを作成
レビュアーに@convictionTeacher を指定してください