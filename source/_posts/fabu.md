---
title: hh今天学习了hexo发布博客
date: 2020-07-08 10:24:48
tags:
---

* hexo init blog  //创建一个叫blog的hexo工程
* npm install hexo-deployer-git --save //安装发布工具（在blog目录）
* hexo new xxx  //创建新博客，名为xxx的md文件
* hexo clean  //清除缓存
* hexo generate //生成新静态文件hexo
* hexo deploy   //把新生成文件部署到博客
* git clone --depth 1 git@github.com:iissnan/hexo-theme-next.git themes/next
                      //在博客根目录blog下下载主题文件
* theme: landscape  //更改文件配置
* deploy: 
  type: git
  repository: GitHub仓库地址
  branch: master


