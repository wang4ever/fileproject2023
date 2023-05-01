# 旺旺淘票

> ### 一个Vue+Express+Mysql的电影售票项目

## 效果预览

### 前端展示
<img src="https://user-images.githubusercontent.com/108270096/235434377-f98ad64c-16ae-4637-b4d2-ec7a7c8272dc.png" width="300px">
### 后台展示
<img src="https://user-images.githubusercontent.com/108270096/235434943-7c9968ce-b7ab-4ac0-a904-37e69af9dcb1.gif" width="300px">



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

#### 3. 项目细节



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
