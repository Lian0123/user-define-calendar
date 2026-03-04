# 自定義年曆系統 (React 靜態範例)

簡介：
- 使用 React 與純前端程式碼實作的自定義年曆系統範例，允許自訂年份、每年月份數、每月天數、每天小時數、每小時分鐘數、日出日落時間以及每年的節日/事件。

如何使用：
1. 直接以瀏覽器開啟 [index.html](index.html)（可使用 file:// 打開）。
	- 若瀏覽器因安全政策阻擋外部資源，可改用內建 HTTP 伺服器（下方示例）。
2. 在介面上設置年、月份數、每月天數等內容。
3. 點「產生年曆預覽」可在下方看到預覽；點「匯出 JSON」或「匯出 JS」下載檔案。

檔案：
- index.html — 主頁面（載入 React 與 Babel CDN）
- src/app.js — React 應用程式
- styles.css — 樣式

注意：此範例使用 Babel 在瀏覽器轉譯 JSX（開發便利），且已將 `src/app.js` 內嵌於 `index.html` 以保證 file:// 可直接開啟。若要用於正式專案建議改用 bundler（例如 Vite / Webpack）進行打包與優化。

若想用本地簡易伺服器（替代 file://）：
```bash
# Python 3
python3 -m http.server 8000
# 然後在瀏覽器開啟 http://localhost:8000/
```

