# kalamos

## 0.6.0

### Minor Changes

- 79eec45: **Ctrl + 滾輪縮放**：按住 Ctrl 滾動滑鼠滾輪即可放大或縮小介面，與「檢視 > 放大 / 縮小 / 實際大小」共用縮放比例（#112）。

## 0.5.0

### Minor Changes

- **Cmd+P 快速開檔**：模糊搜尋目前資料夾的 Markdown 檔並標亮命中字元；輸入框空白時列出最近開啟的檔案，並新增「檔案 > 打開最近使用」子選單（#104）。

### Patch Changes

- **支持 Kalamos**：產品頁、README 與 GitHub 加入 Buy Me a Coffee 連結（#105）。
- **開發流程**：Workflow 權限強化、Biome 格式化與 CI 檢查、以 Changesets 管理版本與 CHANGELOG（#99、#100、#101）。

## 0.4.0

### Minor Changes

- **Windows 支援（實驗性）**：新增 Windows 10 / 11（x64）桌面版本，包含 NSIS 與 MSI 安裝程式、`.md` 檔案關聯、單一執行個體開檔、原生選單列、Windows 快捷鍵提示、關閉前未儲存變更檢查，以及透過無頭 Microsoft Edge / Google Chrome 匯出含書籤的 A4 PDF（#94、#97）。
- **自動化跨平台發佈流程**：新增 tag 觸發的 GitHub Actions 發佈流程，自動建置 macOS（Apple Silicon / Intel）與 Windows（NSIS / MSI）安裝檔、執行 macOS codesign 與 DMG 檢查、產生 `SHA256SUMS.txt` 並建立 Draft Release（#93）。

## 0.3.0

### Minor Changes

- **多文件分頁**：支援開新分頁（`Cmd+T`）、關閉與切換分頁、拖曳調整順序，各分頁獨立保留內容、復原紀錄、游標與捲動位置，並在關閉視窗或結束前提示所有未儲存變更（#81）。
