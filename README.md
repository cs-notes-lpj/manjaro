> 本笔记书用于记录我个人上手使用 [ManjaroLinux](https://manjaro.org/) 的过程

## 主要参考的文档

[ArchWiki](https://wiki.archlinux.org/) & [ManjaroWiki](https://wiki.manjaro.org/index.php/Main_Page)

[ArchLinuxTutorial | 非官方](https://github.com/ArchLinuxStudio/ArchLinuxTutorial)

[wikipedia](https://www.wikipedia.org/)

## 为什么使用 Linux

你可以将苹果的 macOS 看作是 BSD 的孙子、Unix 的曾孙，而将 Linux 看作 Minix 的徒弟、Unix 的徒孙

所以现在比较常见的 macOS 和 Linux 都被称为 UnixLike/类Unix 操作系统

而对于计算机专业相关的学生和从业者而言，选用 UnixLike/类Unix 操作系统好处多多，无需多言，谁用谁知道

---

但 macOS 不仅价格不菲，且系统闭源

相比而言，Linux 开源免费、系统稳定流畅（因此世界上大多数企业的服务器都使用 Linux 系统），与 GNU 的结合更是让 Linux 如虎添翼

并且，Linux 在全世界范围拥有庞大且极其活跃的社区和发展到目前（2022）已经相当完善的文档

使用 Linux 不仅是一个探索和学习的过程，更是一个创造和收获的过程，非常有意思

---

由于我非常喜欢 Linux 的一个发行版 ArchLinux，包括但不限于其：系统滚动更新（采用最新的软件包），软件包管理器 pacman 和官方文档 [ArchWiki](https://wiki.archlinux.org/) 非常好用

因此 ArchLinux 非常适合个人用户日常使用

---

但 ArchLinux 的安装步骤十分复杂繁琐，尽管你能从安装 ArchLinux 的过程中学到很多东西，是其它很多系统一直点击下一步的系统安装方式所不能比的

~~但由于我的笔记本电脑较新，其有 8 个 2G 的内存插槽，这种设计对于 ArchLinux 目前有兼容性问题（目前多于 4 个内存插槽的电脑在安装 ArchLinux 时都会遇到棘手的问题，我暂时没有查询到合适的解决方案）~~

~~所以我选择了现在比较火的一个基于 ArchLinux 且易于安装的系统：ManjaroLinux~~

Archlinux 官方提供了一个用于快速安装 Archlinux 的[脚本](https://github.com/archlinux/archinstall)，经过尝试，succeed ！这适用于不想学习 Archlinux 的安装过程，而只是想要快速得到一个运行起来的 Archlinux 的新手小白或资深 Linux 开发者（显然这种安装方式不适合我）但验证了我的新笔记本电脑是可以成功安装 Archlinux 的 ！

同时，由于我目前还割舍不掉 [KDEConnect](https://liupj.top/2022/06/05/kde-connect/) 这个远比微信文件传输助手强大好用的东西，所以仍坚持使用 KDE

~~另外，我打算先熟悉 Vim 的生态，然后再学习使用平铺式窗口管理器~~

由于我已经非常熟悉 Vim，所以正式开始尝试使用平铺式窗口管理器，看了一下[排行榜](https://www.slant.co/topics/390/~best-window-managers-for-linux)，i3 成为我使用的第一款窗口管理器。

![20221104134357](https://aliyun-oss-lpj.oss-cn-qingdao.aliyuncs.com/images/by-clipboard/20221104134357.png)

## 关于专有软件

大家日常使用的 QQ、微信、WPS 等软件都属于专有软件

它们代码闭源，往往不尊重用户隐私且滥用用户的数据，存在一系列的信息安全问题

因此，这些专有软件只配运行于无任何用户个人隐私的、兼容性最好的系统上

> 在崇尚 free 的 GNU/Linux 上，只使用自由软件，寻找或开发这些专有软件的替代品（free 的意思是自由）

## 关于系统美化

很多刚接触 Linux，又使用图形用户界面的小伙伴，都曾在互联网上查阅与所谓“系统美化教程”相关的网页内容

然后模仿着、结合自己的审美，对自己的 Linux 图形界面进行美化。当然，我也不例外。

---

但是，现在的我有了一定的 Linux 使用经验，我认为：

现在网上很多所谓的“系统美化教程”都极其不讲究，这包括但不限于

上来就让你安装这个安装那个，不加解释，也没有使用官方文档作为参考依据

更有甚者，文章内容逻辑混乱、软件包管理器使用盲目、软件调用、参数指定方式不谨慎，甚至漏洞百出

等等等等

因此，我们应摒弃此类文章，盲目效仿无疑会对你造成误导，并给你的系统稳定性造成极大风险

---

正确的系统美化做法：

要认识到系统美化这件事，它本身就并不重要

因此由于目前我使用 KDE 作为图形化桌面环境

所以只需使用 KDE 默认提供的方式对图形用户界面进行简单调整即可

更何况 KDE 本身就已经十分华丽

## 寻找问题解决方法的正确姿势

1. 分清是操作系统内核的问题，还是桌面环境的问题，还是应用软件的问题，还是互联网络的问题

2. 以官方文档为第一查询途径，因为其中有百分之九十九你想知道的标准答案

3. 如果你需要向他人提问以寻求帮助，那么应当首先阅读[这个项目](https://github.com/tangx/Stop-Ask-Questions-The-Stupid-Ways)

4. 这里给出几个可以提问的链接

    - [ManjaroForum](https://forum.manjaro.org/)

    - [ArchForum](https://bbs.archlinux.org/)

    - [KDEForum](https://forum.kde.org/)

    - [stackoverflow](https://stackoverflow.com/)

5. 你也可以使用搜索引擎，但应拒绝百度，而使用[必应](https://www.bing.com/)或[Google](https://www.google.com/)

## 如果你想自己挑选 Linux 发行版

[Distrochooser](https://distrochooser.de/)

