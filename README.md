# js-tutorial

[JavaScript Stack from Scratch](https://github.com/verekia/js-stack-from-scratch)

をやっていって、簡単なアプリを作成

## メモ

* Compat  
  ブラウザごとにサポートしている JS の記述方法をチェックできるツール
* Husky  
  簡単に、タスクを Git にフックできるようにするツール
* Nodemon  
  ファイルを変更した時に、自動的に server をリスタートさせるツール
* PM2
  Node.js のデーモン化ツール、Production でよく使われる
* Webpack 設定について

  * entry : 起点のファイル, App.js とか index.js とかを指定する
  * output
    * path : 出力先のパス(/dist とかが多い)
    * filename : ファイルの名前(bundle.js とか)
    * publicPath : Production 時の URL や Path を貼る
  * modules
    * test : ファイルマッチのルール
    * [ローダチェーンの話](https://qiita.com/chuck0523/items/caacbf4137642cb175ec#5-%E3%83%AD%E3%83%BC%E3%83%80%E3%83%BC%E3%81%A8%E3%83%AD%E3%83%BC%E3%83%80%E3%83%BC%E3%83%81%E3%82%A7%E3%83%BC%E3%83%B3)
    * [.babelrc の話](https://qiita.com/chuck0523/items/caacbf4137642cb175ec#7-babelrc%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB)
  * dev-tool : デバッグのための SourceMap の出力を設定 .. [詳細](http://dackdive.hateblo.jp/entry/2016/04/13/123000)
  * resolve
    * extensions : 読み込む際に拡張子を省略できるようにする設定
    * alias : ファイル単位で alias をはることができる
