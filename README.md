# 问题集1
第一课时问题整理
1. github是什么 <br/> 
  设计开发软件的平台 IT技术人员的社交网站
2. git是什么<br/>  
  版本控制系统
3. 学习github的5个理由<br/> 
    a.最新的最前沿的技术 软件的初始状态 中间状态 发布 跟上技术更新 每年的年度报告<br/> 
    b.学到开发的技术 编码规范 状态更新<br/> 
    c.记录技术发展<br/> 
    d.提高项目经验 工作机会 <br/> 
    e.托管文档教程 课程开发 丰富的学习资料仓库

4. github的优势<br/> 
    a.只支持git<br/> 
    b.完整协议支持<br/> 
    c.在线文件编辑<br/> 
    d.社交网络元素<br/> 
    e.特色工作模式<br/> 
    f.私有仓库托管<br/> 
    g.通过Ruby on Rails构架

5. 通过github年度报告让你记忆最深刻的信息有哪些<br/> 
	a.最热门的技术<br/> 
	b.最热门的语言<br/> 
	c.决定着我们的学习方向

6. github上有可以个人账号 还可以有（企业 ）账号
7. github上面的两个组成要素是什么<br/>  
   人/组织和仓库/项目
8. github上两个重要页面<br/>   
   个人主页 ，创建仓库
9. 主页菜单都包含什么<br/>  
   概览 仓库 收藏 关注者 关注
10. 仓库的心跳线代表什么<br/> 
    一年内是否活跃 
11. star的作用是？<br/> 
    收藏
12. fork的作用是？<br/> 
    拷贝别人的项目
13. watch的作用是？<br/> 
    关注作者更新
14. 搜索结果分别有哪些类别<br/> 
    存储库，代码，提交，问题，维基，用户
15. 你在github上挖到什么宝<br/> 

# 问题集2
第二课时问题整理
1. 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？<br/> 
   新存储库   创建一个新的存储库<br/> 
   导入存储库  从其他版本控制系统导入所有文件，包括修订历史记录。<br/> 
   新组织  注册我的新团队<br/> 
   新代码  
2. 如何能将仓库中的html文件直接解析成页面？<br/> 
   点击创建的仓库，建立一个新文件，按照HTML格式编写，点击settings，找到gtihub pages 把none改成master branch
3. 如何删除仓库<br/> 
   点击setting 然后找到Delete this repository 
4. Bash是什么操作系统的命令<br/> 
   linux命令
5. Pwd是什么命令<br/> 
   print working directory
6. Cd是什么命令<br/> 
   改变目录 change directory
7. Echo是什么命令<br/> 
   在命令行打印信息
8. 配置git用户名的命令<br/> 
   git config --global user.name "Your Name"
9. 配置邮箱的命令<br/> 
   git config --global user.email "you@example.com"
10. 命令行换行方式<br/> 
   echo \
11. 命令行终结方式<br/> 
   Ctrl+c
12. 使用命令行比GUI方式有何优势<br/> 
    命令行优势：一次可建多个文件夹，复杂操作可以批处理
13. 提交到本地仓库时为什么有暂存区<br/> 
    在暂存区缓一下，如果有问题就直接在暂存区解决
14. 新建代码仓库的命令<br/> 
    $ git init
15. git clone [url] 这个命令的作用是<br/> 
    克隆仓库
16. 添加指定文件到暂存区的命令<br/> 
    $ git add
17. 删除工作区文件，并且将这次删除放入暂存区的命令<br/> 
    $ git rm
18. 改名文件，并且将这个改名文件放入暂存区的命令<br/> 
    $ git mv
19. 提交暂存区到仓库的命令<br/> 
    $ git commit -m
20. 直接从工作区提交到仓库的命令<br/> 
    $ git commit -a -m
21. 显示变更信息的命令<br/> 
    $ git status
22. 查看历史信息的命令<br/> 
    $ git log
23. Commit的意义是<br/> 
    提交
24. Pull的意义是<br/> 
    把远程仓库的代码放到本地
25. Push的意义是<br/> 
    把本地放到远程 
# 问题集3
第三课时问题整理
1. MarKDown是什么？<br/> 
   Markdown是一种轻量级标记语言
2. MarKDown的特点？<br/> 
   纯文本内容，兼容所有的文本编辑器与字处理软件 <br/> 
   可以放到版本管理系统中，追踪历史变更<br/> 
   轻松的导出HTML、PDF和本身的.md文件<br/> 
   简介、高效、可读、直观、学习成本低<br/> 
   专注你的文字内容而不是排版样式，安心写作
3. MarKDown的用途？<br/> 
   IT人士：写日志、技术文稿、记录代码片段、撰写文档<br/> 
   科研人员/学生：撰写科技论文、记笔记<br/> 
   求职者：制作求职简历
4. MarKDown编写工具<br/> 
   百度脑图 有道云笔记 Github
5. MarKDown的区块元素和区段元素分别包含哪些？<br/> 
   标题：<br/> 
     一级标题#
     二级标题## 加空格<br/> 
   文字修饰：<br/> 
     **客户端** 加粗
     *客户端* 斜体
     两个空格是换行<br/> 
   插如图片：<br/> 
     ![名字]（图片网络URL地址）插入图片<br/> 
   有序列表：<br/> 
     1.空格 2.空格<br/> 
   无序列表：<br/> 
  - 空格或者 +空格<br/> 
   链接：<br/> 
     url链接：<http://www.baidu.com><br/> 
     文字链接：[百度首页](http://www/baidu.com)<br/> 
# 问题集4
第四课时问题整理<br/> 
**一、设计基础**<br/> 
1. 什么是设计？<br/> 
有目的地策划
2. 哪些属于设计范畴：<br/> 
平面设计、软件设计、工业设计、概念设计、产品设计
3. 用户界面（UI）设计是什么？<br/> 
界面设计即针对电子产品界面的设计，是一个复杂的有不同学科参与的工程，认知心理学。设计学。语言学等在此都扮演着重要的角色
4. 界面设计三大原则<br/> 
置界面于用户的控制之下；减少用户的记忆负担；保持界面的一致性
5. 用户界面设计的组成部分<br/> 
结构设计（概念设计）、交互设计、视觉设计
6. 结构设计的分类<br/> 
网页结构设计、系统结构设计
7. 什么是交互设计<br/> 
目的是使产品让用户能简单实用。
8. 用户界面（UI）设计工作流程<br/> 
需求调研、模块分析、结构设计、交互设计、视觉设计、界面级源代码、维护和测试
9. 用户界面（UI）设计的发展方向<br/> 
系统架构师、交互设计师、视觉设计师、测试工程师<br/> 
**二、UI设计常识** <br/> 
1. UI是哪两个单词的简称<br/> 
User Interface
2. 什么是VI系统<br/> 
企业视觉识别系统，是企业文化宣传的重要组成部分。企业用于在各种急速膨胀的媒体、多种的传播途径，大量繁杂的信息中凸显个性和身份，用以区别其他企业的视觉方面的识别系统
3. VI设计原则包括？<br/> 
同一性、差异性、文化性、有效性
4. VI系统包含哪两部分<br/> 
基本要素系统、应用系统
5. 对于logo的合法的两种更改<br/> 
logo和文字的组合等比例缩放，logo和文字的组合反白
6. 色彩模式有哪两种<br/> 
RGB模式：适用于显示器、投影仪、扫描仪、数码相机等。<br/> 
CMYK模式：适用于打印机、印刷机等。
7. 图片格式有哪两种？<br/> 
位图和矢量图
8. 两种图片格式的特点是？<br/> 
位图：不可无限放大，UI常用<br/> 
矢量图：可无损耗无限放大，印刷品常用
9. 两种图片格式分别常用的扩展名为？<br/> 
位图：.jpg、.gif、.png<br/> 
矢量图：.ai、.eps、.cdr
10. 可用性设计体现在哪三个方面<br/> 
内容布局、使用人性化、美观
11. 常用到的网络资源有<br/> 
图片、小图标、文字、代码、动画、音乐、其他
12. 客户交流时的注意事项<br/> 
你永远比客户专业<br/> 
永远要保持礼貌<br/> 
要让客户知道你做了哪些工作<br/> 
**三、UI设计流程**<br/> 
1. 前期需求阶段，UI设计所需要考虑的四个问题<br/> 
需求分析、栏目排版、色彩搭配、风格设计
2. UI设计在需求分析阶段需要注意的问题？<br/> 
网站制作目标、网站所处行业、网站包含内容、网站适用人群、其他
3. 在栏目排版时，首页内容通常包含哪些部分？<br/> 
主题栏、更新栏、指南栏、交流栏、广告栏
4. 色彩搭配时需要注意的问题<br/> 
有没有企业色，是否有行业默认颜色，搭配起来是否好看
5. 中期设计阶段需要做的工作有哪些？<br/> 
设计工具的选择、设计制作、布局方式、样式定义、交流沟通
6. 设计效果图时需注意的问题？<br/> 
尽量多用可循环较小的背景图，少用整张大图<br/> 
尽量多用填充色，少用图片<br/> 
尽量多用系统字体，少用特殊字体<br/> 
大面积使用的颜色尽量不超过3个色系<br/> 
7. 前端页面的设计中，html、css和javascript分别的作用是？<br/> 
HTML 定义静态网页、软件
css样式表，布局、字体、颜色、背景、其他效果
js动态交互

# 网页UI评价
聚美优品：颜色：紫色系，网站主要购买者是女性，所以选用粉色系为主色调<br/>
布局：主要部分放在浏览频率大的地方，导航栏清晰<br/>
交互性与易用性：两方面都很强，功能简单易懂，易于操作<br/>
信息可读性：主要以图片为主，更好的展现销售物品的特点，更加直观
风格：网站风格统一<br/>

新浪新闻：颜色：黑白色系，搭配其他颜色使用，更加凸显新闻的严肃性<br/>
布局：热点焦点新闻放在最显眼的位置<br/>
交互性与易用性：功能简单易懂，易于操作<br/>
信息可读性：主要以文字为主，文字的大小是突出重点内容的重要手段<br/>
风格：网站风格统一<br/>

途牛旅游：颜色：用大面积的照片作为背景，更容易凸显网站的功能<br/>
