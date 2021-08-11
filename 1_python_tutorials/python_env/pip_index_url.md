---
sort: 3
---

# PIP Install 依赖安装

直击[镜像源地址的命令后缀](#jump1)

## PIP Install

- 最新版本的依赖安装
```bash
pip install your_lib_name
```

- 指定版本的依赖安装
```bash
pip install your_lib_name=x.x.x
```

- 指定依赖卸载
```bash
pip uninstall your_lib_name
```

```warning
请将上述命令中的 `your_lib_name` 和 `x.x.x` 改为自己所需安装的依赖名称和版本号，不可直接复制粘贴运行！

另外，**建议依赖安装时，请检查当前环境是否为所需安装依赖的环境**，不可粗心大意！
```

## PIP 国内镜像源配置

为了加快 `pip install` 依赖的下载速度，可将 PIP 下载源设置为国内镜像源。

PIP 国内镜像源配置方式分为两种：<font face="黑体" color=blue><b>临时使用</b></font> <font face="黑体" color=red><b>（强烈推荐）</b></font>和<font face="黑体" color=blue><b>永久修改</b></font> <font face="黑体" color=red><b>（不推荐）</b></font>


下文只给出<font face="黑体" color=blue><b>临时使用</b></font>方式的说明。<font face="黑体" color=blue><b>永久修改</b></font>方式的网上教程很多，这里不再赘述。文章最后给出[ PIP 国内镜像源地址](#jump2)

```bash
pip install your_lib_name=x.x.x -i your_lib_url --trusted-host your_lib_url_host
```

```warning
请将上述命令中的 `your_lib_name`、`x.x.x`、 `your_lib_url` 和 `your_lib_url_host` 改为自己所需安装的依赖名称、版本号、镜像源地址和镜像源域名，不可直接复制粘贴运行！

**值得注意的是**，网上大多数教程上是没有 `--trusted-host your_lib_url_host` 这个命令后缀的。不加此后缀，则报以下警告：

> WARNING: The repository located at mirrors.aliyun.com is not a trusted or secure host and is being ignored. If this repository is available via HTTPS we recommend you use HTTPS instead, otherwise you may silence this warning and allow it anyway with '--trusted-host mirrors.aliyun.com'.
```

<span id="jump1"><font face="黑体" color=red><b>这里给出所有镜像源地址的命令后缀，方便复制使用：</b></font></span>
```bash
-i http://mirrors.aliyun.com/pypi/simple/ --trusted-host mirrors.aliyun.com
-i http://pypi.douban.com/simple/ --trusted-host pypi.douban.com
-i https://pypi.tuna.tsinghua.edu.cn/simple/ --trusted-host pypi.tuna.tsinghua.edu.cn
-i http://pypi.mirrors.ustc.edu.cn/simple/ --trusted-host pypi.mirrors.ustc.edu.cn
```

## <span id="jump2">PIP 国内镜像源地址</span>

- 阿里云源（有限速，稳定）
```bash
http://mirrors.aliyun.com/pypi/simple/
```

- 豆瓣源（无限速，稳定）
```bash
http://pypi.douban.com/simple/
```

- 清华源（无限速，不稳定）
```bash
https://pypi.tuna.tsinghua.edu.cn/simple/
```

- 中科大源（无限速，稳定）
```bash
http://pypi.mirrors.ustc.edu.cn/simple/
```

```note
如有不明之处，请联系本文作者加更！
```

<hr>

```tip
本工作室承接各类`代码咨询、调试、代做和指导`，业务范围详见[这里](https://lanping-tech.github.io/#%E6%89%BF%E6%8E%A5%E4%B8%9A%E5%8A%A1)。如有需求，见联系方式：
- **QQ：**`595946720`
- **淘宝搜索店铺：**`览平科技工作室`，联系客服即可。
```