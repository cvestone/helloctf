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
    - [命途行者｜pwn&ai](https://blog.csdn.net/qq_62172019/)
    - [HeYuMeng｜假装看不见，余光千万遍](http://www.heyumeng.online/)
    - [q1@N9｜学习笔记、成长小结and比赛wp](https://qsheep24.wordpress.com)
    - [ba1100n｜ba1100n的学习随笔](http://www.ba1100n.tech)
    - [Lobok｜萝卜的部落格](https://dis4.cn)
    - [Yukon｜醉后不知天在水，满船清梦压星河](https://yukon.icu)
    - [水委｜这里是雨季，你那里阳光明媚吗](https://arch3rn4r.github.io)
    - [virus｜](https://megachar0x01.github.io)

</div>
<div class="grid cards" markdown>

-   :fontawesome-solid-blog:{ .lg .middle } __最近更新__

    ---
    ### [BitSiegeCTF2025-Watcher](http://arch3rn4r.github.io/2025/05/06/BitSiegeCTF2025-Watcher/)  
    >by [水委](https://arch3rn4r.github.io), 2025-05-06

    前置分析题目描述题目下载链接:https://github.com/0xbinder/BitCTF-2025/blob/main/watcher.apk打开modsf，获取到它的基本信息和暴露的组件Package Name： com.example.watcherexported services：com.example.watcher.WatcherService查看WatcherService...
    ### [ble_ctf wp](http://arch3rn4r.github.io/2025/04/26/%E4%BB%8Eble-ctf%E5%AD%A6%E8%93%9D%E7%89%99/)  
    >by [水委](https://arch3rn4r.github.io), 2025-04-26

    0x0 前期配置所需设备：蓝牙适配器，刷入了blectf的esp32,能进行蓝牙操作的设备（kali或者Ubuntu）将blectf靶场刷入esp32安装esptool(如果出现报错那么去查看“安装时报错”那条)1sudo apt-get install esptool克隆仓库1git clone https://github.com/hackgnar/ble_ctf找到当前esp32在linux...
    ### [基于LAN的intent触发](http://arch3rn4r.github.io/2025/04/19/%E5%9F%BA%E4%BA%8ELAN%E7%9A%84intent%E8%A7%A6%E5%8F%91/)  
    >by [水委](https://arch3rn4r.github.io), 2025-04-19

    漏洞简述Firefox for Android（68.11.0 及更低版本）会发送定期发送SSDP信息，在其解析LCATION时没有正确验证LOCATION字段的的信息，它错误地将 LOCATION 字段里的任何字符串（包括 intent:// 这种非标准的 URI）直接传递给了 Android 系统的 Intent 处理机制。（打开 Web 浏览器的 URI 方案定义为 http 或 https...
    ### [Frida-Labs wp](http://arch3rn4r.github.io/2025/04/17/Frida-Labs-wp/)  
    >by [水委](https://arch3rn4r.github.io), 2025-04-17

    0x1 同一个类中的静态方法分析基本结构如下12345678910111213public class MainActivity extends AppCompatActivity {    protected void onCreate(Bundle bundle) {            public void onClick(View view) {                if (...
    ### [Mirai源代码精读(bot部分)](http://www.ba1100n.tech/iot_security/mirai%e6%ba%90%e4%bb%a3%e7%a0%81%e7%b2%be%e8%af%bbbot%e9%83%a8%e5%88%86/)  
    >by [ba1100n](http://www.ba1100n.tech), 2025-03-18

    前言 虽然感觉前人分析挺多，但我觉得很多文章干看看不懂，很多地方跳来跳去，没铺垫我真的有点乱，也没有讲通我的疑 […]...
    ### [frida绕过检测学习](http://arch3rn4r.github.io/2025/03/02/frida%E7%BB%95%E8%BF%87%E6%A3%80%E6%B5%8B%E5%AD%A6%E4%B9%A0/)  
    >by [水委](https://arch3rn4r.github.io), 2025-03-02

    检测点检测Frida的机制一般在Native层实现，通常会创建几个线程轮询检测。查看检测的so先检查检测部分的代码在哪里1234567891011Interceptor.attach(Module.findExportByName(null, "android_dlopen_ext"),      {          onEnter: function (args) {...
    ### [入门MQTT漏挖：从概念，底层原理到rce](http://www.ba1100n.tech/iot_security/%e5%85%a5%e9%97%a8mqtt%e6%bc%8f%e6%8c%96%ef%bc%9a%e4%bb%8e%e6%a6%82%e5%bf%b5%ef%bc%8c%e5%ba%95%e5%b1%82%e5%8e%9f%e7%90%86%e5%88%b0rce/)  
    >by [ba1100n](http://www.ba1100n.tech), 2025-01-26

    前言 别的事情搞得差不多了，又回来继续学习啦这篇存在大量借鉴、复现别人的东西，属于是初学的一个记录吧，在这个过 […]...
    ### [从电线鲨鱼到提取C2服务器ip](http://www.ba1100n.tech/iot_security/%e4%bb%8e%e7%94%b5%e7%ba%bf%e9%b2%a8%e9%b1%bc%e5%88%b0%e6%8f%90%e5%8f%96c2%e6%9c%8d%e5%8a%a1%e5%99%a8ip/)  
    >by [ba1100n](http://www.ba1100n.tech), 2025-01-19

    前言 这是今年西湖论剑的题，没有参加比赛，但赛后群友发了一道很有意思的题目，正好就是之前没学到的，如何分析木马 […]...
    ### [恶意软件开发前置](http://arch3rn4r.github.io/2025/01/04/%E6%81%B6%E6%84%8F%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%911/)  
    >by [水委](https://arch3rn4r.github.io), 2025-01-03

    前提目的是做一个恶意软件，实现基本恶意功能，当前版本专注于实现基本功能，只有基本界面和功能。那么一个恶意软件应当具有什么功能呢，下面主要研究的是怎么做，而不是防御和绕过检测。它将是一个纯粹的恶意软件。以下信息pc和安卓都有，只是将基于Android端开发。。。安卓平台的特殊性基于 Linux 内核： Android 系统基于 Linux 内核，这意味着一些 Linux 系统上的 Rootkit 技...
    ### [探究vxworks文件名恢复](http://www.ba1100n.tech/iot_security/%e6%8e%a2%e7%a9%b6vxworks%e6%96%87%e4%bb%b6%e5%90%8d%e6%81%a2%e5%a4%8d/)  
    >by [ba1100n](http://www.ba1100n.tech), 2024-11-09

    前言 VxWorks以其良好的可靠性和卓越的实时性被广泛地应用在通信、军事、航空、航天等高精尖技术及实时性要求 […]...
    ### [Single Note - Ignite khi qualifying 2024](https://megachar0x01.github.io/posts/Single_Note/)  
    >by [virus](https://megachar0x01.github.io), 2024-10-29

    Purpose : Get The Flag Mitigations : Crash : Decompile : #!/usr/bin/python3 from pwn import * import struct # context.terminal = ['tmux','splitw','-h'] os.environ['XDG_CACHE_HOME'] = '/tmp/' context.l...
    ### [BlackHat Qualifier cockatoo](https://megachar0x01.github.io/posts/cockatoo_BlackHat_2024_Qualifier/)  
    >by [virus](https://megachar0x01.github.io), 2024-10-26

    Purpose : Get The Flag #!/usr/bin/python3 from pwn import * import struct from ctypes import * import subprocess context.terminal = ['tmux','splitw'] os.environ['XDG_CACHE_HOME'] = '/tmp/' context.log...
    ### [从ciscn_2019_c_1看ret2libc](http://arch3rn4r.github.io/2024/09/26/%E4%BB%8Eciscn-2019-c-1%E7%9C%8Bret2libc/)  
    >by [水委](https://arch3rn4r.github.io), 2024-09-26

    前置分析检查保护1234567└─$ checksec '/home/pwn/ciscn_2019_c_1' [*] '/home/pwn/ciscn_2019_c_1'    Arch:     amd64-64-little    RELRO:    Partial RELRO    Stack:    No canary found    NX:       NX enabled    PI...
    ### [简单hook一下](http://arch3rn4r.github.io/2024/09/24/%E7%AE%80%E5%8D%95hook%E4%B8%80%E4%B8%8B/)  
    >by [水委](https://arch3rn4r.github.io), 2024-09-24

    使用的例题是**[CISCN 2022 东北]crackme_Android，**虽然这题的关键点在MD5爆破，但是它的主逻辑函数包括了“成功”和“失败”的判断，可以验证是否成功hook函数我的环境frida 16.4.2雷电模拟器(adb也是使用的雷电模拟器自带的）jadxIDEA初步分析初步分析，拖入模拟器后运行，随便输一个数，得到报错信息在jadx里使用文本搜索找到相应报错信息并得到判断条件...
    ### [Linux沙箱之seccomp介绍](http://arch3rn4r.github.io/2024/09/21/Linux%E6%B2%99%E7%AE%B1%E4%B9%8Bseccomp%E4%BB%8B%E7%BB%8D/)  
    >by [水委](https://arch3rn4r.github.io), 2024-09-21

    介绍seccomp (Secure Computing Mode) 是 Linux 内核的一种安全机制，用于限制进程可以调用的系统调用集。本质上是linux系统调用的防火墙，可查看文档http://man7.org/linux/man-pages/man3/seccomp_rule_add.3.htmlseccomp很强大，它可以遗传给子进程，甚至能限制root用户运行的进程，而且可以自己编写复杂...
    ### [shell的历史命令机制](http://arch3rn4r.github.io/2024/09/21/shell%E7%9A%84%E5%8E%86%E5%8F%B2%E5%91%BD%E4%BB%A4%E6%9C%BA%E5%88%B6/)  
    >by [水委](https://arch3rn4r.github.io), 2024-09-21

    该想法来自chroot实验使用新方法建立bash后，我查看“上一条命令”，既按箭头”⋀“，出现的指令并不是当前界面下的历史命令比如shell1,我的命令是cd .. cat flag.txt shell2，我之前使用的命令是gcc -o 1 1.c ./1在shell1里使用vi新建shell后，再按”⋀“，出现的指令不是cat flag.txt 而是 ./1我知道是“新建”了一个shell，但这...
    ### [linux沙箱之文件系统隔离](http://arch3rn4r.github.io/2024/09/21/linux%E6%B2%99%E7%AE%B1%E4%B9%8B%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F%E9%9A%94%E7%A6%BB/)  
    >by [水委](https://arch3rn4r.github.io), 2024-09-21

    chroot介绍通常来说，提到chroot一般有两个含义，chroot(1)是/usr/bin/chroot,要有一定权限才能使用chroot, chroot(2)是glibc中的一个函数,属于系统调用chroot(1)chroot - run command or interactive shell with special root directory 一个命令行工具，可用于创建沙箱shell...
    ### [python逆向](http://arch3rn4r.github.io/2024/09/18/python%E9%80%86%E5%90%91/)  
    >by [水委](https://arch3rn4r.github.io), 2024-09-18

    参照此文章编写https://rocky.github.io/blackhat-asia-2024-additional/all-notes-printPython 字节码的变化非常大，每个版本之间都有很大的区别。高级字节码的一个方面：许多源信息（如变量名称及其类型）都保存在字节码中。所以反编译回来的程序会和源代码非常像（简直一模一样）。但是来自源文本的注释不会显示在重建结果中，这是因为这些注释不...
    ### [动态符号执行](http://arch3rn4r.github.io/2024/09/18/%E5%8A%A8%E6%80%81%E7%AC%A6%E5%8F%B7%E6%89%A7%E8%A1%8C/)  
    >by [水委](https://arch3rn4r.github.io), 2024-09-18

    初始概念介绍动态符号执行的核心思想是在所谓的符号数据域上模拟程序执行cpu工作在1和0上，如果使用read系统调用读入用户输入，得到的是1和0.作为发送程序的人，无法给它发送一个未知值的变量，但是可以创造一个模拟器来实现它，可以是0，1或者x.随着知道已知数据是什么，未知数据是什么，根据cmp比较未知数据，并基于结果进行跳转123456mov rax, 0  > rax = 0mov rdi, 0...
    ### [格式化字符串漏洞](http://arch3rn4r.github.io/2024/09/16/%E6%A0%BC%E5%BC%8F%E5%8C%96%E5%AD%97%E7%AC%A6%E4%B8%B2%E6%BC%8F%E6%B4%9E/)  
    >by [水委](https://arch3rn4r.github.io), 2024-09-16

    介绍首先来看printf,这是常用的格式化字符串函数，以下是常见用法，能利用%s,%d等来替换不同的值1234printf("Hello!\n");printf("Hello %s!\n", name);printf("There are %d lights!", 5);printf("The average of %d, %d, and %d is %f", 1, 2, 3, float(1+2...

</div>
