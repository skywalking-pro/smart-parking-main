# 解放生产力! 程序员做私活必备的Java开源项目

## 前言

**随着各种UI框架的的逐渐,系统界面逐渐VUE化，项目中代码生成器也可以生成统一规范的界面，代码生成的半智能开发将是新的趋势，单表数据模型和一对多数据模型的增删改查功能直接生成使用,可节省80%工作量，解放生产力。**

## 简介

**SingerBoot是一款基于代码生成器的智能开发平台。引领全新的开发模式，可以帮助解决管理系统类90%的重复编码工作，让开发更多关注业务逻辑。快速提高开发效率，帮助公司节省人力成本，同时又不失灵活性。**

**SingerBoot宗旨是: 提供简单快速的Java开发平台，让公司的项目快速跑起来，让程序员尽可能专注于业务，不必纠结于项目，既保证了公司流程的保密行，又减少了开发人员的工作量。**

**它可以应用在任何J2EE项目的开发中，尤其适合企业信息管理系统（MIS）、内部办公系统（OA）、企业资源计划系统（ERP）、客户关系管理系统（CRM）等，，可以显著提高开发效率90%以上，极大降低开发成本; 而且更好的支持了SAAS系统的开发需求。**

## 为什么选择SingerBoot?

1. **采用主流框架，容易上手; 代码生成器依赖性低,很方便的扩展能力，可完全实现二次开发。**
2. **开发效率很高,采用代码生成器，单表数据模型和一对多(父子表)数据模型，增删改查功能自动生成，菜单/权限配置直接使用。**
3. **页面校验自动生成(必须输入、数字校验、金额校验、时间空间等)。**
4. **封装完善的用户基础权限、强大的数据权限、和数据字典等基础功能，直接使用无需修改。**
5. **常用共通封装，各种工具类(定时任务,短信接口,邮件发送,Excel导出等),基本满足80%项目需求。**
6. **先进的UI库，针对WEB UI进行标准式封装，页面统一采用Antd,前端代码使用简单清晰且便于维护。**
7. **多种首页风格切换,支持自定义首页风格。（经典风格、Shortcut风格、ACE bootstrap风格、云桌面风格）。**
8. **专业接口对接机制，统一采用restful接口方式，集成swagger-ui在线接口文档，Token安全验证，方便客户端对接。**
9. **接口安全机制，可细化控制接口授权，非常简便实现不同客户端只看自己数据等控制。**
10. **方便灵活的权限控制，权限细化管理。**
11. **代码生成器支持resutful接口生成。**

### 联系作者
#### 微信号: SkywalkingPro
#### 见文末微信二维码

## 演示地址
```
登录地址: https://www.skywalking.pro/common-platform
登录账号: admin
登录密码: 123456
```
若演示地址不可用，可翻到文末扫码联系作者微信或者留言

## 软件架构说明

### 前端技术架构

1. Antd-VUE
2. 页面,按钮级别权限控制。
3. 多个组件封装，调用方便。
4. Antv图表组件。
5. WebPack
6. ES6
7. 多环境打包。
8. VUE路由，过滤器，自定义指令。
9. 代码简洁，符合编码规范。

### 后端技术架构

1. SpringBoot2.x
2. Shiro权限框架
3. Redis6.X最新版
4. MyBatis注解版
5. MySQL6.7
6. 分模块开发，自定义启动脚本，JVM调优
7. 多环境,前后端完全分离。
8. 代码生成器。
9. orika传输对象映射器。

## 系统截图展示

### 登陆界面

![输入图片说明](https://singer-coder.oss-cn-chengdu.aliyuncs.com/141525_50700f2b_1808544.png "屏幕截图.png")

### 用户注册

![](https://singer-coder.oss-cn-chengdu.aliyuncs.com/image-20211026153710731.png)

### 系统主页

![image-20211026154652062](https://singer-coder.oss-cn-chengdu.aliyuncs.com/image-20211026154652062.png)

### 菜单管理



![image-20211026154706736](https://singer-coder.oss-cn-chengdu.aliyuncs.com/image-20211026154706736.png)

### 角色管理

![image-20211026154718805](https://singer-coder.oss-cn-chengdu.aliyuncs.com/image-20211026154718805.png)

### 系统用户管理

![image-20211026154828146](https://singer-coder.oss-cn-chengdu.aliyuncs.com/image-20211026154828146.png)

### 系统日志

![输入图片说明](https://singer-coder.oss-cn-chengdu.aliyuncs.com/141732_29a59d45_1808544.png "屏幕截图.png")

### 系统监控-服务器

![image-20211026154851525](https://singer-coder.oss-cn-chengdu.aliyuncs.com/image-20211026154851525.png)

### 系统监控-JVM

![image-20211026154943440](https://singer-coder.oss-cn-chengdu.aliyuncs.com/image-20211026154943440.png)

### 系统日志

![image-20211026155003660](https://singer-coder.oss-cn-chengdu.aliyuncs.com/image-20211026155003660.png)

### 请求追踪

![image-20211026155016809](https://singer-coder.oss-cn-chengdu.aliyuncs.com/image-20211026155016809.png)



## 项目代码展示

### 前端VUE代码截图展示

![image-20211026154147729](https://singer-coder.oss-cn-chengdu.aliyuncs.com/image-20211026154147729.png)

### 后端Java代码截图展示

![image-20211026154128918](https://singer-coder.oss-cn-chengdu.aliyuncs.com/image-20211026154128918.png)

## 系统功能模块概要
+ 系统主页
  - 系统主页折线图统计
    * 系统主页折线图统计
    + 系统模块导航
    
    - 系统在线数，访问数统计
+ 系统管理
  - 系统用户管理
    * 系统用户条件查询
    + 系统用户修改
    
	  - 系统用户删除
  - 系统用户新增
  - 系统菜单管理
    * 系统菜单条件查询
    + 系统菜单修改(可级联修改)
	  
    - 系统菜单删除
  - 系统菜单新增
  - 系统角色管理
    * 系统角色条件查询
	  + 系统角色修改
    
    - 系统角色删除
  - 系统角色新增
  - 系统字典管理
	  * 系统字典条件查询
	  + 系统字典修改
	  
	  - 系统字典删除
	- 系统字典新增
+ 系统监控
  - 在线用户管理
    * 在线用户条件查询
    
    + 在线用户踢出
  - 系统日志管理
    * 系统日志条件查询
    
    + 系统日志分析
  + 系统访问IP分析
  - 系统请求追踪
    * 请求耗时追踪
    
    + 请求方法追踪
  + 请求URL追踪
  + 请响应状态追踪
  - 系统信息
    * JVM信息监控
    
    + 服务器信息监控



##  **联系作者** 

###  微信二维码  

![微信二维码-1](https://singer-coder.oss-cn-chengdu.aliyuncs.com/%E5%BE%AE%E4%BF%A1%E4%BA%8C%E7%BB%B4%E7%A0%81-1.png "微信二维码-1.png")

### 技术交流群

![输入图片说明](https://singer-coder.oss-cn-chengdu.aliyuncs.com/%E6%8A%80%E6%9C%AF%E4%BA%A4%E6%B5%81%E7%BE%A4.png "%BE%.png")

## 安装教程

### 后端安装方法

```
1.  mvn clean package
2.  tar -zxvf common-platform-api.gz (解压tar包)
3.  cd common-platform-api
5.  sh /sbin/startup.sh dev
```
### 前端安装方法
```
1.  yarn install (安装node_moudle)
2.  yarn start (启动)
3.  yarn build:pro (构建生产包)
```
### 使用说明

见上面安装方法

