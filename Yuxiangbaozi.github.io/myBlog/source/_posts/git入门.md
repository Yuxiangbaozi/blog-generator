---
title: git入门
date: 2019-02-12 09:06:25
tags:
---
<h1>今天刚接触Git，我就稍微介绍一下Git的三个最基本命令</h1>
<ul>
    <li>git init命令：当你想新建一个博客的时候，在你目录下面首先要git init初始化，
        初始化后，该目录下面就会新增一个.git的文件，表示初始化成功</li>
    <li>git add命令：当你新增或者修改文件之后，要先用git add添加到缓存区，
        可以git add XXX（文件名）逐个添加，也可以git add .把该目录和下面目录的所有文件一起添加</li>
    <li>git commit -m命令：用来把缓存区的东西提交到本地库，
        可以git commit XXX（文件名） -m逐个提交，也可以git commit . -m所有文件一起提交</li>
</ul>