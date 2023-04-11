# UAFX_Ruby
## 1.資料
### 1-1.メーカーHP 設定ソフトのダウンロードページ
https://www.uaudio.jp/uafx/start  
必須なのはスマホ版。  
パソコン版は機能が少なく、不要かもしれない。
### 1-2.メーカーHP マニュアル（英語）
https://help.uaudio.com/hc/en-us/sections/360012250151-UAFX-Pedals-Documentation?_gl=1*1eb2g5u*_ga*OTE2NTcwNDA0LjE2ODA5NjM1OTA.*_ga_CPJ5176QFT*MTY4MDk2MzU5MC4xLjAuMTY4MDk2MzU5MC4wLjAuMA..
### 1-3.メーカーHP 製品ページ
https://www.uaudio.jp/guitar-pedals/ruby-63-top-boost-amplifier.html
### 1-4.代理店HP
https://hookup.co.jp/support/product/uafx-ruby-63-top-boost-amplifier/manuals  
日本語のマニュアルはこちらにあるので、主にこちらが参考になる。  

## 2.設定
### 2-1.初期化方法
初期化は基本のキではあるが、ことUAFXに関していえば、ペダル本体に保存されるのは「プリセット1つ」だけなので、初期化する必要性はあまりない。  
ボーナスエフェクトも、アプリ側ではなくペダル本体側に保存されるのではあるが、再セットアップ時に再ダウンロードできるので、バックアップする必要はない。  
UAFX ペダルをデフォルト設定に戻すと、保存されていたプリセット、ボーナスエフェクト、および製品登録が削除される。  
初期化すると、スマホとのペアリング、製品登録やボーナスエフェクトのダウンロード等、すべてやり直す必要がある。  
スマホとと再接続する場合、そのまえに、UAFX コントロールからペダルのアイコンをいったん削除し（左にスワ
イプすると削除ボタンが出てくる）、さらにスマホの Bluetooth 設定からもペダルをいったん削除する必要があります。  
また、初期化は時間がかかるため、慌てると初期化に失敗することがある。  
初期化に失敗するとスマホから認識されなくなって音も出なくなるので、その場合は再初期化すること。  
1. リアパネルの「PAIR」ボタンを押したまま、電源を入れる。ペダルのすべてのLEDが点滅し始めるまで “PAIR” ボタンを押し続ける（約10～15秒）、その後、ボタンを離す。  
2. 点滅・点灯が落ち着くまで待つ。  
3. もう一度 “PAIR” ボタンを押してからすばやく離し、ペダルの再起動が完全に完了するまで待つ（約20秒）。  
4. さらにUAFX ペダルの電源を抜いて電源を切り、再度電源を入れる。この2度目の再起動後、ペダルが使用できるようになる。  
5. 「UAFX Control モバイルアプリ」でBluetoothペアリングをやり直し、製品登録などする。うまくいかない場合、一度アプリからログオフしてペダルの情報を消し、再ログインしてから試す。それでもペアリングできない場合、音が出るか確認し、音が出ない場合は初期化に失敗している可能性があるので、再度初期化する。  
### 2-2.初期設定方法
- パソコンにUAFXペダルをつなぎ、設定ソフト「UAFX Controlデスクトップアプリ」を立ち上げると、UAFXペダルが登録され、ボーナスエフェクト（Rubyは追加のスピーカー）や、あればファームウェアアップデートがUAFXペダルのなかにインストールされる。デスクトップアプリでできることは以上。ただし「UAFX Control モバイル・アプリ」では、ファームウェア・アップデートを行えないので、ここまではデスクトップアプリでやるとよい。  
- スマホのGPSとBluetoothを有効にし、「UAFX Control モバイルアプリ」を立ち上げる。続けてUAFXの電源を入れるか、背面の「PAIR」ボタンを押して、「Bluetoothペアリング」をします。  
- モードの切替。ただしライブモードに切り替えると、特にできることはない。
- プリセットモード画面で、「Factory」や「Artist」にあるプリセットをダブルタップすると、ペダルのプリセットにその設定がロードされる。これらのプリセットのデータは、アプリ側ではなく、ペダル本体側に保存されている。  
- セッティング画面では、FSの設定、Bypassの設定、4ケーブルメソッドの設定などができる。
### 2-3.フットスイッチの働き設定
- 初期設定では、左のフットスイッチは「Liveモード（LED赤点灯）」と「Bypass（消灯）」のシーソ、右のFSは「Presetモード（LED緑点灯）」と「Bypass」のシーソーとなる。
- 初期設定は「Live/OFF | Preset/OFF」  
- モードを切り替えたい場合は、「Boost | Live/Preset」がよいか。
- BoostもVibratoもON/OFFしたい場合は、FS設定を「Boost | Vibrato」とする。他のチャンネル（Bril、Norm）ではVibratoできないため、ビブラートチャンネル専用の設定。ただし一度この設定にしてしまうと、モードを変更するのはスマホアプリからしかできなくなる。  
### 2-4.機能概要
- 「UAFX Control モバイルアプリ」で「Presets」の「Factory」や「Artist」でプリセットをダブルタップすると、「Preset」にその設定がロードされる。
- ライブモードのときに、“ALT/AMP/STORE” スイッチを下方向に約0.5秒押し続けると（“PRESET” フットスイッチのLEDが高速で点滅するまで）、その状態の設定がプリセットに保存されます。
- プリセットモードのときに、STOREすると、そのプリセットを呼び出してから変更したパラメーターのみが保存される。（呼び出したプリセットから変更していないパラメーターはどうなる？？）
- 
### 2-5.アンプのチャンネル毎の設定方法
- Brilliant
- Normal
- Vibrato
- 
### 2-6.Room
- Room：altにしてBassノブ
### 2-7.
-


### 2-5.お気に入り設定内容

### 2-6.「Recallシート」
https://media.uaudio.com/support/uafx/uafx-control-maps/UAFX+Ruby+Recall+Sheet.pdf  
UAFXペダルの図。設定値を書き込んでメモにすると便利。  
  
https://media.uaudio.com/support/uafx/uafx-control-maps/UAFX%20Ruby%20Control%20Maps.pdf  
UAFXペダルの部位名称説明図。慣れるまでは見るとわかりやすい。
