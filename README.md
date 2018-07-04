# summer-internship-2018

エウレカサマーインターン2018の技術課題提出用リポジトリです。

## 概要

### 提出方法
このリポジトリをフォークして開発を行い、Pull Request形式で課題提出を行ってください。

タイトルの先頭にAndroid/iOS/Webフロントエンド/サーバーサイドのいずれかを付けてください。

Descriptionに以下の情報を記載してください。

- 仕様説明
    - 実現した機能の簡単な解説
    - スクリーンショット
- 環境構築マニュアル
- 言語/ライブラリ/アーキテクチャなどの選定理由
- こだわりポイント

### 評価ポイント
- 実行可能であること
- 要件が満たせていること
- 適切な命名やコメントなど、チーム開発において必要な要素が満たされていること
- 設計やコーディングルールに一貫性があること
- パフォーマンスに留意した実装になっていること

## Android/iOS/Webフロントエンド

### 課題
1. [GitHub API](https://developer.github.com/v3/activity/)から好きなものを選び、リスト形式で表示してください
2. リスト押下で詳細な情報が閲覧できる画面に遷移してください
3. リストおよび詳細画面に表示する情報は自由に決めてください

### 使用技術
- GitHub APIではGraphQLを使用しても構いません
- ライブラリは自由に使用して構いません
- AndroidはJava/Kotlinのどちらかで開発してください
- iOSはSwiftで開発してください
- WebフロントエンドはなんらかのAltJS（Babel,TypeScript,flowなど）とSPAフレームワーク（React,Vue,Angularなど）で開発してください

## サーバーサイド
以下のどちらかを選択してください。

### 課題1
1. [GitHubトレンド](https://github.com/trending)をリスト形式で表示できるサイトを作成してください
2. リスト押下で詳細な情報が閲覧できる画面に遷移してください
3. リストおよび詳細画面に表示する情報は自由に決めてください

### 課題2
1. 任意のRSSフィードを登録し、リスト形式で表示できるサイトを作成してください
2. リスト押下で詳細な情報が閲覧できる画面に遷移してください
3. リストおよび詳細画面に表示する情報は自由に決めてください

### 使用技術
- HTMLをサーバーサイドレンダリングするアプリケーションとして実装してください
- 開発言語/フレームワークに指定はありません
