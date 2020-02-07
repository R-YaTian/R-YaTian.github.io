---
title: "存储卡测试(H2testw)"
---

{% include toc title="内容表" %}

### 请先阅读

这是一个使用h2testw来检查你的SD卡有无错误的额外环节

Depending on the size of your SD card and the speed of your computer, this process can take up to several hours!

This page is for Windows users only. If you are not on windows, check out the [F3 (linux)](f3-(linux)) or [F3X (mac)](f3x-(mac)) pages.

### 你需要准备

* 最新版本的 [h2testw](/assets/files/h2testw.zip)

### Instructions

1. Copy `h2testw.exe` from the h2testw `.zip` to your desktop
1. Insert your SD card into your computer
1. Run `h2testw.exe`
1. Select "English"
1. Click "Select target"
1. Select your SD card's drive letter
1. Ensure "all available space" is selected
1. Click "Write + Verify"
1. Wait until the process is completed

___

If the test shows the result `Test finished without errors`, your SD card is good and you can delete all `.h2w` files on your SD card
{: .notice--info}

If the test shows any other results, your SD card may be corrupted or damaged and you may have to replace it!
{: .notice--danger}

Return to [Installing Unlaunch](installing-unlaunch)
{: .notice--info}
