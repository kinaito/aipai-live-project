### 播放器状态
![提示](img/prompt.png)

* 播放器有多种状态，每一种都有提示
* 提示的位置都是屏幕中央，无论是 **播放器默认**、还是 **播放器全屏**
* **当出现状态提示时，操作UI不会出现**
* 状态是覆盖在播放器上的页面
* 状态提示，每次只会出现一种

### 提示列表 {#top}
1. [片头开始](#1)
2. [无网络](#2)
3. [加载失败](#3)
4. [缓冲中](#4)
5. [暂停中](#5)
6. [直播结束](#8)
7. [预告](#9)


### 1. 片头开始 {#1}
![](img/s1.png)
爱拍字样下的线条，是动的，表示正在载入中

播放器内部有背景图，避免加载过程单调

[回到列表](#top)


### 2. 无网络 {#2}
![](img/s2.png)

**`重试`**，和操作UI上的 **重新载入** 一样的作用

覆盖在当前的视频上，有一层蒙版降低视频的透明度

[回到列表](#top)


### 3. 加载失败 {#3}
![](img/s3.png)

**`重试`**，和操作UI上的 **重新载入** 一样的作用

覆盖在当前的视频上，有一层蒙版降低视频的透明度

[回到列表](#top)


### 4. 缓冲中 {#4}
![](img/s4.png)

加载中字样上面的图标，是动的，表示在加载中

覆盖在当前的视频上，有一层蒙版降低视频的透明度

[回到列表](#top)


### 5. 暂停中 {#5}
![](img/s5.png)

覆盖在当前的视频上，有一层蒙版降低视频的透明度

[回到列表](#top)


### 6. 直播结束 {#8}
![](img/s8.png)

**`关注主播`**，作用和房间信息里的 **关注主播**，一样

点击后，变成 **`已关注`**

红色标记部分为 [推荐信息](recommend.md) 功能，显示逻辑在该功能内部描述

[回到列表](#top)


### 7. 预告 {#9}
![](img/s9.png)

#### 预告：在 [运营后台]() 去设置的公告内容，用于预告下次直播的时间

**`关注主播`**，作用和房间信息里的 **关注主播**，一样

点击后，变成 **`已关注`**

红色标记部分为 [推荐信息](recommend.md) 功能，显示逻辑在该功能内部描述

[回到列表](#top)
