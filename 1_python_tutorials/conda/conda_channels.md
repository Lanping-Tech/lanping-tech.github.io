---
sort: 2
---

# Conda 国内镜像源及配置

## Conda 国内镜像源

- 清华源
```bash
https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/r
https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/msys2
```

- 中科大源
```bash
https://mirrors.ustc.edu.cn/anaconda/pkgs/main/
https://mirrors.ustc.edu.cn/anaconda/pkgs/free/
```

- 北外源
```bash
https://mirrors.bfsu.edu.cn/anaconda/pkgs/main
https://mirrors.bfsu.edu.cn/anaconda/pkgs/free
```

## Conda 国内镜像源配置

**与其他教程不同的是，本文推荐的配置方法是** <font face="黑体" color=red><b>不配置</b></font>。

```note
这里推荐不配置的原因在于：
- 对**萌新玩家**而言，配置方法**复杂且容易出错**；
- 对**老玩家**而言，人手不止一把梯子，**没必要**；
- 另外，**一手资料**毕竟要比二手资料**香**（版本全）
```

那么问题来了，**不配置**Conda 国内镜像源，**如何提高依赖库的下载速度呢？**

这里参考上一篇 [Conda 基本使用技巧·依赖安装  ](https://lanping-tech.github.io/1_python_tutorials/conda/conda_introduction.html#%E4%BE%9D%E8%B5%96%E5%AE%89%E8%A3%85)中的**第3种安装介绍**-<font face="黑体" color=red><b>指定镜像下载地址和版本的依赖安装</b></font>。如下：

```bash
conda install your_lib_name=x.x.x -c your_lib_url
```

```warning
请将上述命令中的**`your_lib_url` 改为上述 Conda 国内镜像源地址**， `your_lib_name` 和 `x.x.x` 改为自己所需安装的依赖名称和版本号。

另外，**建议依赖安装时，请检查当前环境是否为所需安装依赖的环境**，不可粗心大意！
```

关于Conda 国内镜像源配置的教程很多，这里不再赘述，参考[清华大学Anaconda 镜像使用帮助](https://mirror.tuna.tsinghua.edu.cn/help/anaconda/)。

```note
如有不明之处，请联系本文作者加更！
```

<hr>

```tip
本工作室承接各类`代码咨询、调试、代做和指导`，业务范围详见[这里](https://lanping-tech.github.io/#%E6%89%BF%E6%8E%A5%E4%B8%9A%E5%8A%A1)。如有需求，见联系方式：
- **QQ：**`595946720`
- **淘宝搜索店铺：**`览平科技工作室`，联系客服即可。
```