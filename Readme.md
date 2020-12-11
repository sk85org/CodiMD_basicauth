CodiMDをオンプレミス運用する　　
フロントサーバーの前に https-portalを起き、フロントサーバーでBASIC認証をかける　　

docker-compose up -d すると
データベースおよびアップロードしたファイルを保存する db, upload がそれぞれ作られるが  
uploadは適宜パーミッションを設定する必要がある。
