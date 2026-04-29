# assets/

画像素材の置き場。テキストと違って容量が大きくなるので、
**運用ルールを決めて整理しておくこと** が肝心。

## ディレクトリ構成

```
assets/
├── characters/   ← キャラごとの立ち絵・アイコン・表情差分
│   ├── shunta/
│   ├── iris/
│   ├── mika/
│   ├── takuma/
│   └── bugmaru/
│
├── episodes/     ← 各話のネーム / 完成画像
│   └── NNNN/     ← episodes/NNNN-*.md と対応
│       ├── panel-1.png
│       ├── panel-2.png
│       ├── panel-3.png
│       ├── panel-4.png
│       └── final.png   ← SNS 投稿用 4 コマまとめ
│
└── concept/      ← コンセプトボード・参考画像・ムードボード
```

## ファイル形式

- 公開用: **PNG**（透過 / SNS 投稿用）
- 作業ファイル（`.psd`, `.clip`, `.ai` など）は `.gitignore` 済み
  - 必要なら **Git LFS** か別ストレージで管理することを推奨

## 命名規則

- 小文字 + ハイフン
- 用途を明示: `panel-1.png`, `final.png`, `pose-smile.png` など
- 連番には zero-pad（`panel-01.png` ではなく `panel-1.png` で OK、4 コマなので桁が増えない）
