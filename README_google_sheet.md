# 亞德醫材 保固查詢 DEMO（Google Sheet 版）

## 使用方式
1. 本專案不需要本地 CSV，資料來源直接來自 Google 試算表。  
2. 目前設定連結至：  
   https://docs.google.com/spreadsheets/d/1KN0rAcwCFqLCUbQrVlEh8GdgiOlXa1nvA2oAq3Ex2Gk/gviz/tq?tqx=out:csv&sheet=產品保固紀錄  

## 更新保固資料
- 只要在 Google 試算表 **「產品保固紀錄」** 分頁編輯資料 → 前台頁面會自動更新。  
- 建議欄位：  
  - RecordID  
  - CustomerName  
  - PhoneLast4  
  - InvoiceNo  
  - ProductName  
  - Brand  
  - Model  
  - SerialNo  
  - PurchaseDate  
  - WarrantyMonths  
  - Shop  
  - Notes  
  - ImageURL  
  - WarrantyUntil  
  - LookupKey (手機後四碼 + 發票後四碼)  
  - WarrantyText (保固條款)  

## 內嵌到 Cyberbiz
```html
<iframe src="https://你的帳號.github.io/你的repo名稱/" 
        style="width:100%; height:1100px; border:none;"></iframe>
```

## 注意事項
- 試算表必須設定為「任何有連結的人可檢視」。  
- 如果分頁名稱（目前是「產品保固紀錄」）有更動，需同步修改 index.html 裡的 `CSV_PATH` 連結。  
