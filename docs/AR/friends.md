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
### [house of cat](https://blog.csdn.net/qq_62172019/article/details/136090514)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-02-10

其中rax, qword ptr [rdi + 0xa0] rax会被赋值为wide_data结构体的地址(rdi是我们伪造的io结构体地址)mov    rax, qword ptr [rax + 0xe0] rax被赋值为指向wide_data结构体+0xe0的地址。在_IO_switch_to_wget_mode 函数可以进行一次任意执行。最后可以进入_IO_switch_to_wget_m...
### [l3hctf2024 pwn treasure_hunter](https://blog.csdn.net/qq_62172019/article/details/136064207)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-02-06

可以看到上面的大块可以覆盖到0x20小块的数据区,正好这个小块存放着hashmap的pairs指针我们只需要覆盖其低地址并且在可控制的块伪造pairs和修改一些关键字符(dream操作)就可以完成伪造,伪造之后就可以实现将任意的key放在hashmap中从而实现任意读任意写。我刚才提到了" 修改关键字符 ",如上图在hashmap每插入一对pair的时候都会产生一个字符用于标识key,所以我们只需...
### [dicectf2024 pwn](https://blog.csdn.net/qq_62172019/article/details/136030402)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-02-04

strtok函数在分割字符串的时候会将delim置为\x00这将导致前面的字符串在分割的时候把后面的堆块size某些字节置为\x00,因此可以利用这个漏洞打off by null。打完off by null向前合并之后就简单了直接控制tache块申请到free_hook直接改写就行。主办方虽然没有给libc但是给了题目所使用的dockerfile。本题使用的是Ubuntu18。查看函数,此处调用了...
### [pwn-college kernel l1](https://blog.csdn.net/qq_62172019/article/details/135920197)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-01-29

模块在初始化的时候就已经将flag读出来了所以本题并不需要提权。read函数从用户空间读入一串字符作为password进行比较。write函数下,如果read函数比较正确就返回flag。...
### [THM](https://www.su-cvestone.cn/153/)  
>by [cvestone](https://www.su-cvestone.cn/), 2024-01-26

The Cod Caper 介绍 Hello there my name is Pingu. I've come here to  ......
### [春秋杯2024 house of some](https://blog.csdn.net/qq_62172019/article/details/135875602)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-01-26

fopen函数会在打开设备以后会在_IO_list_all_插入新的IO结构,这一点在后面会用到。在菜单函数这里显然有一个未初始化的变量v4由于getint使用了scanf,"%lld"接收数据在遇到’-'时不会覆盖栈上的数据又由于下面会打印出栈上的值存在一个泄露问题。第一次利用写在114514上面写入新的任意读fake_io1和fake_io2,同时这个fake_io1的chain成员应该是一个...
### [mapnactf2024 pwn ninipwn&protector](https://blog.csdn.net/qq_62172019/article/details/135790635)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-01-23

tips:之所以两个不一起泄露是因为在调试的过程中两个一起泄露需要10个字节刚好覆盖了text_len会导致后面的加密函数越界使得程序崩溃，故分开泄露。先溢出泄露库地址然后将剩下的语句写到bss段上面,然后栈转移,接着调用mprotect函数将bss段改为可执行,最后跳到shellcode处读flag。2.通过格式化字符串泄露程序加载地址最后将win函数的加载地址覆盖回返回地址。开启了沙箱根据其提...
### [mapnactf2024 pwn buggypaint](https://blog.csdn.net/qq_62172019/article/details/135749706)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-01-22

现在申请一次context为0x40的块(称为a块) 这样的话a块就可以控制paint结构体,也就间接控制了一个paint结构体。用任意写将链表的数量改大方便块进入unsortedbin内,然后任意读泄露库的地址。题目所给库版本是2.35存在tache机制,依据tache后进先出的机制,可以先申请一个context大小为0x40的块和三块context超过0x70大小的块(方便待会泄露libc基址...
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
### [N1CTF 2023 pwn_n1array](https://blog.csdn.net/qq_62172019/article/details/134084579)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-10-27

N1CTF2023 pwn_n1array...
### [N1CTF 2023 pwn_Pwnn1canary](https://blog.csdn.net/qq_62172019/article/details/134059794)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-10-26

N1CTF 2023 pwn_Pwnn1canary...
### [细究php反序列化漏洞](https://blog.csdn.net/qq_62172019/article/details/132939068)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-10-01

php反序列化小结...
### [HGAME 2023 new_fast_note](https://blog.csdn.net/qq_62172019/article/details/133359490)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-09-27

因为无编辑功能，所以无法绕过被释放堆块的key字段，要达成doublefree可以将申请多个堆块释放到fastbin上面构造成A->B->A完成利用。接下来就很简单了2.31 几个常用hook还在还可以利用。free函数下存在uaf。成功doublefree。成功getshell。...
### [2023羊城杯决赛 pwn](https://blog.csdn.net/qq_62172019/article/details/132943954)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-09-18

因为库版本是2.23没有对top块大小做检查所以可以正应了题目的名字(house of force)发现第一次申请一个巨大的块泄露地址，第二次可以申请小于0x30的堆块修改top块的大小。第三次申请把malloc_got拿出来写上system第四次申请就成功getshell。注意：直接覆盖成后门地址会因为对齐出问题所以应该跳过push命令以后。没有开pie 堆地址存在固定位置上可以使用unlink...
### [HGAME 2022 ezvm](https://blog.csdn.net/qq_62172019/article/details/132863029)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-09-13

结合刚才调试的操作码可以在原h的位置下写入断点判断加密方式。无pie可以轻松从寄存器找到相对应的加密数组和加密之后的数。断点下在switch就可以知道vm做了什么。既然flag是输入的所以一定有比较函数。在操作码15处有一个比较函数。知道了谁和谁比接下去就是动调。调试可得需要输入32个字母。无壳 放入ida分析。输入h * 32观察。可得加密为异或与移位。...
### [HZNUCTF 2023 final虽然他送了我玫瑰花](https://blog.csdn.net/qq_62172019/article/details/132743092)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-09-07

放入ida分析发现花指令。nop掉就能看到伪代码了。一共使用了五种加密算法。...
### [细究sql注入漏洞](https://blog.csdn.net/qq_62172019/article/details/132615048)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-09-07

它是一种专门用于定义、操作和管理关系型数据库的语言，广泛应用于各种数据库管理系统（DBMS）中，如MySQL、Oracle、SQL Server、PostgreSQL等。虽然各个数据库管理软件遵循sql标准但是相对来讲各个数据库管理软件是作为sql的超集也就是说它们有自己独特的功能。SQL允许用户通过使用预定义的命令和语法来执行各种数据库操作，包括创建、修改和删除数据库、创建和修改表格、插入、更新...
### [ciscn 2019 game](https://blog.csdn.net/qq_62172019/article/details/132182474)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-08-09

漏洞点出在移动功能上面未检查移动前后的坐标导致了越界赋值行为，所以这是一个任意字节写功能。使用这个任意写我们可以修改堆块的大小造成堆块重叠结合tcahe任意地址申请向free_hook写入setcontext+53。最后构造堆块完成利用。开启了沙箱 ，注意了原本这个函数调用了prctl函数进行反调试所以要将这个调用nop掉才能进行调试。有地图创建，人物创建，人物删除，打印人物信息，以及上下左右移动...
### [*ctf 2023 drop](https://blog.csdn.net/qq_62172019/article/details/132129032)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-08-06

*ctf 2023 drop...
### [*ctf 2023 fcalc](https://blog.csdn.net/qq_62172019/article/details/132125319)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-08-05

*ctf 2023 fcalc...
### [*CTF 2022 pwn examination](https://blog.csdn.net/qq_62172019/article/details/132053684)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-08-01

[*CTF 2022]examination...
### [HZNUCTF 2023 final easy_rw](https://blog.csdn.net/qq_62172019/article/details/131943694)  
>by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2023-07-26

[HZNUCTF 2023 final]easy_rw...
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
