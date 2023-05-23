# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## このアプリについて
【概要】：

繰り返し実施するタスクを含む、通常のtodoアプリとは異なる形式のアプリです。

習慣的なtodoと不定期に入るtodoを新規作成することができ、タスクの見方には「習慣todo」「不定期todo」「週タスク」「日別タスク」の4つのパターンがあります。

【機能】：

- 習慣的なtodoの新規作成、閲覧、更新、削除機能
- 不定期に入るtodoの新規作成、閲覧、更新、削除機能
- 週タスクの閲覧機能（1週間のタスクを出力）
- 日別タスクの閲覧機能（その日のタスクを出力）
- タブを切り替えて、習慣todoと不定期todoをそれぞれ表示させることができる
- タブを切り替えて、週タスクと日別タスクをそれぞれ表示させることができる

【環境】：
本アプリはRuby on Railsを使用して作成されています。

【インストール方法】：

まずは、以下のコマンドを使って本アプリのファイルをダウンロードしてください。
```bash
git clone https://github.com/ShishidoYuki/ruby-todo-app.git
```
ダウンロードが完了したら、アプリのディレクトリに移動し、以下のコマンドで必要なgemをインストールしてください。
```bash
bundle install
```
次に、データベースを作成してください。
```bash
rails db:create
rails db:migrate
```
以上で、アプリが起動できるようになります。以下のコマンドでアプリを起動してください。
```bash
rails server
```
【使用方法】：

ブラウザで http://localhost:3000/ を開いてください。
「習慣todo」「不定期todo」「週タスク」「日別タスク」のいずれかのタブをクリックして、表示したいタスクを選択してください。
必要に応じて、新規作成、閲覧、更新、削除を行ってください。