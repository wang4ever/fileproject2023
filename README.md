# 旺旺淘票

> ### 一个Vue+Express+Mysql的电影售票项目

### 后台管理

#### 登录页
![](C:\Users\新旺\Desktop\ppt\管理系统效果1.gif)



## 项目说明 

### 项目目录     

├── film 前端页面项目文件   
├── film_admin 后台管理系统    
├── film_api 前后台接口文件       
├── db_film.sql 数据库文件  

### 安装步骤

#### 1. 拉取项目

#### 2. 导入数据文件db_film.sql (我这里使用的数据库是mysql,用户：root,密码：123456)

#### 3. 项目细节

- [前端页面项目](https://github.com/J1ong/FilmSys/tree/master/film)
- [后台管理项目](https://github.com/J1ong/FilmSys/tree/master/film_admin)
- [前后台接口项目](https://github.com/J1ong/FilmSys/tree/master/film_api)

#### 4. 启动项目

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
