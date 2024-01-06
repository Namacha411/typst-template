# Typst-template

[Typst](https://github.com/typst/typst)で日本語のレポートを書く時用のテンプレート。フォント設定は游明朝。

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
