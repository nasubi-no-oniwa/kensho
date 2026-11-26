# 懸賞金🍆（kensho）のランキング

- 遊ぶページ：https://nasubi-no-oniwa.com/kensho/ （本体は nasubi-site リポジトリの kensho/）
- ここには、ランキング（Firebase の otokonoji の kensho/）のルールだけを置く
- `database.rules.kensho.json` を上げると、GitHub の上で自動で otokonoji に反映する（ほかのゲームのルールはそのまま残す）
- 必要な鍵：`OTOKONOJI_SERVICE_ACCOUNT`（onikiri と同じもの）

## 記録の場所
- `kensho/n/名前の番号`：全期間（名前1つにつき1件）
- `kensho/t/日付/名前の番号`：今日発行された分
- n：名前、b：懸賞金（🍆）、i：異名。懸賞金は名前で決まるので、同じ名前の記録は同じ額でしか書きかえられない
