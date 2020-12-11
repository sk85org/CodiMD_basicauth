CodiMDをオンプレミス運用する

フロントサーバーの前に https-portalを置き、フロントサーバーでBASIC認証(auth.txt)をかける　　

docker-compose up -d 

するとデータベースおよびアップロードしたファイルを保存する db, upload がそれぞれ作られるが  
uploadは適宜パーミッションを設定する必要がある。
