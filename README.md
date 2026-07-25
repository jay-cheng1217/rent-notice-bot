# rent-notice-bot

591 租屋新物件通知 — 資料抓取端。

- `.github/workflows/fetch.yml` 每 15 分鐘依 `config/filters.json` 抓 591,寫入 `data/listings.json`
- `config/filters.json` 由 Telegram bot(Google Apps Script)自動維護,請勿手改
- `data/listings.json` 為抓取結果快照,由 GAS 端讀取後推播

主專案(治理文件與 GAS 程式)在本機 `F:\rent_notice`。
