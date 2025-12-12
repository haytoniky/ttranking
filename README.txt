GitHub Pages 部署指南：

1. 將本壓縮包解壓縮後，進入資料夾。
2. 將所有檔案上傳到你的 GitHub Repository。
3. 確保 index.html 在根目錄。
4. 在 Repository Settings → Pages 啟用 GitHub Pages。
5. 將 CNAME 檔案內容設定為你的自訂網域（目前範例：www.mywebsite.com）。
6. 在網域註冊商設定 DNS：
   - CNAME 記錄指向 username.github.io
   - A 記錄指向 GitHub Pages IP：185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
7. 啟用 Enforce HTTPS。

完成後，你的網站將可透過自訂網域訪問！
