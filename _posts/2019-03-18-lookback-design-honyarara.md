---
layout: post
title: オンライン勉強会を開催してみて
date: '2019-03-18'
categories: diary
banner_image: "/content/images/2019/03/lookback-design-honyarara/banner.jpg"
featured: true
comments: true
published: true
---

2019年3月13日に「家から参加できる勉強会」をコンセプトにオンライン勉強会を開催しました。お試し回という事で実験的な試みをいくつか試してみたので共有していきます。場所がネックにならず参加できる勉強会が増えたら嬉しいので、イベントなどを主催をされている方に有益な情報となれれば幸いです。

<!--more-->

## イベント概要

イベントの詳細はこちらです。iPadをテーマに飛び込みLT5つ、メインセッション1つで1.5時間。登壇者たちとのフリートークで30分。計2時間くらいでした。

[デザインほにゃらら オンライン勉強会 「iPad編 」 - connpass](https://connpass.com/event/119973/)

30人で設定した事前申し込み者は最終的に45人まで増え、ライブ視聴者も最大52人。

## 良かったこと (Keep)
1. 家から参加できる
1. 登壇者も非同期で参加できる
1. スタッフも家から参加できる
1. 当日キャンセルの悩みがない
1. 懇親会がない
1. 前日・当日に飛び入り参加ができる
1. 匿名登壇ができる
1. サンプル動画を作ったおかげでLT動画入稿がスムーズだった
1. Adobe Character Animateの楽しさを知れた
1. イベントページを活用できた
1. アンケートを実施できた

イベント準備から配信まで全て外出することなく開催できたのは本当に嬉しかったです。カメラに映らないので下はパジャマを履いたままの配信でした。

またスピーカーさんや視聴者さんからも子どもと見られて嬉しかったという声もあり非常に励まされました。

<iframe width="640" height="360" src="https://www.youtube.com/embed/EZbupvXW8GE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

子どもの歯磨きをなぜか全国に配信したり。

## 改善点 (Probrem)
1. ライブなのにVTR放送して本当に面白いのか？
1. ハングアウト音声の制御でこけた
1. 動画が一部異なる比率で再生されてしまった
1. アプリの紹介URLが分からず探しづらかった
1. グータンヌーボ形式はあまり良くない
1. 音量レベルが途中から変わっちゃった
1. カメラ位置をもう少し高めに
1. 照明が眩しくて気になった
1. アンケート内容に不足・不備があった

進行を一旦中止して、スピーカー陣との連絡をしてみたり、OBSの設定を変更したりとテンポが良くないところはありました。しかし目に見えて離脱されることもあまりなく、視聴してくださっている方の優しさを感じました。ありがとう！

## 次回の施策 (Try)

以下では、上記項目から特に意見を募りたいもの、備忘録として残しておきたいものを抜き出し言及していきます。

### ライブなのにVTR放送して本当に面白いのか？ → 面白かった

どのセッションも愛に溢れ、得るものも多く内容については最高でした。(ここ重要)

しかし「事前に収録された動画を放映する」という形式は、視聴者の体験からすれば **ただ、動画を見ているだけなのでつまらないのでは？** という疑問もあります。

そもそもライブ感は必要なのか？ ライブ感とは？

考えられるライブっぽい施策としては下記が浮かびます。

1. ワイプを入れる ← 他登壇者さんが顔出し接続してくれたらアリかも
1. LT放送後に登壇者と1対1でやりとりする ← 話しやすい？
1. LT動画放送形式を止めてインタビュー形式にしちゃう ← 勉強会じゃないと意味がない？

まあ、生放送の録画を振り替えってみると、それほど気にならないので **別にこのままで良さそう** です。わたしが心配していたほど皆さん気にならなかったようで楽しんでもらえました。

Twitterで具体的に「良かったですよ」と意見をいただけたので安心することにします。

### ハングアウト音声の制御でこけた → 準備配信時に確認しよ

わたしの声がスピーカー陣に通じてなかったり、スピーカー陣からモニタリング音声がループしたりと、全然うまくいかなかった部分です。

スピーカー陣とはハングアウトで接続し、その音声をOBSを通じてYoutube Liveへ配信していました。

配信構成図はこちら。
![](/content/images/2019/03/lookback-design-honyarara/01.png)

#### マイク接続できなかった問題

わたしのマイク(Miki mic)がハングアウトに認識されておらず、それに気付かないまま配信が始まってしまったのでけっこうてんやわんやでした。

Webカメラのマイク、ヘッドホンのマイクと二つ用意して、ハングアウトとOBSへ分配していたのですが失敗。けっきょくスマホから別アカウントでハングアウトに参加し、そちらのマイクから通話ました。

なぜ、わたしのマイク接続ができなかったのかまずは再現してみないとなんとも言えない。

#### 通話の仕方の事前共有不足
モニタリング音声をそのままスピーカーが拾ってしまってループしてしまうシーンもあったので、スピーカーやスタッフが参照できる簡易メモを整備しておく必要がありますね。

って言うか前日/当日にいきなり、スピーカー陣も話そうぜって言うの急すぎ。

### 動画が一部異なる比率で再生されてしまった → 再エンコしよ
mpeg形式はOBS側で、異なる比率で配置されてしまうようです。

![](/content/images/2019/03/lookback-design-honyarara/02.jpg)

* エンコード形式を具体的に指定する
* こちらで再エンコすることをあらかじめ許諾もらっておく

とかで回避できそう。

### アプリの紹介URLが分からず探しづらかった → チャットでケア

#### スピーカーさん or スタッフさんでケア
チャットケア担当スタッフさんをひとりアサインしておく、もしくはスピーカーさんなどにチャット参加を積極的にしてもらってケアすると良さそう。

#### ライブ配信中に遡ることができる旨を伝える
動画にQR、URLを入れておけばそれで解決できそう。また途中参加した方で、前のLTを聞けなかったと残念がっていた方もいた。Youtube Liveであれば、そこもシークバーをスライドするだけでタイムマシンに乗れるので解決。

#### OBSのシーンにQRやリンクのテロップを追加しておく

これなら事前にしっかり作っておけるので、シーンスイッチでポン出しできますね。

<iframe width="640" height="360" src="https://www.youtube.com/embed/W9HESxDW0V4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

その場でリンクURLやアプリ名を表示させるくらいは簡単にできるのでそれでもいいかも。

### グータンヌーボ形式はあまり良くない → やめよう

<iframe width="640" height="360" src="https://www.youtube.com/embed/oDuuBH6zfDg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

DVDにあるコメンタリーを意識して、グータンヌーボ的にきゃっきゃしたかったけれど、あれば高度な編集技術のたまものでした。

もしやるのであれば、後日再放送版として副音声バージョンで配信するのはおもしろいかも。

イベント本編は、録画で補完しておいてもらってスピーカー陣と本編を見ながら感想戦を広げるのは1粒で二度美味しいし、リテンション施策としてもメリット。

### アンケート内容に不足・不備があった
LTやイベント自体の感想や指摘をもらうためのアンケートをGoogle Formで用意していました。

当日直前の参加してくれた方の項目を追加することを失念してしまいました。ひとりでやってるから仕方ないところある。チャット、Twitterケアでひとりスタッフをお願いするのであれば、イベントページ、アンケートの更新や、質問のフォロー、ピックアップなんかも含めたいところ。

最初はもちろん「スタッフ」としての依頼が必要だけれど、運営を継続していって **一部のリピーター達が自治的にチャットケアをしてくれるようになれば良いのでは…？**

そのためにはコンテンツや運営ポリシーの定義が必要そう。

<small>前にやっていたコワーキングスペースにて、利用者たちによってある程度作られた自治具合はなかなか面白かったので、ああいうのを勉強会コミュニティで再現できるか試してみたいところある。</small>

## 自分で褒めたいところ

いや、やっぱオンライン勉強会最高っしょ。グダったところを改善してテンポ良くなれるまではマイナーアップデートしていけばいい。

### 関係者全員の負担が軽い
スピーカー陣が **場所を問わず、しかも非同期で参加できる**。動画入稿なので **大幅な時間オーバーが起きにくい**。事前チェック可能なので、**LTの質をフォローすることもできる**。(あまりする気はない) **匿名性を維持したまま発表もできちゃう** 。

視聴参加者としてはテンポ良く情報を家から得られる。あとから参照できる。チャットでゆるく交流もできる。

<small>できれば視聴参加者との双方向性をあと一つくらいは追加したいですね。投票システムとか、いきなり音声接続して1分くらい感想もらうとか。</small>

### ドキュメントの整備

過去に参加してきたイベントで、[おそろしいほどドキュメントが充実しているもの](https://cssnite.jp/archives/4speakers.html)があったので、そちらを参考にConnpassにできるだけ情報をまとめました。

サンプル動画や写真だけでもイメージを伝えられたのはLT動画入稿のハードルを下げるのに一役買ったと思ってます。(体感)

<small>LT動画を作成して投げてくる時点で、配信リテラシー高めな人で偏っているという事実もあるとは思うけどね…。</small>

多少うざったいかもだけれど、なるべく個別メッセージを避けスピーカー陣全員に見えるところで個別への対応したところも管理しやすかったです。SlackのDM問題に通じる。

### アウトプットしたからそれだけで偉い
スピーカーとして参加してくださった方々はもちろん、わたしも **勉強会主催というデカめのアウトプットできたんですごく偉い** です。

iPadがあったからという前提にもなりますが、スッピンでも動画を配信する動機として使ってみたAdobe Character Animate。思ったより楽しくてたくさんの表現や可能性を秘めているのでもっといじくりたいです。沼だコレ。

## イベントの方向性について

「寝かしつけタイムと被ってるやんけwww」とお母さんたちの声をエゴサで拾いました。

そうなんすよねー。「自宅から参加できる」というのがコンセプトですが、そのターゲットは実際誰なのか。地方に住んでいる人に寄せるべきか、小さい子どもをケアしている人に寄せるべきか。

### 開催時間について
試しに夜10-12時という遅めの会でもやってみましょうか。わたしの周りでも寝る前の1,2時間は勉強などにあててる人もいるので案外視聴者側は負担ないかも。問題はスピーカー側ですね。遅すぎて明日に響きそう。

一旦やってみて、著しく集まりが悪かったら考えましょう。

## さいごに

![](/content/images/2019/03/lookback-design-honyarara/03.jpg)

Twitterで[#デザインほにゃらら](https://twitter.com/search?f=tweets&vertical=default&q=%23%E3%83%87%E3%82%B6%E3%82%A4%E3%83%B3%E3%81%BB%E3%81%AB%E3%82%83%E3%82%89%E3%82%89&src=typd)ってつけて「すごい！」とか「またやって欲しい！」、「こんなテーマ聞きたい！」、「何時にやってくれ！」とかお願いします。褒められたら、たぶん5月くらいにまたやれそう。