# Git Note

👉[在HackMD瀏覽](https://hackmd.io/@tyzx5246/ryvhJsBQF)

## :bookmark:一般檔案操作架構

![](https://i.imgur.com/WdWsT1I.png)
git 版本控制基本架構（[來源]

```sequence
工作目錄->暫存區: git add <file>
暫存區->儲存庫: git commit -m"紀錄訊息"
```
- `git add <file>` 將當前位於工作目錄的檔案加入暫存區。
- `git commit -m"紀錄訊息"` 將目前位於暫存區的檔案提交到儲存庫。
- `git commit -am"紀錄訊息"` 如果檔案夾已加入「git控管」，  
 用`git commit -am` 一次完成`git add`＋`git commit -m`兩個步驟。
 
- == 工作目錄(Working directory) == Git 相關操作都會在這個目錄下完成
- == 暫存區(Staging area) == 放準備要提交到儲存庫的檔案
- == 儲存庫(Repository) == 是記錄檔案或目錄狀態的地方
- **:triangular_flag_on_post:每次提交檔案時** 建議(修改)小而(功能)完整



