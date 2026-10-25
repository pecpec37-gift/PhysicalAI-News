# 朝5分で読むフィジカルAI News

ロボット・人型ロボット・自動運転など、現実の世界で動くAI（フィジカルAI）の最新情報と企業の動きを、毎朝5分で読める日本語ダイジェストにまとめるスマホ向けアプリです。TomTom TOWNS の一員です。

- 公開URL: https://pecpec37-gift.github.io/PhysicalAI-News/
- 毎朝 6:00ごろ（日本時間）、Claude の定期タスクが新しい号を追加します。

## データの置き場所

- `data/index.json` … 号の一覧（新しい順、最大30号）
- `data/editions/YYYY-MM-DD.json` … 各号の本文

`items[].cat` は `humanoid` `robot` `mobility` `model` `business` `japan`、`items[].stage` は `research`（研究段階）`pilot`（実証段階）`deployed`（実用段階）のいずれかです。
