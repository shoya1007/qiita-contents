---
title: Firestoreで不等価演算子が使えるようになった件
tags:
  - Firebase
  - Firestore
private: false
updated_at: '2020-10-12T18:12:37+09:00'
id: 4bd119dd2af0dae108cd
organization_url_name: null
slide: false
ignorePublish: false
---
#Firestoreでそれまで不等価演算子が使えないと知り、絶望した
Web開発などにおいてFirestoreを使った開発をされる方も多くいらっしゃるかと思います。
先日私も初めてFirestoreを使った開発をしていたのですが、whereを使った条件指定が必要になり調べていたところ、Firestoreでは不等価演算子(!=)は使えないという記述を多く見ました。

何かと視野が狭くなりがちな私は、!= を使わな方法が思いつかんとか思っていたので、絶望に打ちひしがれつつ、わずかな期待を抱きながら某エンジニア質問サイトで、Firestoreで不等価演算子のようなものを使えないかという質問をしました。

#Firestoreが更新されて、不等価演算子が使えるようになっていた（ネ申）
質問を投稿すると、ある一人の方がすぐに回答してくださいました。
「バージョンアップで、!=が使えるようになりましたよ」と。

回答者の方が公式のURLも貼ってくださり、そこにはしっかり記述されていました。

https://firebase.google.com/support/release-notes/js#version_7210_-_september_17_2020
バージョンアップされたのは9月中旬とごく最近のことだったようです。

この情報が有名なのかどうかはわかりませんが、検索した限りでは出てこなかったのでQiitaに投稿することにしました。
少しでも誰かのために役立てることができればと思います。
