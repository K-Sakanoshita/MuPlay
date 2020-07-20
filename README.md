# MuPlay

* 1998年頃から2000年初頭に開発していたMSXturboR向けのMGS/MPK(勤労5号)フォーマットの音楽プレイヤー
* 恥を忍んで当時の内容で公開します（ソースコードのコメントも恥ずかしいけど、そのまま公開）
* 記載しているURLは無くなっています。またGPLのバージョン指定も無く、説明も曖昧ですがそのまま
  * ライセンスはLICENCEファイルに記載しています。

      ==============================================================================
      [名称] MuPLAY Ver 2.61
      [環境] MSX2以降(MSX-DOS2,空メモリ64K以上) / MSXturboRを強く推奨
      [作者] SAKA,協力してくれたみなさん
      [権利] GNU Public Licence準拠
      ==============================================================================
      
      *はじめに
      
      MuPLAYは、いろんなみなさんの協力のおかげで今まで続いてきました。
    
      漢字表示ル－チンを作成して下さった、まさるん氏
      MuPLAYのロゴデザインをして下さった、Mightning Volt1-2-3氏、スエナガカツミ氏
      勤労５号ドライバを作成して下さった、黒田 圭一氏
      英語のマニュアルを作成して下さった、タカミチ氏
      パソコン通信ネット、Illusion City,Mario net,RAY-NETのみなさん
      感想や不具合報告を下さった方達…等
      
      本当にありがとうございます。
       
      *MuPLAY Ver 2.61とは？
      
      MSX用マルチミュ－ジックプレイヤ－です。
      現在の対応ドライバは以下の通りです。
      - MGS(Ain氏作),MPK(K-Kaz氏作),MIO(本杜前氏作),勤労５号(黒田圭一氏作)
      
      動作環境としては実質的にMSXturboR以降専用になります。
      MSX2にDOS2を追加する事で動作はしますが、暴走する可能性が高いはずです。
      
      *起動方法
      
      MUPLAY.COMを環境変数PATHに通ったディレクトリにコピ－します。
      その際、各種ドライバもMUPLAY.COMと同じ場所にコピ－しておいて下さい。
      MIOに関してはコピ－しなくても結構です。常駐させておいて下さい。
      
      ファイルのコピ－が終わったら、コマンドラインから以下のように打ち込みます。
      x:\>MUPLAY 演奏させたいファイル名(ファイル名は省略可)
      
      一瞬待った後に、MuPLAYの起動画面が表示されるはずです。
        
      *操作方法
      
      基本的にマウス操作が中心になります。
      また、キ－ボ－ドでも操作が出来るように設定してあります。
      *慣れるとキ－ボ－ド操作の方が快適です。
  
      [最も重要]
      MuPLAYの終了は[ESC]キ－です。
      マウスでは「EXIT」とかかれたボタンをクリックして下さい。
      
      [画面上部]
      左側に鍵盤が表示されていますが、演奏状態を表示だけです。操作は出来ません。
      
      右側にドライブ名「A: B: 」等が表示されていますが、このドライブ名をクリック
      する事で他のドライブのファイルを検索する事が出来ます。
      キ－ボ－ドではテンキ－の1～8がA～Hドライブの移動に対応しています。
      また、緑色に光っている箇所をクリックするとチャンネルモニタ等の動きを速くし
      たり止めたり、曲をチャンネル単位でon/offする事が出来ます。
       
      [画面中部]
      CDプレイヤ－の様なボタンが並んでいますが、演奏を制御する為に利用します。
      キ－ボ－ドから操作する場合は、ファンクションキ－のF1～F5に対応しています。
      
      [画面下部]
      ファイル一覧が表示されています。演奏したいファイルをクリックする事で演奏を
      始める事が出来ます。キ－ボ－ドの場合は、カ－ソルキ－でファイル名の下にある
      緑の下線を移動させる事が出来ます。(CAPSはoffにしておいて下さい)
      演奏させたいファイル名の下に緑の下線を移動させたらリタ－ンキ－で演奏開始。
      
      *ライセンス
      
      MuPLAYはGPL準拠のオ－プンソ－スソフトウェアとして公開しています。
      
      簡単に説明すると、誰でも自由に複製、改変、配布する事が出来ます。
      MuPLAYを改変した場合、改変後のソ－スリストは公開しなければなりません。
      ちなみに金銭の受け渡しについて制約はありません。売っても構いません。
      ただし、コピ－禁止にして売ることは出来ません。

      もっと簡単に説明すると「独占しちゃだめ。みんなに配ろう」って事です。
      
      *サポ－トサイト
      
      MuPLAYサポ－トサイト
      http://www.activemsx.net/saka/muplay/