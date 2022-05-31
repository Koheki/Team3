# 「商品需要の見える化機能」プロトタイプ
これは[Build@mercari2022](https://mercan.mercari.com/articles/33259/)のHackweekで「私たちの考えた新しいメルカリの出品機能」をテーマに作成した「商品需要の見える化機能」プロトタイプです。
詳細は以下の[デモ映像](#デモ映像)と[プレゼンテーションスライド](#プレゼンテーションスライド)をご覧ください。

## 必要なソフトウェア
- Python 3
- node v16
- ブラウザ

## 動作環境
次の環境で動作することを確認しています。
- OS: macOS 12.3.1
- ブラウザ: Google Chrome 102.0.5005.61
- Python 3.8
- node v16.15.0

## 使い方
### 環境構築
1. このリポジトリをクローンしてください
1. ターミナルから以下のコマンドを実行し、必要なPythonのパッケージをインストールします。
   ```
   cd path/to/Team3/app
   pip install -r requirements.txt
   ```
1. 次にターミナルから以下のコマンドを実行し、必要なnodeライブラリをインストールします。
   ```
   cd path/to/Team3/TypeScript
   npm ci
   ```

### 起動方法
1. ターミナルから以下のコマンドを実行し、サーバを立ち上げます。
   ```
   cd path/to/Team3/app
   uvicorn main:app --reload --port 9000
   ```
1. 次にターミナルの別のウィンドウから以下のコマンドを実行し、アプリを起動します。
   ```
   cd path/to/Team3/TypeScript
   npm start
   ```
1. 起動後、`http://localhost:3000/want`にアクセスするとこの機能のトップページが表示されます。

## デモ映像
### 購入者視点
#### トップページのボタンから登録

### 売り切れ商品のページのボタンから登録

### 出品者視点


## プレゼンテーションスライド
