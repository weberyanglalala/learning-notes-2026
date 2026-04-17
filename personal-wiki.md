# personal-wiki

## 如何建立 personal wiki

### 筆記與知識管理

- note taking
- text editor 文字編輯器
  - vscode
- version control 版本控制
  - git
  - git init
  - git add
  - git commit
  - git push
  - 版控能幫助你什麼
- mindmap 心智圖
  - markmap
- chart 畫圖工具
  - excalidraw
  - mermaid
  - plantuml
- markdown 筆記語法
  - Markdown Preview Enhanced
- static files
  - pdf
  - jpg

### 常用的 VS Code 指令

- create folder
- create file
- delete file
- move file
- search file
- search text
- command palette

### 常見的 CLI 指令

- 用 git bash 執行
- bash command

| Action | Bash (Linux/macOS) | PowerShell (Windows) | PowerShell Alias | 說明 |
| --- | --- | --- | --- | --- |
| Move/Rename | `mv src dest` | `Move-Item src dest` | `mv` | 移動檔案或資料夾，也可以順便重新命名。 |
| Copy | `cp src dest` | `Copy-Item src dest` | `cp` | 複製檔案或資料夾到另一個位置。 |
| Change Directory | `cd <path>` | `Set-Location <path>` | `cd <path>` | 切換到其他資料夾。 |
| Current Directory Path | `pwd` | `Get-Location` | `pwd` | 顯示目前所在資料夾的路徑。 |
| Go To Parent Folder | `cd ..` | `Set-Location ..` | `cd ..` | 切換到上一層資料夾。 |
| Go To Home Folder | `cd ~` | `Set-Location ~` | `cd ~` | 切換到使用者的家目錄。 |
| List Files | `ls` | `Get-ChildItem` | `ls` | 列出目前資料夾中的檔案與資料夾。 |
| List All (Hidden) | `ls -a` | `Get-ChildItem -Force` | `ls -Force` | 列出全部項目，包含隱藏檔。 |
| Create Folder | `mkdir <name>` | `New-Item -Type Directory` | `mkdir` | 建立新的資料夾。 |
| Create File | `touch <name>` | `New-Item -Type File` | `ni -Type File` | 建立新的空白檔案。 |
| Remove File | `rm <name>` | `Remove-Item <name>` | `rm <name>` | 刪除單一檔案。 |
| Remove Folder | `rm -r <name>` | `Remove-Item -Recurse <name>` | `rm -Recurse <name>` | 遞迴刪除整個資料夾及其內容。 |

- `.` 代表目前資料夾。
- `..` 代表上一層資料夾。
