# Splat Scene Dataset

Splatoon2プレイ中の画像セット。[kamiyaowl/splat-scene-detect](https://github.com/kamiyaowl/splat-scene-detect)で使用するために作りました。

# 種類

現在、17クラス別に画像を蓄積しています。[vgg16-tuning-50epoch.h5](https://github.com/kamiyaowl/splat-scene-detect/blob/e2355e60885e411762e6cdfcf1127877c17faf90/models/vgg16-tuning-50epoch.h5)を使って分類した結果を以下の表に示します。

明らかにデータセットが少ないものは当然ながら全く分類できていないため、本データセットの改善の必要があります。

| label           | Error | Correct | Total   |
|-----------------|-------|------|------|
| battle          | 34    | 9522 | 9556 |
| battle_finish   | 66    | 149  | 215  |
| battle_loby     | 39    | 241  | 280  |
| battle_matching | 3     | 1372 | 1375 |
| battle_result   | 86    | 1179 | 1265 |
| battle_rule     | 39    | 216  | 255  |
| battle_start    | 140   | 161  | 301  |
| loading         | 28    | 523  | 551  |
| menu            | 16    |      | 16   |
| other           | 15    |      | 15   |
| salmon          | 726   | 1936 | 2662 |
| salmon_lobby    | 16    |      | 16   |
| salmon_matching | 17    | 109  | 126  |
| salmon_miss     | 21    |      | 21   |
| salmon_result   | 147   | 9    | 156  |
| salmon_start    | 77    |      | 77   |
| weapon_select   | 6     | 150  | 156  |

# スクリーンショット

# battle
試合中の画像全て

![image-battle](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/battle/WIN_20181022_15_12_23_Pro-00001369.jpg)

# battle_finish
バトル終了直後のKeep Outみたいなテープが出ている画面

![image-battle_finish](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/battle_finish/WIN_20181022_15_12_23_Pro-00000608.jpg)

# battle_loby
ロビー画面すべて

![image-battle_loby](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/battle_loby/WIN_20181022_23_13_19_Pro-00001669.jpg)

# battle_matching
バトル全般でのマッチング中画面

![image-battle_matching](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/battle_matching/WIN_20181022_23_13_19_Pro-00000785.jpg)

# battle_result
試合後のジャッジくん～つづける・やめる選択肢まで

![image-battle_result](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/battle_result/WIN_20181022_15_12_23_Pro-00000615.jpg)
![image-battle_result](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/battle_result/WIN_20181022_15_12_23_Pro-00004938.jpg)
![image-battle_result](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/battle_result/WIN_20181022_15_12_23_Pro-00004940.jpg)

# battle_rule
バトル開始直後のルールが表示されている画面

![image-battle_rule](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/battle_rule/WIN_20181022_15_12_23_Pro-00000351.jpg)

# battle_start
ルール表示後の敵味方の武器表示～操作可能になるまで

![image-battle_start](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/battle_start/WIN_20181022_15_12_23_Pro-00000358.jpg)
![image-battle_start](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/battle_start/WIN_20181022_15_12_23_Pro-00000733.jpg)

# loading
読み込み画面遷移中と読み込み中

![image-loading](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/loading/WIN_20181022_15_12_23_Pro-00000026.jpg)

# menu
Xボタンを押したときの画面

![image-menu](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/menu/WIN_20181022_15_12_23_Pro-00005763.jpg)

# other
データ数が少なすぎたものをぶっこんだ

![image-other](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/other/WIN_20181022_15_12_23_Pro-00008074.jpg)

# salmon

サーモンラン試合中すべて
![image-salmon](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/salmon/WIN_20181022_15_12_23_Pro-00005851.jpg)

# salmon_lobby

サーモンランのロビーすべて
![image-salmon_lobby](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/salmon_lobby/WIN_20181022_15_12_23_Pro-00005782.jpg)

# salmon_matching

サーモンランのマッチング中
![image-salmon_matching](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/salmon_matching/WIN_20181022_15_12_23_Pro-00005789.jpg)

# salmon_miss

サーモンラン失敗時のKeep Outみたいなテープ表示
![image-salmon_miss](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/salmon_miss/WIN_20181022_15_12_23_Pro-00006061.jpg)

# salmon_result

サーモンラン終了後からつづける・やめる選択肢まで
![image-salmon_result](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/salmon_result/WIN_20181022_15_12_23_Pro-00006067.jpg)

# salmon_start

サーモンラン開始時のステージ紹介映像
![image-salmon_start](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/salmon_start/WIN_20181022_15_12_23_Pro-00005820.jpg)

# weapon_select

武器選択画面
![image-weapon_select](https://github.com/kamiyaowl/splat-scene-dataset/raw/master/weapon_select/WIN_20181022_15_12_23_Pro-00000263.jpg)
