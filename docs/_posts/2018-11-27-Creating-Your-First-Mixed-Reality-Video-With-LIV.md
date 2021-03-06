---
date: 2018-11-27
title: Creating Your First Mixed Reality Video With LIV
categories:
  - manual
author_staff_member: nekoi7yu
---

このドキュメントは、猫井夕菜([@nekoi7yu](https://twitter.com/nekoi7yu))による寄稿となっております。

## このドキュメントについて

Twitterとかで、キャラクターがVRゲームをプレイしている動画をみたことはありませんか？
ツイッターのハッシュタグで検索するといろんな作品を見ることができます。例 [#バーチャルモーションキャプチャー](https://twitter.com/search?q=%23%E3%83%90%E3%83%BC%E3%83%81%E3%83%A3%E3%83%AB%E3%83%A2%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%82%AD%E3%83%A3%E3%83%97%E3%83%81%E3%83%A3%E3%83%BC)

あんな動画作ってみたいけど、何から手を付けたら良いか分からないという方もいらっしゃると思います。何を隠そう私がそうでした！このドキュメントでは、録画するまでの概要手順をまとめています。逆に詳細な手順は各リンク先に譲っています。

どんなアプリを準備すれば動画作成できるのかをふわっと掴んでいただければ幸いです。


## ステップ

バーチャルモーションキャプチャーといくつかのソフトウェアを組み合わせることでプレイ動画を撮影することができます。

大まかな手順は次の通りです。

1. 次のアプリケーションとモデルをダウンロードする
   * バーチャルモーションキャプチャー
   * LIV
   * OBS
   * アリシアさん（VRMアバター・キャラクターモデル）
1. セットアップを行う
   * LIV Initial Setup を行う
   * Creating externalcamera.cfg for Mixed Reality Compositingの作成を行う
1. OBSで録画する

## アプリケーションとモデルのダウンロード

* バーチャルモーションキャプチャー
  * 本ソフトウェアです。ユーザーのVRでの動きをキャラクターの映像に反映させます。
  * ダウンロードリンク
[https://sh-akira.github.io/VirtualMotionCapture/download.html](https://sh-akira.github.io/VirtualMotionCapture/download.html)
  * インストール方法:
ZIP形式のため、解凍するだけです。
* LIV
  * MR合成するためのソフトウェアです。バーチャルモーションキャプチャーと対応しているゲームの画面を合成します。
  * ダウンロードリンク
[https://store.steampowered.com/app/755540/LIV/](https://store.steampowered.com/app/755540/LIV/)
  * インストール方法:
Steamアプリのため、他アプリと同様にインストールします。
* OBS
  * スクリーンキャプチャを行って動画ファイルを作成するソフトウェアです。
  * ダウンロードリンク
[https://obsproject.com/ja](https://obsproject.com/ja)
  * インストール方法
ダウンロードしたEXEファイルを実行して画面に従ってインストールします。
* アリシアさん
  * VRMモデルです。本モデルをバーチャルモーションキャプチャーに読み込ませて利用します。
  * ダウンロードリンク
[https://3d.nicovideo.jp/works/td32797](https://3d.nicovideo.jp/works/td32797)
  * インストール方法:
ZIP形式のため、展開するだけです。

## セットアップ

* LIV Initial Setup
  * こちらのドキュメントをご参照ください。
  *  [LIV Initial Setup](./LIV-Initial-Setup.html)
* Creating externalcamera.cfg for Mixed Reality Compositing
  * こちらのドキュメントをご参照ください。
  * [Creating externalcamera.cfg for Mixed Reality Compositing](./Creating-externalcamera.cfg-For-Mixed-Reality-Compositing.html)

## 録画する
バーチャルモーションキャプチャーを開いて、「VRM読込」ボタンをクリックして、ダウンロードしたアリシアさんをロードします。

その後の操作等はこちらのドキュメントをご参照ください。
[Mixed Reality Compositing with LIV and Virtual Motion Capture](./MR-Compositing-with-LIV-and-Virtual-Motion-Capture.html)


## さいごに。
必要なソフトが多くうまくいかない場合もあるかと思います。その時はまず [よくある質問と回答](https://github.com/sh-akira/VirtualMotionCapture/wiki/%E3%82%88%E3%81%8F%E3%81%82%E3%82%8B%E8%B3%AA%E5%95%8F%E3%81%A8%E5%9B%9E%E7%AD%94) をご参照ください。ここにはゲームやLIVに関する内容も含まれています。例えば、BeatSaberのCameraPlusMODは削除しないとうまくいかないといったような、直接バーチャルモーションキャプチャーに関係ないものの撮影時にハマりがちな問題が記載されています。

実は最初の環境構築が一番大変だったりします。しかし、ゲーム代を除いて撮影に必要なソフトは無料で入手できますので是非この機会に試してみてくださいっ！そして、その暁にはハッシュタグ付きでツイートや動画投稿していただければ嬉しく思います。

内容は2019年11月07日現在のものであり、各アプリケーションの仕様は予告なく変更される可能性があります。

