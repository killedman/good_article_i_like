1. [25年后重新采访 Linus Torvalds](https://mp.weixin.qq.com/s/KWC43nTsL134n6VkSD2x4w)（中文）
    * ~~Linux Journal 杂志1994年创刊号[采访](https://www.linuxjournal.com/article/2736)了 Linus Torvalds，为了庆祝杂志诞生25周年又重新采访了他（[英语原文](https://linuxjournal.com/content/25-years-later-interview-linus-torvalds)）。上一次采访时，他还没结婚，现在有三个小孩，老大马上就要大学毕业。上一次，杂志问他有何梦想，他说希望 Linux 统治世界。现在，他说早就不开这种玩笑了，因为这话已经不像玩笑了。（@[Y024](https://github.com/ruanyf/weekly/issues/437) 投稿）~~
22. [使用 systemd 创建 Linux 服务](https://medium.com/@benmorel/creating-a-linux-service-with-systemd-611b5c8b91d6)（英文）
* ~~创建 Linux 服务相当容易：使用你喜欢的编程语言编写一个长期运行的程序，并使用 systemd 将其转换为服务。~~
23. [加强 Linux 服务器安全的七个步骤](https://medium.com/@mutendebrian/how-to-secure-your-linux-server-6026cfcdefd8)（英文）
* ~~自己架设 Linux 服务器的时候，按照本文的步骤，可以防止90%以上的攻击。~~
27. [~~如何安装 Alpine Linux 的桌面](https://blog.overops.com/my-alpine-desktop-setting-up-a-software-development-environment-on-alpine-linux/)（英文）~~
* ~~Alpine 是一个极度瘦身的 Linux 发行版，只有 5MB 左右，主要用于制作 Docker 镜像文件。本文介绍 Alpine 的基本知识，如何安装一个基于它的桌面开发环境。~~
32. [我的 Linux 桌面配置](https://hookrace.net/blog/linux-desktop-setup/)（英文）
* 一个高级程序员介绍他的 Linux 桌面开发环境，以及他的各种软件选择。
70. [dd 命令教程](https://opensource.com/article/18/7/how-use-dd-linux)（英文）
    * dd 命令通常用来克隆整块磁盘，或者制作 Linux 系统的 USB 启动盘。这篇文章教你怎么用，其实很简单。
11. [虚拟内存探究](http://blog.coderhuo.tech/2017/10/19/Virtual_Memory_summary/)（中文）
    * 这组系列文章通过实验的方式，介绍虚拟内存的相关概念和实现，这里是中文翻译，还可以参考[英语原版](https://blog.holbertonschool.com/hack-the-virtual-memory-c-strings-proc/)。（@[NeoTse](https://github.com/ruanyf/weekly/issues/491) 投稿）
31. [线程的基本知识](https://www.internalpointers.com/post/gentle-introduction-multithreading)（英文）
* 一篇写得非常好的科普文章，通俗地详尽解释了进程和线程的相关知识。
35. [SSD 硬盘是否可靠？](https://www.backblaze.com/blog/how-reliable-are-ssds/)（英文）
    * 本文介绍了固态硬盘 SSD 的一些知识，以及与传统硬盘可靠性的对比。
    * ![img](https://www.wangbase.com/blogimg/asset/201903/bg2019032914.jpg)
40. [如何成为一个优秀工程师](https://jvns.ca/blog/so-you-want-to-be-a-wizard/)（英文）
* 作者谈了自己在 Stripe 公司担任 SRE （系统可靠性）工程师的经历。
44. [文件系统的过去，现在和未来](https://arstechnica.com/gadgets/2008/03/past-present-future-file-systems/)（英文）
    * 文件系统的历史回顾，介绍各种文件系列的来历和特点。
49. [安全上网指南](https://securitycheckli.st/)（英文）
* 一份安全上网清单，从专业角度告诉你，应该做哪些事情，怎样才能安全地使用互联网。
56. [HTTP 协议简史](https://hpbn.co/brief-history-of-http/)（英文）
* 介绍 HTTP 协议的由来和发展。（@[gusibi](https://github.com/ruanyf/weekly/issues/210) 投稿）
60. [10年博客的经验](https://ferrucc.io/posts/starting-a-blog/)（英文）
* 作者写了10年博客，介绍怎么可以通过博客取得最佳效果。
63. [让你的生活更轻松的9个 Bash 快捷别名](https://medium.com/@raimibinkarim/9-bash-aliases-to-make-your-life-easier-3e5855aa95fa)（英文）
    * 本文介绍9个实用的 Bash 函数，你可以参考他的方式，将自己常用的操作封装成函数，然后设置别名。
67. [MySQL 数据库的字符集，要用 utf8mb4，而不是 utf8](https://medium.com/@adamhooper/in-mysql-never-use-utf8-use-utf8mb4-11761243e434)（英文）
    * MySQL 的 utf8 字符集不是真正的 UTF-8，只支持最多三个字节的字符。真正的 UTF-8 可能会出现四个字节的字符。MySQL 从来没有修复这个 Bug，而是使用另外的解决方法：真正的 UTF-8字符集改用 utf8mb4 的名字提供。.
68. [如何生成 localhost 的证书？](https://letsencrypt.org/docs/certificates-for-localhost/)（英文）
    * 本地开发时，我们常常使用 localhost 访问本地服务，怎样才能生成证书，让 localhost 提供 https 服务呢？
75. [网站域名是否该有 www？](https://bjornjohansen.no/www-or-not)（英文）
* `www.example.com` 和 `example.com` 哪一个合适作为主站的域名？这里的关键问题是，`example.com` 设置的 Cookie 可以被子域名读取，并一起发送到服务器。
79. [vimdiff 教程](https://vimways.org/2018/the-power-of-diff/)（英文）
    * ![img](https://www.wangbase.com/blogimg/asset/201812/bg2018122812.jpg)
    * vimdiff 是一个显示文件 diff 的命令行工具，本文主要介绍怎么改用其他算法，以不同的格式显示 diff。
85. [ssh-agent 转发详解](http://www.unixwiz.net/techtips/ssh-agent-forwarding.html)（英文）
* ssh 登录的时候，比较安全的做法是使用公钥认证。但是，这要求本机必须有私钥。如果你需要在多台机器上使用 ssh  登录，一台台拷贝私钥很麻烦，也不安全，幸好 ssh 提供了 agent 转发功能，允许在一台机器上 ssh  登录的时候，可以使用另一台机器的私钥。
