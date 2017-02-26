api-blueprint-skeleton
====

API Blueprintを楽に始めるためのべんりなやつ

----

毎回思うけど、解説記事でオナニーしてないで、こういう動くものを公開しろよ。  
アホか。

## 動作環境

イニシャルコミット時のものなので、基本的には各処理系の最新バージョンで頼む

- macOS Sierra 10.12.3
- node.js v7.6.0
- yarn v0.20.3

理論的にはLinuxでも動くかも  
Arch Linuxなら将来サポートするかもしれん

## 使い方

0. `git clone https://github.com/mohemohe/api-blueprint-skeleton.git [自分のプロジェクトの名前]`
1. `yarn install`
2. `./src`以下に、API Blueprint形式の`.md`を置く
3. `yarn build`で`./out/api.html`ができる
4. または`yarn watch`でブラウザでLiveReloadできる

## LICENSE

Do What The Fuck You Want To Public License