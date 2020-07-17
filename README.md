# 介绍

长期从事数据分析(Data analysis)和机器学习(Machine learning)方面的工作。个人主页整理一些数据分析的项目和方法，同时提供优质的学习资源，欢迎交流。

**邮件**：`741080630@qq.com`

<table><tr><td bgcolor=Blue>近期要出Pandas速查工具，具体内容为Pandas各方法的使用技巧，由于Pandas官方文档许多方法展示不全面，因此整理这份资料，会附上demo供参考，预计一个月内发布。</td></tr></table>


## 1.疫情数据抓取

通过爬虫获取疫情的数据，最早可获取到1月份至今的数据。数据包括：

  1. 当日数据
  2. 历史数据(时间序列)<br>
  
数据地址：https://wp.m.163.com/163/page/news/virus_report/index.html<br>
代码地址：[基于网易疫情播报平台的数据采集](https://github.com/SalientView/covid_19-data-crawler)

基于疫情数据可以做地理可视化：<br>
<img src="https://imgkr.cn-bj.ufileos.com/930e0505-fd4c-41c1-9769-c72349df7978.png"  width="380" >


## 2.自动化数据分析脚本
+ 机器可以代替人工作吗？答案是不能100%，但或许80%是可以的。在数据分析时有些方法是通用的，适用于所有数据，不需要每次在分析时重新写。<br>
+ 因此在人分析前机器先把数据中的信息展现一遍，基于这个目的我先写了一个辅助分析工具，提升数据分析的效率，更快的获取数据结论。<br>
+ 最终的目的是全自动化的数据分析，目前只达到初级效果。<br>
+ 项目地址：[自动化数据分析](https://github.com/SalientView/Auto_analysis)

## 3.数据可视化配色

还在为作图的配色发愁？<br>
我整理示了python所有的自带调色板，这样可以很方便地查看每种配色的名称和效果.<br>
具体请下载pdf文件《[palette_all](https://github.com/SalientView/palette/blob/master/palette_all.pdf)》

<img src="https://imgkr.cn-bj.ufileos.com/b66a52c5-90f8-4dd6-972c-a7295ff13b64.png"  width="450" >


## 4.地图可视化

基于Pyecharts的地图可视化，包括世界地图、中国地图等，参考代码请移步：[地图可视化](https://github.com/SalientView/MapShow)<br>

<img src="https://imgkr.cn-bj.ufileos.com/d0eabd5c-154a-42dc-9bf9-e172aeb3a2a6.png"  width="800" >
<img src="https://imgkr.cn-bj.ufileos.com/69010da2-5e19-405c-b0b0-eaff97af7aef.png"  width="650" >
<img src="https://imgkr.cn-bj.ufileos.com/51d35116-82db-45e5-be06-88cd09f53945.png"  width="650" >


## 5.词云图看板

以红楼梦为例的中文词云图展示，其他文本数据也可适用，代码地址：[词云图](https://github.com/SalientView/wordcloud)


<img src="https://imgkr.cn-bj.ufileos.com/f026799f-03e6-495a-9daa-231d3e393499.png"  width="90%" >

<img src="https://imgkr.cn-bj.ufileos.com/221f531c-35b5-4862-bc53-42c8174dd333.png"  width="90%" >




## 6.用python下载YouTube视频、B站视频
不需要下载任何软件工具就可以下载YouTube视频，还支持国内视频网站例如B站等。

查看代码请移步[视频下载脚本](https://github.com/SalientView/YouTube_Download)。

效果如下：

![](https://imgkr.cn-bj.ufileos.com/1b196cd8-f753-4512-9e22-198d4df996cc.png)

![](https://imgkr.cn-bj.ufileos.com/1d35f8da-b759-4205-aa6a-cf4c9f87a6ad.png)


## 7.Linux学习

Linux懂的不多，才刚开始学习，以下是一些可以在线使用的工具或网站。

|	内容	|	地址	|
|	----	|	----	|	
|	命令解释	|	http://explainshell.com/|	
|	通过RPG游戏练习VIM使用|		http://vim-adventures.com/|	
|	练习软件快捷键|		http://shortcutfoo.com/|	
|	免费编程书籍	|	https://github.com/geekwolf/free-books|	
|	实时文本交互聊天|		http://collabedit.com/|	
|	在线编写运行分享C++代码编辑器|		http://cpp.sh/|	
|	浏览器运行虚拟机|		http://copy.sh/v24/|	
|	命令或记录网站|		http://commandlinefu.com/|	
|	Linux发行版的详细信息|		https://distrowatch.com/|	
|	在线查看命令帮助	|	http://linuxmanpages.com/|	
|	适用Linux环境的软件搜索引擎|		http://awesomecow.com/|	
|	Linux好玩游戏合集|		http://penguspy.com/|	
|	在线查看内核代码及不同版本的差异|		http://lxr.free-electrons.com/|	


## 8.SQL学习

本资源以MySQL为目标，因为MySQL方面的文章已经有前人整理的非常到位，直接拿来用即可，不需要自己在重新整理，学习资源如下：

|	内容	|	地址	|
|	----	|	----	|	
|配置环境|https://www.jianshu.com/p/edca5142391c|
|测试题|https://zhuanlan.zhihu.com/p/53302593|
|在线写SQL|https://sqlzoo.net/<br>https://sqlbolt.com/<br>http://xuesql.cn/<br>http://sqlfiddle.com/<br>https://leetcode-cn.com/|
|关于SQL语句的执行顺序|https://zhuanlan.zhihu.com/p/48048479<br>https://www.cnblogs.com/yyjie/p/7788428.html<br>https://zhuanlan.zhihu.com/p/63299573|

## 9.北大课程资料整理

学习爱好者们搜集了许多大学的课程资料，具体请移步：[北大课程资料](https://github.com/SalientView/libpku)


