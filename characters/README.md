# 登場キャラクター

| ID         | 名前       | 役割              | プロフィール                         |
| ---------- | ---------- | ----------------- | ------------------------------------ |
| `shunta`   | Shunta     | 主宰 / エンジニア  | [shunta.md](./shunta.md)             |
| `mika`     | ミカ       | デザイナー        | [mika.md](./mika.md)                 |
| `takuma`   | タクマ     | プロデューサー    | [takuma.md](./takuma.md)             |
| `iris`     | アイリス   | AI アシスタント   | [iris.md](./iris.md)                 |
| `bugmaru`  | バグまる   | バグの化身        | [bugmaru.md](./bugmaru.md)           |

> 各キャラがどういう経緯でデジラボに参画したかは [`../docs/origin.md`](../docs/origin.md) を参照。

## キャラファイルの書き方ルール

- 1 ファイル 1 キャラ
- ファイル名はローマ字小文字（ID と一致させる）
- 先頭に front matter を置く（エピソード側で参照しやすくするため）
- **設定変更は必ず PR にする**（変更履歴を Git に残すのがこのリポジトリの肝）

## キャラ追加時のチェックリスト

- [ ] `characters/<id>.md` を新規作成（テンプレートは既存ファイルを参考に）
- [ ] このページの一覧表に追記
- [ ] [`docs/relationships.md`](../docs/relationships.md) に関係性を追記
- [ ] 立ち絵 / アイコンを `assets/characters/<id>/` に追加
