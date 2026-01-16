---
title: "如何下载和安装Python"
date: 2024-01-16
description: "详细的Python下载和安装教程，适合Windows用户"
tags: ["python", "安装", "教程", "windows"]
categories: ["python"]
weight: 2
math: false
---

### 一、首先进入Python官方网站

我是在必应里面直接搜索的，找到下面这个图片的链接进去

![Python官网首页](/images/Pasted-image-20260115135710.png)
![Python官网首页2](/images/Pasted-image-20260115135832.png)

### 二、找到Downloads

因为我是Windows电脑，所以直接点进Windows去下载，进去之后的页面是这样：

![Python下载页面](/images/Pasted-image-20260115140014.png)

**如果找不到这个页面也可以尝试点击下方的链接，应该就可以跳过这个步骤直接进入该界面**

[Python Releases for Windows | Python.org](https://www.python.org/downloads/windows/)

### 三、判断电脑是64位还是32位

（如果已经知道了就下载对应的installer就行）

#### *step 1. 按 Win+R 键打开"运行"对话框

*Win就是Fn和Alt中间那个Windows键*

![运行对话框](/images/Pasted-image-20260115140610.png)

#### *step 2. 输入 `msinfo32` 并按回车(Enter)

![输入msinfo32](/images/Pasted-image-20260115140909.png)

#### *step 3. 右侧找到系统类型

![系统类型](/images/Pasted-image-20260115141043.png)

这个系统类型是 `X64` 就是64位系统，是 `X32` 就是32位系统

### 四、下载installer并运行

下载好之后运行，因为这一部分我没有截图，可以考虑观看b站视频，链接如下：

[Python安装教程_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1f3411t73m/?spm_id_from=333.337.search-card.all.click&vd_source=8f23d8e73564506b0d54c607add3bf31)

![Python安装界面](/images/Pasted-image-20260115141426.png)

这个界面我们把两个选项都勾选上，并且选在第二个 **Customize installation**

![可选功能](/images/Pasted-image-20260115141601.png)

这个界面所有的都选上，然后点击next

![高级选项](/images/Pasted-image-20260115141759.png)

在这个界面我们就可以在 **Browse** 里面选择我们希望安装的位置，我修改到了D盘，新建了文件夹python，改完之后大概长这样：

![选择安装路径](/images/Pasted-image-20260115141936.png)

点击安装之后出现：

![安装成功](/images/Pasted-image-20260115142004.png)

这个successful就说明安装成功了，这个界面可以关闭了

### 五、找到安装好的Python

点击桌面下方四个蓝色方块的图标，在搜索里面搜索python：

![开始菜单搜索](/images/Pasted-image-20260115142256.png)
![搜索结果](/images/Pasted-image-20260115142448.png)

点击这个IDLE就可以了：

![Python IDLE](/images/Pasted-image-20260115142532.png)

IDLE分为交互模式和编辑器模式，详情可看第二部分。
