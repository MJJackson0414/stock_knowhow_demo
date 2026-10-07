# 股票交割款入門（demo）

給第一次接觸證券交割業務的人看的單頁說明：從「買一檔台股」開始，看券商、交割銀行和核心系統怎麼分工，以及一扣、二扣、大借大貸是什麼。

內容只保留業務流程層級的說明，系統名稱都改成通用說法，不含系統實作細節。

## 內容

1. 一句話說明證券清算系統是什麼
2. 角色
3. 買台股的 T／T+1／T+2 流程（圖 1）
4. 買進與賣出時錢怎麼流（圖 2）
5. 一扣與二扣，含 T+2 當天時間軸（圖 3）
6. 其他業務：定期定額、承銷、複委託、證交所出入金

## 本機預覽

直接用瀏覽器開 `index.html` 就可以，不需要建置。

## 用 GitHub Pages 部署

1. 到 repo 的 **Settings → Pages**。
2. **Source** 選 **Deploy from a branch**。
3. **Branch** 選 `main`，資料夾選 `/ (root)`，按 **Save**。
4. 等一兩分鐘，網址會是 `https://mjjackson0414.github.io/stock_knowhow_demo/`。

repo 根目錄有 `.nojekyll`，GitHub Pages 會直接提供靜態檔案，不經過 Jekyll。
