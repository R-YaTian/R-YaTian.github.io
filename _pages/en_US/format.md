---
title: "存储卡格式化"
---

{% include toc title="内容表" %}

### 请先阅读

   这是一个使用 专业格式化工具 格式化存储卡的必备步骤!

### 你需要准备

* V4.0版本的 [SDFormatter](/assets/files/SDFormatter.zip)

### 步骤说明

1. 解压 `SDFormatter.zip` 中的所有文件到一个文件夹
1. 把你的SD卡插到电脑上
1. 运行 `SDFormatter.exe`
1. 点击 "选项设置"
1. 将 `逻辑打开调整` 打开, 并点击 "OK"
1. 选择SD卡所在盘符
1. 确认 "逻辑打开调整" 显示为开启
1. 点击 "格式化"
1. 等待格式化完成后关闭程序

### 注意事项与额外步骤

如果你的SD卡容量在 "2G及以下" 或 "64G及以上", 你还需要在完成以上格式化步骤后使用[Guiformat](/assets/files/guiformat.zip)将你的SD卡格式化为FAT32
{: .notice--danger}

1. 解压 `guiformat.zip` 中的所有文件到一个文件夹
1. 运行 `guiformat.exe` 或 `guiformat-x64.exe` (根据你的操作系统体系结构选择对应程序)
1. 选择SD卡所在盘符
1. 点击 "开始"
1. 等待格式化完成后关闭程序

___

回到 [安装 Unlaunch](installing-unlaunch)
{: .notice--info}
