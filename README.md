# CoreToDo

## 概要

iOSアプリ開発の練習として作成したToDoアプリです。

## 仕様

### 環境
- データ保存にはCoreDataを使用しています。
- 環境はSwift3/Xcode8です。
- AutoLayoutを使用しています。

### 使い方

#### 最初の画面

- アプリを起動するとカテゴリごとのタスクが一覧表示されます。
- 右下のプラスボタンを押すと、「次の画面」へ遷移します。
- タスク一覧からタスクをスワイプすると削除できます。
- タスク一覧からタスクをタップすると、「次の画面」へ遷移し、そのタスクの編集ができます。

#### 次の画面

- タスク入力とカテゴリ選択後1つ目のプラスボタンを押すとタスクが追加されます。
- 2つ目の入力欄に追加したいカテゴリを入力してから2つ目のプラスボタンを押すと新しいカテゴリが追加されます。
- "ToDo"、"Shopping"以外のカテゴリを選択し、ゴミ箱ボタンを押すとそのカテゴリを削除できます。
- タスク編集時はカテゴリ追加ができません。

## 作り方
作り方の手順をチュートリアルとして[Qiita](http://qiita.com/MasayaHayashi724/items/0d27f4abf7b14c72107f)で公開しています。

公開後に実装した機能については機能説明のみを追記しているので、具体的なコーディングは解説していません。

何かありましたらお気軽にコメントください。
