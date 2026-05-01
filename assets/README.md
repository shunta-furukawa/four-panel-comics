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
│       ├── sheet-1.png   ← シート 1（起）
│       ├── sheet-2.png   ← シート 2（承）
│       ├── sheet-3.png   ← シート 3（転）
│       ├── sheet-4.png   ← シート 4（結）
│       └── final.png     ← 任意。全シート結合版
│
└── concept/      ← コンセプトボード・参考画像・ムードボード
```

> 1 話 = 4 シート × 4 コマ = 全 16 コマ。
> X 投稿時は `sheet-1.png` 〜 `sheet-4.png` を 4 枚添付する。

## ファイル形式

- 公開用: **PNG**（透過 / SNS 投稿用）
- 作業ファイル（`.psd`, `.clip`, `.ai` など）は `.gitignore` 済み
  - 必要なら **Git LFS** か別ストレージで管理することを推奨

## 命名規則

- 小文字 + ハイフン
- 用途を明示: `sheet-1.png`, `final.png`, `pose-smile.png` など
- 連番は zero-pad なし（`sheet-1.png` で OK）
