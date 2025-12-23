# tweet_app

Tweet Appは、ユーザーが短いメッセージ（ツイート）を投稿、閲覧、削除できるシンプルなソーシャルネットワーキングアプリです。Ruby on Railsで構築されており、ユーザー認証とツイートの基本的なCRUD操作をサポートしています。

このアプリは、Web アプリケーション開発の基礎を理解するために設計された[Progate Ruby on Rails コース](https://prog-8.com/paths/rails)の一部として作成されました。


## 機能

- ユーザー認証（サインアップ、ログイン、ログアウト）
- ツイートの投稿、閲覧、編集、削除
- ユーザーごとのツイート表示
- 全ユーザーのツイートを含むタイムライン表示

## 必要要件

- Ruby: 3.1.6
- Rails: 7.0

### データベースの初期化

```
bundle exec rake db:create
bundle exec rake db:setup
```

## インストール
1. リポジトリをクローン:
   ```
   git clone https://github.com/username/tweet-app.git
   cd tweet-app
   ```

2. 依存関係をインストール:
   ```
   bundle install
   ```

3. データベースをセットアップ:
   ```
   rails db:create
   rails db:migrate
   ```

4. Railsサーバーを起動:
   ```
   rails server
   ```

5. ブラウザで http://localhost:3000 にアクセスしてアプリを表示します。

## 使い方

- アカウントを作成します。
- ホームページから新しいツイートを作成します。
- タイムラインで全てのツイートを閲覧します。
- 必要に応じて自分のツイートを編集または削除します。


## テストの実行

テストスイートを実行するには、以下のコマンドを使用します:
```
rails test
```
