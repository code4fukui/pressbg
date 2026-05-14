# pressbg

**Code for Japan** x **Code for FUKUI** によるプロジェクトです。

ロゴが並ぶタイル状のグリッドをリアルタイムで調整・生成できる、動的な背景ジェネレーターです。オンラインでのプレゼンテーション、カンファレンス、イベント時の背景（バックドロップ）としての使用に最適です。

## デモ

**ライブデモ:** [**https://code4fukui.github.io/pressbg/**](https://code4fukui.github.io/pressbg/)

## 機能

* **交互に並ぶロゴグリッド:** Code for JapanとCode for FUKUIのロゴを、市松模様（チェッカーボード）状にフルスクリーンで表示します。
* **リアルタイムな密度調整:** キーボード操作で、グリッド内のタイル数を即座に調整できます。
* **フルスクリーンモード:** 画面の任意の場所をクリックすると、フルスクリーン表示を切り替えることができます。
* **ゼロ依存関係:** ビルド不要で、単一のHTMLファイルからブラウザ上で直接動作します。

## 操作方法

* **`↑` 上矢印キー**: グリッドの密度を上げます（最大50x50）。
* **`↓` 下矢印キー**: グリッドの密度を下げます（最小2x2）。
* **マウスクリック**: フルスクリーンモードを切り替えます。

## 使い方

ローカルで実行するには、リポジトリをクローンし、最新のWebブラウザで `index.html` を開いてください。

```bash
git clone https://github.com/code4fukui/pressbg.git
cd pressbg
# ブラウザで index.html を開く
```

## 実装

このプロジェクトは、Vanilla JavaScript（ES Modules）とブラウザのFullscreen APIを使用した単一の `index.html` ファイルで構成されています。軽量なDOM操作のために [stdom.js](https://js.sabae.cc/stdom.js) に依存しており、これは `js.sabae.cc` のCDNから読み込まれます。

## ライセンス

[LICENSE](LICENSE) を参照してください。
