---
title: 轻松开始
weight: 1
type: docs
next: /wiki/rules
---
这篇简易的教程旨在引导您快速上手对星屹工作室官方网站的编辑。

<!--more-->

## 快速编辑

当您只需对本网站的部分条目做出修改时，可以在Github网页中快速完成。

**需求：**

+ 一个能流畅访问Github的网络环境
+ 一个获取了对[本网站所在仓库](https://github.com/CTNStudio/official_website)的写入权限的Github账号

{{% steps %}}

### 找到文件目录

+ 当右侧边栏在您的设备上可用时，点击`在Github上编辑此页 →`按钮
+ 当右侧边栏在您的设备上不可用时，访问[`https://github.com/CTNStudio/official_website/tree/main/content`](https://github.com/CTNStudio/official_website/tree/main/content)，并按照官网url链接中`https://www.ctnstudios.top/`之后的部分，找到您想要编辑页面对应的markdown源文件
    + 首页对应的文件即为最初目录下的`_index.md`文件
    + 当所编辑页面指向一个文件夹时，其对应源文件为此文件夹下的`_index.md`文件
    + 当所编辑页面直接指向一个`.md`文件时，该文件即为所需文件

### 进行修改

点击编辑按钮，对您想修改的部分进行调整。
{{< callout type="info" >}}
  相关文件采用**Markdown**格式，请注意遵循Markdown语法。若您不了解且没有意愿了解Markdown，请考虑自行寻找Markdown生成器
{{< /callout >}}

### 提交更改

点击保存按钮，仓库中内置的工作流会自动部署您的全部更改。您需要等待大约30秒。
{{< callout type="important" >}} 
  若长时间未部署完成，请访问[此链接](https://github.com/CTNStudio/official_website/deployments)检查您的更改是否成功部署，若失败请重新提交任务，**若多次部署失败，请与星屹工作室管理组联系**
{{< /callout >}}

{{% /steps %}}

## 高级编辑
若需批量编辑页面、增加/删除页面、调整网站配置等操作，您需要在本地进行编辑。

**需求：**

+ 一个能流畅访问Github的网络环境
+ 一个获取了对[本网站所在仓库](https://github.com/CTNStudio/official_website)的写入权限的Github账号
+ 在电脑上安装[Git](https://git-scm.com/install/windows)（也可使用Github Desktop等Git的GUI工具）
+ 在电脑上安装[Hugo](https://gohugo.io/installation/windows/)

{{% steps %}}

### 将仓库克隆到本地

### 在本地进行部署
+ 在powershall中进入克隆的仓库所在的目录
+ 运行如下命令
```PowerShell
hugo server
```
+ 随后，您可访问`localhost:1313`查看您在本地的部署，若想停止部署，请按`Ctrl`+`C`

### 找到文件目录

+ 网站的核心配置文件为根目录下的`hugo.yaml`文件
+ 所有页面位于`content`文件夹，您可按照官网url链接中`https://www.ctnstudios.top/`之后的部分，找到您想要编辑页面对应的markdown源文件
    + 首页对应的文件即为最初目录下的`_index.md`文件
    + 当所编辑页面指向一个文件夹时，其对应源文件为此文件夹下的`_index.md`文件
    + 当所编辑页面直接指向一个`.md`文件时，该文件即为所需文件

### 进行修改

可以参阅下列网站了解如何编辑：
+ [Hextra官方文档](https://imfing.github.io/hextra/zh-cn/docs/)
+ [Hugo官方文档](https://gohugo.io/documentation/)
{{< callout type="info" >}}
  当您保存更改时，本地服务器会自动重新部署更改，无需重新运行`hugo server`
{{< /callout >}}

### 提交更改

向仓库中提交更改，仓库中内置的工作流会自动部署您的全部更改。您需要等待大约30秒。
{{< callout type="important" >}} 
  若长时间未部署完成，请访问[此链接](https://github.com/CTNStudio/official_website/deployments)检查您的更改是否成功部署，若失败请重新提交任务，**若多次部署失败，请与星屹工作室管理组联系**
{{< /callout >}}

{{% /steps %}}
