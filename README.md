# X-Boot
[![AUR](https://img.shields.io/aur/license/yaourt.svg)](https://github.com/Exrick/xmall/blob/master/License)
[![](https://img.shields.io/badge/Author-Exrick-orange.svg)](http://blog.exrick.cn)
[![](https://img.shields.io/badge/version-1.1-brightgreen.svg)](https://github.com/wqh0109663/x-boot)
[![GitHub stars](https://img.shields.io/github/stars/wqh0109663/x-boot.svg?style=social&label=Stars)](https://github.com/wqh0109663/x-boot)
[![GitHub forks](https://img.shields.io/github/forks/wqh0109663/x-boot.svg?style=social&label=Fork)](https://github.com/wqh0109663/x-boot)

> 作者大四作品 能力经验有限 如有错误欢迎指正 期待您的捐赠支持！

### 宣传视频
- [作者亲自制作XBoot文字快闪宣传视频](http://www.bilibili.com/av30284667)
- [作者亲自制作其他项目宣传视频](https://www.bilibili.com/video/av23121122/)
### [在线Demo](http://xboot.exrick.cn)
http://xboot.exrick.cn
### 前台基于Vue+iView项目地址： [xboot-front](https://github.com/Exrick/xboot-front)
### 项目简介 
- [x] 代码拥有详细注释 无复杂逻辑 核心使用 SpringBoot 2.0.5.RELEASE
- [x] JPA + Mybatis-Plus任意切换
- [x] 操作日志记录方式任意切换Mysql或Elasticseach记录
- [x] 极简代码生成 只需输入类名和字段 自动创建数据库表
- [x] 动态权限管理 菜单按钮权限+数据权限配置
- [x] 支持社交账号、短信等多方式登录 不干涉原用户数据 实现第三方账号管理
- [x] 基于Websocket消息推送管理、基于Quartz定时任务管理
- [x] Actuator可视化数据监控
- [x] 后台提供分布式限流、同步锁、验证码等工具类 前端提供空白Vue模版
- [x] 可动态配置SSO、短信、邮件、Vaptcha验证码等
- [x] 为什么要前后端分离
    - 都什么时代了还在用JQuery？ 

### 截图预览

![QQ截图20180826163917.png](https://i.loli.net/2018/08/26/5b826868e2359.png)

![QQ截图20180826163956.png](https://i.loli.net/2018/08/26/5b8268c57d1e3.png)

![QQ截图20180826164058.png](https://i.loli.net/2018/08/26/5b8268d63d156.png)

![QQ截图20180826164129.png](https://i.loli.net/2018/08/26/5b8268dec28ee.png)

![QQ截图20180826164144.png](https://i.loli.net/2018/08/26/5b8268e6a091f.png)

![QQ截图20180826164226.png](https://i.loli.net/2018/08/26/5b8268efab94a.png)

### [完整版截图细节展示](https://github.com/Exrick/x-boot/wiki/%E5%AE%8C%E6%95%B4%E7%89%88%E6%88%AA%E5%9B%BE%E7%BB%86%E8%8A%82%E5%B1%95%E7%A4%BA)

### 前端所用技术
- Vue 2.5.x、Vue Cli 3.x、iView、iview-admin、iview-area、Vuex、Vue Router、ES6、webpack、axios、echarts、cookie等
- 前台为基于Vue+iView的独立项目请跳转至 [xboot-front](https://github.com/Exrick/xboot-front) 项目仓库查看
### 后端所用技术
##### 各框架依赖版本皆使用目前最新版本
- Spring Boot 2.0.5.RELEASE
- SpringMVC
- Spring Security
- [Spring Data JPA](https://docs.spring.io/spring-data/jpa/docs/2.0.6.RELEASE/reference/html/)
- [MyBatis-Plus](http://mp.baomidou.com)
- [Redis](https://github.com/Exrick/xmall/blob/master/study/Redis.md)
- [Elasticsearch](https://github.com/Exrick/xmall/blob/master/study/Elasticsearch.md)：基于Lucene分布式搜索引擎
- [Druid](http://druid.io/)：阿里高性能数据库连接池 [Druid配置官方中文文档](https://github.com/alibaba/druid/tree/master/druid-spring-boot-starter)
- [Json Web Token(JWT)](https://jwt.io/)
- [Quartz](http://www.quartz-scheduler.org)：定时任务
- [Beetl](http://ibeetl.com/guide/#beetl)：模版引擎 代码生成使用
- [Thymeleaf](https://www.thymeleaf.org/)：发送模版邮件使用
- [Hutool](http://hutool.mydoc.io/)：Java工具包
- [Jasypt](https://github.com/ulisesbocchio/jasypt-spring-boot)：配置文件加密(thymeleaf作者开发)
- [Swagger2](https://github.com/Exrick/xmall/blob/master/study/Swagger2.md)：Api文档生成
- MySQL
- [Nginx](https://github.com/Exrick/xmall/blob/master/study/Nginx.md)
- [Maven](https://github.com/Exrick/xmall/blob/master/study/Maven.md)
- 第三方SDK或服务
    - [七牛云文件存储服务](https://developer.qiniu.com/kodo/sdk/1239/java)
    - [Mob全国天气预报接口](http://api.mob.com/#/apiwiki/weather)：需注册账号创建应用后申请填入AppKey后免费使用
    - 完整版
        - [Vaptcha人机验证码](https://www.vaptcha.com/)
        - [阿里云短信服务](https://dysms.console.aliyun.com)
- 其它开发工具
    - [Lombok](https://projectlombok.org/)
    - ~~[JRebel](https://github.com/Exrick/xmall/blob/master/study/JRebel.md)：开发热部署~~ 已无法免费使用 改回devtools
    - [阿里JAVA开发规约插件](https://github.com/alibaba/p3c)

### 本地运行部署
- 安装依赖并启动：[Redis](https://github.com/Exrick/xmall/blob/master/study/Redis.md)、[Elasticsearch](https://github.com/Exrick/xmall/blob/master/study/Elasticsearch.md)(当配置使用ES记录日志时需要)
- [Maven安装和在IDEA中配置](https://github.com/Exrick/xmall/blob/master/study/Maven.md)
- 建议使用IDEA([破解/免费注册](http://idea.lanyus.com/)) 安装 `Lombok` 插件后导入该Maven项目 若未自动下载依赖请在根目录下执行 `mvn install` 命令
- MySQL数据库新建 `xboot` 数据库，配置文件已开启ddl自动生成表结构但无初始数据，请记得运行导入sql文件
- 修改配置文件 `application.yml` 相应配置，其中有详细注释，所有配置只需在这里修改
- 编译器中启动运行 `XbootApplication.java` 或根目录下执行命令 `mvn spring-boot:run` 默认端口8888 访问接口文档 `http://localhost:8888/swagger-ui.html` 说明启动成功 管理员账密admin|123456
- 前台页面请启动基于Vue的 [xboot-front](https://github.com/Exrick/xboot-front) 项目，并修改其接口代理配置
> 温馨提示：若更新代码后报错，请记得更新sql并清空Redis缓存
### 开发指南及相关技术栈文档
- [项目基本配置和使用相关技术栈文档【必读】](https://github.com/Exrick/x-boot/wiki/%E9%A1%B9%E7%9B%AE%E5%9F%BA%E6%9C%AC%E9%85%8D%E7%BD%AE%E5%92%8C%E4%BD%BF%E7%94%A8%E7%9B%B8%E5%85%B3%E6%8A%80%E6%9C%AF%E6%A0%88%E6%96%87%E6%A1%A3%E3%80%90%E5%BF%85%E8%AF%BB%E3%80%91)
- [如何使用XBoot后端在30秒内开发出增删改接口](https://github.com/Exrick/x-boot/wiki/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8XBoot%E5%90%8E%E7%AB%AF%E5%9C%A830%E7%A7%92%E5%86%85%E5%BC%80%E5%8F%91%E5%87%BA%E5%A2%9E%E5%88%A0%E6%94%B9%E6%8E%A5%E5%8F%A3)
- [具体X-Boot增删改文档示例](https://github.com/Exrick/x-boot/wiki/CRUD)
- 完整版
    - [第三方社交账号登录配置](https://github.com/Exrick/x-boot/wiki/%E7%AC%AC%E4%B8%89%E6%96%B9%E7%A4%BE%E4%BA%A4%E8%B4%A6%E5%8F%B7%E7%99%BB%E5%BD%95%E9%85%8D%E7%BD%AE)
    - [短信登录配置](https://github.com/Exrick/x-boot/wiki/%E7%9F%AD%E4%BF%A1%E7%99%BB%E5%BD%95%E9%85%8D%E7%BD%AE)
    - [Vaptcha人机验证码配置使用](https://github.com/Exrick/x-boot/wiki/vaptcha%E4%BA%BA%E6%9C%BA%E9%AA%8C%E8%AF%81%E7%A0%81%E9%85%8D%E7%BD%AE%E4%BD%BF%E7%94%A8)

### [分布式扩展](https://github.com/alibaba/dubbo-spring-boot-starter/blob/master/README_zh.md)

### XBoot后端学习分享（更新中）
1.[Spring Boot 2.x 区别总结](https://github.com/Exrick/x-boot/wiki/SpringBoot2.x%E5%8C%BA%E5%88%AB%E6%80%BB%E7%BB%93)

2.Spring Security整合JWT

3.Spring Security实现动态数据库权限管理

4.[Spring Boot 2.x整合Quartz](https://github.com/Exrick/x-boot/wiki/Spring-Boot-2.x%E6%95%B4%E5%90%88Quartz)

5.[基于Websocket实现发送消息后右上角消息图标红点实时显示](https://github.com/Exrick/x-boot/wiki/%E5%9F%BA%E4%BA%8EWebsocket%E5%AE%9E%E7%8E%B0%E5%8F%91%E9%80%81%E6%B6%88%E6%81%AF%E5%90%8E%E5%8F%B3%E4%B8%8A%E8%A7%92%E6%B6%88%E6%81%AF%E5%9B%BE%E6%A0%87%E7%BA%A2%E7%82%B9%E5%AE%9E%E6%97%B6%E6%98%BE%E7%A4%BA)

### Docker下后端集群部署(更新中)

> 前端集群部署请跳转至[xboot-front](https://github.com/Exrick/xboot-front)项目查看

1.[Docker的安装与常用命令](https://github.com/Exrick/x-boot/wiki/Docker%E7%9A%84%E5%AE%89%E8%A3%85%E4%B8%8E%E5%B8%B8%E7%94%A8%E5%91%BD%E4%BB%A4)

2.基于PXC架构Mysql数据库集群搭建

3.Redis集群搭建

4.Elasticsearch集群搭建

5.XBoot后端集群部署

### 作者其他项目推荐
- [XPay个人免签收款支付系统v1.2](https://github.com/Exrick/xpay)

    - 现已支持移动端支付 手机扫码体验

    ![](http://p77xsahe9.bkt.clouddn.com/18-7-21/16350122.jpg)

- [XMall：基于SOA架构的分布式电商购物商城](https://github.com/Exrick/xmall)

    ![](https://i.loli.net/2018/07/22/5b54615b95788.jpg)

- 微信小程序APP 
    - [前台源码点我提前获取](http://xpay.exrick.cn/pay) [预览视频](https://v.qq.com/x/page/f0627kf4x1e.html)

    ![](https://i.loli.net/2018/07/21/5b52e1de385e7.png)
- 机器学习笔记
    - [Machine-Learning](https://github.com/Exrick/Machine-Learning)
### 技术疑问交流
- QQ交流群 `475743731(付费)`，可获取各项目详细图文文档、疑问解答 [![](http://pub.idqqimg.com/wpa/images/group.png)](http://shang.qq.com/wpa/qunwpa?idkey=7b60cec12ba93ebed7568b0a63f22e6e034c0d1df33125ac43ed753342ec6ce7)
- 免费交流群 `562962309` [![](http://pub.idqqimg.com/wpa/images/group.png)](http://shang.qq.com/wpa/qunwpa?idkey=52f6003e230b26addeed0ba6cf343fcf3ba5d97829d17f5b8fa5b151dba7e842)
- 作者博客：[http://blog.exrick.cn](http://blog.exrick.cn)
### [捐赠](http://xpay.exrick.cn/pay)
