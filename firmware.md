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
1. Local file に [key_toys_95_rev1_default.hex]または、[key_toys_95_rev1_left.hex] を指定します。<br>
(写真ではkey_toys_73_default.hexになってます)
1. Microcontroller は atmega32u4 を指定します。
1. AUto-Flash のチェックボックスに☑をします。<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc7.png"><br>
1. キーボードのリセットスイッチを押して書き込みます。<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc5.png"><br><br>
このような表示が出れば書き込み完了です。<br><br>
**これを左右のpromicro2つ分行えば作業完了です('ω')**
<br>
***
<br>
<br>
***
