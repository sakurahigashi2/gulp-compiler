# postCSS,JSコンパイラタスク

## 環境準備
#### 1. `yarn` または `npm` をグローバルにインストール
```
$  brew install yarn
```
または `npm` をインストール  
バージョン管理ツール込みでのインストールは[こちら](https://qiita.com/taketakekaho/items/dd08cf01b4fe86b2e218)を参照

#### 2.パッケージ群をインストール
```
$ yarn install
```
または
```
$ npm install
```

## 使い方
postCSS,JSを変換
```
$ gulp allSetAssets
```
ファイルの変更監視実
```
$ gulp watch
```

## 備考
デフォルトの設定では `frontend/css` `frontend/js` 直下のファイルを `assets/css` `assets/js` 直下に出力する
