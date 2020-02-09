---
title: "FAQ"
layout: single-no-ads
---

如果你需要帮助,请加QQ群: 715782902
{: .notice--info}

<a name="faq_fatmismatch" />**Q:** Unlaunch 卡在 `MISMATCH IN FAT COPIES` 我该怎么办?
{: .notice--info}

**A:** 这个错误是由twlnf引起的。它有一个很严重的bug:无法在修改后正确更新整个NAND。这导致某些自制程序(如Unlaunch安装程序)报错。好在,此问题是可以解决的,但修复它的 “方法” 并不是固定的,而且在很大程度上因系统而异。通常,删除过去通过twlnf安装的任何DSiWare都可以解决此问题。或者把所有 DSiWare 移到SD卡并移回系统可能会有帮助。(总之,不要再使用 twlnf 往 机身存储 安装 DSiWare)

<a name="faq_2gbsd" />**Q:** 我可以使用 大于2G的SD卡 安装并运行 HiyaCFW 吗?
{: .notice--info}

**A:** 使用类似 [GUIFormat](/assets/files/guiformat.zip) 的工具低格你的SD卡可能会有帮助，但这不会让你绕开DSi系统菜单的block限制。不过，你可以 [使用TWiLightMenu++替代系统菜单](installing-twilight-menu++) 来 “解决” 这个问题。

<a name="faq_uninstall" />**Q:** 我可以安全的卸载Unlaunch吗?
{: .notice--info}

**A:** UnlaunchV1.5及更高版本的安装程序可以卸载Unlaunch。请记住，如果您在系统NAND上安装了任何DSiWare，或以其他方式弄乱了系统文件，则这可能会导致您的机器 **变砖**。

<a name="faq_wifi" />**Q:** 不是说DS Wifi的官方服务器已经关闭了么，我现在还能使用DS Wifi服务吗?
{: .notice--info}

**A:** 跟着这个 [教程](https://gist.github.com/jaames/5e1c0fcea96a3e47f888526d28531720) 操作，这让你可以继续使用DS Wifi服务(通过私人自制服务器),即使任天堂在2014年关闭了DS Wifi服务。
