---
title: "存储卡测试(H2testw)"
---

{% include toc title="内容表" %}

### 请先阅读

   这是一个使用h2testw来检查你的SD卡有无错误的额外环节

   测试所花费的时间取决于你的SD卡大小及电脑速度, 这个过程可能持续几个小时!

   你最好在测试之前格式化你的SD卡

### 你需要准备

* 最新版本的 [h2testw](/assets/files/h2testw.zip)

### 步骤说明

1. 从 `h2testw.zip` 中解压 `h2testw.exe` 到你的桌面(或其他任意位置)
1. 把你的SD卡插到电脑上
1. 运行 `h2testw.exe`
1. 点击 "选择路径"
1. 选择SD卡所在盘符
1. 确认 "所有可用的空间" 已被选择
1. 点击 "写入并测试"
1. 等待测试过程结束

___

如果测试结束并显示 `测试已完成,没有发现错误.`这说明你的SD卡状态良好, 你可以进行格式化并继续进行下一步操作
{: .notice--info}

如果测试结束后出现其他任何结果, 你的SD卡可能已损坏并且你可能需要换一张卡
{: .notice--danger}

回到 [安装 Unlaunch](installing-unlaunch)
{: .notice--info}
