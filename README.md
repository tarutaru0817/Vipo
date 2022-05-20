# Vipo

PHP自作

## 概要
ビールの感想を投稿・閲覧できるサイトを作成しました。

管理者ユーザと会員ユーザ、非会員ユーザの3種類のユーザを使用できます。

管理者ユーザのみユーザの一覧・削除ができ、非会員ユーザは感想の一覧機能・ランキング機能のみ利用できます。

## 使い方
〇非会員ユーザ

感想一覧機能、ランキング機能のみをログインなしで利用できます。

〇会員ユーザ

ユーザアカウント：test@test.test

パスワード：test

感想のCRUD処理、ランキング機能、お気に入り登録、ユーザのCRUD処理が利用できます。

〇管理者ユーザ

ユーザアカウント：kanri@test.test

パスワード：kanri

会員ユーザの機能に加え、ユーザ一覧・削除機能が利用可能です。

## 環境
ZAMPP/MySQL/PHP/Laravel

## データベース
DB名：vipo

テーブル

お使いのphpMyAdminに上のデータベースを作り、入っているDB.sqlをインポートしていただければお使いいただけるようになると思います。
