---
title: Material主题
---
# Material主题

[![](https://img.shields.io/badge/Maintained--by-EasyHexo-42B983.svg?longCache=true&style=flat-square)](https://github.com/EasyHexo/Easy-Hexo)
[![](https://img.shields.io/badge/Author-ffy-800080.svg?longCache=true&style=flat-square)](https://github.com/ffdy)

:::tip
注意，这里介绍的Material主题是1.5.2的版本，新手不建议使用最新的版本，因为好像有很多Bug（作者最近失联了）
:::

[Material主题地址](https://github.com/viosey/hexo-theme-material)

## Material主题演示

![演示](https://camo.githubusercontent.com/1e9260f301fe915fb3e4826831fde943229523cb/68747470733a2f2f692e6c6f6c692e6e65742f323031372f30392f30372f353962313336376637366664622e706e67)

## 下载Material主题

1. 进入 Github，下载 [Material](https://github.com/viosey/hexo-theme-material/releases) 主题 1.5.2 的版本。

2. 将下载下来的主题解压，将解压的文件夹重命名为 `Material`。

3. 将这个文件夹放到你的博客根目录下的 themes 文件夹下。

![i6XOpT.png](https://s1.ax1x.com/2018/10/27/i6XOpT.png)

## 启用Material主题

:::tip
这里有两个 `_config.yml` 文件，一个位于博客根目录,另一个位于主题文件夹下，下面分别叫他们`根 _config.yml `文件和`主题 _config.yml `文件。
:::

进入Material文件夹,将`_config.template.yml` 重命名为 `_config.yml`
（这个 `_config.yml` 文件是 `主题_config.yml` 文件）

:::tip
建议你将 `_config.template.yml` 文件备份，防止一些不可描述的的问题。
:::

![i6x8mQ.png](https://s1.ax1x.com/2018/10/27/i6x8mQ.png)

回到主题根目录，打开`根 _config.yml `文件，找到 `theme` 属性

![i6zA3V.png](https://s1.ax1x.com/2018/10/27/i6zA3V.png)
![i6Lih8.md.png](https://s1.ax1x.com/2018/10/27/i6Lih8.md.png)

将后面的字段改为你刚刚改的主题文件夹的名字，比如我的`Material`。
:::tip

在 yml 中，冒号后面必须加一个空格，否则会报错。

:::

OK，Material 主题就正式启用了下面，就是见证奇迹的时候了，有没有一点小激动呢?

回到博客根目录，打开终端，输入:

```brash
$ hexo clean
```
回车

![icPF6P.png](https://s1.ax1x.com/2018/10/27/icPF6P.png)

完美！！！:tada:

好，再输入:
```brash
$ hexo g
```
回车

![icPQlq.png](https://s1.ax1x.com/2018/10/27/icPQlq.png)

完全OK！！！:tada:

输入:
```brash
$ hexo s
```
回车

![icPqhj.png](https://s1.ax1x.com/2018/10/27/icPqhj.png)

打开浏览器输入`http://localhost:4000`，即可看见你博客的样子。

![icPW9A.png](https://s1.ax1x.com/2018/10/27/icPW9A.png)
![icP2hd.png](https://s1.ax1x.com/2018/10/27/icP2hd.png)

点片文章试试，如果没问题，那么恭喜你！
:tada: :tada: :tada: :tada:

如果你想让你的Blog马力全开,那么请继续往下看

