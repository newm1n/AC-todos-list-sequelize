# TODO List x Sequelize

## Features - 功能

1. 使用者可以註冊、登入、登出 Todo List
2. 使用者可以查看、新增、編輯、刪除 Todo 資料

## Installation and execution - 安裝與執行步驟

1. 開啟Terminal, clone此專案至本機

2. 進入存放此專案的資料夾

3. 安裝 npm 套件
```
npm install
```

4. 安裝nodemon (若已安裝請直接進行下一步)
```
npm install -g nodemon
```

5. 開啟 Workbench 建立專案資料庫
```
drop database if exists todo_sequelize; 
create database todo_sequelize; 
use todo_sequelize;
```

6. 使用 Migrations 在資料庫建立 schema 
```
npx sequelize db:migrate
```

7. 製作種子資料
```
npx sequelize db:seed:all
```

8. 啟動伺服器
```
npm run dev 
```

9. 若出現以下字樣，表示伺服器已啟動並成功連結
```
App is running on http://localhost:3000
```
10. 若欲暫停使用
```
ctrl + c
```
