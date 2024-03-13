# GIT版控步驟與介紹
01.初始化後會創建.git資料夾會追蹤目前到之後有什麼變化
```
git init
```
02.檢查目前目錄狀態
```
git status
```
03.檔案交給 Git ，讓 Git 開始「追蹤」目錄，此時內容加到暫存區
```
git add .
```
"目前"所在的目錄全部提交
```
git add {FileName}
```
04.將暫存區的內容提交到儲存庫（Repository）保留
```
git commit -m "{Msg}"
```
"修改記錄"
git commit 只會處理"暫存區"裡的內容
```
git commit -a -m 'Git test'
//加上-a就不用 先git add
```
05.推到GitHUb
```
git push origin
```
補充說明
設定個人資訊,多人合作時可以知道是誰做的
```
git config --global user.name "{Name}"       
```
```
git config --global user.email "{email}"       
```
查看config資訊
```
git config --list
```