## tty的概念
终端：输入输出设备
tty/console:表示物理终端
/dev/tty:总是指向当前正在运行的终端
tty:直接连到电脑上的设备，tty1-63为linux下63个终端，
pts:伪终端，一般指ssh远程登录的终端，或者是图形界面下打开的终端

ttySn：一般作为串行终端设备


查看tty 
who
使用who命令在ubuntu下看到的是整个图形界面使用的tty，即tty7，事实上要看某个打开的终端使用的是哪个设备，得使用tty命令，一般是/dev/pts/*,因为是虚拟终端。
或者
w
显示tty的信息

或者直接用tty命令查看



