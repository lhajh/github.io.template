# lhajh

我的个人博客：<https://lhajh.github.io>，欢迎 Star 和 Fork。

## 概览

<!-- vim-markdown-toc GFM -->
* [效果预览](#效果预览)
* [Fork 指南](#fork-指南)
* [贴心提示](#贴心提示)
* [经验与思考](#经验与思考)
* [评论和网站统计](#评论和网站统计)
* [致谢](#致谢)

<!-- vim-markdown-toc -->

## 效果预览

**[在线预览 &rarr;](https://lhajh.github.io)**

![screenshot home](/assets/images/RkUc52u.png)

## Fork 指南

Fork 本项目之后，还需要做一些事情才能让你的页面「正确」跑起来。

1. 正确设置项目名称与分支。

   按照 GitHub Pages 的规定，名称为 `username.github.io` 的项目的 master 分支，或者其它名称的项目的 gh-pages 分支可以自动生成 GitHub Pages 页面。

2. 修改配置。

   网站的配置基本都集中在 `/_config.yml` 文件中，将其中与个人信息相关的部分替换成你自己的，比如网站的 title、url、tracking_id(网站统计) 和 Disqus(评论系统) 的用户名等。如果你着急看到效果，tracking_id和Disqus可以先不设置。这两个设置见[评论和浏览统计](#评论和网站统计)。

3. 删除我的文章与图片。

   如下文件夹中除了 template.md 文件外，都可以全部删除，然后添加你自己的内容。

   * `/_posts` 文件夹中是我已发布的博客文章。
	   * 文章使用markdown格式，文件名参照已有的文件命名
   * `/assets/images` 文件夹中是我的文章和页面里使用的图片。

4. 修改「关于」页面。

   `/about.md` 文件内容对应网站的「关于」页面，里面的内容多为个人相关，将它们替换成你自己的信息

## 贴心提示

1. 排版建议遵照一定的规范，推荐 [中文文案排版指北（简体中文版）][1]。

2. 在本地预览博客效果可以参考 [Setting up your Pages site locally with Jekyll][2]。

## 经验与思考

* 简约，尽量每个页面都不展示多余的内容。

* 有时一图抵千言，有时可能只会拖慢网页加载速度。

* 言之有物，不做无痛之呻吟。

* 如果写技术文章，那先将技术原理完全理清了再开始写，一边摸索技术一边组织文章效率较低。

* 杜绝难断句、难理解的长句子，如果不能将其拆分成几个简洁的短句，说明脑中的理解并不清晰。

* 可以学习一下那些高质量的博主，他们的行文，内容组织方式，有什么值得借鉴的地方。

## 评论和网站统计

### Disqus评论模块的添加

[Disqus网址](https://disqus.com/)，注册完账号登录后点击右上角头像下的`Home`跳转到主页，然后点击齿轮按钮选择`Add Dusqus To Site`，跳转后拉到页面最下方，点`GET STARTED`，再次跳转后选择`I want to install Disqus on my site`，然后在新页面中填写你的`Website Name`和选择`Category`，如下图：

![Create a new site](/assets/images/Rgs2HU.png)

创建成功后，在新页面点击`Install Disqus`，Platform选择为`Universal Code`，拉到页面最下面点击按钮即可。

然后点击`Configure Disqus`，将Website Name改为你想要的名称，我的为`https://lhajh.github.io`(这个随便设置，而且以后还可以更改)，URL设置为你的`Github page`地址，然后Disqus网站设置完成。

![Configure Disqus for Your Site](/assets/images/GrsJ43F.png)

在 /_config.yml 文件中，修改`disque: your Website Name.disqus.com`.
注意：这个Website Name是和选择`Category`一起设置的那个，不是第二次设置的那个，第二次设置的是在评论系统上面显示的名字，如下图：

![Disqus interface](/assets/images/JRdd4H.png)

### 网站统计
[Google Analytics(GA)](http://www.google.cn/analytics/analytics/#)是著名互联网公司谷歌提供的网站数据统计服务,可以实时监控网站上发生的活动。
使用Google账号登录，点击右上角`SIGN IN`，选择`Analytics`,进入GA管理页面,配置跟踪站点，如下图：

![set website](/assets/images/aF3Jf.png)

设置好账号名称、网站名称和网站网址(注意区分http和https)，选择行业类别和报告时区。拉到页面最底下，点击获取跟踪ID，如下图：

![fetch ID](/assets/images/bhE6Jf.png)

在“管理 >> 跟踪信息 >> 跟踪代码”中找到你的跟踪ID,如下图：

![track ID](/assets/images/Ce4K8g.png)

将上图中跟踪ID填写到 `/_config.yml`的`tracking_id : 'UA-xxxx-1'`

## 致谢

本博客外观基于 [DONGChuan](https://dongchuan.github.io) 修改，感谢！

[1]: https://github.com/mzlogin/chinese-copywriting-guidelines
[2]: https://help.github.com/articles/setting-up-your-pages-site-locally-with-jekyll/
