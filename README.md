# 建立 Json 檔

npm install -g json-server  
or  
yarn global add json-server  
安裝 Json 套件

json-server --watch --port 555 db.json  
監控資料庫狀態 & 獲得網址

# 使用 Postman

## Get 獲得

輸入網址 下拉式選單 Get 獲得 Json 檔內容

## Post 新增

radio 選擇 Body 檔案格式 Json
將要新增的內容輸入 按下 send 新增資料

## Put 修改

網址後要加入 /id EX : http://localhost:555/users/3
指定要修改的資料

## Delete 刪除

同修改 加入指定 ID
刪除後再使用 GET 會發現找不到 因為刪掉了
