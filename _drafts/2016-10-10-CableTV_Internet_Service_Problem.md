---
layout: post
date: 2016-10-10
title: "Cable TV Internetを申し込んですぐに解約した話"
categories: CableTV Internet 
excerpt: "ケーブルテレビのインターネットサービスを申し込みましたがすぐに解約しました。"
timezone: Asia/Tokyo
---


## preface / background

これまで使っていた環境は、NTT フレッツ光、ただしマンションの都合でVDSLとなってます。
最近、ネットが使えなくなるときがたまにあり、また夜もスビードが十分に出なくインターネットを利用していてストレスを感じることがちょくちょくあったのでプロバイダを変えようか考えていたところでした。

うちのマンションは非常に古いです。

## ケーブルテレビ会社の来訪

詳細は分かりませんが、マンションの管理組合の方で今後もマンションの価値を上げる施策の一環としてケーブルテレビ網の整備が挙げられたようです。(ケーブルテレビ会社による後押しもあったとは予想つきます。)
で、強制的に本マンション全戸のテレビ端子を工事するということになり、仕方なくテレビ端子の前の棚を動かし、休日の時間をあけて私が対応することになりました。

### それまでのケーブルテレビの印象

実家では一時期JCOMのインターネットサービスを利用していました。いまのテレビ番組自体はうちの親が申し込んで使っているはず。
ADSLでも10Mbpsとか出る当時、その価格に対してJCOMのインターネットサービスは非常に高いものでした。（いまも高いのだと思いますが。)
私が実家にいたときはそのサービスを利用していましたが、私は一人暮らし先も決まり、両親はインターネットはまったく利用しないため解約しました。
この当時のやりとりなどから、
・ケーブルテレビは高い
・解約手続きが面倒（電話が繋がりにくいこと含め）

など、あまりいい印象は持っていませんでした。なので、今回も「当然、インターネットサービスやケーブルテレビサービスを進められるだろうが別に必要としてないし断ろう」と考えてました。
ケーブルテレビ会社によるインターネットサービスの利点はあまり時間帯によらず一定の高速

### ケーブルテレビ会社がきたあとの印象

営業の方だけ合って色々話しやすい方でした。
で、うちのマンションがわりと規模が大きいため、月額料金が想定より低く、現在利用しているNTTフレッツひかりより安くなることがわかりました。
また、この点検と同時に申し込めばいまの工事スタッフがそのままインターネット工事も行うため工事費10,000円も無料になるとのことでその場で申し込んでしましました。
工事費云々は営業トークなのは重々承知してましたが、人件費を回収するために工事費がかかるのも分かりますし後日また家にはいってもらうのも面倒と考えればちょうどいいタイミングだと判断しました。
前述したとおり、プロバイダを変えることも検討していたので。


どうやらアップロードはその仕組みからノイズが載ってしまい、それが集約されるポイントでデータ通信に影響を及ぼすため、スピードを技術的にこれ以上あげられない模様。
たまたま、CEATECにいったときに会場に同技術を家の中やホテル内に整備する企業ブースがあり、話をきいてみたところパスフィルターを入れることで対応しているとのこと。
たぶん、ケーブルテレビの方はこのパスフィルターを入れた上で無視できないノイズが引き続き流れているのではと予想しています。


### ケーブルテレビ会社のインターネットサービス

予想通り安定したスピードが出ていました。

## 余談

話はこれで終わりなのですが、このあともとのNTTひかりに戻したあと設定を見直しました。
具体的には
VDSLモデム　→　NTTひかり電話ルータ　→　Wi-Fiルータ　→　各機器

という設定なのですが、NTTひかり電話ルータにDHCPをすべて任せて、Wi-Fiルータをアクセスポイントとして振る舞う形にしました。
前から、ipv6の環境を使ってみたいと思ってたのと、NTTひかり電話のルータとネットワークを同一にすることでスマートフォンやタブレットから家庭内電話の内線として使えたり、ルータ自身をVPNサーバとして稼働させることができるため、メリットが色々有るためです。

* スマートフォンやタブレットをひかり電話の内線として利用する

* VPN設定を行う

この話はたぶん続きます。




## 最後に