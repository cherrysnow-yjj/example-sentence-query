例句查找小助手
=============

### 截图

![很难看的截图](https://raw.github.com/cherrysnow-yjj/example-sentence-query/master/assets/figure.png)

这是一个用来帮助标注者标注数据的一个小工具。在标注者拿不准某些句子片段应该如何划分或者如何标词性时，这个小助手可以提供一定的参考。

### 配置

例句文件的格式可以参考项目中的sample，很简单的。

在0.0.2以后，为了提高加载速度，数据文件需要预先使用marshal进行序列化。具体可以运行data.py脚本，命令如下：

```
python data.py [your_raw_file] corpus.db
```

### 开发

依赖以下一些模块

* pyqt4
* py2exe

界面是用qt designer画的。

### 运行

我们可以运行`quickfind.py`文件来加载这个小工具，命令如下：

```
python quickfind.py
```
