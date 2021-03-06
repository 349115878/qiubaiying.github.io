---
layout:     post
title:      My Indie Game Diary 第四篇
subtitle:   3dmax 骨骼导入UE4
date:       2018-3-2
author:     Trump
header-img: img/post-bg-debug.png
catalog: true
tags:
- 3dmax
- UE4
---

# My Indie Game Diary 第四篇 3dmax 骨骼导入UE4流程
## 准备工作
- 将模型合并，并指定材质Id，和上文低模一样，这里指定了两个材质Id。如图：

![](http://mingchuan.wang/img/MyIndieGameDiary_4/1.png)

## 导出 SkeletonMesh 到UE4

选中Mesh -> 导出选中对象。

![](http://mingchuan.wang/img/MyIndieGameDiary_4/2.png)

指定路径，并命名

![](http://mingchuan.wang/img/MyIndieGameDiary_4/3.png)

参数配置

![](http://mingchuan.wang/img/MyIndieGameDiary_4/4.png)
![](http://mingchuan.wang/img/MyIndieGameDiary_4/5.png)

打开UE4引擎将模型导入，（如果也想导入动画则，可选中Import Animations）。

![](http://mingchuan.wang/img/MyIndieGameDiary_4/6.png)

导入成功如图

![](http://mingchuan.wang/img/MyIndieGameDiary_4/7.png)

## 导出动画到UE4

选中骨骼（注意不要选中控制器啊）-> 导出选中对象。
![](http://mingchuan.wang/img/MyIndieGameDiary_4/8.png)

指定路径，并命名

![](http://mingchuan.wang/img/MyIndieGameDiary_4/9.png)

参数配置

![](http://mingchuan.wang/img/MyIndieGameDiary_4/10.png)
![](http://mingchuan.wang/img/MyIndieGameDiary_4/5.png)

导入UE4 选项,选中刚刚导入的Skeleton Mesh

![](http://mingchuan.wang/img/MyIndieGameDiary_4/11.png)

## 更换材质贴图后效果图

可以动了！！！

![](http://mingchuan.wang/img/MyIndieGameDiary_4/12.png)


版权声明：本文为博主原创文章，未经博主允许不得转载。
