# Dark Timeline Project Planner v5 JST + Scroll Fix

## 修正内容
- カレンダー曜日ズレをさらに修正
  - `toISOString()` を使わず、ローカル日付 `YYYY-MM-DD` を手動生成
  - `YYYY-MM-DD` を `new Date()` に直接渡さず、年月日を分解してローカル時刻で生成
- 横スクロール対策を強化
  - html/body/#app/main/panel/form/card/item/nav に overflow-x 対策
  - `min-width:0`、`max-width:100%`、`overflow-wrap:anywhere` を追加
  - ボタン・入力欄・フォーム・チェックボックス列のはみ出しを抑制
- 曜日タスクの終了時刻対応を維持

## GitHub Pages
ZIPを解凍し、中身をリポジトリ直下に上書きアップロードしてください。
確認URL例: `https://seiya-star.github.io/-/?v=v5`
