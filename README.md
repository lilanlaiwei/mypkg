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
ros2 launch mypkg talk_listen.launch.py
```
talkerから/countupを通じてlistenerにメッセージを送信し、表示する。

## 結果
```
[listener-2] [INFO] [1672576645.404412479] [listener]: Listen: 0
[listener-2] [INFO] [1672576645.861709843] [listener]: Listen: 1
[listener-2] [INFO] [1672576646.362042525] [listener]: Listen: 2
[listener-2] [INFO] [1672576646.861349089] [listener]: Listen: 3
[listener-2] [INFO] [1672576647.361680882] [listener]: Listen: 4
[listener-2] [INFO] [1672576647.862018433] [listener]: Listen: 5
[listener-2] [INFO] [1672576648.362095711] [listener]: Listen: 6
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

* © 2022 Riran Seo
