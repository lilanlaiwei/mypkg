# mypkg
[![test](https://github.com/lilanlaiwei/mypkg/actions/workflows/test.yml/badge.svg)](https://github.com/lilanlaiwei/mypkg/actions/workflows/test.yml)

## 概要
* ロボットシステム学の課題で作成したリポジトリです。
* ROS2のパッケージ

## トピック(/countup)
* 数字をカウントするtalkerというノードから、型が16ビット符号付整数のメッセージを受け取る。
* 貰ったメッセージを表示するlistenerというノードに、上記で受け取ったメッセージを送信する。


## 実行例
```
$ ros2 launch mypkg talk_listen.launch.py
```
talkerから/countupを通じてlistenerにメッセージを送信し、表示する。

## 結果
```
・
・
・
[listener-2] [INFO] [1672579712.024946200] [listener]: Listen:0
[listener-2] [INFO] [1672579712.498224600] [listener]: Listen:1
[listener-2] [INFO] [1672579712.998138400] [listener]: Listen:2
[listener-2] [INFO] [1672579713.498063500] [listener]: Listen:3
[listener-2] [INFO] [1672579713.998130800] [listener]: Listen:4
[listener-2] [INFO] [1672579714.498274700] [listener]: Listen:5
・
・
・
```

## 必要なソフトウェア
* ROS2
## テスト環境
* Ubuntu 22.04 LTS
                       
## 著札建、ライセンスについて                                               
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
	* [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)

* © 2023 Riran Seo
