# lhajh

我的个人博客：<https://lhajh.github.io>，欢迎 Star 和 Fork。

## 概览

<!-- vim-markdown-toc GFM -->
* [效果预览](#效果预览)
* [Fork 指南](#fork-指南)
* [贴心提示](#贴心提示)
* [经验与思考](#经验与思考)
* [tracking_id和Disqus](#tracking_id和Disqus)
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

   网站的配置基本都集中在 /_config.yml 文件中，将其中与个人信息相关的部分替换成你自己的，比如网站的 title、url、tracking_id(网站流量统计) 和 Disqus(评论系统) 的用户名等。如果你着急看到效果，tracking_id和Disqus可以先不设置。这两个设置见最后。

3. 删除我的文章与图片。

   如下文件夹中除了 template.md 文件外，都可以全部删除，然后添加你自己的内容。

   * /_posts 文件夹中是我已发布的博客文章。
	   * 文章使用markdown格式，文件名参照已有的文件命名
   * /assets/images 文件夹中是我的文章和页面里使用的图片。

4. 修改「关于」页面。

   /about.md 文件内容对应网站的「关于」页面，里面的内容多为个人相关，将它们替换成你自己的信息

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

## tracking_id和Disqus

- [Disqus](https://disqus.com/)
- [tracking_id](http://www.google.cn/analytics/analytics/#)
- http://www.jianshu.com/p/91c01f236846

## 致谢

本博客外观基于 [DONGChuan](https://dongchuan.github.io) 修改，感谢！

[1]: https://github.com/mzlogin/chinese-copywriting-guidelines
[2]: https://help.github.com/articles/setting-up-your-pages-site-locally-with-jekyll/
