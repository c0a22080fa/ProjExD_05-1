# ゲーム のタイトル
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公キャラクターのダニエルをキーボードを使って操作するゲームで、アイテム等を使い敵を倒したりしBESTSCOREを目指すゲーム。

## ゲームの実装
###共通基本機能
* 背景画面スクロールに関するクラス
* 主人公に関するクラス
### 担当追加機能
* 主人公の操作    (平岡:C0A22120)
* score関係+コイン  (高橋:C0B22086)
* 障害物(unnko)+GAMEOVER表示  (島多:C0A22080)
* scoreに応じて出世（パワーアップ　(中條C0B22110)
* 無敵モードの実装  (永田:C0A22112)
### ToDo

### メモ
障害物をできるだけよけて最高スコアを目指すゲーム
spaceキーを押すとジャンプできる（二段まで）
スコアが100ポイントを超えると見た目がムキムキになる
スコアを５０ポイント消費することで無敵モードになれる
