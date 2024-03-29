# schedule_registry
スケジュールの登録、従業員の管理を行います。<br>
ログイン認証、登録/更新/削除などの基本的な操作が含まれています。

## Description
ログイン後のTOPページはログイン者が登録したスケジュールを一覧で表示します。<br>
従業員は自分以外のスケジュール内容に、「いいね！」を行うことができます。<br>

## Demo
[![Image from Gyazo](https://i.gyazo.com/a40d2d49ca2710d9fb14d17a54c62c61.gif)](https://gyazo.com/309bf71e357947d0fba4de8d9670b657)

## Dependency
- Eclipse Java EE 2020-12
- Taglibs Standerd Impl 1.2.5
- Javax.Servlet Api 4.0.1
- Mysql Connector Java 8.0.23
- Hibernate 5.4.28
- javax Servlet Jsp Jstl Api 1.2.1
- Lombok 1.18.16

## Usage
1. 以下のURLにアクセスし、ログイン画面が表示されます。<br>
``http://localhost:8080/schedule_registry/?action=Auth&command=showLogin``
2. ユーザー名、パスワードを入力し、ログインします。
(employee number:1, password:1)

## Authors
Ayano.Honma

## Reference
[レイアウト-1](https://saruwakakun.com/html-css/reference/buttons#section1)<br>
[レイアウト-2](https://jajaaan.co.jp/css/css-headline/)<br>
