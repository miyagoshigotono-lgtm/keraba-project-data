# ケラバの保存データ

ケラバの入力ファイルを社内で共有するための非公開リポジトリです。

[メインの計算アプリを開く](https://miyagoshigotono-lgtm.github.io/bolt-effective-length/#keraba)

## 保存する

1. アプリのケラバ画面で「保存」を押し、JSONファイルをPCへ保存します。表示中の「通常」または「瓦」だけを保存します。
2. [ファイルの登録画面](https://github.com/miyagoshigotono-lgtm/keraba-project-data/upload/main/projects)を開き、保存したJSONを選びます。
3. 「Commit changes」で登録します。同じファイル名を指定すると更新履歴を残して置き換えます。

## 別PCで開く

1. [projects](projects)のJSONファイルを開き、「Download raw file」でダウンロードします。
2. アプリのケラバ画面で「開く」を押し、そのJSONを選びます。

GitHubへの登録は利用者が行います。アプリから入力を自動送信することはありません。
別アカウントの担当者が使う場合は、所有者がこの非公開リポジトリへのアクセス権を付けてください。
複数人で同じファイルを編集するときは、作業前に最新ファイルを開き、保存・登録前に他の更新がないか確認してください。

ファイル形式は`keraba-project`の版1です。入力だけを保存し、図面と発注書の数値はアプリが再計算します。
公開用の`bolt-effective-length`と旧`kerabaCut`には実際の物件データを登録しません。
