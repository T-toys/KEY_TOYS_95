# KEY_TOYS_73 ファームウェア

## キーマップ
5×19の格子配列ですので、マップレイアウトの自由度は比較的高いです。一体型ですが文字キーをスプリットさせて配置しています。<br>
2つ目のレイヤーの数字キー位置にFキーを割り当てています。<br>
中央にテンキーを配置した（default）と、左にテンキーを配置した（left）の、2つのレイアウトを用意しています。

<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_95/blob/master/image/key_toys_95-keylayout-default.png">（default）
<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_95/blob/master/image/key_toys_95-keylayout-left.png">（left）

## ファームウェアを書き込む

[QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases) を用意します。<br>
[key_toys_95_rev1_default.hexまたは、key_toys_95_rev1_left.hex](https://github.com/T-toys/qmk_firmware-key_toys) を用意します。<br>
（Download ZIPでファイルをダウンロードして[key_toys_95_rev1_default.hex]または、[key_toys_95_rev1_left.hex]を用意してください）

<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc1.png">

QMK Toolboxでファームウェアを書き込みます。PCとプロマイクロをUSBケーブルで接続します。
1. Local file に key_toys_73_default.hex を指定します。
1. Microcontroller は atmega32u4 を指定します。
1. AUto-Flash のチェックボックスに☑をします。<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc7.png"><br>
1. キーボードのリセットスイッチを押して書き込みます。<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc5.png"><br><br>
**このような表示が出れば書き込み完了です('ω')**
<br>
***
<br>
<br>
***

## ≪キーマップとマトリクスについて≫

73キーをプロマイクロ1つで動かしているので、使用できるピンを全部使ています。<br>
(Duplex-Matrixを使えばよさそうなのですが、理解できていません)<br>
9×9のマトリクスを作り、それぞれのキーを割り当てているためコードが変な感じになってます。<br>
<img width="350" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc2.png"><img width="350" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc3.png"><br>
<br>
キーマップを変更する際は下の図を参照し、適宜変更下さい。<br>
<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/key_toys_73-keylayout-2.png">

