# ROUND1ぼうけんワールド

ROUND1を舞台にした「ぼうけんワールド」ゲームの開発リポジトリです。

## フォルダ構成

```text
.
├─ worlds/
│  ├─ world1/
│  ├─ world2/
│  ├─ world3/
│  ├─ world4/
│  └─ world5/
└─ assets/
   ├─ images/
   ├─ audio/
   ├─ fonts/
   ├─ data/
   └─ shared/
```

- `worlds/world1`〜`worlds/world5`: 各ワールド固有の企画、ステージ、コード、データ
- `assets/images`: 共通の画像、背景、UI素材
- `assets/audio`: 共通のBGM、効果音
- `assets/fonts`: 共通フォント
- `assets/data`: 複数ワールドで使う設定・データ
- `assets/shared`: 上記に当てはまらない共通素材

## 開発の進め方

1. 各ワールドの内容は対応する `worlds/worldN` にまとめます。
2. 複数ワールドで再利用する素材は `assets` に置きます。
3. 大きな変更を始める前に、対象ワールドのREADMEへ目的や仕様を追記します。
4. ファイル名は、できるだけ半角英数字とハイフンを使います。

## 現在の状態

初期フォルダ構成を作成した段階です。各ワールドのREADMEを企画・仕様の入口として育てていきます。
