---
layout: post
title: Start！妙妙屋的由来？
date: 25-02-17 00:00:00 +0800
category: Tina的胡言乱语
thumbnail: /style/image/1.png
icon: chat
---


* content
{:toc}

## 网站的由来？

Tina有很多三分钟热度的爱好，比如说手绘、建模、写小说等等...  
这么多爱好零零散散的，有时候想和朋友分享，就比较困难  
于是就突然想建立一个网站  
作为一个“Tina随心所欲の作品集”  
于是去查了下各种建站方式，发现“GitHub + Jekyll Themes”很适合我  
于是就动手做了！  


## “GitHub + Jekyll Themes”的优劣势  

**优势**  
1.免费免费免费！（重要的事情说三遍）  
2.简单
无需服务器或数据库，只需上传文件  
可以直接套模板，代码小白的救星！  
  
**劣势**  
1.域名是固定的（.github.io）  
2.Jekyll Themes套模板就意味着个性化程度低  

  
## 建站攻略！
  
**1. 注册 GitHub 账号**  
访问 GitHub，点击“Sign up”注册账号。  
完成邮箱验证。  
  
**2. 创建一个新的仓库**  
登录 GitHub，点击右上角“+”号，选择“New repository”。  
输入仓库名：你的用户名.github.io（例如，用户名为 john，则仓库名为 john.github.io）。  
选择“Public”（公开），勾选“Add a README file”，然后点击“Create repository”。  
  
**3. 选择一个 Jekyll 主题**  
访问 Jekyll Themes，选择一个你喜欢的免费主题（我使用的是：pinghsu-jekyll）。  
下载主题文件（通常是ZIP格式）。  
  
**4. 上传主题到 GitHub**  
解压下载的主题文件。  
打开你的 GitHub 仓库，点击“Add file” -> “Upload files”。  
将解压后的主题文件全部上传到仓库。  
  
**5. 修改配置文件**  
在仓库中找到 _config.yml 文件，点击编辑（铅笔图标）。  
修改以下内容：  
name: 网站标题（如“我的作品集”）。  
description: 网站描述（如“展示我的设计作品”）。  
url: 填写 https://你的用户名.github.io。  
点击“Commit changes”保存。  
  
**6. 预览网站**  
访问 https://你的用户名.github.io，就可以查看你的网站啦~  
如果看不到更新，可能需要等待几分钟，或者检查 _config.yml 配置是否正确。  
