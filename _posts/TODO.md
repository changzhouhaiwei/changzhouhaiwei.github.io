---
layout: post
title:  "日记2023-11-03"
date: 2023-11-03 13:40:18 +0800
categories: Unity
tags: Unity
---


# 1.GC泛滥的地方,   tolua相关。
##	setparent 整改
##	transform.position

	setWorldPosX
	setWorldPosY 
	setLocalPosX
	setLocalPosY

### 完成情况:
	文件夹 FightEditorScene 完成


# 2.动作状态机修改。
	免除不必要的状态切换问题。
	使用animator.CrossFade animator.Play

	#需要整体修改animator,再议。

# 3.镜头代码修改。
	原跟随相机删除
	虚拟相机
	增加常驻虚拟相机处理
	移除阴阳师视角

# 4.列表卡顿。
	例如任务领奖 

# 5.变体研究。 （是否需要升级2020）
	内存占用

# 6.UI粒子是否有优化方案

# 7.通信优化。

# 8.战斗断线重连处理。

# 9.移植数码宝贝HotFixLua逻辑。

# 10.内存池优化
	修改粒子效果的播放问题，统一制作成由程序控制播放，play on awake参数
	
# 11.状态机处理游戏复杂流程。
	procedure

# 12.飞书组。
	使用钉钉文档处理。
	上限100G,文档不粘贴，只给svn路径。

# 13.触摸
	模型点击
	滑动转动视角


