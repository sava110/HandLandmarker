# MediaPipeを使った手形状認識Webアプリケーション 

## 概要（Overview）
MediaPipe の Hand Landmarkerを使い。、手の21か所の特徴点（landmarks）をリアルタイムで検出するAIモデルを実装したWebアプリケーションを作成しました。

## 必要なもの
- VIsual Studio Code (VSCode)
- Google ChromeなどのWebブラウザ
- Webカメラ

## セットアップ手順
### 1. このリポジトリをクローン
- `git clone https://github.com/sava110/HandLandmarker.git`
- または、 .zipでダウンロードして展開をしてください。

### 2. VSCodeでフォルダを開く 
- VSCodeを起動し、index.htmlがあるフォルダを開きます。

### 3. Live Server拡張機能をインストール
  1. VSCode左側の拡張機能アイコン（四角いアイコン）をクリック
  2. 検索欄に`Live Server`と入力
  3. 「Live Server」(By Ritwick Dey)を選択し、「install」ボタンをクリック

### 4. サンプルを起動
  1. index.htmlをエディタで開く
  2. 右下の「Go Live」ボタンをクリック
  （または、右クリック→「Open with Live Server」をクリック）

## 使い方(How to Use)
このアプリは、WebブラウザからMediaPipeを使った手形状認識を体験できます。
※Google Chromeを推奨

1. **アプリにアクセス**：提供したURLをクリックして、アプリのトップページにアクセスします。
2. **検出開始**：トップページにある「start」をクリックします。※ブラウザがカメラの使用許可を求めてきたら、必ず「許可」を押してください。
3. **手形状を認識させる**：Webカメラに向かって、片手あるいは両手で何かしらの形を作ってみてください。
4. **カメラを停止する**：認識を終了したい場合は、「stop」ボタンをクリックしてください。

## 機能
- **手の検出（最大2本の手）**：最大2本の手を認識できます。右手と左手の区別も可能です。
- **21個の3次元ランドマークの検出**：デベロッパーツールより、landmarksの数と座標（x, y, z）の確認がConsoleに表示されます。

## ライセンス（License）
- このプロジェクトは、MITライセンスのもとで公開しています。
