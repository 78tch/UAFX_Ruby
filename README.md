ｗｐ# UAFX_Ruby
## 1.はじめに
### 1-1.UAFX Ruby ってなに？
ストンプBOX（単体エフェクター）形状のアンプシュミレーターであり、VOX AC30 をベースにしている。  
フットスイッチで、ノブの目盛り状態のとおりの音がでる「ライブモード」と、ノブの目盛りに関わらず、保存した設定の音が出る「プリセットモード」との２つを切り替えながら使う。  
なお、プリセットスロットに保存できるプリセットは１つだけである。  
残しておきたいプリセットができた場合は、「リコールシート」に目盛りを手書きメモするか、「UAFX Control モバイル・アプリ」の「User」領域に保存すれば、別の設定でプリセットを上書きしても、のちにアプリから再度ロードすることができる。  
### 1-2.チャンネルについて
アンプシュミレーターとしては、3チャンネル分のモデリングを内蔵しており、「ライブモード」の時は、「CHANNEL」スイッチで切り替える。  
1. BRILLIANTチャンネル：63年製の「トップ・ブースト」。“BOOST” は、EP-III プリアンプからの入力ゲインを加えるが、低めだとなめらかになる。  
2. NORMALチャンネル：61年製の「ノン・トップ・ブースト」。“BOOST” は、ゲルマニウム・トランジスタ・ベースのトレブル・ブースター回路からの入力ゲイン。  
3. VIBRATOチャンネル：63年製の「トップ・ブースト」、ビブラートは速さや深さを調整でき、切ることもできるし、設定すれば、フットスイッチでON/OFFすることもできる。“BOOST” は、クリーンなゲイン。  
### 1-3.スピーカーについて
「SPEAKER」スイッチでスピーカー（キャビネット）を選択する。  
もともと3つ内蔵しているが、製品登録すればさらに3つ追加され、6種類のスピーカーのなかから選択できる。  
それぞれマイクも反映されているが、マイクだけ変更することはできない。  
### 1-4.ノブについて
「ライブモード」にして、チャンネル・スイッチとスピーカー・スイッチの位置を決めたら、後はノブで調節する。  
1. どのチャンネルでも使うノブ：「VOLUME」、「CUT」、「OUTPUT」、「BOOST」、altにして「ROOM」  
2. 「BRIL」チャンネルだけで使うノブ：「BASS」、「TREBLE」  
3. 「VIB」チャンネルだけで使うノブ：altにして「SPEED」、「INTENSITY」（INTENSITYを0にすると、ビブラートがOFFになる。）  
### 1-5.音作り手順概要
1. ライブモードにする。
2. 3チャンネルそれぞれ、まずは各ノブ12時から始める。
3. 「VOLUME」を、ノイズが気にならない限界まで上げる。
4. 「BOOST」を0からMAXまで回して、そのチャンネルで心地よい所を探す。
5. 「OUTPUT」を、ノイズが気にならない限界まで上げる。
6. 「CUT」（Brilはさらに「BASS」、「TREBLE」）で、音質を微調節する。
7. 「ROOM」やビブラートを調節する。
8. 「VOLUME」を下げて「OUTPUT」を上げて、より心地よい音になるか試す。
9. 以上を適宜繰り返す。
10. ライブモードの設定が固まってきたら、改めてスピーカー（6種類）をオーディションする。
11. FSでオンオフできるのは「BIBRATO」か、「BOOST」かのどちらかなので、どちらをON/OFFしたいか考える。
12. 必要なら、「UAFX Control モバイルアプリ」でFS設定を「Boost | Live/Preset」または「Vibrato | Live/Preset」にする。
13. 設定が固まったら、「リコールシート」に目盛りをメモる。
14. 「Alt/Amp/Store」スイッチをStoreに0.5秒以上倒すことで、いまの設定がプリセットスロットに保存され、「UAFX Control モバイル・アプリ」でつないでいると、「User」領域にも保存される。
  
## 2.資料
### 2-1.メーカーHP 設定ソフトのダウンロードページ
https://www.uaudio.jp/uafx/start  
プリセットをザッピングするなど、普段使うのはスマホ版。  
パソコン版は機能が少ないが、ファームウェアアップデートだけはパソコン版でしかできない。  
### 2-2.メーカーHP マニュアル（英語）
https://help.uaudio.com/hc/en-us/sections/360012250151-UAFX-Pedals-Documentation?_gl=1*1eb2g5u*_ga*OTE2NTcwNDA0LjE2ODA5NjM1OTA.*_ga_CPJ5176QFT*MTY4MDk2MzU5MC4xLjAuMTY4MDk2MzU5MC4wLjAuMA..
### 2-3.メーカーHP 製品ページ
https://www.uaudio.jp/guitar-pedals/ruby-63-top-boost-amplifier.html  
### 2-4.代理店HP
https://hookup.co.jp/support/product/uafx-ruby-63-top-boost-amplifier/manuals  
日本語のマニュアルはこちらにあるので、主にこちらが参考になる。  
  
## 3.設定
### 3-1.初期化方法
初期化は基本のキではあるが、ことUAFXに関していえば、ペダル本体に保存されるのは「プリセット1つ」だけなので、初期化する必要性はあまりない。  
「アンプ」である、とみれば、「つまみは都度0に戻して、都度いいポジションまで回す。目盛りにしるしを付ける。」ぐらいの運用でもよいのかもしれない。  
ボーナスエフェクトも、アプリ側ではなくペダル本体側に保存されるのではあるが、再セットアップ時に再ダウンロードできるので、バックアップする必要はない。  
UAFX ペダルをデフォルト設定に戻すと、保存されていたプリセット、ボーナスエフェクト、および製品登録が削除される。  
初期化すると、スマホとのペアリング、製品登録やボーナスエフェクトのダウンロード等、すべてやり直す必要がある。  
スマホとと再接続する場合、そのまえに、UAFX コントロールからペダルのアイコンをいったん削除し（左にスワ
イプすると削除ボタンが出てくる）、さらにスマホの Bluetooth 設定からもペダルをいったん削除する必要があります。  
また、初期化は時間がかかるため、慌てると初期化に失敗することがある。  
初期化に失敗するとスマホから認識されなくなって音も出なくなるので、その場合は再初期化すること。  
1. リアパネルの「PAIR」ボタンを押したまま、電源を入れる（約10～15秒）。  
2. 「SPEAKER」のLEDが１つずつ順に点灯したのち、３つ同時に点滅し始めたら、ボタンを離す。  
3. すぐにもう一度 “PAIR” ボタンを一瞬押してからすばやく離す。ペダルの再起動がかかる。完全に起動するまで待つ（約20秒）。  
4. さらにUAFX ペダルの電源を抜いて電源を切り、再度電源を入れる。この2度目の再起動後、ペダルが使用できるようになる。  
5. 「UAFX Control モバイルアプリ」でBluetoothペアリングをやり直し、製品登録などする。うまくいかない場合、一度アプリからログオフしてペダルの情報を消し、再ログインしてから試す。それでもペアリングできない場合、音が出るか確認し、音が出ない場合は初期化に失敗している可能性があるので、再度初期化する。  
### 3-2.初期設定方法
- パソコンにUAFXペダルをつなぎ、設定ソフト「UAFX Controlデスクトップアプリ」を立ち上げると、UAFXペダルが登録され、ボーナスエフェクト（Rubyは追加のスピーカー）や、あればファームウェアアップデートがUAFXペダルのなかにインストールされる。デスクトップアプリでできることは以上。ただし「UAFX Control モバイル・アプリ」では、ファームウェア・アップデートを行えないので、ここまではデスクトップアプリでやるとよい。  
- スマホのGPSとBluetoothを有効にし、「UAFX Control モバイルアプリ」を立ち上げる。続けてUAFXの電源を入れるか、背面の「PAIR」ボタンを押して、「Bluetoothペアリング」をします。  
- モードの切替。ただしライブモード画面では、、特にできることはない。アプリからモードを切り替えられることに意味がある。  
- プリセットモード画面で、「Factory」や「Artist」にあるプリセットをダブルタップすると、ペダルのプリセットにその設定がロードされる。これらのプリセットのデータは、アプリ側ではなく、ペダル本体側に保存されている。  
- セッティング画面では、FSの設定、Bypassの設定、4ケーブルメソッドの設定などができる。
### 3-3.フットスイッチの働き設定
- 初期設定では、「Live/OFF | Preset/OFF」で、左のフットスイッチは「Liveモード（LED赤点灯）」と「Bypass（消灯）」のシーソ、右のFSは「Presetモード（LED緑点灯）」と「Bypass」のシーソーとなる。
- モードを切り替えたい場合は、「Boost | Live/Preset」が使いやすいか。
- BoostもVibratoもON/OFFしたい場合は、FS設定を「Boost | Vibrato」とする。他のチャンネル（Bril、Norm）ではVibratoできないため、ビブラートチャンネルで使う時専用の設定となる。ただし一度この設定にしてしまうと、モードを変更するのはスマホアプリからしかできなくなる。  
### 3-4.音色のオーディション
- 「UAFX Control モバイルアプリ」でプリセットのカテゴリー（User、Factory、Artist、Favorite）でプリセットをダブルタップすると、プリセットスロットにロードされる。  
- プリセットを右方向にスワイプすると、フェイバリットとして登録が行える。解除するには、再度プリセットを右方向にスワイプする。プリセットをフェイバリットとして登録すると、プリセット名に星印が付く。  
- 気に入ったプリセットがあったら、パラメーターは見られないが、説明は見られる。調整したものを「User」カテゴリーに保存するとよいか。  
### 3-5.プリセットスロットへの保存
- ライブモードのときに、“ALT/AMP/STORE” スイッチを下方向に約0.5秒押し続けると（“PRESET” フットスイッチのLEDが高速で点滅するまで）、その状態の設定がプリセットに保存されます。  
- プリセットモードのときに、STOREすると、そのプリセットを呼び出してから変更したパラメーターのみが保存される。（呼び出したプリセットから変更していないパラメーターはどうなる？？）  
### 3-6.アンプのチャンネル毎の設定方法
- Brilliant：63年製の「トップ・ブースト」、“CUT”、“BASS”、“TREBLE” ノブで調整する。“BOOST” ノブは、EP-III プリアンプからの入力ゲインを加えるが、低めだとなめらかになる。「WORN BLUE」スピーカーなど。
- Normal：61年製の「ノン・トップ・ブースト」、“CUT” ノブのみで調整し、“BASS”、“TREBLE” ノブは機能しない。“BOOST” ノブは、ゲルマニウム・トランジスタ・ベースのトレブル・ブースター回路からの入力ゲインを加える。「SILVER」スピーカーなど。
- Vibrato：63年製の「トップ・ブースト」、“CUT” ノブのみで調整し、“BASS”、“TREBLE” ノブは機能しない。“BOOST” ノブは、クリーンなゲインを加える。ビブラートは、フットスイッチでOFFにすることもできる。  

## 4.各ノブ
### 4-1.ボリューム（VOLUME）
アンプのゲインを調整する。  
“VOLUME” ノブを上げるとアンプのキャラクターが変化し、オーバードライブやコンプレッションが強くなる。  
クリーンな「ポスト・アンプ」のボリュームを調整する場合は、“Output” コントロールを使用してください。  
### 4-2.カット（CUT）
パワーアンプをフィルタリングすることで、高域を低減する。  
このノブを時計方向に回していくと、よりダークなトーンとなる。  
### 4-3.アウトプット（OUTPUT）
出力レベルを調整する。  
ノブが正午の位置に設定されている時、バイパスされたボリュームとほぼ同じレベルになる。  
### 4-4.ベース（BASS）／ルーム（ROOM）
BASSが効くのはBRILチャンネルのみ。  
ノブを時計方向に回すと、低域周波数がカットされる。  
ROOMはまずは12時から始めるとよい。
### 4-5.トレブル（TREBLE）／スピード（SPEED）
TREBLEが効くのはBRILチャンネルのみ。  
ノブを時計方向に回すと、高域周波数がカットされる。  
ビブラートスピードが効くのはVibratoチャンネルのみ。  
### 4-6.ブースト（BOOST）／インテンシティ（INTENSITY）
ブーストでは、ブースト量を調整する。このノブを “OFF” に設定すると、ブースト回路をバイパスできる。  
インテンシティでは、ビブラートの強さを調整する。  
### 4-7.ベースとトレブルを調整する際の注意点
- これら2つのノブを左に振り切ると、「中域が減少し、低域と高域が増加する」という非常に極端なEQカーブとなる。  
- これら2つのノブを正午の位置付近まで上げると、中域が増え、よりナチュラルでフラットな、充実したトーンになる。  
- これら2つのノブを同じような位置に調整することで、使いやすいサウンドを見つけやすい。  
  
### 5.設定の手順
1. まずはライブモードで、「BRIL」チャンネル、「NORM」チャンネル、「VIB」チャンネルの音を確認する。
2. スピーカーは、「BRIL」はBlue Mod（上LEDが緑）、「NORM」はSILVER（上LEDが赤）、「VIB」は（？）から試すとよいかも。
3. ノブ類はいずれも12時で始める。「VOLUME」、「CUT」、「OUTPUT」、（BRILのみ「BASS」、「TREBLE」）、「BOOST」、altにして「ROOM」、（VIBのみ「SPEED」、「INTENSITY」）
4. ノブ類を、12時、12時から少し左に振る、左に振り切る、12時から少し右に振る、右に振り切る、の5通りを試す。いったん12時に戻して、ほかのノブも試す。
5.  「UAFX Control モバイルアプリ」でFactoryやArtistのプリセットをオーディションする。
6. 音色として使えるのはライブモードとプリセットモードの2つだけなので、使いたい音色を2つに絞り、どちらをプリセットスロットに入るか決める。演奏中にノブを触らないのであれば、どちらでもよい。
7. ライブモードの時の音色を、ノブを使って設定する。
8. ライブモードの設定が固まってきたら、改めてスピーカー（6種類）をオーディションする。
9. FSでオンオフできるのは「BIBRATO」か、「BOOST」かのどちらかなので、どちらをON/OFFしたいか考える。
10. 「UAFX Control モバイルアプリ」でFS設定を「Boost | Live/Preset」または「Vibrato | Live/Preset」にする。
  
### 6.「Recallシート」
https://media.uaudio.com/support/uafx/uafx-control-maps/UAFX+Ruby+Recall+Sheet.pdf  
UAFXペダルの図。設定値を書き込んでメモにすると便利。  
  
https://media.uaudio.com/support/uafx/uafx-control-maps/UAFX%20Ruby%20Control%20Maps.pdf  
UAFXペダルの部位名称説明図。慣れるまでは見るとわかりやすい。
