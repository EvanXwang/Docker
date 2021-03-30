# Docker

### 以line_bot_basic 為示範- 範本練習筆記

### 1. 本地端 Docker操作步驟


1.將套件記錄匯出 - pip3 freeze > requirements.txt  
2.將需封裝的程式，全放在同一資料夾  
3.資料夾內新增 Dockerfile > 填寫相關參數  
4.cmd > docker build -t xxx .  (xxx為檔名)  
5.cmd > docker run -p 8800:8800 -it xxx      

