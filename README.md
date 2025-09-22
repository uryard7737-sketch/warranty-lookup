# 亞德醫材 保固查詢 DEMO（RWD＋展開／CSV 版）

本版本會在載入時讀取 `warranty_records_sample.csv`，並支援欄位 **WarrantyText**（每個商品可填不同條款）。

## CSV 欄位（至少）
RecordID, CustomerName, PhoneLast4, InvoiceNo, ProductName, Brand, Model, SerialNo, PurchaseDate, WarrantyMonths, Shop, Notes, ImageURL, WarrantyUntil, LookupKey, WarrantyText

- `LookupKey`：建議用「手機後四碼 + 發票後四碼」（例如 1688 + 4485 → 16884485）
- `WarrantyText`：自由填寫條款，支援換行（在 CSV 用引號包起來即可）

## 如何部署
1. 將 `index.html` 與 `warranty_records_sample.csv` 放在 GitHub repo **root**。
2. Settings → Pages → Source 設 `main / (root)`。
3. 完成後即可由 Pages 直接載入 CSV。

## 內嵌到 Cyberbiz
```html
<iframe src="https://你的帳號.github.io/你的repo名稱/" style="width:100%; height:1100px; border:none;"></iframe>
```

## 常見問題
- 若頁面顯示「資料載入失敗」，請確認 CSV 檔名、路徑（要放 root）、與欄位名稱拼字。

