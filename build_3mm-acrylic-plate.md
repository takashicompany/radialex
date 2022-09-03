# アクリル3mmプレート


[遊舎工房さん](https://shop.yushakobo.jp/)の[自作キーボードオープンソースPCB](https://shop.yushakobo.jp/products/oss_pcb?variant=44403999539431)と[キーボードアクリルプレートサービス](https://shop.yushakobo.jp/collections/services/products/keyboard_acrylic_plate?variant=44150778986727)を利用することで、お好きなカラーのRadialexを作ることが可能です。
場合によってはお手頃な値段でRadialexをつくることが可能です。

<img src="https://github.com/takashicompany/radialex/blob/master/images/25.jpg?raw=true" width="600px"/>

アクリルケースの.aiデータは[こちら](https://github.com/takashicompany/radialex/raw/master/case/radialex-yusha-Laser_A4.ai)になります。

### キット相当の部品
|部品|必要個数|リンクと値段|備考|
|:--|:--|:--|:--|
|[Radialex PCB](https://shop.yushakobo.jp/products/oss_pcb?variant=44403999539431)|1|¥1,100||
|[アクリルケース](https://shop.yushakobo.jp/collections/services/products/keyboard_acrylic_plate?variant=44150778986727)|1|¥3,830~||
|[ダイオード](https://shop.yushakobo.jp/collections/all-keyboard-parts/Diode)|45|¥220|アクリル3mmプレートの場合は[リードタイプ](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800di-01-100)、[SMDタイプ](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800di-02-100)のどちらにも対応。|
|[m2スペーサー(7mm)](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800c2?variant=37665435222177)|8|¥396||
|[m2ネジ(5mm)](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800n2?variant=37665432993953)|12|¥220||
|m2ネジ([8mm](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800n2?variant=37665433026721) or 10mm)|4|¥220|8mmネジを使った場合は[中央プレートの取り付け](https://github.com/takashicompany/radialex#7-%E4%B8%AD%E5%A4%AE%E3%83%97%E3%83%AC%E3%83%BC%E3%83%88%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91)は1枚のみ。10mmのネジで2枚取り付け可能。|
|[タクタイルスイッチ 2pin](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800ts-01-1)|1||¥11||
|[Kailh スイッチソケット(MX用)](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a01ps)|1~45|¥187|最低1つは必要。全てのキースイッチをソケット化する場合は45個必要|
|[ウレタンクッション](https://shop.yushakobo.jp/products/a0800ur-01-6?)|6|¥132|6個でも正しく貼れば安定しますが、不安な方は2セット買っておくことを推奨します。|

### 組み立ての際にご自身で用意が必要なもの
|部品|必要個数|備考|
|:--|:--|:--|
|[Cherry MX（互換）スイッチ](https://shop.yushakobo.jp/collections/all-switches/cherry-mx-%E4%BA%92%E6%8F%9B-%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81)|45||
|[Cherry MX（互換）キーキャップ](https://shop.yushakobo.jp/collections/keycaps/cherry-mx-%E4%BA%92%E6%8F%9B-%E3%82%AD%E3%83%BC%E3%82%AD%E3%83%A3%E3%83%83%E3%83%97)|45|全て1u。Chery MX(互換)スイッチ軸に対応するもの。|
|[Pro Micro](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/pro-micro)|1||
|USBケーブル|1|Pro MicroとPCを接続します。|

### より一層オシャレに・使いやすくするために
|部品|個数|備考|
|:--|:--|:--|
|[コンスルー](https://shop.yushakobo.jp/products/31)|2|取り付けるとMCU(Pro Micro)をPCBから取り外すことが可能です。PCBは12pinと13pinに対応しておりますのでMCUのピン数にあわせて選択してください。|
|[LED(SK6812MINI-E)](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/sk6812mini-e-10)|2|中央のキーとキーボード手前側の穴をバックライトで光らせることができます。|
|[LED(WS2812B)](https://shop.yushakobo.jp/collections/all-keyboard-parts/products/a0800ws-01-10)|10|アンダーグロウライトとしてキーボードの底面を光らせることができます。|

### 組み立て方

基本的には[通常版のRadialexの組み立て方](https://github.com/takashicompany/radialex#1-pcb%E3%81%AE%E8%A1%A8%E8%A3%8F%E3%82%92%E7%A2%BA%E8%AA%8D%E3%81%99%E3%82%8B)と同様です。
(一部部品は、通常版と異なります。)

[Daihuku Keyboard](https://www.youtube.com/c/DaihukuKeyboard)さんの[自作キーボード作ってみた Radialex編](https://www.youtube.com/watch?v=C8Qqe03oXgY)をご覧になるとより理解が深まるかと思います。

ご留意いただきたい点としましては、低コスト化のためボトムプレートの一部をくり抜いております。  
使用には問題ないかと思いますが、通常版とは打鍵感などが異なる可能性があります。  
<img src="https://github.com/takashicompany/radialex/blob/master/images/build/IMG_0974.jpg?raw=true" width="600px"/>

### 免責事項

当キーボードビルドガイドにて組み立てた際に生じた不利益や責任は組み立てたご自身に帰属します。

