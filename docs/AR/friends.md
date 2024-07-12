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
    - [Yukon｜醉后不知天在水，满船清梦压星河](https://yukon.icu)

</div>
<div class="grid cards" markdown>

-   :fontawesome-solid-blog:{ .lg .middle } __最近更新__

    ---
    ### [ctfshow刷题笔记](https://yukon.icu/2024/07/19/snote1/)  
    >by [Yukon](https://yukon.icu), 2024-07-19

    pwn141-(持续更新中…)pwn141Hint  : Use after free !12345678910111213141516171819202122232425262728293031323334353637383940414243444546unsigned int add_note(){  int v0; // esi  int i; // [esp+Ch] [ebp-1Ch]...
    ### [fuzzing原理探究(下)：boofuzz背后的生成算法](http://ba1100n.tech/binary_security/fuzzing%e5%8e%9f%e7%90%86%e6%8e%a2%e7%a9%b6%e4%b8%8b%ef%bc%9aboofuzz%e8%83%8c%e5%90%8e%e7%9a%84%e7%94%9f%e6%88%90%e7%ae%97%e6%b3%95/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-07-11

    那么，就来看看基于生成的boofuzz吧，虽然后面实现了持续生成的方案，但没有任何反馈调整变异机制，所以其实还 […]...
    ### [buuctf](https://www.su-cvestone.cn/465/)  
    >by [cvestone](https://www.su-cvestone.cn/), 2024-07-10

    Web [极客大挑战 2019]PHP 考察点：php原生反序列化bypass __wakeup() 先根据页面提示fuzz出网站 ......
    ### [实战式打靶随记](https://www.su-cvestone.cn/460/)  
    >by [cvestone](https://www.su-cvestone.cn/), 2024-07-08

    方法指导 记录什么 学习技术专题的要点； 成功调试或配置的命令； 找到的参考资料； 技术⼼得； 反思、复盘和整理 记录方式 要点式 ......
    ### [fuzzing原理浅析(上)：afl，afl++背后的变异算法](http://ba1100n.tech/binary_security/fuzzing%e5%8e%9f%e7%90%86%e6%b5%85%e6%9e%90%e4%b8%8a%ef%bc%9aafl%ef%bc%8cafl%e8%83%8c%e5%90%8e%e7%9a%84%e5%8f%98%e5%bc%82%e7%ae%97%e6%b3%95/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-07-08

    前言 对于防御者来说，现有的内存损坏和控制流劫持保护措施提供的保护并不完整。对于软件开发人员来说，手动代码分析 […]...
    ### [DUCTF2024复现-Sign-in](https://yukon.icu/2024/07/08/signin/)  
    >by [Yukon](https://yukon.icu), 2024-07-08

    DUCTF2024复现-Sign-inhttps://play.duc.tf/challengesno pie源码（就喜欢这种给源码的比赛）1234567891011121314151617181920212223242526272829303132333435363738394041424344454647484950515253545556575859606162636465666768697...
    ### [7.7本周小结](http://ba1100n.tech/after_meal/7-7%e6%9c%ac%e5%91%a8%e5%b0%8f%e7%bb%93/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-07-07

    这周回去帮表妹筛选志愿什么的，我发现，还是有很多人不知道有往年录取分数线表格这种东西可供快速筛选，那两本书信息 […]...
    ### [IO_FILE](https://yukon.icu/2024/07/07/IO_file/)  
    >by [Yukon](https://yukon.icu), 2024-07-07

    FILE结构IO_FILE 结构外包裹着另一种结构IO_FILE_plus，其中包含了一个重要的指针 vtable 指向了一系列函数指针。在 libc2.23 版本下，32 位的 vtable 偏移为 0x94，64 位偏移为 0xd8，并且，根据程序调用的不同，其所在位置也不同：对于 fopen 的情况下是位于堆内存，对于 stdin\stdout\stderr 是位于 libc.so 中123...
    ### [uiuctf2024 Learning Process Record](https://www.su-cvestone.cn/445/)  
    >by [cvestone](https://www.su-cvestone.cn/), 2024-07-04

    misc Astea(等待学习) Description 所以正如题目描述，这是一道jail类型，我还没有尝试过这种类型，源代码看 ......
    ### [6.30本周小结](http://ba1100n.tech/after_meal/6-30%e6%9c%ac%e5%91%a8%e5%b0%8f%e7%bb%93/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-06-30

    因为课程需要写一个算法相关的报告，所以本周阅读了AFL、AFL++的源代码和相关paper，并且进行了fuzz […]...
    ### [6.24本周小结](http://ba1100n.tech/after_meal/6-24%e6%9c%ac%e5%91%a8%e5%b0%8f%e7%bb%93/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-06-24

    算是把之前四个月的内容做了一个阶段性的完结，虽然结果是失败的，但学到很多东西，从只会x86汇编和逆向、pwn基 […]...
    ### [记一次失败的VxWorks5.x iot设备漏挖经历](http://ba1100n.tech/iot_security/%e8%ae%b0%e4%b8%80%e6%ac%a1%e5%a4%b1%e8%b4%a5%e7%9a%84vxworks5-x-iot%e8%ae%be%e5%a4%87%e6%bc%8f%e6%8c%96%e7%bb%8f%e5%8e%86/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-06-20

    前言 家里有两台不用的路由器，型号分别是水星的MW313R和MW325R，曾经只会php之流的web安全、一些 […]...
    ### [CVE-2019-17621 RCE复现](http://ba1100n.tech/iot_security/cve-2019-17621-rce%e5%a4%8d%e7%8e%b0/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-06-20

    前言 这个命令注入漏洞跟之前的有点不太一样 简介 CVE-2019-17621 dlink-822/855 命 […]...
    ### [6.17本周小结](http://ba1100n.tech/after_meal/6-17%e6%9c%ac%e5%91%a8%e5%b0%8f%e7%bb%93/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-06-17

    这周忙于各种课程结尾的事情（英语课程超多东西要搞要准备）和学校的一些手续，由于学校渗透课程缘故，完整地刷了下p […]...
    ### [实战式打靶随记](https://www.su-cvestone.cn/423/)  
    >by [cvestone](https://www.su-cvestone.cn/), 2024-06-16

    方法指导 记录什么 学习技术专题的要点； 成功调试或配置的命令； 找到的参考资料； 技术⼼得； 反思、复盘和整理 记录方式 要点式 ......
    ### [密码保护：网安学习基础阶段checklists](https://www.su-cvestone.cn/419/)  
    >by [cvestone](https://www.su-cvestone.cn/), 2024-06-16

    无法提供摘要。这是一篇受保护的文章。...
    ### [6.10本周小结](http://ba1100n.tech/after_meal/6-10%e6%9c%ac%e5%91%a8%e5%b0%8f%e7%bb%93/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-06-10

    这周对vxworks的固件进行了逆向，可惜并没有找到符号表，也没有可以参照的代码，所以进行了逆向工程，大概逆向 […]...
    ### [记一次UART串口调试实战](http://ba1100n.tech/iot_basic/%e8%ae%b0%e4%b8%80%e6%ac%a1uart%e4%b8%b2%e5%8f%a3%e8%b0%83%e8%af%95%e5%ae%9e%e6%88%98/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-06-02

    前言 面对某固件，虽然没有加密，但binwalk是没有办法正常提取的，然后试了试网上的办法好像不太行，还没细究 […]...
    ### [hvv面试题总结归纳](https://www.su-cvestone.cn/412/)  
    >by [cvestone](https://www.su-cvestone.cn/), 2024-05-23

    蓝队 Top10漏洞篇 owasp top10(最新2021版)有哪些？ 官方报告 Broken Access Control 破 ......
    ### [密码保护：混音课程笔记](https://www.su-cvestone.cn/308/)  
    >by [cvestone](https://www.su-cvestone.cn/), 2024-03-12

    无法提供摘要。这是一篇受保护的文章。...

</div>
