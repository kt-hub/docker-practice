docker-compose run -p 54040:4040  ngrok ngrok http http://192.168.33.15:48888

ngrok http -auth="username:password" 8080
auth オプションはログインしてauthtokenをインストールしてから使用できる