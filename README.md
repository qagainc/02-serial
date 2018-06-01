在原来基础上，把串口工具改成了PY3.6下可运行。

Serial Tool
================================================================
用python2.7、Tkinter、pyserial模块开发的串口调试工具<br>

已将串口工具和USB整合在一起
* [SlaveDebugTool](https://git.oschina.net/jakey.chen/SlaveDebugTool)

安装使用
================================================================
需要安装的模块：<br>
在Windows下:<br>
    默认是有安装Tkinter的，因此只需要安装pyserial<br>
    可以通过pip来安装：<br>
        pip install pyserial<br>
    或者到 https://pypi.python.org/pypi/pywinusb 下载最新版安装<br>
        python setup.py install<br>
    或者到 http://www.lfd.uci.edu/~gohlke/pythonlibs/下载安装版<br>
在Ubuntu下：<br>
    默认是没有安装Tkinter的<br>
    需要先进行必要模块的安装<br>
    使用apt-get安装tk<br>
        sudo apt-get install python-tk<br>
    pyserial可以通过pip来安装：<br>
        pip install pyserial<br>
    或者到 https://pypi.python.org/pypi/pyserial 下载最新版安装<br>
        python setup.py install<br>
执行python main.py即可开始使用(ubuntu下需要使用root权限 sudo python main.py)<br>

使用技巧
================================================================
在左侧列表框，可以显示出当前连接的串口设备。<br>
可以通过双击打开设备（或者点击下面的Open打开设备）<br>
状态栏会有相应的提示信息<br>
点击Clear可以清楚计数和接收的数据<br>
其他待定，暂使用良好，暂未发现Bug和需要改进的地方。<br>