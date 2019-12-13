# README

# 本のレンタルサービス

## 概要
電子書籍のレンタルサービスです。
小説投稿サービス
会員登録は無料だがレビューは有料。（悪口は禁止）
読んだ本をお金で評価できる（ランキング化）

## コンセプト
いい本をシェア

## バージョン
Ruby 2.6.5
Rails 6.0.1

## 機能一覧
- [ ] ログイン機能
- [ ] ユーザー登録機能
  - [ ] メールアドレス、名前、パスワードは必須
- [ ] パスワード再設定機能
- [ ] 画像一覧表示機能
  - [ ] コメント数を表示
  - [ ] お気に入り数を表示
- [ ] 画像投稿機能
  - [ ] タイトルと記事内容は必須
- [ ] 画像編集機能
- [ ] 画像削除機能
  - [ ] 画像編集と画像削除は投稿者のみ実行可能
- [ ] 画像お気に入り機能
  - [ ] 画像のお気に入りについては1つの画像に対して1人1回しかできない
  - [ ] 自分自身の画像にはお気に入りできない
- [ ] コメント投稿機能
- [ ] コメント削除機能
- [ ] コメント編集機能
  - [ ] コメント編集とコメント削除はコメントした本人のみ可能
- [ ] コメント機能とお気に入り機能についてはページ遷移なしで実行できる

## カタログ設計
https://docs.google.com/spreadsheets/d/e/2PACX-1vQRNOY03ypjIxTthuBAq_pKatH-w-vyCbr_It0KMQrlU1ReItaus1DUbHTiFMKFv4aEKWN6vssLElaC/pubhtml

## テーブル定義
https://docs.google.com/spreadsheets/d/e/2PACX-1vTQJC1TV38hLwTivc5LreMtPzjxj9OpqrFgVkYysZXHb1FttKg2MSbUP6r-U8-7noU52UHzQRxsY_SE/pubhtml

## 画面遷移図
https://docs.google.com/spreadsheets/d/e/2PACX-1vTLVdnF81Q_O93ebHGBfckJJhjXO4EKeHcYtX1mRxl3bk0ILjeOdI_pwmlmUeOI_aUBezdSoi_YJe71/pubhtml

## 画面ワイヤーフレーム
https://docs.google.com/spreadsheets/d/e/2PACX-1vQW9UJIBgpQ7Ijd9oAv-vZYcxsO0X8r9bM9zWLJ4IOYV9aLLgRwe6T24Ae9gjOF-8gdesbHqiBhHtRi/pubhtml

## 使用予定Gem
* carrierwave(イメージ表示)
* mini_magick（イメージサイズ）
* devise（ログインシステム）
* stripe（決済システム）


# English Ver

# README

# Easy Image

## Overview
Image service specialized in only posting titles and articles.
You can favorite Images and make comments.

## Concept
Simple Image

## Version
Ruby 2.5.1
Rails 5.2.1

## Functions list
- [ ] Login function
- [ ] User registration function
  - [ ] Email address, name and password are required
- [ ] Password reset function
- [ ] Image list display function
  - [ ] Show number of comments
  - [ ] Show number of favorites
- [ ] Image post function
  - [ ] Title and article content is required
- [ ] Image edit function
- [ ] Image deletion function
  - [ ] Posters can only do Image edit and Image deletion
- [ ] Image favorite function
  - [ ] You can favorite only once per one Image
  - [ ] You can't favorite your own Image
- [ ] Comment post function
- [ ] Comment deletion function
- [ ] Comment edit function
  - [ ] Only comment contributors can edit and delete comments
- [ ] The comment function and favorite function can be executed without page transition.

## Catalog design,Table_Definition,Screen transition diagram,,Wire frame
https://docs.google.com/spreadsheets/d/1V3sqZjVF5Oep0ek7hkLYGuIKSnhiTLqTbq46GpjP94E/edit#gid=0

## To be used Gem
* carrierwave
* mini_magick
* devise
