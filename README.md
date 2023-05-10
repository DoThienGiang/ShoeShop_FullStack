# ShoeShop_NodeJS
## Ngôn ngữ lập trình :

* Frontend : ReactJS, Redux

* Backend : Nodejs (Express ejs + Mongodb)

*  video hướng dẫn       
    -  https://www.youtube.com/watch?v=1NWBO8L81J8
## CHATBOT
- [_Chatbot nodejs ecommerce_](https://github.com/search?q=chatbot+nodejs+ecommerce)
- [_Shopyst - Trợ lý mua sắm thông minh dựa trên web cho các nền tảng thương mại điện tử._](https://github.com/Nitinkumar-Gove/shopyst)
- [_Chat bot cho phép người dùng tìm kiếm và mua sản phẩm._](https://github.com/sunnysetia93/EcommerceChatBot)


## SERVER

## Error khi import mongoose from "mongoose"; 
 
**Case 1:**
- cài đặt thêm :
    ```
    npm install nodemon @babel/core @babel/node @babel/preset-env -D
    ```
- file package.json thêm : 
    ```
    "repository": {
        "type": "module"
    },
    ```
    và
    ```
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "start": "babel-node server.js"
    },
    ```
**Case 2:**
- Thay thế ~~`import mongoose from "mongoose"; `~~
- Thành _**`const express = require('express') `**_

## Project Start-up Guide

**File .env:**
    _**`PORT = 5000`**_
    _**`NODE_ENV = development`**_
    _**`JWT_SECRET = shoeshop123456`**_
    _**`MONGO_URL = mongodb://localhost:27017/ElectronicsShop`**_
    _**`PAYPAL_CLIENT_ID = ARkRYU9dwrLkT14GpoOnctsF-tud0kt7DiR_uWvOHIbKZoXKyQ4C2h8mYwpPQpiOTPJgd6oN2f37dXVK`**_

**Cài đặt phụ thuộc:**
-  các phụ thuộc:
    _**`npm install @types/mongoose bcryptjs cors dotenv express `**_
    _**`npm install express-async-handler jsonwebtoken mongoose morgan`**_
    _**`npm install --save-dev concurrently nodemon`**_

**Run project:**
- chạy lệnh : 
    _**`npm install`**_
-  vô mongodb đăng nhập bằng gmail dothiengiang1994@gmail.com để kiểm tra database

**vào Postman test thôi:**
- các đường dẫn chạy trên _PostMan_:
- Import user: _**`http://localhost:5000/api/import/user`**_
- Import product: _**`http://localhost:5000/api/import/products`**_
- Get all product: _**`http://localhost:5000/api/products`**_
- Single product: _**`http://localhost:5000/api/products/id_product`**_
- Login: _**`http://localhost:5000/api/users/login`**_
- User Profile: _**`http://localhost:5000/api/users/profile`**_
- Register: _**`http://localhost:5000/api/users`**_
- Order Details: _**`http://localhost:5000/api/orders/id_order`**_

## DashBoard
    - .env:
        - REACT_APP_SERVER_URL = http://localhost:5000
        - REACT_APP_SERVER_URL = https://server-shoeshop.onrender.com
    
    - cài đặt : 
        - npm install
    
    - Run
        - npm start => chạy chương trình

## Client
    - cài đặt : 
        - npm install
    - tạo 1 file .env điền các DL sau:cài đặt : 
        - REACT_APP_SERVER_URL = http://localhost:5000
        - REACT_APP_SERVER_URL = https://server-shoeshop.onrender.com
    - Run
        - npm start => chạy chương trình
