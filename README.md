# 鷺江國中《書蟲報》網站

這是一個可直接由 GitHub Pages 發布的靜態網站，首頁為 `index.html`，第 72 期全文頁為 `issue72.html`。

## 發布到 GitHub Pages

1. 在 GitHub 建立一個新的 repository（例如 `bookworm-site`）。
2. 將本資料夾內的檔案與目錄上傳到 repository 根目錄，確認 `index.html` 位於最外層。
3. 開啟 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選 **Deploy from a branch**，分支選 `main`、資料夾選 `/(root)`，按 **Save**。
5. 等待 Pages 完成部署；網址會是 `https://<GitHub 使用者名稱>.github.io/bookworm-site/`。請以 Pages 設定頁顯示的網址為準。

本網站使用相對連結 `issue72.html`，放在 repository 根目錄即可正確開啟全文頁。
