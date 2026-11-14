# authorization-app-practice

## 概要
COACHTECH 教材 Tutorial 10-3「認可機能 ハンズオン演習」で作成した成果物です。
ポリシーの定義と実行をしました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- Policy / Gate（認可）
- Laravel Fortify（認証）
（**他に使ったものがあれば追記してください**）

## 学んだこと
- make:policyでポリシーを生成。
- 命名規則に従えばポリシーは自動検出される。
- @canはGate::allowsと同じような意味。権限があれば～できる。

## 動作確認
（**どうやって動かして確認するかを記載してください**）
http://localhost にアクセス。ログイン、編集、削除が行えてログインユーザーが自分以外の投稿の削除や編集ができないか確認。

