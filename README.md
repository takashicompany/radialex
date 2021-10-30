# Radialex

40%サイズのキーボードです。  
放射状のキーレイアウトは手を自然な体勢のまま置くことが可能で、指を最短距離で動かすことで文字を打つことが可能です。  
キーボードの中央部にはあなたの象徴となるキーやキーキャップを配置することができます。  
LEDのバックライトで輝かせることも可能です。
また、MXソケットによるキースイッチの付替えにも対応しております。

![qmk](https://github.com/takashicompany/radialex/blob/master/images/01.jpg?raw=true)

## 必要な部品

### キットに同梱されているもの
|部品|個数|備考|
|:--|:--|:--|
|PCB|1|スルーホール/表面実装のダイオードに対応。|
|トッププレート|1||
|ボトムプレート|1||
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
|コンスルー|1|12pin、13pinに対応しておりますのでMCU(Pro Micro)にあわせて選択が可能です。|
|MXソケット|44|中央のキー以外は、キースイッチのはんだ付け/MXソケットによる挿し込みの両方に対応。|
|LED(SK6812MINI-E)|2|中央のキーとキーボード手前側の穴をバックライトで光らせることができます。|
|LED(WS2812B)|10|アンダーグロウライトとしてキーボードの底面を光らせることができます。|



## 組みたて方

### 1. PCBの表裏を確認する

表  
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8285.jpg?raw=true)

裏  
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8288.jpg?raw=true)

### 2. ダイオードをはんだづけする

プリントにあわせてダイオードの向き(端に黒線がついているもの)を確認します。  
スルーホール型のダイオード、表面実装型のダイオードの両方に対応しております。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8291.jpg?raw=true)

ダイオードを穴に通るように折り曲げます。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8293.jpg?raw=true)

はんだ付けを行います。  
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8295.jpg?raw=true)

ニッパーで足を切る際は、可能な限り平坦になるようにすると後の作業が楽に進めます。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8296.jpg?raw=true)

全部で45箇所となります。  
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8298.jpg?raw=true)

### 3. 中央のキーのMXソケットの取り付け

中央のキーのみMXソケットでキースイッチを固定します。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8299.jpg?raw=true)

MXソケット
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8302.jpg?raw=true)

MXソケットのはんだ付け部分の片方に事前にはんだを載せておきます。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8301.jpg?raw=true)

ピンセットでMXソケットを抑えながら事前に載せたはんだを溶かしながらMXソケットとPCBをはんだ付けします
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8304.jpg?raw=true)

もう片方もはんだ付けを行います。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8305.jpg?raw=true)

### 4. リセットスイッチの取り付け

リセットスイッチの取り付け場所はPCBの裏面中央のやや手前側です。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8307.jpg?raw=true)

リセットスイッチがPCBの裏面から押せるように穴に通します。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8308.jpg?raw=true)

表面からはんだ付けを行います。この際、可能な限り平坦になるようにニッパーで切ると後の作業がスムーズに行えます。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8310.jpg?raw=true)


### 5. トッププレートとキースイッチの取り付け

トッププレートやボトムプレート、中央プレートはアクリルの保護シートが貼ってるので、組み立てる際に剥がしてください。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8311.jpg?raw=true)

製造の工程上、模様が発生している可能性がありますが、ご理解いただけますと幸いです。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8314.jpg?raw=true)

PCBにトッププレートを載せます。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8317.jpg?raw=true)

トッププレートにキースイッチを取り付け、はんだ付けもしくはMXソケットへの差し込みを行います。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8318.jpg?raw=true)

### 6. 中央プレートの取り付け

中央プレートは二種類あります。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8316.jpg?raw=true)

18mmのネジとスペーサーを用います。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8507.jpg?raw=true)

PCBの裏側から、スペーサーでネジと中央プレートを取り付けます。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8508.jpg?raw=true)

表面は下図のようになります。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8494.jpg?raw=true)

### 7. Pro Microの取り付け

Pro Microを取り付けます。  
PCBはコンスルーに対応しております。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8498.jpg?raw=true)

PCBの裏面にPro Microを取り付けます。  
Pro Microを取り付ける際に、ピンの位置を留意ください。(BLE Micro Proなどで使えるように13ピンになっております)
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8499.jpg?raw=true)

下図のように取り付けられれば成功です。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8500.jpg?raw=true)

### 8. ファームウェアの用意と確認

[Remap](https://remap-keys.app/catalog/IxsMPjShxAP0NbiQGbKQ/firmware)からVIAのファームウェアを書き込むことが可能です。

![image](https://user-images.githubusercontent.com/4215759/139539025-4ada6038-2dd5-4387-ac68-e3610fac70aa.png)

ファームウェアのソースコードは[こちら](https://github.com/qmk/qmk_firmware/pull/14949)です。

VIAのファームウェアを書き込んだ状態で[Remap](https://remap-keys.app/)からキーマップを変更できます。
![image](https://user-images.githubusercontent.com/4215759/139539096-175f39c2-4c4b-44d3-99c1-fb897aff14cb.png)

### 9. LEDの取り付け(オプション)

Radialexでは、2種類のLEDを搭載できます。  
1-2番はバックライト(SK6812MINI-E)、3番から12番まではアンダーグロウ(WS2812B)となります。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8323.jpg?raw=true)

バックライトのLEDを付ける際はシルクで塗られたところにGND(LEDの角が欠けている部分)が来るように配置します。  
事前にはんだを乗せておくのが良いです。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8324.jpg?raw=true)

4箇所をはんだ付けします。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8325.jpg?raw=true)

中央のキースイッチと手前の穴が光ります。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8326.jpg?raw=true)

アンダーグロウも同様に、シルクの三角の部分にGND(LEDが角が欠けている部分)が来るように配置します。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8334.jpg?raw=true)

同じく4箇所をはんだ付けします。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8335.jpg?raw=true)

12箇所が光るかを確認します。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8518.jpg?raw=true)

### 10. ボトムプレートの取り付け

最後にボトムプレートを取り付けます。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8312.jpg?raw=true)

トッププレート側は8mmのネジ、ボトムプレート側は4mmのネジでスペーサーを赤丸の位置に留めます。

![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8515b.jpg?raw=true)

最後に滑り止めシールを貼って完成です。  
打鍵時にガタつく場合はキーボード全体を軽く曲げると解消することがあります。
![image](https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8516.jpg?raw=true)
