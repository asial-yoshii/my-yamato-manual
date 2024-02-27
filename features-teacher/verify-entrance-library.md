---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: false
  pagination:
    visible: false
---

# ✅ 図書館への入館

My Yamatoの教員向け機能を使用した図書館への入館について解説したします。

## 認証コード画面

<figure><img src="https://images.unsplash.com/photo-1706211306706-8f36d91c8379?crop=entropy&#x26;cs=srgb&#x26;fm=jpg&#x26;ixid=M3wxOTcwMjR8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MDg0ODk0NTJ8&#x26;ixlib=rb-4.0.3&#x26;q=85" alt="" width="188"><figcaption></figcaption></figure>

My Yamatoにログインした後のトップ画面の右下に、認証コードを表示するためのボタンがあります。そちらをタップすることで認証コードをQRコードで表示する画面が立ち上がります。

セキュリティを保つため認証コードは30秒ごとに自動更新され続けます。差し代わり中のタイミング、もしくは、差し代わり直前のタイミングでは認証が失敗することがあります。識別コードの表示に余裕を持ってご入館いただけますようお願いいたします。

## My Yamatoを使用する入館

&#x20;認証コード画面のQRコードを、入館ゲートにあるコードリーダーにかざしてゲートを開きます。

## 入館チェックの仕組み

ゲート開閉の可否は、My Yamatoの基盤システムを経由して判断されます。具体的に、ゲートが開くまでに以下のステップが実行されます。

1. コードリーダーがデジタル学生証の認証コードを読み取る
2. コードリーダーがMy Yamatoの基盤システムに認証コードを照会する
3. 基盤システムがコードリーダーに認証結果（学籍番号）を返す
4. コードリーダーがゲートに開閉を指示する
