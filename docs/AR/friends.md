---
isarchive: true
comments: true
glightbox: false
hide:
  - footer
  - toc
  - edit
  - view
---

<div class="grid" style="display: grid;grid-template-columns: 32% 33% 32%;" markdown>

<div class="grid cards" style="display: grid; grid-template-columns: 1fr;" markdown>

-   :material-archive-plus:{ .lg .middle } __最近归档__

    ---

    待更新ww


-   :material-archive-star:{ .lg .middle } __完整归档__

    ---

    待更新ww



</div>

<div class="grid cards" markdown>

-   :material-star-face:{ .lg .middle } __社区推荐__

    ---

    待更新ww


</div>

<div class="grid cards" markdown>

-   :material-account-group:{ .lg .middle } __战队招新__

    ---

    待更新ww


</div>

</div>

<div class="grid cards" markdown>

-   :octicons-people-24:{ .lg .middle } __师傅们__

    ---
    - [cvestone｜风之子 pwn大学在读小学生](https://www.su-cvestone.cn/)
    - [antigone｜蒟蒻CTFer CUIT驾校在读 逆向苦手](https://antigone4224.github.io/)
    - [shark｜鲨鱼辣椒](https://www.shark45.cn/)
    - [Lobok｜是否有个我们完成了缘分](http://dis4.cn/)
    - [摸鱼的猫｜酷爱摸鱼&正在准备考研的ctfer](https://blog.csdn.net/qq_62172019/)
    - [HeYuMeng｜假装看不见，余光千万遍](http://www.heyumeng.online/)
    - [q1@N9｜学习笔记、成长小结and比赛wp](https://qsheep24.wordpress.com)
    - [ba1100n｜ba1100n的学习随笔](http://www.ba1100n.tech)
    - [Lobok｜萝卜的部落格](https://dis4.cn)

</div>
<div class="grid cards" markdown>

-   :fontawesome-solid-blog:{ .lg .middle } __最近更新__

    ---
    ### [4.7本周小结](http://ba1100n.tech/index.php/331/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-04-07

    继续刚仿真环境修复。周一周二感觉有点混乱不知道怎么办好，尝试安装qiling框架，结果发现坑是真的多，比如IDA>=7.5的话，必须安装1.4.5的qiling而不是pip默认最新的1.4.6，以及qilingIDA插件的一些代码问题需要被手动修复。而且qiling的continue似乎有些小问题，下断点也会被无视掉，最好excute till。但是好在最后还是学会如何使用IDA的qiling插件...
    ### [3.31本周小结](http://ba1100n.tech/index.php/325/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-31

    这周前两天半其实一直在干活，在思考某件东西怎么改进优化，导致没有怎么复现漏洞什么的，周三下午上课的时候很认真地看完了一个内存漏洞的前因后果，然后后面逆向了主要的数据的流程，但发现目前自己还是在动态调试上太生疏了QwQ，后面回家了一下，所以这两天又没有学习。实际上最近确实研究了两个mips内存破坏方面的漏洞，但都没有来的及彻底搞清楚,虽然确实梳理出来了漏洞点前后的相关功能，也因为曾经的学习能...
    ### [3.24本周小结](http://ba1100n.tech/index.php/315/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-24

    这周其实很低效率，很想很想复现点不一样的东西，结果就是，周一周二课比较多，而且都是不能偷学东西的课，但晚上没有珍惜时间，周一晚上玩RON刷S去了，（这游戏通关简单，但刷S是真的折磨）周二吃完饭甚至忍不住在宿舍玩了两小时才去工位（这byd游戏刷S是真的折磨）。。。那天晚上学习了MIPS的堆栈、寄存器之类的东西，为复现MIPS上的漏洞做准备，以及因为要配iot仿真环境，所以学习了一波LD_PR...
    ### [工控协议漏挖入门之初尝boofuzz与电线鲨鱼抓包分析Modbus](http://ba1100n.tech/index.php/267/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-21

    0x00 前言并非有意开新坑的，但是其实昨天上课学到了一下下，然后四节课里面塞了那么多东西感觉云里雾里的，所以想趁着还没忘记赶紧总结一下，以供日后不时之需，其实学习到的这方面的东西尚且非常浅薄。。。还请海涵而且听说工控的溢出漏洞其实很难转化成RCE，因为缺少很多库函数，但是，也恰恰是因为这是工控，如果存在远程的dos漏洞，就足以形成损失了，所以还请不要在fofa乱测试，如果真的伤及...
    ### [LD_PRELOAD与linux木马的一种隐匿方法](http://ba1100n.tech/index.php/257/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-20

    LD_PRELOADLinux ELF 共享库加载顺序LD_PRELOAD -> /etc/ld.so.preload -> DT_RPATH(编译指定) -> LD_LIBRARY_PATH -> [/etc/ld.so.conf] -> /lib -> /usr/lib什么是LD_PRELOAD(Load Preload，加载的预加载)正常情况下...
    ### [3.17 本周小结](http://ba1100n.tech/index.php/222/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-17

    这样公布学习进展的方式对我来说是某一种监督，接受透明的监督让我觉得后背发凉，但同时也让我反思了不少上周进展的问题这周算是对漏洞复现开了个头，但其实以老师的任务为重，然后把工位的电脑什么的搞好了，感觉在那边学习其实可以学得很快，椅子和空气都舒服多了而且周日到周四上午的进展还是比较快的，课堂上见缝插针地去学习老师、自己的东西，然后课下完成老师的任务以后开始自己的学习，那几天晚上还搞到很...
    ### [IpTIME C200 BackdoorRCE(CVE-2021-26614)](http://ba1100n.tech/index.php/207/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-14

    漏洞简介CVE-2021-26614 ipTIME C200摄像头存在后门，可以造成rce，当时还是属于1day状态poc：跟随https://www.iotsec-zone.com/article/135的思路进行1day的分析看看补丁比对分析比对漏洞补丁c200_1_058.bin与c200_1_060.bin各自的iux_get.cgi，...
    ### [Netgear DGN1000 RCE](http://ba1100n.tech/index.php/136/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-13

    前言声明：技术讨论仅限合法用途，不要用于从事相关违法行为，否则行为后果与本人无关实际上这里需要两枚漏洞才能达成rce效果，一枚是带有鉴权的rce，另一枚则是绕过鉴权而且这还是mirai变种比较青睐的一个漏洞漏洞详情带鉴权RCEpoc注意仅仅在英语的页面有这个syscmd.htmhttp://114.51.41.91/syscm...
    ### [Pspray: Timing Side-Channel based Linux Kernel Heap Exploitation Technique](http://ba1100n.tech/index.php/110/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-13

    虽然研究方向目前不是这个，但上个学期因为课程缘故，精读完这篇顶会论文以后，不禁赞叹，韩国那边的作者团队真的太细致了，对这一时序侧信道问题进行了如此精细的思考和测试，还提出了缓解方案，甚至基于未来应用该方案的考量，对其进行了性能测试。无论是不是做相关领域的事情，都要有这种探究精神👍很棒很棒但在反复思考的过程中，发现了缓解方案仍然可以被绕过💀，当时放在课程报告里面了，刚刚想起来，感觉还是搬出来...
    ### [密码保护：混音课程笔记](https://www.su-cvestone.cn/308/)  
    >by [cvestone](https://www.su-cvestone.cn/), 2024-03-12

    无法提供摘要。这是一篇受保护的文章。...
    ### [3.9本周小结](http://ba1100n.tech/index.php/83/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-09

    更换科研的方向，实际上跟IOT安全有关系，好消息是不需要搞ai相关的东西了，而且不需要自己瞎搞了摸清楚了新的学期的事情，课程还是挺多的，打了两台靶机以后就去专攻科研了，而且有点奇怪，我的靶机环境有些是不能走通的，折腾了大半天，但别人却可以QwQ，为了保持一定的学习速度就没有细究了IOT安全看了三个漏洞，其实偏web的那些理解起来不难，很快的，就是工具实在难安装。。。我是说firmw...
    ### [密码保护：攻防艺术](https://www.su-cvestone.cn/260/)  
    >by [cvestone](https://www.su-cvestone.cn/), 2024-03-08

    无法提供摘要。这是一篇受保护的文章。...
    ### [xnuca2020-babyV8](https://blog.csdn.net/qq_62172019/article/details/136332456)  
    >by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-02-27

    xnuca2020-babyV8...
    ### [*ctf 2019 oob](https://blog.csdn.net/qq_62172019/article/details/136294799)  
    >by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-02-26

    *ctf 2019 oob...
    ### [HTB pwn Dragon Army](https://blog.csdn.net/qq_62172019/article/details/136264417)  
    >by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-02-23

    HTB pwn Dragon Army...
    ### [HTB pwn Bad grades&Restaurant](https://blog.csdn.net/qq_62172019/article/details/136181222)  
    >by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-02-19

    HTB pwn Bad grades&Restaurant...
    ### [CTFwebSSRF篇](http://www.heyumeng.online/index.php/181/)  
    >by [HeYuMeng](http://www.heyumeng.online/), 2024-02-16

    CTFshow WEB入门SSRF服务端请求伪造web351url=http:/127.0.0.1/flag.phpweb352url=http://127.0.0.2/flag.phpweb353url=http://2130706433/flag.phpurl=http://0x7f.0.0.1/flag.phpurl=http://0/flag.phpurl=htt...
    ### [CTFwebXSS篇](http://www.heyumeng.online/index.php/176/)  
    >by [HeYuMeng](http://www.heyumeng.online/), 2024-02-16

    CTFshow WEB入门XSS跨站脚本攻击XSS漏洞通常分为三种类型：反射型XSS、存储型XSS、DOM-Based XSSweb316题目如图所示，使用经典语句<script>alert(1)</script>测试成功，在攻击服务器准备一个文件接收cookie，get.php<?php$cookie=$_GET['c'];$myfile=fopen("cookie.txt","w...
    ### [HTB pwn Evil Corp](https://blog.csdn.net/qq_62172019/article/details/136121775)  
    >by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-02-15

    HTB pwn Evil Corp...
    ### [HTB gamepwn LightningFast](https://blog.csdn.net/qq_62172019/article/details/136114870)  
    >by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-02-14

    HTB game LightningFast...

</div>
