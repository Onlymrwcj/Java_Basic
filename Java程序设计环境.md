# Java程序设计环境

## [安装Java开发环境](https://www.bilibili.com/video/BV1f54y1U7Vy)

可以看看我B站上面录制的视频

### 1.下载JDK

在搜索引擎上搜索jdk，可以看到 ![](https://raw.githubusercontent.com/Onlymrwcj/blog-pic1/main/img/20210713170056.png)

选择第一个，进入oracle的官网

[jdk下载](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)

![](https://raw.githubusercontent.com/Onlymrwcj/blog-pic1/main/img/20210713170742.png)

向下滑动挑选适合自己的JDK版本

![](https://raw.githubusercontent.com/Onlymrwcj/blog-pic1/main/img/20210713171702.png)

### 2.安装JDK

双击下载好的exe文件，开始进行安装，如果C盘存储比较小的话，可以安装到其他的盘符，记住一定要自己能够找到！

![JDK的安装路径](https://camo.githubusercontent.com/68371fe52fd37014bece467d6bbf41aa8eaf62218d2bd42a0b4c4b0a07e9f326/68747470733a2f2f757365722d676f6c642d63646e2e786974752e696f2f323031392f392f372f313664303739303831333463323136663f696d61676556696577322f302f772f313238302f682f3936302f666f726d61742f776562702f69676e6f72652d6572726f722f31)

### 3.配置Java环境

jdk安装好，我们对于电脑的环境进行配置

右键我的电脑---->属性——->高级系统设置——>高级——>环境配置——>

![img](https://img-blog.csdnimg.cn/img_convert/3d0da61a9206cf33eecda50184a44db9.png)

2.点击环境变量配置，点击下方的“新建”按钮，在弹出的“新建系统变量”窗口中，新建一个名为“JAVA_HOME”的环境变量，变量值为Java的安装路径

3.配置Path环境变量，该变量已经存在，所以在列表中选择Path，点击下方的“编辑”按钮，在弹出的窗口中添加如下信息：%JAVA_HOME%\bin。

4.进行测试，检测环境是否配置成功

按下快捷键 win+r 跳出搜索框，输入cmd

在cmd命令行中输入Java -version

如果有相关的反应则说明配置成功

