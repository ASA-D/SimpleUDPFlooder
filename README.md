SimpleUDPFlooder
================

C言語ソケットプログラミングを用いたUDP flood。

使用したライブラリ
==================

Libnet 1.2を使用した。 
詳しくは以下の資料を参照すること

http://fossies.org/dox/libnet-libnet-1.2/　

Libnet APIのインストール
=====================

debianであればこのコマンドを実行する。
```
sudo apt-get install libnet1-dev
```

使い方
===========

このmakefileは、"sup "という名前の実行ファイルを生成する。
```
Usage: sup <Destination IP> <Destination UDP port> <Number of packets to create>
```
raw socketを開くには、root権限が必要。
