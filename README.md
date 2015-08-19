# HZW_Repository

先创建远程库，然后，从远程库克隆（没有进行关联远程库。注意。）

Android studio clone过程
1、
Android Studio 1.1默认安装了Git插件和GitHub插件
进入设置页面（ctrl+alt+s)，Settings>Version Control>Git，设置Git命令的路径
设置GitHub 账号，Settings>Version Control>GitHub,设置登陆账号和密码

2、
从GitHub克隆项目：VCS>Checkout from Version Control>GitHub,
选择想要克隆的项目，设置好目录和项目名称，点击Clone即可。Android Studio 会在本地新建一个Project.

clone 项目之后，如果不是AS项目，会提示说自建成AS项目。设置时，use local gradle distrubition:如：
D:\Tool_Android_Studio\android_studio\gradle\gradle-2.2.1
这样就可以了。

3、
将项目分享到GitHub:VCS>Import into Version Control>Share Project on GitHub

会弹出个github设置窗，设置好名称和描述，就可以在GiHub上新建一个repository，然后就可以push和pull代码了。
（注意是：github本就没有的这个仓库的。）