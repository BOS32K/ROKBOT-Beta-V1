# ROK Bot BetaV0.1

## 自述
此腳本包含客戶端驗證，製作時間花費28h，目前屬於測試版本仍有些許邏輯錯誤

## 目前已有功能:
1. **自動尋找田地並且耕種**
2. **自動收穫城市農田**
3. **多開處，調整你的 `config.json` 來設置運作的模擬器**
4. **客製化田地等級**

---

## 未來添加項目:
1. **自動驗證**
2. **全自動種田**
3. **自動練兵**
4. **自動完成每日活動**

---

## 本腳本使用工具如下:
- **Python 3.15**
- **Ldplayer**

本腳本只需 Ldplayer，exe 已打包所需要的函數庫

## 注意
1. 請勿在同 IP 情況下大量登入
2. `main.exe` 需要待在原本資料夾，移動可能會導致報錯
3. 為了能更方便的調試 exe 這裡除了 `.config.json` 請勿調試
4. 本檔案有 ID 驗證，如有需要的可 DM DC: **bos32k**
5. Ldplayer 設置請到開啟 adb 調適 ([test.png](test.png))

---

## 安裝 SDK 平台工具

1. 到 [Google 官方下載 SDK Platform Tools](https://developer.android.com/studio/releases/platform-tools)
2. 加入系統環境變數 `Path`

---

### 示例命令
```bash
# 設置環境變數
set PATH=%PATH%;C:\platform-tools

# 啟用 adb 調試模式
adb devices
