<p><h1 align="center">电影购票微信小程序带后台管理</h1></p>

- <b>完整代码获取地址：从戎源码网 ([https://armycodes.com/](https://armycodes.com/))</b>
- <b>技术探讨、资料分享，请加QQ群：692619798</b> 
- <b>作者微信：19941326836  QQ：952045282</b> 
- <b>承接计算机毕业设计、Java毕业设计、Python毕业设计、深度学习、机器学习</b>
- <b>选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 一条龙服务</b>
- <b>所有选题地址 ([https://github.com/YuLin-Coder/AllProjectCatalog](https://github.com/YuLin-Coder/AllProjectCatalog)) </b>


## 一、系统介绍
本系统是小程序前台，带后台管理

本系统分为管理员、用户两种角色

管理员功能：
- 登录、统计分析、密码修改、用户管理、广告管理、影院管理、分类管理、电影管理、场次管理、订单管理、管理员管理

用户功能：
- 登录、注册、电影展示、电影票选座、提交订单、电影搜索、分类展示电影、选择影院、我的信息、我的订单、我的收藏

## 二、所用技术
后端技术栈：
- Springboot
- SpringMvc
- mybatis
- mysql
- jwt
- shiro

前端技术栈：
- html
- ajax
- jquery
- 微信小程序
- bootstrap

## 三、环境介绍
基础环境 :IDEA/eclipse, JDK 1.8, Mysql5.7及以上, Maven3.6, 微信开发者工具

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、微信小程序页面
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)

### 2、管理员页面
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)

## 五、浏览地址
- 前台访问路径：
  账号密码：test/123456 

- 后台访问路径：http://localhost:10001/admin/login.html
  账号密码：admin/123456

## 六、安装教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql

2. 使用IDEA/Eclipse导入film-server项目，导入时，若为maven项目请选择maven; 等待依赖下载完成

3. 修改resources目录下面application-dev.yml里面的数据库配置和文件路径配置

4. com/wfuhui/WfuhuiApplication.java启动后端项目

5. 微信小程序打开film-miniapp项目，编译好之后就运行成功了

