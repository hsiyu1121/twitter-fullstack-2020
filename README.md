# Simple Twitter

[simple twitter 連結在此](https://github.com/hsiyu1121/twitter-fullstack-2020.git) 


# 網站畫面

登入入口

![image](https://github.com/hsiyu1121/twitter-fullstack-2020/signup.png)

twitter頁面

![image](https://github.com/hsiyu1121/twitter-fullstack-2020/twitter.png)

 公開聊天室
 
 ![image](https://github.com/hsiyu1121/twitter-fullstack-2020/profile.png)

# 網站功能


+ 註冊成為一般使用者即可使用該網站

+ 使用者可以發佈貼文

+ 使用者可以喜歡/取消喜歡貼文

+ 使用者可以追蹤/取消追蹤其他使用者

+ 使用者可以修改個人帳戶與編輯個人資料

+ 使用者可以追蹤,退追蹤其他使用者

+ 使用者可以到貼文底下留言按like

+ 使用者可以在公開聊天室與同時在線的朋友聊天


# How to run this project
1. To build this project locally:
```
git clone https://github.com/michaelnctu/twitter-fullstack-2020.git
```
2. After directing into the file
```
npm install
```
3. nodemon
```
npm install nodemon 
```
4. Workbench新增database
```
CREATE DATABASE forum;
```
5. Workbench使用database
```
use forum;
```
6.匯入遷徙檔案
```
npx sequelize db:migrate
```
8.匯入種子資料
```
npx sequelize db:seed:all
```
9.啟動程式
```
node app.js or nodemon app.js
```
10.成功執行
```
在 terminal 可以看到 Example app listening on port 3000!
```
11.開啟瀏覽器
```
網址列輸入localhost:3000
```

# 測試帳號
| 帳號 | 密碼 |
| :------------- | :------------- |
| root | 12345678  |
| user1 | 12345678  |
| user2| 12345678  |
| user3| 12345678  |
| user4| 12345678  |
| user5| 12345678  |


# 共同開發人員

[Sheng Yao's GitHub](https://github.com/ShengYaoHuang)

[Michael's GitHub](https://github.com/michaelnctu)

