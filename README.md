# 克卜勒 AI 教師

扮演天文學家約翰尼斯·克卜勒（1571–1630）的 AI 物理教師網頁，給高中物理課使用。

## 功能

- **AI 對話**：克卜勒以第一人稱、繁體中文回答，可切換「探究引導」與「直接講解」兩種教學模式。
- **人物資料**：生平、代表作與 1589–1630 年表。
- **行星運動三定律**：可調離心率的橢圓軌道動畫（等時間掃過等面積），以及六顆行星的 T²/a³ 驗證表。

## 使用方式

1. 開啟網頁後，在聊天視窗上方輸入 Anthropic API 金鑰（可在 <https://console.anthropic.com> 申請）。
2. 金鑰只保存在使用者自己的瀏覽器，直接傳送給 Anthropic API，不會寫進程式碼或上傳到其他地方。
3. 共用電腦請不要勾選「記住在這台電腦」。

## 檔案

| 檔案 | 說明 |
|---|---|
| `index.html` | 網頁本體（HTML、CSS、JavaScript 都在同一個檔案） |
| `kepler.jpg` | 克卜勒畫像 |

## 部署到 GitHub Pages

儲存庫的 **Settings → Pages**，Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。約一分鐘後網址為：

```
https://<你的帳號>.github.io/kepler-ai-teacher/
```
