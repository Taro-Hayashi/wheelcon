# Wheel con 取り扱い説明書([English](README_EN.md))
  
## 内容品  
- Wheel con... 1個
- 着せ替えプレート... 1個
- ゴム足... 4個
![](img/IMG_2659.jpg)

## ご用意いただくもの  
- Type-C USBケーブル  
- Windows/Mac/Linux（iPad、Androiで使用はできますが設定ができません）  

## 使用方法
まずは動作ソフト（ファームウェア）をインストールします。  
PCに接続するとRPI-RP2というドライブとして認識されます。  
![](img/rpi.jpg)  

こちらのファイルをダウンロードしてドラッグ&ドロップしてください。  
- [tarohayashi_wheel_con_vial.uf2](https://github.com/Taro-Hayashi/wheelcon/releases/download/0.23/tarohayashi_wheel_con_vial.uf2)

自動的にRPI-RP2ドライブが消えたらファームウェアのインストール完了です。  

![](img/IMG_2672.jpg)  
お好みでプレートを変更したりゴム足を付けたりして使ってください。  

## キーのカスタマイズ
キーのカスタマイズにはVialをご利用ください。
- Vial https://vial.rocks

接続し、入れ替えたいキーをドラッグ&ドロップすると設定が変更されます。

## その他
### ファームウェアの更新方法
一番上のホイールを押し込みながらPCに接続するとRPI-RP2ドライブが出てくるのでそちらに新しいファームウェアをドラッグ&ドロップしてください。  

### 出荷状態へのリセット方法
ねじを外して分解し、裏面のボタンを押しながらPCに接続するとRPI-RP2ドライブが出てきます。  
![](img/IMG_2667.jpg) 

こちらのページの一番下の項目からflash_nuke.uf2をダウンロードしてドラッグアンドドロップしてください。  
- https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html
  
一旦ドライブが消え、また現れたらリセット完了です。

### ファームウェアのソースコード
- https://github.com/Taro-Hayashi/vial-qmk/tree/tarohayashi/keyboards/tarohayashi/wheel_con

### 謝辞
このキーボードは原型師のCKB様のアイデアをもとに依頼を受けて製作しました。  
- https://twitter.com/miku1596

### 販売サイト（予定）
- BOOTH https://tarohayashi.booth.pm/items/5553379
