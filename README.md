# 旺旺淘票

> ### 一个Vue+Express+Mysql的电影售票项目

### 后台管理

#### 登录页

![管理后台登录页面1](C:\Users\新旺\Desktop\ppt\管理后台登录页面1.png)

**功能展示**

![管理系统效果1](https://user-images.githubusercontent.com/108270096/235437052-f02b3e03-4f18-4150-98ca-1772e008c95f.gif)


## 项目说明 
本项目是一款基于Web开发的电影院购票系统，旨在为用户和电影院提供便捷、高效的服务。该系统主要包括前台系统和管理员后台界面两部分。

​        前台系统是用户进行购票、评价、打分、选座位等操作的平台。用户可以通过注册账号登录进入系统，选择心仪的电影并查询排片信息，然后根据自己的需要购买相应的电影票，支付成功后即可获电影取单号。此外，用户还可以对观影体验进行评价和打分，并查看其他用户的评价和打分情况，以便做出更加明智的选择。

​        管理员后台界面则是管理电影、用户、电影排片等相关事务的平台。管理员可以添加新电影及其相关信息，如电影名称、导演、演员、时长、类型等，以便用户进行搜索和选择。同时，管理员也可以添加新用户，管理用户信息，如账号、密码、联系方式等。此外，管理员还可以对已上映或即将上映的电影进行管理和排片，安排影院、放映时间等相关事宜，以确保电影院的运营效率和盈利能力。

  

## 效果预览

### 前端展示
<img src="https://user-images.githubusercontent.com/108270096/235434377-f98ad64c-16ae-4637-b4d2-ec7a7c8272dc.png" width="300px">

### 项目目录     

├── film 前端页面项目文件   
├── film_admin 后台管理系统    
├── film_api 前后台接口文件       
├── db_film.sql 数据库文件  

### 安装步骤

#### 1. 拉取项目

```bash
#依次执行以下命令
cd FilmSys
cd film
npm install
cd ../film_admin
npm install
cd ../film_api
npm install
```

#### 2. 导入数据文件db_film.sql (我这里使用的数据库是mysql,用户：root,密码：123456)


##### 1. 启动前后台接口项目

```bash
#输入命令前要先进入到film_api中
nodemon app.js
```

##### 2. 启动前端页面项目

```bash
#输入命令前同样需要进入到film中
npm start
```

##### 3. 启动后台管理项目

```bash
#输入命令前同样需要进入到film_admin中
npm start
```

#### 5. 最后

- 浏览器地址栏输入http://localhost:8080/ 可看前端页面，切换到移动设备就可以正常看到移动版页面了
- 浏览器地址栏输入http://localhost:8081/ 可到后台登录界面（账号：admin，密码：admin） 
- 接口服务器启动在3000端口
