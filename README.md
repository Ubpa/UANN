# UANN
ANN (Approximate Nearest Neighbors) library, ported to CMake

[官方网站](http://www.cs.umd.edu/~mount/ANN/)，[官方文档](http://www.cs.umd.edu/~mount/ANN/Files/1.1.2/ANNmanual_1.1.pdf) 

由于项目没有提供 CMakeLists.txt，故我将其改为 CMake 项目

## 使用说明

### test

运行程序后输入 [data/test/test1.in](data/test/test1.in) 的内容，可在调试窗口中得到同于 [data/test/test1.save](data/test/test1.save) 的输出

### sample

添加命令参数 `-df ../data/sample/data.pts -qf ../data/sample/query.pts` 来运行程序，可在调试窗口中得到同于 [data/sample/sample.save](data/sample/sample.save) 的输出

### ann2fig

本程序可以将 test 的 dump 文件转换成 fig 图像文件，然而 fix 图像文件需要用 [xfig 软件](https://www.xfig.org/) 才能打开，在 linux 上可使用，[在 window 上安装](http://www.gohappycup.com/personal/latex/xfig.html) 十分不易（并且作者直说明能最高支持 Windows XP）。故不研究，有兴趣的自行尝试。

