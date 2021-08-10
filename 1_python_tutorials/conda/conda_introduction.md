---
sort: 1
---

# Conda的简介、安装、基本使用技巧

## Conda 简介

> Conda是一个开源的软件包管理系统和环境管理系统，用于安装多个版本的软件包及其依赖关系，并在它们之间轻松切换。

Conda支持的语言：`Python`、`R`、`Ruby`、`Lua`、`Scala`、`Java`、`JavaScript`、`C/C++`、`FORTRAN`。其中，最流行的是作为`Python`的环境管理工具。

Conda支持的平台：`Linux`、`OS X` 和 `Windows`

```note
Conda 的优势在于可以很便捷地将不同项目的不同依赖使用虚拟环境进行隔离。
```

## Conda 安装

Conda的配置安装分为以下**3种方式**：

### **方式一：Anaconda 安装** <font face="黑体" color=red>(新手推荐)</font>

第一种方式是最常见的 Anaconda 安装，读者可根据自己平台（`Linux`，`OS X` 或 `Windows`）点击下方链接进行下载安装。

[https://www.anaconda.com/products/individual#Downloads](https://www.anaconda.com/products/individual#Downloads)

见下图红框中的蓝色链接：
![conda_introduction_image_1](https://s3.bmp.ovh/imgs/2021/08/1b81f5f4de1f977b.jpg)

由于网上安装资料很多很详细，安装过程也很简单，这里就不在赘述。

### **方式二：Miniconda 安装** <font face="黑体" color=blue>（强迫症推荐）</font>

第二种方式是Miniconda安装方式。

Miniconda 是 Conda 免费最小的安装程序。它是 Anaconda 的小型引导程序版本，仅包含 Conda、Python、所依赖的包以及少量其他有用的包，包括 `pip`、`zlib`等。

同样，读者可根据自己平台（`Linux`，`OS X` 或 `Windows`）点击下方链接进行下载安装。

[https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)

见下图红框中的蓝色链接：
![conda_introduction_image_2](https://s3.bmp.ovh/imgs/2021/08/307756eb54c73d50.png)

```tip
在以上两种安装方式中，读者不需要提前安装 `Python` ，只需在创建虚拟环境中指定 `Python` 及其版本即可。
```

### **方式三：pip 安装** <font face="黑体" color=orange>（中二推荐）</font>

第三种方式是通过 `pip` 进行Conda的安装。这种方式不常用，读者可自行尝试。

读者可通过在 `CMD` (或 `Terminal` )中，运行以下 `shell` 来进行安装。

```bash
pip install conda
```

```warning
使用这种方式的前提是读者使用的平台已安装 `Python` ，且可以正常使用 `pip` 命令。
```

## Conda 基本使用技巧

这里列举了一些最为常用的 Conda 命令的基本使用技巧，更为详细的命令及参数说明请参见 [Conda general commands](https://conda.io/projects/conda/en/latest/commands.html#conda-general-commands)。

### 创建环境

### 进入/切换环境

### 安装依赖

### 退出环境

### 清理环境

### 删除环境


<hr>

```tip
本工作室承接各类`代码咨询、调试、代做和指导`，如有需求，请联系QQ：595946720，或将需求发邮件至595946720@qq.com
```

<center><font face="黑体" size=4 color=blue>淘宝搜索店铺：「览平科技实验室」</font></center>

<center><img src="images/icon.jpg" width="30%" height="30%" ></center>