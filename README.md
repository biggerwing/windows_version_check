## Windows操作系统版本检测工具
如果网络可达，Windows Server 2003 R2及其以上版本的
操作系统版本识别率理论上能达以100%

###### windows_version_check-Linux 运行在Linux平台
###### windows_version_check.exe 运行在Window平台


用法：
- 	-h [ip]:	检测一个主机对应的操作系统版本，不可与-f同时用
- 	-f [path]:	对文件中的ip地址做检测，一行一个ip，不可与-h同时用
- 	-r [n] :	设置检测线程，默认为1
- 	示例1: ./command -h 10.1.1.1
- 	示例2：./command -f ip.txt -r 20

Linux下运行效果：
[![Linux下运行效果](https://github.com/biggerwing/windows_version_check/blob/master/windows_version_check-Linux_verify.png "Linux下运行效果")](https://github.com/biggerwing/windows_version_check/blob/master/windows_version_check-Linux_verify.png "Linux下运行效果")

Windows下运行效果：
[![Windows下运行效果](https://github.com/biggerwing/windows_version_check/blob/master/windows_version_check-Windows_verify.png "Windows下运行效果")](https://github.com/biggerwing/windows_version_check/blob/master/windows_version_check-Windows_verify.png "Windows下运行效果")
