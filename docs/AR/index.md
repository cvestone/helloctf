---
comments: true

---
# OurCtfer
## List
- [antigone｜蒟蒻CTFer CUIT驾校在读 逆向苦手](https://antigone4224.github.io)
- [cvestone｜风之子 pwn大学在读小学生](https://www.su-cvestone.cn/)
- [shark｜鲨鱼辣椒](https://www.shark45.cn)
- [Lobok｜是否有个我们完成了缘分](http://dis4.cn)
- [摸鱼的猫｜酷爱摸鱼&正在准备考研的ctfer](https://blog.csdn.net/qq_62172019/)
- [HeYuMeng｜萌瓜学习记](http://www.heyumeng.online/)
- [q1@N9｜学习笔记、成长小结and比赛wp](https://qsheep24.wordpress.com)

## Recent Post
### [231216WargamesMY CTF](https://www.su-cvestone.cn/144/)  
>by [cvestone](https://www.su-cvestone.cn/), 2024-01-19

pwn Magic Door 考察点： （1）查看程序保护 开了nx保护，利用shellcode困难，且是amd64 （2）查看程 ......
### [hexo+githubpage搭建并添加博客RSS](https://www.su-cvestone.cn/135/)  
>by [cvestone](https://www.su-cvestone.cn/), 2024-01-17

非原创，由各个博客综合提取，主要为了查找方便，感谢这些bloggers提供的珍贵参考材料 安装必要环境 node 下载对应操作系统 ......
### [wordpress报道篇](https://qsheep24.wordpress.com/2024/01/17/wordpress%e6%8a%a5%e9%81%93%e7%af%87/)  
>by [q1@N9](https://qsheep24.wordpress.com), 2024-01-17

cppu在读本科小白，，hello world以后也会坚持完善个人blog...
### [如何爆破呢](http://www.heyumeng.online/index.php/157/)  
>by [HeYuMeng](http://www.heyumeng.online/), 2024-01-16

CTFshow WEB入门爆破web21这里第一题，我们看到需要输入账号密码登录，打开burp抓个包看看，输入账号密码后，在抓包历史中我找到了验证包，看到了什么，看到了==，应该是base64编码，去md5在线查了可以猜出来账号密码中间用分号隔开，然后利用bp，自定义迭代，载入字典，开始跑就行了正确的编码显而易见，把最后一串编码解密就得到了账号密码，然后回去输入账号密码就可以看到flag了，...
### [HTB_machines](https://www.su-cvestone.cn/128/)  
>by [cvestone](https://www.su-cvestone.cn/), 2024-01-15

PivotAPI “红队笔记”学习记录 信息搜集 nmap tcp详细扫描结果： sudo nmap -sT -sV -sC -O ......
### [offsec PG lab](https://www.su-cvestone.cn/125/)  
>by [cvestone](https://www.su-cvestone.cn/), 2024-01-14

简单 PlanetExpress 端口扫描 可知目标web服务用了Pico CMS系统，优先看web服务 暂时没找到可利用点，尝试 ......
### [世界，您好！](https://www.shark45.cn/2024/01/11/hello-world/)  
>by [shark](https://www.shark45.cn), 2024-01-11

欢迎使用 WordPress。这是您的第一篇文章。编辑或删除它，然后开始写作吧！...
### [安全开发实验室](https://www.su-cvestone.cn/88/)  
>by [cvestone](https://www.su-cvestone.cn/), 2024-01-05

每天一安全开发，脚本小子远离我~ 本实验室专门分析一些安全工具的代码，知其然知其所以然，持续更新......
### [计算机等级备考心得](http://www.heyumeng.online/index.php/80/)  
>by [HeYuMeng](http://www.heyumeng.online/), 2024-01-03

自动化专业计算机二级WPS已过，计算机三级网络技术已过，计算机四级网络工程师已过。同学L：计算机在日常生活中无处不在，涉及各个方面的领域，在学习计算机二级后可以学到很多技能知识应用到各个方面，解决很多问题，在备考时我经常在b站搜索教程便于我更好的理解和掌握他的使用方法，我考的是二级wps office，当然他可供九种选择，wps是我认为简单且实用的其中之一，做题过程中首先要仔细阅读弄清基本...
### [HTB_ctf](https://www.su-cvestone.cn/76/)  
>by [cvestone](https://www.su-cvestone.cn/), 2024-01-01

Hardware Debugging Interface 考察点 SALEAE Logic分析器的异步串行解码操作 描述 We a ......
### [Pingctf2023 Dangleme 复现](https://antigone4224.github.io/PingCTF2023-dangleme-%E5%A4%8D%E7%8E%B0)  
>by [antigone](https://antigone4224.github.io), 2023-12-29

复现:Pingctf 2023 dangleme环境搭建用官方wp在本地发现打不通，只能试着去复现官方题目的环境，下载文件查看dockerfile后发现，他们使用了redpwnjail搭建题目环境,FAQ里有如何更改dockerfile辅助调试的方法,其实也就是撤销将环境迁移进jail的过程，然后再安装一些调试所需要的工具，python3环境，gdb，pwntools，pwndbg这些...
### [ctfshow](https://www.su-cvestone.cn/30/)  
>by [cvestone](https://www.su-cvestone.cn/), 2023-12-27

菜狗杯 misc 损坏的压缩包 考察点：文件不符改后缀 先丢到binwalk分析，发现是由png和zlib文件组成的，再丢到win ......
### [你想有多pwn(入门第二章)](https://www.su-cvestone.cn/25/)  
>by [cvestone](https://www.su-cvestone.cn/), 2023-12-27

--b站up主"国资社畜"《你想有多pwn》学习记录与补充 0x00 提升pwn体验 pwndbg插件 (待续，pwndbg调试时 ......
### [你想有多pwn(入门第一章)](https://www.su-cvestone.cn/20/)  
>by [cvestone](https://www.su-cvestone.cn/), 2023-12-27

--b站up主"国资社畜“《你想有多pwn》学习记录与补充 0x00 前言 qaq真的很感谢这个up主提供的pwn入门课程，对pw ......
### [CTFweb信息搜集篇](http://www.heyumeng.online/index.php/7/)  
>by [HeYuMeng](http://www.heyumeng.online/), 2023-12-13

在CTFshow平台刷了web入门的信息搜集篇的题目，对这篇内容做个总结。查看网页源代码鼠标右击会看到”查看源代码可以使用快捷Ctrl+U来查看源码Q在地址栏前面加上view-source，如view-source: https://www.baidu.com;浏览器的设置菜单框中，找到“更多工具”，然后再找开发者工具，也可以查看网页源代码通过bu...
### [你好！](http://www.heyumeng.online/index.php/1/)  
>by [HeYuMeng](http://www.heyumeng.online/), 2023-12-13

欢迎来到我的博客！...
### [Yet Another Sample Page](https://antigone4224.github.io/Yet-Another-Sample-Page)  
>by [antigone](https://antigone4224.github.io), 2018-01-06

Text can be bold, italic, strikethrough or keyword.Link to another page.There should be whitespace between paragraphs.There should be whitespace between paragraphs. We recommend including a READ...
### [Sample Page](https://antigone4224.github.io/Sample-Page)  
>by [antigone](https://antigone4224.github.io), 2017-12-12

Text can be bold, italic, strikethrough or keyword.Link to another page.There should be whitespace between paragraphs.There should be whitespace between paragraphs. We recommend including a READ...
### [One More Sample Page](https://antigone4224.github.io/One-More-Sample-Page)  
>by [antigone](https://antigone4224.github.io), 2017-12-11

Text can be bold, italic, strikethrough or keyword.Link to another page.There should be whitespace between paragraphs.There should be whitespace between paragraphs. We recommend including a READ...
### [Another Sample Page](https://antigone4224.github.io/Another-Sample-Page)  
>by [antigone](https://antigone4224.github.io), 2017-12-10

Text can be bold, italic, strikethrough or keyword.Link to another page.There should be whitespace between paragraphs.There should be whitespace between paragraphs. We recommend including a READ...
