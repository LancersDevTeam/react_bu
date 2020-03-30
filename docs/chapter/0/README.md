# りあくと部 ホームルーム

## ホームルームの目標

ローカル開発環境の整備を行う

## 目次

1. Visual Studio Code をインストールしましょう
2. Node.js をインストールしましょう
3. npm がインストールされていることを確認しましょう

## 手順

### 1. Visual Studio Code をインストールしましょう

Web サイトを作るにあたり、テキストエディタは必須です。

メモ帳でも Web サイトを作ることは可能ですが、開発効率を考え、今回は Visual Studio Code を使用することを推奨します。

[公式サイト](https://code.visualstudio.com/)より Visual Studio Code のダウンロードを行い、ついでにインストールまで行いましょう。

また今後については、Visual Studio Code を使用することを前提とした上で手順の記載を行っていきます。

Visual Studio Code 以外のテキストエディタを使用される場合は、随時読み替えや臨機応変な対応を行うようにしてください。

### 2. Node.js をインストールしましょう

Node.js について理解を深めたい方は、[こちら](https://ja.wikipedia.org/wiki/Node.js)をご覧ください。

さっそくインストールを行った Visual Studio Code を起動しましょう。

Visual Studio Code からターミナルを開き、以下のコマンドを実行します。

`node -v`

コマンドを実行した結果、`v12.7.0`など、バージョンが表示された場合、既に Node.js がインストールされているため、この手順は不要です。

`command not found`などと表示された場合は、Node.js がインストールされていないため、以下の手順を踏んでください。

[公式サイト](https://nodejs.org/ja/)より Node.js のダウンロードを行い、ついでにインストールまで行いましょう。

今回の開発では、推奨版及び最新版は問いません。

また、Node.js のバージョンについては、[公式サイトの記載](https://create-react-app.dev/docs/getting-started#creating-an-app)を満たしているか確認しましょう。

### 3. npm がインストールされていることを確認しましょう

npm について理解を深めたい方は、[こちら](<https://ja.wikipedia.org/wiki/Npm_(%E3%83%91%E3%83%83%E3%82%B1%E3%83%BC%E3%82%B8%E7%AE%A1%E7%90%86%E3%83%84%E3%83%BC%E3%83%AB)>)をご覧ください。

Visual Studio Code のターミナルにて、以下のコマンドを実行します。

`npm -v`

コマンドを実行した結果、`6.10.0`など、バージョンが表示されると思われます。

Node.js をインストールした時に、同時に npm もインストールされるので、別途インストールなどは不要です。

また、npm のバージョンについては、[公式サイトの記載](https://create-react-app.dev/docs/getting-started#quick-start)を満たしているか確認しましょう。
