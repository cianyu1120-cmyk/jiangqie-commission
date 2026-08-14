# 姜且｜Word Commission

GitHub Pages 版委託作品展示網站。

## 發布網站
1. Repository → Settings → Pages
2. Build and deployment → Source 選 `GitHub Actions`
3. 等待 Actions 完成
4. 網站網址通常是 `https://cianyu1120-cmyk.github.io/jiangqie-commission/`

## 線上新增作品
網站右上角 `＋ MANAGE` → GitHub 同步。

第一次使用需要 GitHub Fine-grained personal access token：
- Resource owner：你的帳號
- Repository access：Only select repositories → `jiangqie-commission`
- Repository permissions → Contents → Read and write

Token 只保存在目前瀏覽器工作階段的 `sessionStorage`，網站不會把 token 寫入作品檔或送到其他服務。儲存作品時，瀏覽器直接呼叫 GitHub Contents API 更新 `works.js`，再由 GitHub Pages 自動部署。

## 作品管理
- 新增、編輯、公開／隱藏、刪除
- 常用標籤按鈕
- R18 閱讀警告
- 搜尋、篩選、排序、分頁
- 首頁作品卡直接開啟閱讀模式
