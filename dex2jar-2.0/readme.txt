1. 将需要反编译的dex文件（这里是classes.dex）复制到 dex2jar 解压目录下。

2. 打开命令行进入 d2j-dex2jar.bat 文件所在目录，输入命令 d2j-dex2jar.bat classes.dex 。

	但是我运行之后还是不行，依然是权限问题。后来找到一个解决方法：

	chmod a+x *.sh

此时可以看到目录中多出了classes-dex2jar.jar文件。

把jar copy到gui 目录

3. 使用 jd-gui 打开
