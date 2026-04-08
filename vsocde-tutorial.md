# VS Code 簡易教學

- [Tutorial: Get started with Visual Studio Code](https://code.visualstudio.com/docs/getstarted/getting-started)

這份教學是給剛開始使用 VS Code 的使用者，重點介紹幾個最常用的功能：快捷鍵、檔案搜尋、Command Palette，以及如何搜尋程式碼。

## 1. 開啟與切換常用功能

如果你正在使用 macOS，下面這些快捷鍵最常用：

- `Command + P`：快速搜尋並開啟檔案
- `Command + Shift + P`：開啟 Command Palette
- `Command + Shift + F`：全專案搜尋文字
- `Command + F`：搜尋目前檔案中的文字
- `Command + B`：顯示或隱藏側邊欄
- `Command + \`：開啟或關閉內建終端機

這幾個快捷鍵熟悉之後，日常操作會快很多。

## 2. 如何搜尋檔案

當專案裡有很多檔案時，最快的開啟方式不是用滑鼠找資料夾，而是直接用檔案搜尋。

操作方式：

1. 按 `Command + P`
2. 輸入檔名的部分文字
3. 用方向鍵選擇目標檔案
4. 按 `Enter` 開啟

例如你想找 `setup.md`，只要按 `Command + P` 後輸入 `setup`，通常很快就能找到。

## 3. 如何使用 Command Palette

Command Palette 是 VS Code 很核心的功能，幾乎所有指令都可以從這裡執行。

開啟方式：

- 按 `Command + Shift + P`

常見用途：

- 輸入 `Reload Window` 重新載入編輯器
- 輸入 `Format Document` 格式化目前檔案
- 輸入 `Preferences: Open Settings` 開啟設定
- 輸入 `Markdown: Open Preview` 預覽 Markdown

如果你忘記某個功能在哪裡，先打開 Command Palette 搜尋，通常就能找到。

## 4. 如何搜尋程式碼

VS Code 提供兩種常見搜尋方式：

### 目前檔案內搜尋

如果你只想找目前這個檔案裡的文字：

1. 按 `Command + F`
2. 輸入要查找的關鍵字
3. 使用 `Enter` 或搜尋箭頭切換結果

這適合快速找某個函式名稱、變數或段落內容。

### 整個專案搜尋

如果你想在整個專案中找某段程式碼或文字：

1. 按 `Command + Shift + F`
2. 輸入關鍵字
3. 查看所有符合結果的檔案與行數
4. 點選結果直接跳到對應位置

這在以下情境特別有用：

- 想找某個函式在哪些地方被使用
- 想知道某個變數在哪裡定義
- 想一次修改某個固定字串

## 5. 搜尋小技巧

你可以善用下面幾個方式讓搜尋更準確：

- 使用完整函式名稱來縮小結果
- 先用 `Command + P` 找檔案，再用 `Command + F` 找內容
- 用 `Command + Shift + F` 搜整個專案時，先從明確關鍵字開始
- 搜尋結果太多時，可以改用更完整的字詞

## 6. 建議的練習方式

如果你剛開始使用 VS Code，可以這樣練習：

1. 用 `Command + P` 開啟一個檔案
2. 用 `Command + F` 在檔案中搜尋某個字
3. 用 `Command + Shift + F` 搜尋整個專案
4. 用 `Command + Shift + P` 打開 Command Palette，試著執行 `Markdown: Open Preview`

只要把這幾個動作練熟，日常編輯和找資料會順很多。

## 7. 總結

對初學者來說，最值得先記住的是這三個快捷鍵：

- `Command + P`：找檔案
- `Command + Shift + P`：找指令
- `Command + Shift + F`：找整個專案的內容

這三個功能幾乎就是 VS Code 日常操作的核心。