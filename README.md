# 股票交割款入門（demo）

給第一次接觸證券交割業務的人看的單頁說明：從「買一檔台股」開始，看券商、交割銀行和核心系統怎麼分工，以及一扣、二扣、大借大貸是什麼。

內容只保留業務流程層級的說明，系統名稱都改成通用說法，不含系統實作細節。

## 頁面

| 檔案 | 內容 |
|---|---|
| `index.html` | 台股一般交割：證券清算系統是什麼、角色、T／T+1／T+2 流程、錢怎麼流、一扣與二扣。其他業務頁的基礎，建議先讀 |
| `regular.html` | 定期定額：圈存、解圈、扣款解圈，兩種券商節奏 |
| `ipo.html` | 承銷：申購、申退、競價拍賣，截止日與截止次日、扣帳順序、大借大貸只算成功額 |
| `sub-brokerage.html` | 複委託：下單當下即時圈存、逾時與處理中的判讀、台幣與外幣差別、授權 |

共用樣式在 `style.css`。

## 本機預覽

直接用瀏覽器開 `index.html` 就可以，不需要建置。

## 用 GitHub Pages 部署

1. 到 repo 的 **Settings → Pages**。
2. **Source** 選 **Deploy from a branch**。
3. **Branch** 選 `main`，資料夾選 `/ (root)`，按 **Save**。
4. 等一兩分鐘，網址會是 `https://mjjackson0414.github.io/stock_knowhow_demo/`。

repo 根目錄有 `.nojekyll`，GitHub Pages 會直接提供靜態檔案，不經過 Jekyll。
