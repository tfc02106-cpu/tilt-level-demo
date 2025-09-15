
# 手機水平角度 Demo（GitHub Pages 版）

這個資料夾只要丟到 GitHub Pages，就能在 HTTPS 下讀取 iPhone/iPad 的裝置方向（beta/gamma）並顯示簡易水平儀。

## 使用方式
1. 建一個公開 repo，例如 `tilt-level-demo`。
2. 上傳 `index.html` 到 repo 根目錄。
3. 打開 GitHub → **Settings → Pages**，Source 選擇 **Deploy from a branch**，Branch 選擇 `main` / `/ (root)`。
4. 儲存後，稍等即可得到網址：`https://<你的帳號>.github.io/tilt-level-demo/`。GitHub Pages 會自動配置 HTTPS。
5. iPhone 上開啟網址，點按「請求感測權限並開始」，即可看到水平角與泡泡。

## 常見問題
- iOS 需要使用者手勢授權感測器；請點按按鈕。
- 若沒有顯示角度，請確認：Safari 設定中「動作與方向取用」已允許、網址是 `https://`、或在 `http://localhost` 測試。
- 若頁面 404，確定 Pages 的 Branch/資料夾設定在 **root**，或把檔名放在子資料夾時路徑要正確。

