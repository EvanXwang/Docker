# Docker
###Docker相關指令
 
1. docker build -t dockerhub/xxx .  (建立容器)(dockerhub 自己的hub帳號 / xxx 檔名)(後面記得加 .) 
2. docker push dockerhub/xxx  (上傳至docker hub)
3. docker ps (檢示運行狀態)
4. docker stop  xxx (先暫停目前運行的)
5. docker rm xxx (刪除 )
6. docker logs xxx (查看目前運行狀況)
7. docker logs xxx -f    (持續監控執行緒)  
8. docker run -d -p 8000:8000 --name aaa dockerhub/xxx  (aaa 可自取名稱， xxx為docker hub上面的檔名)    

Docker_Linebot_basic - line_bot_basic 為示範- 本地端操作
