# 將檔案上傳到GitHub流程

## 檔案上傳三部曲
```git
# 1. 將test.py加入暫存區
git add test.py

# 2. 將test.py提交檔案到儲存庫，記錄版本訊息
git commit -m "版本訊息"

# 3. 將test.py上傳
git push -u origin main
```
![](https://i.imgur.com/qWcgYG1.png)

## 第一次上傳
先在GitHub建立一個coding的專案

```git
# 1. 產生README.md檔案
echo "# coding" >> README.md
# 2. 將資料夾初始化，交給git託管
git init
# 3. 將README.md加入暫存區
git add README.md
# 4. 將README.md提交檔案到儲存庫，記錄版本訊息
git commit -m "first commit"
# 5. 把資料夾跟雲端上的GitHub專案做連結
git remote add origin https://github.com/zoelin2022/coding.git
# 6. 將README.md上傳
git push -u origin main
```
![](https://i.imgur.com/RuyEucO.png)

