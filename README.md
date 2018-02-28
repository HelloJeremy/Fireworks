# 通过Github展示个人静态页面

>个人开发的静态页面可以通过放到github上，可以通过外访问这个项目。

#### 在github上新建一个项目
- **新建项目Fireworks**
- **clone Fireworks到个人电脑**
#### 新建一个Fireworks分支

本文新建分支及git的其他操作通过WebStorm的git客户端实现。
新建一个Fireworks的gh-pages分支：
![图一](https://github.com/HelloJeremy/Fireworks/blob/master/pic/new%20branch1.png?raw=true)
![2](https://github.com/HelloJeremy/Fireworks/blob/master/pic/addBranch2.png?raw=true)

>注意事项：新建的分支中会继承master分支的所有文件，如果我们需要一个干净的、空白的分支。我们需要手动删除所有的文件，然后将这个干净的分支提交推送到github上。

#### 将静态文件发布到gh-pages分支上
![static pages](https://github.com/HelloJeremy/Fireworks/blob/master/pic/staticPages.png?raw=true)

#### 通过个人的https://你的github用户名.github.io/项目名/访问
我的Fireworks项目访问路径：https://hellojeremy.github.io/Fireworks/
#### 配置个人域名指向这个静态页面
1、ping你的http://你的github用户名.github.io，得到一个IP；

2、修改你的域名解析记录，添加一个A记录，用得到的IP；
![绑定域名](https://github.com/HelloJeremy/Fireworks/blob/master/pic/domain.png?raw=true)
3、登录http://github.com>进入项目>Settings>Custom domain>输入你的域名>Save。
![绑定域名](https://github.com/HelloJeremy/Fireworks/blob/master/pic/setting_domain.png?raw=true)

现在可以通过网址：http://ecutgis.online/在线预览我的Fireworks项目



#### 参考链接
[github怎么绑定自己的域名？](https://www.zhihu.com/question/31377141)

[用github来展示你的前端页面吧](https://www.jianshu.com/p/d1ae8f6bdcb8)