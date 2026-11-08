# 會計遊戲 Accounting Games

靜態網站，部署於 GitHub Pages。 / Static site deployed on GitHub Pages.

```
index.html     首頁 Landing page
game1/         遊戲一 會計分錄挑戰 Journal Entry Challenge (index.html)
game2/         遊戲二 會計科目大分類挑戰 Account Classification (index.html)
.nojekyll      關閉 Jekyll 處理 Disable Jekyll
```

## 部署 Deploy
1. 在 GitHub 建立新 repository（例如 `accounting-games`，Public）。
2. 上傳本資料夾所有內容（含 `.nojekyll`）。
3. Settings → Pages → Source 選 `Deploy from a branch`，Branch 選 `main` / `(root)`，Save。
4. 約 1–2 分鐘後網址為 `https://<你的帳號>.github.io/accounting-games/`。

## 注意 Notes
- GitHub Pages 僅支援靜態檔案（HTML/CSS/JS）；若遊戲需要 PHP、資料庫或後端 API（如排行榜、成績記錄），無法直接在 Pages 執行。
- 檔案內連結請用相對路徑（`./img/a.png`），避免以 `/` 開頭。
