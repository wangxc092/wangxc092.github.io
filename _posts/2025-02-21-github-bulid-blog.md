---
title: 使用github pages构建个人博客（傻瓜式操作）
type: bulid blog
---
# 使用github pages构建个人博客（傻瓜式操作）

> 准备工作：  
>1、一台能上网的电脑，操作系统不限。  
>2、手  

## 1、导入仓库  
首先你需要一个github账号，这里不说注册方法了，可以自己百度~~连百度都不会还想建站😂~~
首先进入[我的的网站模板](https://bgithub.xyz/wangxc092/wangxc092.github.io/fork)   
填写仓库名，格式为：用户名.github.io，并点击Create fork，基本的仓库就创建好了。

>小提示：fork地址为GitHub镜像站，请提前登记。

## 2、修改配置文件  
我们的网站结构如下⬇️  
``` yml
根目录
|
|--_posts/   #文章存放目录
|--_sass/
|--_includes/
|--_layouts/
|--assets/
|--images    #图片
config.yml   #配置文件
```
