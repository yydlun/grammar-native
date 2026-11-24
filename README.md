# grammar-native

N2 の文法を、意味が近いもの同士でグループにして覚えるための Anki デッキです。「不得不」のグループ、「忍不住」のグループ、みたいに、似た文法を並べて違いを見ながら覚える作りにしています。

カードの見た目は native-nihongo と同じスタイル。関連文法は［関］にグループ表示され、紛らわしいペアには違いのメモ付き。音声は自動生成されます。

## 下载

固定链接（永远指向最新版）：https://github.com/yydlun/grammar-native/releases/latest/download/grammar-native.apkg

牌组名：文法（native 样式）::N2，共 60 个高频文法点，按 10 个功能组编排（不得不／忍不住／逆接／条件／推量／様態／変化／限定／基準／句型）。

## 构建

`python3 build.py`（需要 genanki、janome）→ `dist/grammar-native.apkg`。数据在 `data/cards.json`，由 `tools/gen_data.py` 生成。
