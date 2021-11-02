# Radialex

<img src = "https://github.com/takashicompany/radialex/blob/master/images/02.jpg?raw=true" width="600">

Radialex(ラディアレックス)は一体型の40%のキーボードです。  
放射状に規則的に配置されたキーレイアウトは手を自然な体勢のまま置くことができ、ホームポジションから最短距離で文字を打つことを可能としています。  
キーボードの中央部にはシンボルとしてのキーやキーキャップを配置することができ、またバックライトLEDによるライトアップがされます。  
オプションでMXソケットによるキースイッチの取り替えや、LED、コンスルーにも対応しており、使用するスタイルにあわせた組み立てが可能です。  
また、ファームウェアがVIA(Remap)に対応しているため、Webブラウザからキーマップを書き換えることが可能です。

<img src = "https://github.com/takashicompany/radialex/blob/master/images/01.jpg?raw=true" width="300">
<img src = "https://github.com/takashicompany/radialex/blob/master/images/04.jpg?raw=true" width="300">

## 必要な部品

### キットに同梱されているもの
|部品|個数|備考|
|:--|:--|:--|
|PCB|1|リードタイプと表面実装のダイオードに対応。|
|トッププレート|1||
|ボトムプレート|1||
|ダイオード（リードタイプ)|45||
|m2スペーサー(6mm)|8||
|m2ネジ(4mm)|8||
|m2ネジ(8mm)|4||
|m2ネジ(16mm)4||
|リセットスイッチ|1||
|MXソケット|1||
|滑り止めシール|8||

### 別途用意するもの
|部品|個数|備考|
|:--|:--|:--|
|キースイッチ|45|Cherry MX互換のもの。|
|キーキャップ|45|全て1u。Chery MX互換のもの。|
|Pro Micro|1||
|USBケーブル|1|Pro MicroとPCを接続します。|

### オプション
|部品|個数|備考|
|:--|:--|:--|
|コンスルー|2|12pin、13pinに対応しておりますのでMCU(Pro Micro)にあわせて選択が可能です。|
|MXソケット|44|中央のキー以外は、キースイッチのはんだ付け/MXソケットによる挿し込みの両方に対応。|
|LED(SK6812MINI-E)|2|中央のキーとキーボード手前側の穴をバックライトで光らせることができます。|
|LED(WS2812B)|10|アンダーグロウライトとしてキーボードの底面を光らせることができます。|



## 組みたて方

### 1. PCBの表裏を確認する

表  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8285.jpg?raw=true" width="600">

裏  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8288.jpg?raw=true" width="600">

### 2. ダイオードをはんだづけする

プリントにあわせてダイオードの向き(端に黒線がついているもの)を確認します。  
スルーホール型のダイオード、表面実装型のダイオードの両方に対応しております。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8291.jpg?raw=true" width="600">

ダイオードを穴に通るように折り曲げます。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8293.jpg?raw=true" width="600">

はんだ付けを行います。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8295.jpg?raw=true" width="600">

ニッパーで足を切る際は、可能な限り平坦になるようにすると後の作業が楽に進めます。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8296.jpg?raw=true" width="600">

全部で45箇所となります。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8298.jpg?raw=true" width="600">

### 3. 中央のキーのMXソケットの取り付け

中央のキーのみMXソケットでキースイッチを固定します。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8299.jpg?raw=true" width="600">

MXソケット  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8302.jpg?raw=true" width="600">

MXソケットのはんだ付け部分の片方に事前にはんだを載せておきます。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8301.jpg?raw=true" width="600">

ピンセットでMXソケットを抑えながら事前に載せたはんだを溶かしながらMXソケットとPCBをはんだ付けします  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8304.jpg?raw=true" width="600">

もう片方もはんだ付けを行います。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8305.jpg?raw=true" width="600">

### 4. リセットスイッチの取り付け

リセットスイッチの取り付け場所はPCBの裏面中央のやや手前側です。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8307.jpg?raw=true" width="600">

リセットスイッチがPCBの裏面から押せるように穴に通します。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8308.jpg?raw=true" width="600">

表面からはんだ付けを行います。この際、可能な限り平坦になるようにニッパーで切ると後の作業がスムーズに行えます。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8310.jpg?raw=true" width="600">


### 5. トッププレートとキースイッチの取り付け

トッププレートやボトムプレート、中央プレートはアクリルの保護シートが貼ってるので、組み立てる際に剥がしてください。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8311.jpg?raw=true" width="600">

製造の工程上、模様が発生している可能性がありますが、ご理解いただけますと幸いです。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8314.jpg?raw=true" width="600">

PCBにトッププレートを載せます。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8317.jpg?raw=true" width="600">

トッププレートにキースイッチを取り付け、はんだ付けもしくはMXソケットへの差し込みを行います。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8318.jpg?raw=true" width="600">

### 6. 中央プレートの取り付け

中央プレートは二種類あります。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8316.jpg?raw=true" width="600">

18mmのネジとスペーサーを用います。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8507.jpg?raw=true" width="600">

PCBの裏側から、スペーサーでネジと中央プレートを取り付けます。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8508.jpg?raw=true" width="600">

表面は下図のようになります。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8494.jpg?raw=true" width="600">

### 7. Pro Microの取り付け

Pro Microを取り付けます。  
PCBはコンスルーに対応しております。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8498.jpg?raw=true" width="600">

PCBの裏面にPro Microを取り付けます。  
Pro Microを取り付ける際に、ピンの位置を留意ください。(BLE Micro Proなどで使えるように13ピンになっております)  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8499.jpg?raw=true" width="600">

下図のように取り付けられれば成功です。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8500.jpg?raw=true" width="600">

### 8. ファームウェアの用意と確認

[Remap](https://remap-keys.app/catalog/IxsMPjShxAP0NbiQGbKQ/firmware)からVIAのファームウェアを書き込むことが可能です。  
<img src = "https://user-images.githubusercontent.com/4215759/139539025-4ada6038-2dd5-4387-ac68-e3610fac70aa.png" width="600">

ファームウェアのソースコードは[こちら](https://github.com/qmk/qmk_firmware/pull/14949)です。

VIAのファームウェアを書き込んだ状態で[Remap](https://remap-keys.app/)からキーマップを変更できます。  
<img src = "https://user-images.githubusercontent.com/4215759/139539096-175f39c2-4c4b-44d3-99c1-fb897aff14cb.png" width="600">

### 9. LEDの取り付け(オプション)

Radialexでは、2種類のLEDを搭載できます。  
1-2番はバックライト(SK6812MINI-E)、3番から12番まではアンダーグロウ(WS2812B)となります。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8323.jpg?raw=true" width="600">

バックライトのLEDを付ける際はシルクで塗られたところにGND(LEDの角が欠けている部分)が来るように配置します。  
事前にはんだを乗せておくのが良いです。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8324.jpg?raw=true" width="600">

4箇所をはんだ付けします。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8325.jpg?raw=true" width="600">

中央のキースイッチと手前の穴が光ります。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8326.jpg?raw=true" width="600">

アンダーグロウも同様に、シルクの三角の部分にGND(LEDが角が欠けている部分)が来るように配置します。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8334.jpg?raw=true" width="600">

同じく4箇所をはんだ付けします。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8335.jpg?raw=true" width="600">

12箇所が光るかを確認します。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8518.jpg?raw=true" width="600">

### 10. ボトムプレートの取り付け

最後にボトムプレートを取り付けます。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8312.jpg?raw=true" width="600">

トッププレート側は8mmのネジ、ボトムプレート側は4mmのネジでスペーサーを赤丸の位置に留めます。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8515b.jpg?raw=true" width="600">

最後に滑り止めシールを貼って完成です。  
打鍵時にガタつく場合はキーボード全体を軽く曲げると解消することがあります。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8516.jpg?raw=true" width="600">
