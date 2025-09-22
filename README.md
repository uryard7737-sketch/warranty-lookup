# Warranty Lookup DEMO

這是一個簡單的「數位保固查詢系統」範例，可直接部署到 GitHub Pages。

## 部署步驟
1. 到 GitHub 建立一個新的 repo（例如 `warranty-lookup`）。
2. 上傳 `index.html` 與 `warranty_records_sample.csv`。
3. 進入 repo → Settings → Pages → Source → 選 `main branch / root` → Save。
4. 幾秒後你會得到一個網址，例如：
   ```
   https://yourname.github.io/warranty-lookup/
   ```

## 內嵌到 Cyberbiz
在 Cyberbiz 自訂 HTML 中放：
```html
<iframe src="https://yourname.github.io/warranty-lookup/"
        style="width:100%; height:900px; border:none;"></iframe>
```
即可在你的官網顯示查詢系統。
