# Typst-template

日本語でレポートを書く時用のテンプレート

[template.typ](template.typ)をインポートし、
```typ
#import "template.typ": *

#show: project.with(
  title: "タイトル",
  authors: (
    "山田 太郎",
  ),
  date: "2024/01/06"
)
```
のように使う

このフォルダをダウンロードして`main.typ`を書き換えて使うのが楽

## 例

- [サンプルコード](main.typ)
- [出力例](main.pdf)
