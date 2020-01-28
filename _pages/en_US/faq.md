---
title: "FAQ"
layout: single-no-ads
---

如果你需要帮助,请加QQ群:715782902
{: .notice--info}

<a name="faq_fatmismatch" />**Q:** Unlaunch 卡在 `MISMATCH IN FAT COPIES` 我该怎么办?
{: .notice--info}

**A:** 这个错误是由twlnf引起的。它有一个很严重的bug:无法在修改后正确更新整个NAND。这导致某些自制程序(如Unlaunch安装程序)报错。好在,此问题是可以解决的,但修复它的 "方法" 并不是固定的,而且在很大程度上因系统而异。通常,删除过去通过twlnf安装的任何DSiWare都可以解决此问题。或者把所有 DSiWare 移到SD卡并移回系统可能会有帮助。(总之,不要再使用 twlnf 往 机身存储 安装 DSiWare)

<a name="faq_2gbsd" />**Q:** Can I use an SD card higher than 2GB with HiyaCFW?
{: .notice--info}

**A:** Low-level "full" formatting your SD card with a tool like GUIFormat can help as well, but this will not get you around the DSi Menu's block limit. However, [replacing the System Menu with TWiLight Menu++](installing-twilight-menu++) completely removes the limit.

<a name="faq_notwlmenupp" />**Q:** Why don't I see TWiLight Menu++?
{: .notice--info}

**A:** You're in SysNAND instead of the SDNAND. The HiyaCFW Helper isn't applying the CFW's patches properly, so please wait for a fix in the helper.

<a name="faq_uninstall" />**Q:** Is there a safe way to remove Unlaunch?
{: .notice--info}

**A:** Yes, Unlaunch v1.5 and higher's installer can uninstall Unlaunch. Keep in mind that this may result in an **irrecoverable brick** if you have installed any arbitrary DSiWare to your system NAND, or have otherwise messed with system files.

<a name="faq_wifi" />**Q:** Is it possible to still use DS Wifi services, even though it shut down?
{: .notice--info}

**A:** By following [this guide](https://gist.github.com/jaames/5e1c0fcea96a3e47f888526d28531720), it is possible to still use Nintendo Wifi Services even though it has shut down back in 2014.
