## 项目简介

>项目来源于：[https://gitee.com/darlingzhangsh/graduation_project](https://gitee.com/darlingzhangsh/graduation_project)

本系统是基于**Thymeleaf+SpringBoot+Mybatis**。是非常标准的SSM三大框架（
**SpringBoot就是一个大框架，里面包含了许多的东西，其中Spring就是最核心的内容，其中也包含Spring MVC**）实现的的家庭财务管理系统。

**难度等级：中等**

## 技术栈

### 编辑器

IntelliJ IDEA 2019.1.1 (Ultimate Edition)

### 前端技术

基础：html+css+JavaScript

框架：[Apache ECharts](https://www.echartsjs.com/zh/index.html)+[JQuery](https://www.runoob.com/jquery/jquery-tutorial.html)+[Layui](https://www.layui.com/)

### 后端技术

SpringBoot 2.1.1.RELEASE

模板引擎：thymeleaf

数据库：mysql 5.7.27（个人测试使用）

jdk版本：1.8.0_181（个人测试使用）



## 本地运行

> 若有疑惑可查看[视频版本](https://zhuanlan.zhihu.com/p/132508106)。

1.下载zip直接解压或安装git后执行克隆命令 
```
git clone https://gitee.com/darlingzhangsh/graduation_project.git
```
2.使用idea打开项目，配置maven、jdk即可。

3.打开Navicat For Mysql，创建**cwgl**数据库，并运行**sql/cwgl.sql**。

4.修改**application.yml**中数据库相关的内容。

5.运行**com.example.cwgl.CwglApplication**,运行成功后，[http://localhost:8080](http://localhost:8080)为登录页面。

系统管理员初始账号：zsh 

系统管理员初始密码：zsh




## 注意
- 该项目未声明mysql、jdk使用版本，以上版本号均为个人测试使用版本。
- 注意**修改application.yml中数据库相关的内容。**


## 项目截图
![登录](../../public/oldPicturesFromGitee/blog20200417135301.png)
![首页](../../public/oldPicturesFromGitee/blog20200417135302.png)
![支出管理](../../public/oldPicturesFromGitee/blog20200417135303.png)
![统计报表](../../public/oldPicturesFromGitee/blog20200417135304.png)
![收入管理](../../public/oldPicturesFromGitee/blog20200417135305.png)
![用户管理](../../public/oldPicturesFromGitee/blog20200417135306.png)
![角色管理](../../public/oldPicturesFromGitee/blog20200417135307.png)

## 声明
- 该项目收集于gitee，本人只是代为说明使用技术、注意点及启动方式，帮助大家进行学习交流。
- **若通过gitee地址无法下载该项目或无法正常运行，可私信我，本人免费协助。**


#### 推荐阅读
- [JSP+Servlet+JDBC+DBCP2实现在线购书系统](https://mp.weixin.qq.com/s/kFHzkRtL6FNN9koaWAjDkg)
- [JSP+Servlet+JDBC实现的shine网上书城](https://mp.weixin.qq.com/s/GvfywZwg28IMYk5Q2ZWcOw)
- [JSP+Servlet+JDBC实现的云端汽修后台管理系统](https://mp.weixin.qq.com/s/kalGv5T8AZGxTnLHr2wDsA)
- [JSP+Servlet+JDBC实现的学生信息管理系统](https://mp.weixin.qq.com/s/K-H50joCXeE0cnwmtoqhJw)
- [JSP+Servlet+C3P0+Mysql实现的YCU movies电影网站](https://mp.weixin.qq.com/s/bJ1lGNDrVwzXx5z9dDaV-w)
- [JSP+Servlet+C3P0+Mysql实现的图书馆管理系统](https://mp.weixin.qq.com/s/MdGVYX_8t-CiOasghGPrRw)

---

本篇已收录于个人GitHub仓库[https://github.com/coderzcr/JavaWeb-Project-Source-Share](https://github.com/coderzcr/JavaWeb-Project-Source-Share)，欢迎Star。


欢迎关注我的公众号“**张有路**”，原创技术文章第一时间推送。

![](../../public/oldPicturesFromGitee/qrcode.gif)


