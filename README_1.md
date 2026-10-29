# 計時器工具箱

單一檔案（`index.html`）的網頁計時器合集，免安裝、免伺服器，可用 GitHub Pages 架設並嵌入 Google 協作平台。

## 內含計時器

| 網址後綴 | 計時器 | 重點 |
|---|---|---|
| `#gym` | 重訓計時器 | 總時間正計時、每組訓練計時、組間休息倒數（剩 3 秒嗶聲）、自動紀錄每組、可複製紀錄 |
| `#interval` | 間歇訓練 HIIT | Tabata 等運動／休息循環，內建常用組合 |
| `#pomodoro` | 番茄鐘 | 專注／短休息／長休息自動循環，統計今日番茄數 |
| `#teach` | 試教計時器 | 設定總時間與教學步驟分配，顯示目前步驟、剩餘時間、是否超時，結束後列出預計 vs 實際 |
| `#countdown` | 倒數計時 | 課堂活動通用倒數，可加減 1 分 |
| `#speech` | 發表計時 | 綠→黃→紅燈號，時間快到一聲鈴、時間到兩聲鈴 |
| `#exam` | 考試時鐘 | 投影用大時鐘，顯示科目、起訖、剩餘時間與提醒 |
| `#stopwatch` | 碼錶 | 0.01 秒精度、分圈紀錄 |

快捷鍵：空白鍵 開始／暫停、F 全螢幕、試教時 ← → 切換步驟。
設定、方案與紀錄存在使用者瀏覽器的 localStorage，不會上傳。

## 部署到 GitHub Pages

1. 在 GitHub 新增 repository（例如 `YuSiangTimer`，設為 Public）。
2. 上傳 `index.html` 與本 `README.md` 到 main 分支根目錄。
3. Settings → Pages → Source 選「Deploy from a branch」，Branch 選 `main` / `(root)`，儲存。
4. 約 1 分鐘後網址為 `https://<帳號>.github.io/YuSiangTimer/`。

## 嵌入 Google 協作平台

插入 → 嵌入 → 「依網址」貼上網址（可加 `#teach` 等後綴直接開啟指定計時器），再把嵌入框拉高。
嵌入框內瀏覽器可能不允許全螢幕，頁面右上角會出現「↗」可改在新分頁開啟（投影時建議用新分頁）。
