# 粉體混合比例敏感度分析 PWA

水泥／爐石粉二元系統粉體混合比例敏感度分析工具

## 部署至 GitHub Pages

1. 建立新 Repository（建議命名：`sensitivity-analysis`）
2. 將本資料夾所有檔案上傳至 `main` 分支根目錄
3. 進入 Settings → Pages → Source 選 `main` 分支 `/root`
4. 儲存後約 1～2 分鐘即可訪問

## 檔案說明

| 檔案 | 說明 |
|------|------|
| `index.html` | 主應用程式（含完整 CSS / JS） |
| `manifest.json` | PWA 安裝資訊 |
| `sw.js` | Service Worker（離線快取） |
| `icon.png` | App 圖示（原圖，根目錄） |
| `icon-192.png` | 192×192 圖示 |
| `icon-512.png` | 512×512 圖示 |
| `.nojekyll` | 停用 Jekyll，確保 GitHub Pages 正常運作 |

## PWA 安裝

- **桌面 Chrome**：網址列右側「安裝」按鈕
- **Android Chrome**：瀏覽器選單 → 「新增到主畫面」
- **iOS Safari**：分享 → 「加入主畫面」
