# NotchShelf

macOS 選單列檔案暫存架。滑過螢幕頂端中央即可展開，拖入檔案、暫存參照，再拖到需要的 App。

## 下載與安裝

請從本 repo 的 **Releases** 下載最新 DMG，打開後將 **NotchShelf.app** 拖入 **Applications**。

- macOS 14 或更新版本。
- 同一個 App 支援 Apple Silicon 與 Intel。
- 本版本採 ad-hoc 簽署，尚未使用 Developer ID 簽署及 Apple 公證。macOS 可能阻擋開啟；此檔不具備公證下載版本的信任狀態。

## 功能

- 瀏海／無瀏海螢幕的頂端觸發，離開後 0.15 秒開始收回。
- 拖入檔案與資料夾、縮圖、持久保存及失效項目清理。
- 單選、Command／Shift 多選、Command+A 全選，Backspace 移除參照。
- 選取檔案後按空白鍵開啟系統快速查看，支援多選；雙擊開啟、右鍵在 Finder 顯示、滑鼠滾輪橫向捲動。
- 原生拖出檔案；可設定成功拖出後移除 Shelf 項目。
- AirDrop 分享選取或全部檔案，也可直接拖入 AirDrop 按鈕；分享視窗置中顯示。
- Esc 直接收回，不必先點選檔案；登入啟動與選單列清空。
- 支援外接螢幕、Spaces、全螢幕及睡眠喚醒。

Shelf 儲存檔案參照，不備份原始內容。移除、清空及分享不會刪除原始檔案。

此公開 repo 僅供發佈說明與 DMG 下載；原始碼保存在獨立私人 repo。此處不包含 App 原始碼。
