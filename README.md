## 前言

本系列文章旨在从零开始学习游戏辅助的工作流程和开发方法，了解游戏背后的攻防对抗手段，重点侧重数据和call的追踪查找。

侧重方向在于学习整个分析过程以及思路方法，最终实现的效果和游戏不是关心的重点。

涉及到的技术有：

- windows API Hook
- dll注入
- 汇编语言
- Windows编程
- C/C++基础

没有上述的前置知识建议劝退

## 游戏选择与环境搭建

这里用来进行分析的游戏是口袋西游，链接如下：

链接：https://pan.baidu.com/s/1nXUoK8UUEI3t3-hgAQ5pBg 
提取码：e57t 
复制这段内容后打开百度网盘手机App，操作更方便哦

下载以后直接解压缩，element文件夹中的ELEMENTCLIENT.EXE就是口袋西游主程序

选择这个游戏的好处在于，这个游戏是老版本的口袋西游，不会一直更新，难度也非常适合新手，方便进行调试学习。

在正式开始逆向之前建议先玩一段时间，熟悉一下游戏，后续操作起来会比较方便

## 交流群

 点击链接加入群聊【鬼手PC逆向交流2群】：https://jq.qq.com/?_wv=1027&k=5LnbOvc 

群号码：1017057661