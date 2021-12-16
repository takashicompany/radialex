# Radialex Rev2の組み立て方

## [Rev1](https://github.com/takashicompany/radialex/blob/master/build_rev1.md)との違い
- Pro Microの取り付け位置をPCBの表面にしています。
- 一部の説明画像はRev1のものを流用しておりますが、Pro Microの取り付け以外の工程は同様に進めていただければ問題ございません。
## 必要な部品

### キットに同梱されているもの
|部品|個数|備考|
|:--|:--|:--|
|PCB|1|リードタイプと表面実装のダイオードに対応。|
|トッププレート|1||
|ボトムプレート|1||
|中央トッププレート|1||
|中央積層プレート|1||
|ダイオード（リードタイプ)|45||
|m2スペーサー(5mm)|8||
|m2ネジ(4mm)|8||
|m2ネジ(8mm)|4||
|m2ネジ(18mm)4||
|リセットスイッチ|1||
|MXソケット|1||
|滑り止めシール|6||

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

### 6. Pro Microの取り付け

Pro Microを取り付けます。  
PCBはコンスルーに対応しております。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_9185.jpg?raw=true" width="600">

Pro Microの取り付け位置を確認します。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_9187.jpg?raw=true" width="600">


PCBにピンヘッダ(又はコンスルー)を取り付けます。  
穴は13個ありますが、Pro Microの取り付け穴は12個なので、1つ余ります。  
Pro Microの印字とPCBの印字が合うように挿してください。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_9190.jpg?raw=true" width="600">

ピンヘッダ(コンスルー)にPro Microを挿してはんだ付けをします。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_9192.jpg?raw=true" width="600">

ピンの余った部分はニッパーで切ります。    
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_9194.jpg?raw=true" width="600">

ピンヘッダの場合は裏面からはんだ付けを行います。  
(コンスルーの場合は、PCBとのはんだ付けをしなくて大丈夫です)
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_9198.jpg?raw=true" width="600">

### 7. 中央プレートの取り付け

中央プレートは二種類あります。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8316.jpg?raw=true" width="600">

18mmのネジとスペーサーを用います。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8507.jpg?raw=true" width="600">

PCBの裏側から、スペーサーでネジと中央プレートを取り付けます。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8508.jpg?raw=true" width="600">

表面は下図のようになります。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8494.jpg?raw=true" width="600">

### 8. ファームウェアの用意と確認

[Remap](https://remap-keys.app/catalog/IxsMPjShxAP0NbiQGbKQ/firmware)からVIAのファームウェアを書き込むことが可能です。  
<img src = "https://user-images.githubusercontent.com/4215759/139539025-4ada6038-2dd5-4387-ac68-e3610fac70aa.png" width="600">

Remapの使い方は[千葉千夏/あずさんの記事](https://note.com/azulee/n/n8557fdfbc679#MkVkQ)で説明されております。


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

ボトムプレートを取り付けたら滑り止めシールを底面に取り付けます。
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8813.jpg?raw=true" width="600">

赤丸の位置に貼るとグラつきが少ないです。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/build/IMG_8812b.jpg?raw=true" width="600">

### 11. キーキャップを取り付ける

最後にキーキャップを取り付けて完成です。  
<img src = "https://github.com/takashicompany/radialex/blob/master/images/01.jpg?raw=true" width="600">

### 12. 自慢する
完成しましたら、ぜひSNSなどに写真を投稿頂ければと思います。  
Twitterのハッシュタグは`#Radialex`を付けていただけば幸いです。  
キットを組み立てた感想や、キーボードを使った所感などをお待ちしております！  

また、毎週日曜日の１9時より実施されている[#KEEP_PD](https://twitter.com/hashtag/KEEB_PD?f=live)に投稿頂くこともオススメです。  
開催の告知は[@KEEB_PD](https://twitter.com/KEEB_PD)にて行われております。

ご不明な点などございましたら、[@takashicompany](https://twitter.com/takashicompany)にメンションやDM頂ければと思います！
