
# GitHub Pages Reports Scaffold

把你的 HTML 報告放到 `reports/`，推到 GitHub，Pages 就會自動產生公開連結：
`https://<user>.github.io/<repo>/reports/<filename>.html`

## 一次性設定
1. 建一個 **Public** repo，推上這些檔案（或直接上傳）。
2. 到 **Settings → Pages** 啟用 GitHub Pages：Source 選 `main`，Folder 選 `/ (root)`。
3. 等 1 分鐘，首頁（目錄）：`https://<user>.github.io/<repo>/`。

## 之後每次更新
- 把新檔放進 `reports/`，檔名建議用 `kebab-case`（別用空白）。
- `git add . && git commit -m "add: chapter 03" && git push`
- 直接分享連結：`https://<user>.github.io/<repo>/reports/<filename>.html`

## Notion 嵌入
在 Notion 輸入 `/embed`，貼上任一報告網址即可。
