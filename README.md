# my_scss
Emmetの記法学習ついでに作成したscss（Sass）です。
PRECSSによる記述を行い、短縮系はEmmetです。

PRECSS
https://precss.io/

## 役割
- style.scss ...親ファイル。特に記述は行わない。
  - _xtender.scss ...接頭辞：なし。プレースホルダー用のパーシャルです。あったら面白いかなと。Emmet風です。
  - _var.scss     ...接頭辞：なし。変数用。空です。
  - _mixin.scss   ...接頭辞：なし。@mixin用。空です。
  - _base.scss    ...接頭辞：なし。タグ用。また、汎用的なルールセットも。
  - _helper.scss  ...接頭辞：hp。margin, padding, text-align...等、1プロパティのみのパーシャルです。
  - _generalLayout.scss ...接頭辞：ly。displayやwidth等のごく一般的なレイアウトを予め作成したパーシャルです。
  - _layout.scss  ...接頭辞：ly。配置に関するルールセット用です。
  - _block.scss   ...接頭辞：bl。大きなモジュール用です。
  - _element.scss ...接頭辞：el。小さなモジュール用です。
  - _unique.scss  ...接頭辞：un。1ページのみで使用する、特殊なルールセット用です。
