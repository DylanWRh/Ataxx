## **同化棋**

这是21秋北京大学计算概论A的项目作业——同化棋AI。关于同化棋的规则和相关代码测试的API，可参见同化棋(Ataxx)的[Botzone Wiki](https://wiki.botzone.org.cn/index.php?title=Ataxx)。

对这里的相关文件，介绍如下；

1) 文件夹`History-Botzone`和`History-Demo`：均为项目建设过程中相对比较重要的历史版本，两文件夹内分别为适应Botzone测评API的代码和可以直接在本地运行的代码。
2) 文件夹`Release`：内含可执行文件`Ataxx by WRH-Demo.exe`，可直接在Windows本地运行的课执行文件
3) 文件`Ataxx-Src-BotZone.cpp`和`Ataxx-Src-Demo.cpp`：最终版本的Botzone API适应程序和本地运行程序。

编译需要[`easyx`](https://easyx.cn/)图形库

因为搭建项目时并不会用C++写面向对象，所以（特别是图形界面构建和棋子移动等行为的）代码实际上十分混乱冗余
