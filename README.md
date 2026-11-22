# Antigravity Swarm 指南

這份繁體中文指南用一次網站改版示範如何在 Google Antigravity 的 Swarm 側欄追蹤分工與交接。讀者可以查看 Board 貼文、Members 狀態和 Overview 概覽，試用成員狀態示範，並了解圖形重播與看板資料來源。

[閱讀線上指南](https://antigravity-swarm-guide.gh.miniasp.com/)

## 本機預覽

在儲存庫根目錄執行：

```sh
python3 -m http.server 8000
```

開啟 [http://localhost:8000/](http://localhost:8000/)。可點選目錄跳到各節、切換成員狀態，以及展開原始碼地圖來檢查互動。頁面的範例資料僅供說明，程式碼位置可能隨 Antigravity 版本變動。

## 檔案與部署

- `index.html` 包含指南、樣式與示範程式。
- `assets/` 包含網站圖示和社群分享預覽圖。
- `CNAME` 記錄 GitHub Pages 的自訂網域。GitHub Pages 從 `main` 分支的根目錄部署。

© 2026 [Will 保哥](https://www.facebook.com/will.fans/)。原創指南及網站程式碼依 [MIT 授權](LICENSE) 提供。本指南以 [Google Antigravity](https://antigravity.google/) 內建的 Swarm 外掛為參考。Antigravity 名稱及 Swarm 標誌歸各自權利人所有。
