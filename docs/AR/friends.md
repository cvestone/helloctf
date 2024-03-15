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
    ### [IpTIME C200 BackdoorRCE(CVE-2021-26614)](http://122.112.221.240/index.php/207/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-14

    漏洞简介CVE-2021-26614 ipTIME C200摄像头存在后门，可以造成rce，当时还是属于1day状态poc：跟随https://www.iotsec-zone.com/article/135的思路进行1day的分析看看补丁比对分析比对漏洞补丁c200_1_058.bin与c200_1_060.bin各自的iux_get.cgi，...
    ### [Netgear DGN1000 RCE](http://122.112.221.240/index.php/136/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-13

    前言声明：技术讨论仅限合法用途，不要用于从事相关违法行为，否则行为后果与本人无关实际上这里需要两枚漏洞才能达成rce效果，一枚是带有鉴权的rce，另一枚则是绕过鉴权而且这还是mirai变种比较青睐的一个漏洞漏洞详情带鉴权RCEpoc注意仅仅在英语的页面有这个syscmd.htmhttp://114.51.41.91/syscm...
    ### [Pspray: Timing Side-Channel based Linux Kernel Heap Exploitation Technique](http://122.112.221.240/index.php/110/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-13

    虽然研究方向目前不是这个，但上个学期因为课程缘故，精读完这篇顶会论文以后，不禁赞叹，韩国那边的作者团队真的太细致了，对这一时序侧信道问题进行了如此精细的思考和测试，还提出了缓解方案，甚至基于未来应用该方案的考量，对其进行了性能测试。无论是不是做相关领域的事情，都要有这种探究精神👍很棒很棒但在反复思考的过程中，发现了缓解方案仍然可以被绕过💀，当时放在课程报告里面了，刚刚想起来，感觉还是搬出来...
    ### [密码保护：混音课程笔记](https://www.su-cvestone.cn/308/)  
    >by [cvestone](https://www.su-cvestone.cn/), 2024-03-12

    无法提供摘要。这是一篇受保护的文章。...
    ### [ctfshow web做题记录](https://www.shark45.cn/2024/03/12/ctfshow-web%e5%81%9a%e9%a2%98%e8%ae%b0%e5%bd%95/)  
    >by [shark](https://www.shark45.cn/), 2024-03-12

    ①、查看源码，有一串令人在意的字符，查询后发现是base64编码，解一下就知道flag了②、很明显的sql注入这里说二种解法第一种：sql注入第一步： 万能密码，用1和1’判断是什么类型的注入。随后用or语句判断真假后面必须为真值再用#注释掉后面的内容。1′ or true #第二步：查字段数，先用order by语句1′ or true order b...
    ### [3.9本周小结](http://122.112.221.240/index.php/83/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-09

    更换科研的方向，实际上跟IOT安全有关系，好消息是不需要搞ai相关的东西了，而且不需要自己瞎搞了摸清楚了新的学期的事情，课程还是挺多的，打了两台靶机以后就去专攻科研了，而且有点奇怪，我的靶机环境有些是不能走通的，折腾了大半天，但别人却可以QwQ，为了保持一定的学习速度就没有细究了IOT安全看了三个漏洞，其实偏web的那些理解起来不难，很快的，就是工具实在难安装。。。我是说firmw...
    ### [Zyxel硬编码后门(CVE-2020-29583)](http://122.112.221.240/index.php/79/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-09

    漏洞详情Zyxel (CVE-2020-29583) 硬编码后门Username: zyfwpPassword: PrOw!aN_fXp概括Zyxel 发布了针对荷兰 EYE 研究人员最近报告的防火墙和 AP 控制器硬编码凭证漏洞的补丁。建议用户安装适用的固件更新以获得最佳保护。 漏洞是什么？在某些 Zyxel 防火墙和 AP 控制器的“zy...
    ### [浅谈CGI](http://122.112.221.240/index.php/68/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-09

    虽说目前的web服务基本上都是基于前后端解耦的各种框架进行开发，之前学head first servlet这本书的时候甚至看到作者当时（十年前）就说CGI技术已经比较落后了但是目前看到有好些物联网设备都是使用CGI技术的，所以可以了解一下，实际上跟servlet有一些相似之处。以网上现成的例子（https://blog.csdn.net/no_pao_spite/article/d...
    ### [密码保护：攻防艺术](https://www.su-cvestone.cn/260/)  
    >by [cvestone](https://www.su-cvestone.cn/), 2024-03-08

    无法提供摘要。这是一篇受保护的文章。...
    ### [D-Link DIR-823G命令注入（CVE-2021-43474）](http://122.112.221.240/index.php/13/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-08

    前言实际上goahead是个漏洞高发区，学习一下有很多好处只搞到了D-Link DIR-823G v1.02 B03没有搞到D-Link DIR-823G v1.02 B05的固件，不过大差不差漏洞详情固件解包惯例binwalk可以看到有个Squashfs文件系统，漏洞存在于web文件夹内：开放服务情况...
    ### [Hello world!](http://122.112.221.240/index.php/1/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-03-08

    Welcome to WordPress. This is your first post. Edit or delete it, then start writing!Hello world!最先出现在ba1100n。...
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
    ### [HTB gamepwn CubeMadness1&CubeMadness2](https://blog.csdn.net/qq_62172019/article/details/136107916)  
    >by [摸鱼的猫](https://blog.csdn.net/qq_62172019/), 2024-02-13

    HTB gamepwn CubeMadness1&CubeMadness2...

</div>
