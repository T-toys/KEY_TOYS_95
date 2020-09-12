# KEY_TOYS_95 ビルドガイド


## 部品一覧

### キット付属部品

| 名前 | 数量 | 備考 |
| ---- | ---- | --- |
| PCB | 1枚 | |
| トッププレート | 1枚 |  |
| ボトムプレート | 1枚 |  |
| Mill-Maxソケット | 190個 | 実装済 |
| ダイオード | 95個 | 実装済 |
| タクタイルスイッチ | 1個 | 実装済 |
| M2ネジ 5mm | 22個 | プレート接続用 |
| M2スペーサー 9.5mm | 11個 | プレート接続用 |
| M2スペーサー 15mm | 4個 | チルトスタンド用 |
| サック | 4個 | チルトスタンド用 |
| ゴム足 | 8個 |  |

### キット以外の使用部品

| 名前 | 数量 | 備考 |
| ---- | ---- | --- |
| Pro Micro | 1個 |  |
| スプリングピンヘッダ | 2個 | Pro Micro用 12P |
| キースイッチ | 73個 | MX互換のもの |
| キーキャップ | 73個 | MX互換のもの |
| グリース |  | スタビライザー用<br>(無くても可) |

## 組み立てに使う道具

| 名前 | 備考 |
| ---- | ---- |
| はんだこて |  |
| ハンダ | 0.8mm推奨 |
| ピンセット |  |
| +ドライバー | #0,#1 |
| ハンダ吸取り線 |  |

（組立には使用しませんが、キーキャッププーラー・キースイッチプーラーがあればキャップ・スイッチ交換に非常に便利ですので用意することをお勧めします）

## 組み立て方

### ダイオード

1. PCB裏面にダイオード用のパッドがあります。片側のパッドに予備ハンダを行います。<br>
1. ダイオードには向きがあり、シルク表示『 ▷❘ 』の『 ❘ 』側と、ダイオード表示『 ❘ 』の向きを合わせます。<br>
（PCB取付向きは全ヵ所同じ向きにしています）<br>
1. ダイオードをPCBの取付位置に合わせ、ダイオードの足の上からコテを当てダイオード仮付けします。<br>
（この工程で位置が決まりますのでダイオードが浮いていないか、反対側の足がパッドに乗っているか等の確認をします）<br>
1. 反対側の足をハンダ付けします。<br>
1. 予備ハンダした側を再ハンダし、本付けします。<br>
（目視で確認したところ、リードタイプを使用する場合はスペースキー・エンターキー・バックスペースキーのスタビライザーワイヤーと干渉する恐れがありますので加工が要する可能性があります。ご注意ください）<br>
<img width="400" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_133109.jpg1"><img width="400" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_134246.jpg1">

### スイッチソケット

1. PCB裏面にソケット用のパッドがあります。シルクの表示通りにソケットをPCBにセットします。<br>
1. 片側をハンダ付けします。この時にソケットが浮いていないか確認をします。<br>
（浮いている場合はソケットを上から押さえ、仮付けしているハンダにコテを当てて修正します）<br>
1. 反対側をハンダ付けします。<br>
    <img width="400" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_162927.jpg1">

### Pro Micro

1. PCBとスプリングピンヘッダとPro Microを組込みます。<br>
 1-1. PCBの表面側からピンを差し込みます。スプリングピンヘッダは推奨の向きがあります。<br>
　　樹脂部分側面の小さな穴を基準に、穴が無い方のピンがPCB側。穴が開いている方のピンがPro Micro側。<br>
　　また、2つのヘッダは穴が同じ方向を向くように取り付けます。<br>
 1-2. USBコネクタがPCBの外側を向く位置にし、Pro Microのチップ部品のついている側からピンを差し込みます。<br>
1. Pro Micro側のピンをハンダ付けします。<br>
（PCB側のピンはハンダ付けしません）<br>
<img width="400" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_163037-2.jpg1"><img width="400" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_163150-2.jpg1">

### リセットスイッチ

1. PCBの表面側からスイッチの足を差し込みハンダ付けします。<br>
    <img width="400" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_163402-2.jpg1">

### スタビライザー

1. スタビライザーを組みます。<br>
 1-1. アウターの下から軸を入れます。(向きがあります)<br>
 1-2. 軸を上に持ち上げてワイヤーの先を軸に差し込みます。<br>
 1-3. ワイヤーをアウターのキャッチに固定します。<br>
<img width="400" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_164027-2.jpg1"><img width="400" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_164211-2.jpg1"><br>

1. キャップのサイズが2U以上の箇所にスタビライザーを取り付けます。<br>
 2-1. PCB表面の大きい方の穴にホック側を差し込み、小さい方の穴にナット側を差し込みます。<br>
 2-2. PCB裏面からネジで固定します。<br>
     <img width="800" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_171039-2.jpg1">

### プレートの準備

1. トッププレート裏面に7.5mmスペーサーをネジで取り付けます。<br>
    <img width="400" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_172513.jpg1">

### キースイッチ

1. スイッチのピンが付いている方をトッププレート表面から差込み、スイッチをプレートに固定すます。<br>
（ピンの位置はPCBのソケット位置に合わせます）<br>
1. プレートに固定されたスイッチピンをPCBのソケットに差し込みます。<br>
<img width="266" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_225006-2.jpg1"><img width="266" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_225106-2.jpg1"><img width="266" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_225208-2.jpg1"><br>


### プレート組

1. 組上がったトッププレート&PCBにボトムプレートをネジで取り付けます。<br>
    <img width="800" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_230501-2.jpg1">

### その他

1. キーキャップをスイッチに取り付ける。<br>
2. ゴム脚をキーボード底面の縁に取り付ける。<br>
3. お好みで、ボトムプレートのネジを15mmスペーサーに変更することでチルトさせることができます。<br>
    <img width="800" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_231423-2.jpg1">
<br>
<br>

### 完成です('ω')
<img width="1000" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/IMG_232837-2.jpg1">
   

