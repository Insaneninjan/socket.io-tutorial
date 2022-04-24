# Chat app
- Express X Socket.io

## Flow
1. Expressでサーバを作成
2. サーバ側でsocket.ioの用意
3. クライアント側で送信
4. サーバ側で受け取って再度送信

# Tips
- Node.js
    - __dirname => Current Directoryを指す
    - sendFile() => ファイルを送信(あくまで指定したファイルしか読み込まない)
    - express.static() => 静的アセットを全て送信
- Socket io
JSと連携を取ることができる
    - emit() => 送信することができる

# Library
- socket.io
WEB Socketを利用することができる
[Official](https://socket.io/)
    - WEB Socket
    WebSocketはリアルタイムWeb技術の一種であり、リアルタイムかつ双方向な通信を実現するプロトコル
