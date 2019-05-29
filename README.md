# reset_css
＊,＊ :before, *:after {
box-sizing: border-box;
}
を追記

## 主な仕様
- 全要素border-boxがデフォルト(追記)
    →width,heightを0にしてもpaddingだけ残るようになる点だけ気をつけてください
- aタグ
 - font-color:inherit
 - :visited{color:inherit}


後は
- padding,marginを0に
- font-size 100%
- list-style none
etc...
だったりと一般的なreset.cssと変わりないと思われます。
注意事項等発見次第報告します。
他、追記事項が出てきたら都度更新していければと思います。

元サイト
http://html5.jp/html5doctor/html-5-reset-stylesheet.html

元サイトはこれを改良
https://meyerweb.com/eric/tools/css/reset/
