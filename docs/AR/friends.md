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
    - [virus｜](https://megachar0x01.github.io)

</div>
<div class="grid cards" markdown>

-   :fontawesome-solid-blog:{ .lg .middle } __最近更新__

    ---
    ### [羊城杯2024](https://yukon.icu/2024/08/28/ycb2024/)  
    >by [Yukon](https://yukon.icu), 2024-08-28

    羊城杯20241.pstack看汇编能发现控制rbp就能控制buf，溢出只有0x10字节，打栈迁移1234567891011121314151617181920212223242526272829303132333435363738394041424344454647484950515253545556575859606162636465666768697071727374757677787980...
    ### [浅析Vxworks符号表恢复以及vxhunter改进点](http://ba1100n.tech/after_meal/%e6%b5%85%e6%9e%90vxworks%e7%ac%a6%e5%8f%b7%e8%a1%a8%e6%81%a2%e5%a4%8d%e4%bb%a5%e5%8f%8avxhunter%e6%94%b9%e8%bf%9b%e7%82%b9/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-08-27

    前言 上次挖水星路由器，没有机会恢复Vxworks符号表，因为固件内部已经抹除了符号表了(其实没有完全抹掉，下 […]...
    ### [8.26本周小结](http://ba1100n.tech/after_meal/8-26%e6%9c%ac%e5%91%a8%e5%b0%8f%e7%bb%93/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-08-26

    这周机器到货了以后，连上uart串口，发现机器的各个地址确实是写死的！！甚至是栈地址，居然都是固定的，ret2 […]...
    ### [8.19本周小结](http://ba1100n.tech/after_meal/8-19%e6%9c%ac%e5%91%a8%e5%b0%8f%e7%bb%93/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-08-19

    周二回到学校了，静下心来看了几天那个栈溢出复现，用户态仿真因为是qemu-user带起来的，有很多特性不一样， […]...
    ### [ubuntu libc库大全](https://yukon.icu/2024/08/18/glibc_all_in_one/)  
    >by [Yukon](https://yukon.icu), 2024-08-18

    3a153b657c1b4a50d0b4b41bc23a9dbbce832fab3f7c9a678438c884837c1d101ac27840183beb9e450aee75d20075b3ad40510f9ea4d1207750ab9db735bd66775cdcdb07489a5c053c152b90c1f7b2a6c8ab92bc5516426c4120431bb11f5171dba6...
    ### [8.12本周小结](http://ba1100n.tech/after_meal/8-12%e6%9c%ac%e5%91%a8%e5%b0%8f%e7%bb%93/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-08-11

    这周还在家里，在市里图书馆学习，幸好现在图书馆允许用之前老早就安装好的桌子下的电源了·，感谢，但是能不能把狐臭 […]...
    ### [House_of_apple2](https://yukon.icu/2024/08/10/hoa2/)  
    >by [Yukon](https://yukon.icu), 2024-08-10

    House of apple2上一篇博客中我们使用的house of apple1，需要和house of emma一起使用从而控制程序流，这一篇我们利用几条新的IO利用链，只通过劫持_wide_data来控制程序的执行流利用条件已知heap地址和glibc地址能控制程序执行IO操作，包括但不限于：从main函数返回、调用exit函数、通过__malloc_assert触发能控制_IO_FILE的...
    ### [House_of_apple1](https://yukon.icu/2024/08/10/house_of_apple1/)  
    >by [Yukon](https://yukon.icu), 2024-08-10

    House_of_apple1简述利用_IO_wstrn_overflow这个函数，通过伪造file的结构，这个函数可以覆盖传入fp->_wide_data上的地址覆盖为可以知道的堆地址，攻击效果和进行一次largebin attack一样，实现任意地址写已知地址。利用条件使用house of apple的条件为：1、程序从main函数返回或能调用exit函数2、能泄露出heap地址和libc地址...
    ### [House of kiwi & emma](https://yukon.icu/2024/08/09/house_of_kiwi/)  
    >by [Yukon](https://yukon.icu), 2024-08-09

    本文是为了学习apple做的铺垫，两种利用手法的利用原理是基于ctfshow的pwn213和pwn214动调和一些师傅的博客总结得出，如有侵权联系删除House of kiwi利用条件能够触发__malloc_assert能够申请到_IO_file_sync 和 _IO_helper_jumps这两个位置并且修改。利用原理在函数sysmalloc中，有一个检查top chunk是否对其的代码片段：...
    ### [堆-杂](https://yukon.icu/2024/08/09/%E5%A0%86-%E6%9D%82/)  
    >by [Yukon](https://yukon.icu), 2024-08-09

    bb2cd3915cb2779a5ff0f382ab08328858af39cfc75d69237ee2c5d43e061a3defb123903f0149e58a007374380ce1c57ffec623b675ac6f50d051c05d1daad2ddec5493a80375aa2cdd5523d19f500df7bfdecd5af5292e435a80e8dcc97269ca0530...
    ### [TFCctf2024](https://yukon.icu/2024/08/07/TFCctf2024/)  
    >by [Yukon](https://yukon.icu), 2024-08-06

    可惜来的有点晚了，比赛已经结束了GUARD-THE-BYPASSGuard this cookie.Note: If you successfully create a working exploit in the provided Docker, ensure you try the exploit multiple times on the remote system if any issue...
    ### [8.5本周小结](http://ba1100n.tech/after_meal/8-5%e6%9c%ac%e5%91%a8%e5%b0%8f%e7%bb%93/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-08-05

    这周其实效率很低，周一到周四上午的学习主要是arm pwn、mips pwn以及qiling fuzz，但比较 […]...
    ### [阅读HITCON2024-setjmp题解笔记](http://ba1100n.tech/binary_security/%e9%98%85%e8%af%bbhitcon2024-setjmp%e9%a2%98%e8%a7%a3%e7%ac%94%e8%ae%b0/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-07-29

    前言 做这道题的时候当时刚刚重新学堆，其实确实观察到uaf的点，以及想到剩下root本身就可以double f […]...
    ### [7.26本周小结](http://ba1100n.tech/after_meal/7-26%e6%9c%ac%e5%91%a8%e5%b0%8f%e7%bb%93/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-07-26

    这周的周一到周三主要是跟着Nop师傅去分析了几个固件，然后发现很多时候之所以我到今天都还没有cve编号，其实是 […]...
    ### [浅析tcache安全机制演进过程与绕过手法](http://ba1100n.tech/binary_security/%e6%b5%85%e6%9e%90tcache%e5%ae%89%e5%85%a8%e6%9c%ba%e5%88%b6%e6%bc%94%e8%bf%9b%e8%bf%87%e7%a8%8b%e4%b8%8e%e7%bb%95%e8%bf%87%e6%89%8b%e6%b3%95/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-07-26

    前言 本文重点关注tcache本身的结构、取用放入的原子操作，以及其free安全机制的演变过程， 大概分水岭在 […]...
    ### [House Of Roman](https://yukon.icu/2024/07/26/io_stdout_libc/)  
    >by [Yukon](https://yukon.icu), 2024-07-26

    De1CTF weapon1234567891011unsigned __int64 menu(){  unsigned __int64 v1; // [rsp+8h] [rbp-8h]  v1 = __readfsqword(0x28u);  puts("1. create you weapon");  puts("2. delete you weapon");  puts("3. rename...
    ### [bugku_awd_pwn](https://yukon.icu/2024/07/26/awd_bugku1/)  
    >by [Yukon](https://yukon.icu), 2024-07-25

    Bugku_AWD_PWNbugku的 “当前可公开信息”：bugku的awd会给我们一个ip，例如本次比赛我们队的ip是192-168-1-21.pvp4772.bugku.cn，其他人的ip是192-168-1-X.pvp4772.bugku.cn，需要我们自己写脚本发现账号密码：team1:206a75a313e0cded3610aa5e4exxxxxxtoken（用来使用api提交flag...
    ### [House_of_orange](https://yukon.icu/2024/07/25/house_of_orange/)  
    >by [Yukon](https://yukon.icu), 2024-07-24

    House Of  Orange2.23见wkctf复现一文：https://yukon.icu/2024/07/18/wkctf/2.24新增检测以及绕过思路与2.23不同的点在于，2.24对于vtable的位置进行了约束，增加了一个检测函数：IO_validate_vtable123456789101112static inline const struct _IO_jump_t *IO_va...
    ### [DASCTF2024复现](https://yukon.icu/2024/07/24/dasctf2024/)  
    >by [Yukon](https://yukon.icu), 2024-07-24

    springboard分析123456789101112131415161718192021222324int __cdecl main(int argc, const char **argv, const char **envp){  int i; // [rsp+Ch] [rbp-4h]  myinit(argc, argv, envp);  puts("Life is not boring,...
    ### [浅析_IO_FILE相关利用、FSOP与House_of_Orange技术](http://ba1100n.tech/binary_security/%e6%b5%85%e6%9e%90_io_file%e7%9b%b8%e5%85%b3%e5%88%a9%e7%94%a8%e3%80%81fsop%e4%b8%8ehouse_of_orange%e6%8a%80%e6%9c%af/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-07-23

    前言 曾经的学习止步于此，现在，在高版本堆的背景下，仍然值得一学 为什么要学习_IO_FILE？ _IO_FI […]...

</div>
