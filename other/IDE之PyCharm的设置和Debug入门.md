### PyCharm 设置

- [pycharm快捷键及一些常用设置](http://blog.csdn.net/fighter_yy/article/details/40860949)
- [配置PyCharm(背景色+字体大小+解释器选择)](http://blog.csdn.net/vernice/article/details/50934869)


### PyCharm 调试

- [最全Pycharm教程（10）——Pycharm调试器总篇](https://blog.csdn.net/u013088062/article/details/50214459)


### PyCharm 代码调试快捷键：

- F8：单步
- F7：单步，进函数里面（无函数时同 F8）
- Shift+F8：单步跳出
- Alt+F9：运行到光标所在位置处
- Alt+F8：测试语句
- F9：重新运行程序（实际是到下个断点）
- Ctrl+F8：切换断点
- Ctrl+F8：查看断点

Debug 相关功能

- F8：step over 单步

  遇到断点后，程序停止运行，按F8单步运行。

- F7：step into 进入

  配合F8使用。单步调试 F8 时，如果某行调用其他模块的函数，在此行 F7，可以进入函数内部，如果是 F8 则不会进入函数内容，直接单步到下一行。

- Alt+shift+F7：step into mycode

  个人理解 F8 和 F7 的综合。1、没遇到函数，和 F8 一样；2、遇到函数会自动进入函数内部，和 F8 时按 F7 类似的

- shift+F8：跳出

  调试过程中，F7进入函数内后，shift+F8跳出函数，会回到进入前调用函数的代码。不是函数地方shift+F8跳出，怎么用没太明白，但最终会执行到结束。

- F9：resume program

  按翻译是重启程序 ，实际是 下个断点，当打多个断点是，F9会到下一个断点

常用：F8，F9，其次  Alt+shift+F7，或 F7，shift+F8

