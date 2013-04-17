# What's Android ?

Kouta Imanaka(kota.imanaka@s-cubism.jp)

2013-04-17 / S-Cubism 社内勉強会

---
= data-x="-1000"
# Tech Rank

## ★・・・・

技術的知識がなくても楽しめるように制作しました

---
= data-y="1000"
# mdpress

このスライドはmdpressにて制作されました

---
= data-y="1000"
# なにそれ？

Markdown記法でImpress.jsを制作できる

---
= data-y="1000"
# Impress.js って？

今見ているこれがImpress.js

HTML5/CSS3技術を使用してエレガントなプレゼンテーションを行う

---
= data-y="1000"
# なんでMarkdown ?

巷にあふれるスライドの多くは

- 題名
- 本文

の構成になっている。

多くの発表でPowerPointはオーバースペック

テキストベースで編集できるのもイイネ！

---
= data-y="1000"
# Markdown最高!

Markdownを覚えましょう

- 社内エンジニアWiki
- GithubのReadme.md
- Qiita
- and more...

多くのサイトで標準マークアップ言語として採用されている！

---
= data-y="1000"
# いろいろできる

    #include<stdio.h>

    int main(void){
        printf("Hello,Markdown!");
        return 0;
    }

---
= data-y="1000"
# いろいろできる

> 神は賽を投げない
> - Albert Einstein

---
= data-y="1000"
# いろいろできる

![世界一有名な林檎](./image/apple-logo.gif)

---
= data-y="1000"
# いろいろできる

## (大きすぎた・・・

<img src="./image/apple-logo.gif" width="150px" />

---
= data-y="1000"

# 本題に戻る

---
# Androidってなに

<s>人造人間。人の形をしたロボット</s>

---
# Android

Open Handset Allianceが発表・提供し、Googleが開発する

携帯電話・移動体通信端末向けOS・ミドルウェア

ARM、Intel x86、MIPSなどのCPUアーキテクチャ上で動作する

---
# オープンソース

ソースコードは*Apache License 2.0*で提供されている。

(WebkitライブラリはLGPL、LinuxカーネルはGPL)

- Androidの改変物はソースコードを公開する義務がない
 - しかしLinuxカーネルは公開義務がある

※Google Map等のGoogle権利のソフトウェアはプロプライエタリ

(ソースコード非公開、Googleの利用規約に同意する必要がある)

---
# OSSプロジェクト
# との関連

Linuxの関連技術が多く採用されているが、

一部NetBSD等からマージされている

- Bionic:標準Cライブラリ
 - NetBSDのlibc
 - Linuxのlibc

---
# ランタイム環境

- Java言語を用いてアプリ作成
 - 標準ライブラリ豊富
 - 外部ライブラリも潤沢
 - 自由度は非常に高い
  - NDK経由でC言語ライブラリを動かしたり
  - mruby環境を動かしたり

コンパイラ、SDK、開発キットは

公式サイトから無償ダウンロードできる。

---
# Android x部作

- 歴史
- 使い方
- 開発
- to be continued...

---
# 歴史

- Wikipediaより抜粋
 - [Android - Wikipedia](http://ja.wikipedia.org/wiki/Android)
 - [iPhone - Wikipedia](http://ja.wikipedia.org/wiki/IPhone)

---
= data-x="1000"
|日付|歴史|
|:-:|:--|
|2008-07-11|<font color="orange">▲</font>iPhone 3G|
|2008-10-21|<font color="blue">■</font>T-Mobile G1(Android 1.0)|
|2009-06-19|<font color="orange">▲</font>iPhone 3GS|
|2009-07-10|<font color="red">●</font>Docomo HT-03A(G1の兄弟機)(Android 1.5)|
|2009-11-08|<font color="blue">■</font>Motorola DROID(Android 2.0)|

---
= data-x="2000"
|日付|歴史|
|:-:|:--|
|2010-01-05|<font color="blue">■</font>Google NexusOne(Android 2.1)|
|2010-04-01|<font color="red">●</font>Docomo SO-01B(Xperia X10)(Android 1.6)|
|2010-06-24|<font color="orange">▲</font>iPhone 4|
|2010-06-30|<font color="red">●</font>au IS01(Android 1.6)|
|2010-11-26|<font color="red">●</font>Docomo SC-02B(Galaxy S)|
|2010-12-16|<font color="blue">■</font>Google Nexus S(Android 2.3)|

---
= data-x="3000"
|日付|歴史|
|:-:|:--|
|*2011*-01-05|<font color="blue">■</font>Motorola Xoom(Android 3.0)|
|2011-09-08|<font color="red">●</font>Galaxy Tab 10.1(初のXi対応タブレット)|
|2011-10-14|<font color="orange">▲</font>iPhone 4S|
|2011-10-19|<font color="red">●</font><font color="blue">■</font>Galaxy Nexus(Android 4.0)|
|*2012*| |
|2012-09-21|<font color="orange">▲</font>iPhone 5|
| |デザイナーが変わった(Holo Light/Dark)|
| |Android 4.1(Project Butterなど)|
| |Android版Chrome|

---
= data-x="4000" data-rotate="180"
|日付|歴史|
|:-:|:--|
|*2013*|Android 5.0?|
| |Project Glass?|
| |Nexus 5?|
| |one more thing?|

---
= data-x="5000"
もっと歴史を知りたい人はこちら

- [SlideShare - 20121113 Android昔話2012](http://www.slideshare.net/youten_redo/20121113-android2012)
- [【歴史】Android昔話 2012【まとめ】 ‐ ニコニコ動画:Q](http://www.nicovideo.jp/watch/sm19473473)
 - SlideShareの音声付きバージョン

---
= data-scale="1"
# Androidの
# つかいかた

人それぞれなので難しい。

「俺はこうしている！」も難しい。

- 脳内がNoSQL構造のため、関連データが引っ張ってこれない＞＜

---
= data-scale="2"
# 「マニアック」

妙な使い方にフォーカスしたいと思います。

---
= data-scale="3"
# ホームアプリ変更

- ホームボタンを押した時に表示されるアプリ
 - アプリ起動したり
 - ウィジェット置いたり

メーカー・キャリア標準のホームアプリは、

デザイン重視のため、ボトルネックになることがある

> 美人は三日で飽きる - 誰か

---
= data-scale="4"
# お勧めの
# ホームアプリ

- Nova Launcher
- LauncherPro
- ADW.Launcher

無料版＋機能追加する有料版　の構成

---
= data-scale="5"
# ユビキタス！

PC・Androidの垣根を下げれば仕事効率化！

(会社で使用する時は自己責任で。俺は会社アカウントでは使ってません。)

---
= data-scale="6"
# Chrome
# ↓
# Android

- PushBullet

URLだけでなく、いろんなデータをモバイル環境にプッシュできる。

- Google Chrome

Chromeの「見ているタブ」はアカウントに紐付けられた環境なら確認OK

---
= data-scale="7"
# NFC (FeliCa Push)

「これからはNFCの時代」と言われて早2年。

もう来ない、つーか日本では難しいよね！

しかしNFC、意外と便利。知っておきましょう。

---
= data-scale="8"
# Android Beam

動作条件
- NFC対応機種
- Android 4.0以降のOS
- AndroidビームをON

端末同士をかざすことで、

様々なデータを送ることが出来る

---
= data-scale="9"

- テキスト
 - URL
 - 文字
- 画像(4.1以降)
 - NFCでペアリング
 - Bluetooth経由でメインデータを転送
- 重いデータ(4.1以降)
 - NFCでペアリング
 - Wi-Fi Directでメインデータを転送

---
= data-scale="10"
# データはつくれる

NFC転送データは自由に作成できる

- [Torokun/android-beam-library · GitHub](https://github.com/Torokun/android-beam-library)

上記ライブラリを組み込むと、

Android Beamデータを自在に作成できる！

---
# 開発系の話が
# 出てきたので

終わります。

ご清聴ありがとうございました。