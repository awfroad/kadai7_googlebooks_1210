# kadai7_googlebooks_1210
xamppを利用したブックマークアプリ

## ①課題内容（どんな作品か）
### キーワードで険悪した本をDBに保存するアプリ
- 検索したキーワードに関連する本がXAMPPのDBに入ります。

## ②工夫した点・こだわった点
### 検索したキーワードに関連する本の情報が直接DBに入ります。
- APIで得た情報をDBに保存する様にしました。
- 一覧画面でDBに入った本のデータが検索キーワードと共に表示されます。
- 登録リストの画像をクリックすると本のプレビューが、  
  タイトルをクリックすると本の詳細ページが開きます。

## ③難しかった点・次回トライしたいこと(又は機能)
### 難しかったこと
- 何らかのAPIで取得したデータをDBに保存出来ないかと考え、  
  まずYouTubeアプリで動画を引っ張ってくるところまで進めましたが、  
  検索するとすぐに1日の使用上限に達することが分かり、YouTubeアプリを断念。  
  次にAWSでamazonから本のDB作りに切り替えて挑戦しましたが、  
  APIキー以外にもassociate IDが必要であり、登録に時間がかかりそうなため、これも断念。  
  ようやくGoogle Books APIに辿り着き、完成に至りました。
- Google books APIとDBとの接続が難しかったです。  
  山崎先生のYouTubeとOpen AIを駆使しながら作りました。

### 次回トライしたいこと
- 検索がデフォルトなので、検索キーワードに関連するおすすめ本５冊が、  
  リストアップされる様にしたいです。

## ④質問・疑問・感想、シェアしたいこと等なんでも
- [感想]データ入力を手打ちではなく、APIで入力したいと先週から  
  頑張りましたが、手強かったです。なかなか進まないので焦りました。  
  ただ、回り道をした分、APIの使用フローが少し理解出たことと  
  APIを利用するにはもう少し知識と習熟が足りないということが  
  分かったのが収穫でした。
