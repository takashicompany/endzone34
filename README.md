# EndZone34
<img src="https://github.com/takashicompany/endzone34/blob/master/images/13.jpg?raw=true" width="600px">

ミニマルな34キーのキーボードです。  
LEDとOLED、MXソケットに対応しています。


# 組み立て方

## ビルドログ

- [いとうひよこさんのNote](https://note.com/tsubuan_145/n/n91b1f3b4b958)

## 1. 部品の確認

### キットに同梱されているもの

|項目|個数|備考|
|:--|:--|:--|
|PCB|1|
|トッププレート|1|
|ボトムプレート|1|
|側面プレート|2|左右有り。キースイッチをMXソケットで取り付ける場合は不要|
|ProMicroプレート|1|
|ProMicro側面プレート|2|
|M2ネジ 10mm|18|
|M2ナット|18|
|ダイオード|34|
|リセットスイッチ|1|
|ゴム足シール|8|

### ご自身で用意されるもの
|項目|個数|備考|
|:--|:--|:--|
|キースイッチ|34|Cherry MX互換|
|キーキャップ|34|
|Pro Micro|1|必要な場合はコンスルーもご用意ください|

### MXソケットを利用する際に必要な部品

PCBがMXソケットに対応しているため、スペーサーとネジを別途ご用意頂き、キースイッチの付け替えが可能になります。
(MXソケットを使用する場合は側面プレートを取り付けることはできません。)

|項目|個数|備考|
|:--|:--|:--|
|MXソケット|34||
|両雌ネジスペーサー 7mm|8|
|M2ネジ 4mm|16|

## 2. ダイオードのはんだ付け

### ① PCBの裏表の確認

**こちらが表面**  
<img src="https://user-images.githubusercontent.com/4215759/126894525-773ba025-c7d0-44b4-b621-7f6577b48b53.jpg" width="600px">

**こちらは裏面**  
<img src="https://user-images.githubusercontent.com/4215759/126894585-142a470f-e593-4c37-b550-63f11f83f5d1.jpg" width="600px">

はんだ付けは**裏面**に行います

### ① マスキングテープで表面にはんだが漏れないようにする

(テープを見えやすくするために黒色のPCBで説明します)  
<img src="https://user-images.githubusercontent.com/4215759/126894591-0aa202f8-ddf5-49a7-866e-eff337febe99.jpg" width="600px">

当キットではトッププレートとPCBを密着させる方式なので、表面にはんだが漏れて凹凸ができないように、マスキングテープなどで穴を塞ぎましょう。

### ② ダイオードをはんだづけする

https://user-images.githubusercontent.com/4215759/126895350-43ae4cd4-408b-4ff4-ab5c-2903e0420978.mov

PCBのダイオードのはんだづけ箇所の片方にはんだを乗せておき(予備はんだ)、ピンセットでダイオードを持ちながら予備はんだを溶かしながらダイオードをはんだづけします。  
片方のはんだづけが終わったら、動画と同じく反対側をはんだづけしましょう。

<img src="https://user-images.githubusercontent.com/4215759/126895375-f9ed7d87-6309-47e0-a9c6-8ba0dcb1f50a.jpg" width="600px">

全部で34箇所あります。

## 3-a. キースイッチのはんだ付け

キースイッチをはんだ付けする場合は、以下の手順になります。

### ① トッププレートを取り出す

アクリル製のトッププレートを取り出します。  
<img src="https://user-images.githubusercontent.com/4215759/126895380-a1f796a2-ae36-4808-9bd4-5b905b892258.jpg" width="600px">

ネジ穴部分にアクリル栓が詰まっている場合は、ピンセットやネジで押し出すと取り出すことができます。  
全てのネジ穴が空いていることを確認しましょう。  
<img src="https://user-images.githubusercontent.com/4215759/126895396-c0a1bd8e-2ec5-4dfe-bb3b-8bd2f8c0f7a9.JPG" width="600px">

トッププレートの台紙を剥がします。   
剥がしづらい場合は、台紙を少し濡らすと剥がれやすくなります。
<img src="https://user-images.githubusercontent.com/4215759/126895426-e8640625-1db9-4baa-8a32-026198d6a06e.jpg" width="600px">

下記の画像のように両面を剥がします。  
<img src="https://user-images.githubusercontent.com/4215759/126895437-3d4e0273-b667-4c01-8f44-bf94b0c98d5c.jpg" width="600px">

### ② トッププレートを仮止め

当キーボードキットは、PCBとトッププレートを密着させる必要があるため、キースイッチのはんだ付けの際にトッププレートがぐらつかないようにすると作業が楽になります。  
同梱しているネジとナットを使って、PCBの表側にトッププレートを固定しましょう。
<img src="https://user-images.githubusercontent.com/4215759/126895447-308ed78c-42a7-4233-b667-47324edb83b9.jpg" width="600px">

あくまで仮止めですので、全ての箇所を固定しなくても問題ありません。
下記の画像は目安です。  
固定できたらPCBとトッププレートに隙間が無いことを確認してください。
<img src="https://user-images.githubusercontent.com/4215759/126895481-6ce317e6-be39-40ae-984d-888452d5d134.jpg" width="600px">


### ③ キースイッチをはんだ付けする
PCBとトッププレートを固定できたら、キースイッチのはんだ付けを行います。  
キースイッチがズレないように、マスキングテープなどで固定すると作業が楽になります。
<img src="https://user-images.githubusercontent.com/4215759/126895488-fe6b9e68-e52c-407f-99d6-171a6529950f.jpg" width="600px">

各キースイッチ、2箇所をはんだ付けします。  
**取付箇所毎にキースイッチの向きが異なります。**  
<img src="https://user-images.githubusercontent.com/4215759/126895489-a5922c4b-b8d9-4cd1-9489-31fa1a8f5b84.jpg" width="600px">

34個のキースイッチをはんだ付けできたら、高さがズレているものがないかを確認します。  
加えて、再びPCBとトッププレートの間に隙間が無いことを確認します。
<img src="https://user-images.githubusercontent.com/4215759/126895492-a566139d-4c8c-4a24-8d7d-7e2b8b899902.JPG" width="600px">

## 3-b. MXソケットでキースイッチを取り付ける場合

キースイッチをMXソケットではんだ付けする際は、以下の方法になります。
なお、この場合は側面プレートではなく、スペーサーでトッププレートとボトムプレートを固定することとなります。

### ① PCBにMXソケットをはんだ付けする
<img src="https://user-images.githubusercontent.com/4215759/130913743-2265f70a-8f87-489a-b21e-a28d4806142d.jpg" width="600px">

### ② トッププレートを取り出す

「3-a. ① トッププレートを取り出す」と同様にトッププレートを取りだします。

### ③ トッププレートにキースイッチを取り付ける

PCBとトッププレートの仮止めとして、キースイッチを数個取り付けます。
<img src="https://user-images.githubusercontent.com/4215759/130913892-a92a20e3-07d4-4a30-842e-7fbab8786a86.jpg" width="600px">

以下は一例になります。  
<img src="https://user-images.githubusercontent.com/4215759/130914164-16052508-99b8-425e-9912-5e8f743ec015.jpg" width="600px">

キースイッチをいくつか取り付けた後に、PCBにはんだ付けしたMXソケットにトッププレートに仮止めしたキースイッチを取り付けます。
<img src="https://user-images.githubusercontent.com/4215759/130914384-20df652b-4ba4-4f10-8206-29b138792810.jpg" width="600px">

トッププレートがたわまないように気をつけながら、全てのMXソケットにキースイッチを付けていきます。
<img src="https://user-images.githubusercontent.com/4215759/130914584-5a904de9-97eb-409a-9f0a-62029b2382ad.jpg" width="600px">

### ④ トッププレートにスペーサーを取り付ける

以下の赤丸の箇所にスペーサーを取り付けます。  
トッププレートとスペーサーをネジで固定します。  
<img src="https://user-images.githubusercontent.com/4215759/130913346-73cdc445-184c-42b2-86b9-32fa93fcf8db.jpg" width="600px">

下記の写真のように、トッププレートからネジで固定されたスペーサーがPCBを貫通してPCBの裏側に出ていると正しく取り付けられています。
<img src="https://user-images.githubusercontent.com/4215759/130919567-c3b19e0f-3aa8-426e-a505-f6feef43de17.jpg" width="600px">

## 4. リセットスイッチのはんだ付け
※リセットスイッチのはんだ付けは必須ではありません。組み立て後も、ピンセット等を用いて底面からリセット操作が可能です。

### ① PCBの裏面からリセットスイッチを差し込む
<img src="https://user-images.githubusercontent.com/4215759/126895513-850890f0-5a0d-4d82-aef1-96d515f441b8.jpg" width="600px">

### ② PCBの表面からはんだづけをする
<img src="https://user-images.githubusercontent.com/4215759/126895522-ec2ba4fd-2c97-4dfc-a83c-48aea7393018.JPG" width="600px">

### ③ はんだ付けした部分を可能な限り平らにする
<img src="https://user-images.githubusercontent.com/4215759/126895525-d86694ba-c97f-4b46-a288-1206dbca8fed.JPG" width="600px">

Pro Microとぶつかってしまう可能性があるので、ニッパーなどで平らにします。

<img src="https://user-images.githubusercontent.com/4215759/126895529-fdb3105b-c0b3-409e-beb0-6fee376ecae1.JPG" width="600px">

### ④ 絶縁テープなどではんだ付け部分を覆う

<img src="https://user-images.githubusercontent.com/4215759/126895533-0814e6e1-a732-43bd-86ee-b806592b716c.JPG" width="600px">

## 5. Pro Microの取り付け

Pro Microをご用意いただきます。  
PCBはコンスルーとはんだ付けの両対応をしています。  
<img src="https://user-images.githubusercontent.com/4215759/126895543-56accb04-8077-454f-94be-085d3c845eaf.jpg" width="600px">

Pro Microのチップなどが載っていない方を表側にし、PCBの表側に指します。
<img src="https://user-images.githubusercontent.com/4215759/126895549-f8d90fb0-62f2-4dfa-81a0-af3d200127a1.JPG" width="600px">

一度ここで、ProMicroをPCなどに繋ぎ、ファームウェアを焼いて動作確認をすると問題があった際に、対処が容易です。  
<img src="https://user-images.githubusercontent.com/4215759/126895554-4dc2b0e9-85dd-43cd-94e3-fb11aa716727.JPG" width="600px">

ファームウェアは[こちら](https://github.com/takashicompany/endzone34/blob/master/README.md#%E3%83%95%E3%82%A1%E3%83%BC%E3%83%A0%E3%82%A6%E3%82%A7%E3%82%A2)。

## 6. Pro Microプレートの取り付け
まずはPro Microの側面プレートを取り付けます。  
側面プレートは二種類あるので、お好みで選んでください。  
<img src="https://user-images.githubusercontent.com/4215759/126895680-4bd94580-d05f-48d8-85d3-459e2f21e28c.jpg" width="600px">

台紙を剥がして、側面プレートを2枚トッププレートに載せます。    
<img src="https://user-images.githubusercontent.com/4215759/126895684-b4fa8d95-6dea-4094-a893-0a0eb82f55be.jpg" width="600px">

次にPro Microプレートを取り付けます。  
<img src="https://user-images.githubusercontent.com/4215759/126895697-443e4e40-8269-4075-bd0e-9fce353177f4.jpg" width="600px">

台紙を剥がして、側面プレートの上に載せます。  
<img src="https://user-images.githubusercontent.com/4215759/126895702-e42f9994-50bd-474f-88f0-8d626ca4f466.jpg" width="600px">

ネジとナットで固定します。  
<img src="https://user-images.githubusercontent.com/4215759/126895705-bd5703d4-1cb5-424f-bc2f-8316c95f99bd.jpg" width="600px">

裏面は下記の写真のようにナットで抑えます。  
<img src="https://user-images.githubusercontent.com/4215759/126895714-fc3b19d0-3944-4e93-a1b8-4b8c3684a4d2.jpg" width="600px">

MXソケットを利用する場合は、ナットの代わりにスペーサーを用いると良いです。

## 6. LEDの取り付け

LEDの取り付けは必須ではありません。一度組み立てた後で取り付けることでも可能です。  
LEDはWS2812Bを使用します。下記の画像の順番で取り付けます。 
<img src="https://user-images.githubusercontent.com/4215759/126898714-dd84bf8a-0f16-42e6-a23e-a31729f15cd4.jpg" width="600px">

取り付ける際に、PCBのプリント(角の塗りつぶし)とLEDの角の向きが合うようにします。 
<img src="https://user-images.githubusercontent.com/4215759/126898731-9baded0d-d4ca-40aa-a9f6-068f9fe2a321.JPG" width="600px">

まずは予備ハンダをします。利き腕側で手前の側の部分からはんだ付けをすると楽にできます。
<img src="https://user-images.githubusercontent.com/4215759/126898744-23300a74-0750-41a6-bd80-d87521df9511.jpg" width="600px">

一つのLEDの4箇所をはんだづけします。  
<img src="https://user-images.githubusercontent.com/4215759/126898750-b483c58f-3f24-47ad-90ba-0691f00034ef.jpg" width="600px">

一つはんだ付けができたら、LEDが光るかを確認しましょう。  
USBでPCにキーボードを接続した後、`RGB_TOG`キーを押して、LEDが光るかを確認します。  
<img src="https://user-images.githubusercontent.com/4215759/126898756-685618e8-bbce-4e0a-ba85-c973addb2beb.jpg" width="600px">

全部で9つのLEDを取り付けられることができます。  
<img src="https://user-images.githubusercontent.com/4215759/126898759-282007fd-3089-4eb0-8b3b-c8228f2afacd.jpg" width="600px">


## 7. ケースの組み立て

※ MXソケットでキースイッチを固定する場合は、側面プレートを取り付けることができません。

側面プレートを取りだします。側面プレートは左右で分かれています。
<img src="https://user-images.githubusercontent.com/4215759/126898770-d50f50d9-1583-4ffb-94e3-77e5cecc3eec.jpg" width="600px">

ボトムプレートも取りだします。  
<img src="https://user-images.githubusercontent.com/4215759/126898780-a9a70aba-c896-428a-82ed-cc0f741d1f81.jpg" width="600px">

台紙を取り外して、側面プレートとボトムプレートをネジとナットで取り付けます。
<img src="https://user-images.githubusercontent.com/4215759/126898857-2d92d840-b4a7-4438-8ee3-ebaf84119c3c.jpg" width="600px">

<img src="https://user-images.githubusercontent.com/4215759/126898868-3e9a30e7-942d-445b-b667-a7a795960940.JPG" width="600px">

側面プレートとボトムプレートを取り付けた後は、ゴム足をケースに貼ります。
<img src="https://user-images.githubusercontent.com/4215759/126898870-df9cf744-0b1a-4a42-ba35-7c661f12075b.jpg" width="600px">

### MXソケットでキースイッチを取り付けた場合

以下の赤丸の箇所をネジ止めします。  
<img src="https://user-images.githubusercontent.com/4215759/130918068-1f28270c-306a-4f74-9756-10986f06874a.jpg" width="600px">

# 8. ファームウェア

## [QMK Firmware](https://github.com/qmk/qmk_firmware)
- QMK Firmware公式に[マージ済み](https://github.com/qmk/qmk_firmware/pull/13847)です
- [keyboards/takashicompany/endzone34](https://github.com/qmk/qmk_firmware/tree/master/keyboards/takashicompany/endzone34)にファームウェアを用意しております。

## VIA用のファームウェアは[こちら](https://github.com/takashicompany/endzone34/releases/download/via-0.0.3/takashicompany_endzone34_via.hex)
- [Remap](https://remap-keys.app/)へ登録済みですので、上記のVIA対応したファームウェアをPro Microに書き込むことでブラウザからキーマップの変更が可能です。
- (2021/09/01) OLEDの表示とレイヤー数を8にしたファームウェアを追加しました。

# 9. OLEDが点灯しない場合
ファームウェアの容量の関係でVIAのファームウェアにOLEDが入っていないことがあります。  
疎通を確認するために、[デフォルトのファームウェア](https://github.com/takashicompany/endzone34/releases/download/via-0.0.2/takashicompany_endzone34_default.hex)で一度OLEDの確認をお願いします。

<img src="https://github.com/takashicompany/endzone34/blob/master/images/08.jpg" width="600px">

# 10. 自慢する

完成しましたら、ぜひSNSなどに写真を投稿頂ければと思います。  
Twitterのハッシュタグは`#EndZone34`を付けていただけば幸いです。  
キットを組み立てた感想や、キーボードを使った所感などをお待ちしております！  

また、毎週日曜日の１9時より実施されている[#KEEP_PD](https://twitter.com/hashtag/KEEB_PD?f=live)に投稿頂くこともオススメです。  
開催の告知は[@KEEB_PD](https://twitter.com/KEEB_PD)にて行われております。

ご不明な点などございましたら、[@takashicompany](https://twitter.com/takashicompany)にメンションやDM頂ければと思います！
