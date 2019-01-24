# mtform-custom-css
[MovableType.net](https://movabletype.net/) フォームCSS用　SCSSファイル

## 前提
### HTML構造
フォームの html は、管理画面上での入力によって、既定クラス付きで自動出力される HTML
参考：[フォームを独自 CSS でデザインする](https://movabletype.net/support/form/custom-css.html)
※すでに上記のクラス名から変更が入っているが、当SCSSファイルには反映済

### CSSスタイル
フォームに予め指定されているクラスには、デフォルトでスタイルが設定（app.css）されている。

## mtform.scss
フォームのスタイルを任意で変更するための CSS が「カスタムCSS」
管理画面上で手書きしていたカスタムCSSを、既定クラスを一覧にし、 SCSS ファイル化。
MovableType.net 内の該当プロジェクト下 app.css の設定を上書き変更する

## 使い方
1. 任意でスタイルを変更し、コンパイル
2. コンパイル後の CSS ファイルを、MovableType.net 管理画面「カスタムCSS」の入力欄にコピペ
3. 保存をクリックして、表示確認
