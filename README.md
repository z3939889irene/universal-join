# Universal Join（最終版，支援 ?k= 關鍵字 + 桌機顯示帶關鍵字 QR）

- LIFF：2008415501-DxLWdBGd
- OA：@camel-live
- 預設關鍵字：line會員限定立刻解鎖優惠

## 用法（同一入口）
- 加上 `?k=與小駱駝一起領好禮`（官網）
- `?k=line會員限定立刻解鎖優惠`（FB）
- `?k=會員限定驚喜`（IG）
- `?k=YT觀眾專屬好禮`（YT）
- `?k=TikTok粉絲專屬福利`（TikTok）
- `?k=新好友領取折扣金`（官網廣告）
- `?k=新加入好友領取折扣金`（FB&IG 廣告）

## 佈署
1) 建 GitHub Repo（建議：`universal-join`）並上傳 `index.html`。
2) Settings → Pages：Source = Deploy from a branch / Branch = main / Folder = /(root)。
3) 取得 Pages 網址，填入 LINE Developers（LINE Login Channel → LIFF → Endpoint URL）。
4) Scopes 勾 `openid`、`profile`、`chat_message.write`；Add friend option = On (Normal)。

## 桌機 QR
本頁在桌機會顯示「帶關鍵字」的 QR（使用 oaMessage），掃完直接切回 LINE 並預填文字。
