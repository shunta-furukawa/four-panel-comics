# エピソード索引

各話の脚本・ネーム・公開状況を管理します。

## 命名ルール

```
episodes/NNNN-slug.md
```

- `NNNN`: 4 桁の通し番号（例: `0001`, `0042`）
- `slug`: 内容を表す短い英小文字スラッグ（例: `hello-degilab`）

## status の意味

| status      | 意味                                       |
| ----------- | ------------------------------------------ |
| `draft`     | プロット段階。セリフ未確定                 |
| `inking`    | ネーム / 下書き作業中                      |
| `ready`     | 公開準備完了。投稿待ち                     |
| `published` | 公開済                                     |

## フォーマット

**1 話 = 4 シート × 4 コマ = 全 16 コマ**。X 投稿時はシート画像を 4 枚添付する。
詳しいリズム設計は [`../design-system/rhythm.md`](../design-system/rhythm.md) を参照。

## 一覧

| 番号   | タイトル                            | status | tags                       |
| ------ | ----------------------------------- | ------ | -------------------------- |
| 0001   | AI ゲートウェイ、いずれ来る？        | draft  | AI / アーキテクチャ / 思考実験 |
| 0002   | AI に強い会社の正体                  | draft  | AI / 組織論 / 思考実験       |

## 新規エピソードの作り方

1. `_template.md` をコピー
   ```bash
   cp episodes/_template.md episodes/0001-your-slug.md
   ```
2. front matter を埋める
3. 4 シート × 4 コマ の全 16 コマを埋める
4. ネームを `assets/episodes/NNNN/sheet-1.png 〜 sheet-4.png` に配置してリンク
5. PR を立ててセルフレビュー
