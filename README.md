# grammar-native

JLPT の文法を、意味が近いもの同士でグループにして覚えるための Anki デッキです。「不得不」のグループ、「忍不住」のグループ、みたいに、似た文法を並べて違いを見ながら覚える作りにしています。

カードの見た目は native-nihongo と同じスタイル。関連文法は［関］にグループ表示され、紛らわしいペアには違いのメモ付き。各カードにはレベル（N1〜N3）、語域（話＝口語常用／書＝書面）、常用度（★1〜3）のタグが付いています。音声は自動生成されます。

## 下载

固定链接（永远指向最新版）：https://github.com/yydlun/grammar-native/releases/latest/download/grammar-native.apkg

牌组结构（父牌组「文法（native 样式）」，N2 在最上）：
- `1_N2`：118 个文法点
- `2_N3`：62 个文法点
- `3_N1`：63 个文法点

共 243 个文法点，按 10 个功能组编排（不得不／忍不住／逆接／条件／推量／様態／変化／限定／基準／句型），同组同级别的文法互相链接成组。

## 构建

`python3 build.py`（需要 genanki、janome）→ `dist/grammar-native.apkg`。数据在 `data/cards.json`，由 `tools/gen_data.py`（＋ `tools/rows_extra.py`）生成。
