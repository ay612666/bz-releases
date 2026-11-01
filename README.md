# 玄奧八字 Android 發布

此倉庫只保存公開安裝包、版本說明和 App 讀取的 `update-manifest.json`，不包含應用原始碼或客戶資料。

發布順序：

1. 使用固定簽章建置 APK。
2. 建立 GitHub Release 並上傳 APK。
3. 以 APK 實際大小與 SHA-256 生成更新清單。
4. 最後更新 `update-manifest.json`。

App 只會在使用者於設定頁手動檢查時讀取清單，不做背景自動下載或靜默安裝。
XuanAo BaZi Android release artifacts and update manifest
