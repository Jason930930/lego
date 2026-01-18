# Anniversary LEGO Project

這是一個偽裝成 LEGO 說明書頁面的週年紀念驚喜網頁。

## 如何使用

**git**
git status
git add .
git commit -m "write your message"
git push origin main

1. **準備影片**：
   - 準備好您的週年紀念影片。
   - 將影片檔名命名為 `video.mp4`。
   - 將該 `video.mp4` 檔案放入此專案的 `lego` 資料夾中（與 `index.html` 同一層）。

2. **自定義內容**（可選）：
   - 打開 `index.html`。
   - 搜尋 "Set 5201314" 或 "Our Anniversary Special Edition" 文字，將其修改為您想要的日期或標題。
   - 修改側邊欄的詳細資訊（年份、零件數等）。

3. **測試**：
   - 在您的電腦上直接雙擊打開 `index.html` 看看效果。

## 如何發布到 GitHub Pages

1. **上傳影片**：
   - 確保 `video.mp4` 已經在資料夾中。
   - 將所有更改（包含新加入的影片）Commit 並 Push 到 GitHub。
     ```bash
     git add .
     git commit -m "Add anniversary video and site design"
     git push
     ```
   
2. **開啟 Pages**：
   - 到 GitHub 儲存庫頁面。
   - 點選 **Settings** (設定) > **Pages** (左側選單)。
   - 在 **Build and deployment** 下的 **Branch** 選擇 `main` (或 `master`) 並儲存。
   - 等待幾分鐘，網頁就會生成並提供網址。

3. **分享**：
   - 將網址傳給女朋友，告訴她這是樂高的最新說明書頁面！

## 注意事項
- 影片檔案不要太大，否則 GitHub Pages 載入會很慢 (建議 50MB 以內，或使用 Handbrake 壓縮)。
- 支援手機與電腦觀看。