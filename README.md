# 使用Screen潇潇洒洒跑代码
参考https://blog.csdn.net/FionaAI/article/details/105174160

创建screen：`screen -S yjl`

然后运行代码

ctrl+a+d退出screen

查看创建的screen：`screen -ls`

查看自己screen的名字

例如我的：`23293.yjl`

重新打开screen：`screen -r 23293.yjl`

删除screen：`screen -X -S 23293.yjl quit`

