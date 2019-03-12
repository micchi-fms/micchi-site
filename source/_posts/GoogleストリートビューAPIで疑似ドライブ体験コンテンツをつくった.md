---
title: GoogleストリートビューAPIで疑似ドライブ体験コンテンツをつくった
date: 2016-01-01 00:00:00
tags: works
toc: true
photos : https://i.gyazo.com/f12f932a2484f6c61bda90e4be9d0db8.jpg
---
![](https://i.gyazo.com/f12f932a2484f6c61bda90e4be9d0db8.jpg)
Googleのストリートビュー画像を連続で表示していけば、路線上をクルマが走っている映像ができるのではないかと思い、Songle APIとGoogleストリートビューAPIを使用して、ドライブを疑似体験できるコンテンツ「どこでもドライブぅ～」を作成しました。


# 実装
- Songle API
- Google ストリートビューAPI
- javascript
- HTML
- CSS

# デモ
![](https://i.gyazo.com/19bba626ca44b442e6d2c1c0979f2005.gif)
ドライブといえば音楽なので、ドライブ映像に合わせた音楽を検索できる機能をつくりました。
このフォームで好きな音楽を選択してもらい、その後にドライブしたいルートを入力します。

![](https://gyazo.com/41547edd8e0149d2c40bdd74ec8e78a5.gif)
そうすると、Googleストリートビューのパノラマ映像とSongleの動画情報が読み込まれ、音楽を聴きながら、ドライブ疑似体験映像が再生されます。

# つくってみて
googleストリートビューを読み込むのに相当な時間が掛かってしまうので、出発地と目的地は短くないといけないという欠点があります。
ですが、このGoogleストリートビューを使えば、例えばVRでドライブ体験ができる可能性があると考えています。