---
title: 使用github pages构建个人博客
type: bulid blog
---

## 1、准备工作 
首先你需要一个github账号，因为这样我们才可以领取免费域名并免费托管文件，这里进入官网：github.com，点击右上角的sginup并填写注册信息就好了。  
## 2、导入仓库  
如果用网上所说的使用jekyll在本地部署的话，那么一切会变得非常复杂，对小白非常不友好，有时还要配置ssh，非常麻烦，但是现在你可以fork我的仓库，导入就可以用。  
进入我的仓库fork地址：https://github.com/wangxc092/wangxc092.github.io/fork  
将仓库的名称改为：你的用户名.github.io，再点击creat fork就好了
![fork仓库](/images/bulid-blog-fork.jpg)  
>username换成你的用户名！
>username换成你的用户名！
>username换成你的用户名！  
>重要的事情说三遍！

## 3、修改网站界面  
既然仓库都导入了，我们总算不能还是正常的界面和我的的文章吧，此时我们就要修改网站配置了。  
#### 3.1、config.yml（网站界面配置文件）  
网站标题，描述，网址：  
``` yml
title:          你的博客名称
description:    "你的描述"
url:            你的网站url
```
