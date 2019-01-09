# mtform-custom-css
MovableType.net フォームCSS用　SCSSファイル

## 前提
### HTML構造
フォームの html は、管理画面への入力によって、既定クラス付きで出力される HTML  
参考：[フォームを独自 CSS でデザインする](https://movabletype.net/support/form/custom-css.html)  
※すでに上記のクラス名から変更が入っているが、当SCSSファイルには反映済

### CSSスタイル
フォームに予め指定されているクラスには、デフォルトでスタイルが設定（app.css）されている  
※MovableType.net内の該当プロジェクト下 app.css 参照

## mtform.scss
フォーム のスタイルを任意で変更するための CSS が「カスタムCSS」
管理画面上で、手書きで書いていたカスタムCSSを、
既定クラスの一覧化、 SCSS ファイルにした。

## 使い方
1. 任意でスタイルを変更して、コンパイル
2. コンパイル後の CSS ファイルを、MovableType.net 管理画面「カスタムCSS」の入力欄にコピペ
3. 保存をクリックして、表示確認
