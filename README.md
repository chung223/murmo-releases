# Murmo

**全地端 macOS 語音助手** — 語音輸入 × 即時口譯字幕 × 會議紀錄 × 筆記問答
**Fully on-device voice assistant for macOS**

零月租 · 無使用上限 · 隱私不外流 | No subscription · No caps · Private

## ⬇️ 下載 / Download
👉 **[下載最新版 Murmo.dmg](https://github.com/chung223/murmo-releases/releases/latest/download/Murmo.dmg)**

## 安裝 / Install
1. 打開 DMG，把 **Murmo** 拖進 `Applications`
2. ⚠️ **第一次：右鍵點 Murmo → 打開 → 再按「打開」**（見下方）
3. 安裝 [Ollama](https://ollama.com/download)
4. 開 Murmo → 走「**開始**」分頁：一鍵下載模型、給權限

## ⚠️ Gatekeeper（重要 / Important）
Murmo 是**自簽** app（未經 Apple 公證），第一次 macOS 會擋「無法驗證開發者」。這正常，**只需一次**：

**Applications 裡對 Murmo 按右鍵 →「打開」→ 再按「打開」。**

Murmo is **self-signed**. On first launch macOS will block it — this is expected. **Right-click → Open → Open.** If still blocked:
```bash
xattr -dr com.apple.quarantine /Applications/Murmo.app
```

## 需求 / Requirements
macOS 26+ · Apple Silicon · [Ollama](https://ollama.com)（模型約 8GB，精靈會下載）
