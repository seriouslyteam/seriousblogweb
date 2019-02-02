# seriousblogweb
A blog with Vue.js

> 从零开始学 Web & Server 

#### 1.start
> 学习前端、后端。如果有收获，说不定转行了？全栈？做管理也需要技术吧~ 参与的每个人都可以收获：前端技能、后端技能、Git管理、写作等完整项目经验。那么如果这个小项目完成了，可以考虑仿一个成熟的完整应用，例如：头条等。

#### 2.Blog

做什么，由小及大，做个人网站最简单，最有成就感，也便于入门。
项目所涉及的知识点以及我们要做的。

* Web：
    * 框架 Vue.js 
    * 基础控件：Button,图片，文字，List,MarkDown渲染，上传文件
    * 项目新建，发布
    * 功能：图片上传，markdown显示

* Serve
    * 项目新建，发布
    * Golang 
    * 数据库分表，设计表
    * 图片上传，富文本持久化，
    * 根据域名或者关键字段拆分blog
*  目标是颜值高，自己喜欢的风格
#### 3.准备
* 学习资源
    * 1.[Vue.js菜鸟教程](http://www.runoob.com/vue2/vue-tutorial.html)
    * 2.[Go菜鸟教程](http://www.runoob.com/go/go-tutorial.html)
    * 
    
#### 4.怎么做
* 要求
  * 代码规范：[参考阿里 Java 规范](https://github.com/alibaba/p3c/blob/master/%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4Java%E5%BC%80%E5%8F%91%E6%89%8B%E5%86%8C%EF%BC%88%E8%AF%A6%E5%B0%BD%E7%89%88%EF%BC%89.pdf)
  * 代码规范：大小写，驼峰 ，暂定 MVVM 模式
  * 分支管理：master 开发分支，版本完成后拉分支备份，分支名：sw_1.0
  * commit 规范： 1.《功能》描述
* start
    * 找一个免费的服务器 
    * 域名备案
    * web 提交一个空白页面 
    * Server 提供一个test 接口
    * Web 接入统计
    
* Version 1.0
    * web 首页列表
    * Server 首页接口

* Version 2.0
    * 详情页面 & 补充
    * 标签 & 其他接口

#### 补充
* 1.文档要完善
* 2.timeline 
* 3.协作平台：https://tower.im/teams/fb0140d7bb99f924b4ba4a98369deb5d/projects/
```

### 后台
1.文章详情接口

String headPictureUrl 
String title
String time
String detailText
String nextBlog
String lastBlog

2.Home List
List blogs
String headPictureUrl 


3.上传
解析为静态页面，数据库持久化


### web
* 默认配置
	* 个人信息
	* Head 信息

* 1.上传页面

* 2.首页

* 3.详情页面
```
* 实现blog的增，删，改
