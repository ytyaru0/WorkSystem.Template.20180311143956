# Markdownの不足

MarkdownはHTMLと比べて編集が楽。

だが、足りない機能も多い。

* `<table>`の縦結合
* `<kbd>`の入力 [markdown-it-kbd](https://www.npmjs.com/package/markdown-it-kbd)
* `<ruby>`の入力
* `<h1>`にリンクを貼れない（日本語テキストのまま）
* `<table>`で縦方向に`<th>`があるテーブルが作れない（KeyValue）
* `<table>`で縦方向にも`<th>`があるテーブルが作れない（Matrix）
* グラフが書けない

https://qiita.com/ygkn/items/0b485f6aedd15eadec33

[markdown-it-plugin](https://www.npmjs.com/browse/keyword/markdown-it-plugin)

あと、ファイルパス、ファイル名、クラス名、オブジェクト名を示すときもある。

種類|HTMLタグ
----|--------
手順書|`<kbd>`, ファイルパス
小説|`<ruby>`

これらを、見やすいテキストのまま、簡単に入力できるような構文にしたい。

種類|HTMLタグ
----|--------
手順書|`<kbd>`|`[Ctrl Shift Alt C]`, `[" + y]`, `enter, space esc, f1, fn, ins, del pgup, pgdn, prtsc, sysrq, numlk, scrlk, pausebreak,`任意のテキスト可。スペース区切り
小説|`<ruby>`|`{漢字|かん|じ}`



さらにいえば、グラフが書けない。

https://gist.github.com/hashrock/208b84c61558663e40bb
https://github.com/knsv/mermaid


