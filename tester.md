# IR Station テスター資料

## テスト端末

以下の各端末で確認して頂きたいです．既にお持ちの端末だけで大丈夫です．

  * And:  Android端末
  * Win:  Windows PC
  * Mac:  Apple Mac PC
  * iPh:  iPhone or iPod touch
  * oth:  その他，ブラウザを使用できる端末

## 動作確認項目

### IR-Stationのセットアップについて

各端末でチェックして頂きたいもの

|And|Win|Mac|iPh|oth|項目|
|:--|:--|:--|:--|:--|:--|
||||||電源をつないだら，「IR-Station」という名前のSSIDが現れるかどうか|
||||||WiFiにつないだ時点で自動でSetup画面が表示されるかどうか|
||||||http://192.168.4.1 につなぐとsetup画面が表示されるかどうか|
||||||WiFi Stationモードとしてセットアップできるか|
||||||接続が切れることはあるか|

どれか一つの端末でチェックして頂きたいもの

|チェック|項目|
|:--|:--|
||アクセスポイントモードとしてセットアップできるか|


### IR-Stationのメイン機能について

各端末でチェックして頂きたいもの

|And|Win|Mac|iPh|oth|項目|
|:--|:--|:--|:--|:--|:--|
||||||画面は乱れていないか，変なところはないか|
||||||http://hostname.local のように名前でのアクセスはできるか．|

どれか一つの端末でチェックして頂きたいもの

|チェック|項目|
|:--|:--|
||Informationsに書いてある情報は正しいか．|
||赤外線の登録は上手くできるか|
||赤外線の送信は上手くできるか|
||画面上のログは正しく表示されているか|
||ボタンの名前変更は上手くできるか|
||赤外線データのダウンロードは上手くできるか|
||赤外線データのアップロードは上手くできるか|
||赤外線データの削除は上手くできるか|
||WiFiの変更（つなぎ変え）機能は上手く動作するか|

### 赤外線コントロール可能の家電製品

赤外線リモコンを搭載した家電製品の中で，IR-Stationによりコントロールできた端末と，できなかった端末を教えていただきたいです．

例:

可能

 * テレビ(SHARP LC-32W25)
 * LED証明(アイリスオーヤマ　型番はわからない)

不可能

  * エアコン(ダイキン工業株式会社 AN22JRS-W)

### mDNS（マルチキャストDNS）機能について

LAN内でIR-Stationに接続するとき，IPアドレスで接続する方法と， http://hostname.local のようにhostnameで名前アクセスする方法があります．後者はmDNSという技術を用いています．このmDNSは，Apple Inc.のBonjourというソフトウェアにより実装されており，Apple端末でしか今のところ動作しません．ｓかし，iTunesなどのAppleのソフトウェアがインストールされたWindows PCにもBonjourがインストールされており，使えることがわかっています．

mDNSでのアクセスは，IPアドレスを知る必要がないのでとても便利ですが，環境によっては接続が不安定で，つながらなかったり遅かったりする欠点があります．

そこで，mDNSを使ってIR-Stationに接続したとき，どのくらい時間がかかるかを調べていただきたいです．これは，接続するたびに変わると思います．しばらくの間接続せずにおいておくと，次の接続に時間がかかることがあります．それも含めて確認をお願いします．

### その他

その他，気になった点や，欲しい機能などをできるだけ多く，詳しく教えていただきたいです．