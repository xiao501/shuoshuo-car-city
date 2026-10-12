# 碩碩車車城

給 1.5～3 歲小孩玩的車車遊戲，可離線使用的網頁 App（PWA）。

## 檔案
- index.html：遊戲本體
- manifest.webmanifest：App 名稱、圖示設定
- sw.js：離線快取
- icons/：主畫面圖示

## 更新遊戲
1. 換掉 index.html
2. 把 sw.js 第一行的 VERSION 加 1（例如 'v1' → 'v2'）
3. 上傳到 GitHub，手機上的 App 要有網路時開兩次才會換成新版
