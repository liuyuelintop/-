很多时候我们只想执行一个指令需要 root 权限， 如果每次都要用到 su 切换身份输入 root 密码太麻烦了。Linux 上有一种机制是 sudo 权限， 可以暂时提升权限。 新开的账号没有 sudo 权限， 首先需要将 "newuser" 加到 sudo 清单：<br>
1.进入超级用户模式。 也就是输入 `su - root` , 然后输入密码<br>
2.添加文件的写权限。 也就是输入命令行`chmod u+w /etc/sudoers`<br>
![屏幕快照 2018-07-21 下午3.48.47.png](https://upload-images.jianshu.io/upload_images/13089440-2c187dae6911f014.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3.编辑/etc/sudoers文件。也就是输入命令`vim /etc/sudoers`, 进入编辑模式，找到这一行`root ALL=(ALL:ALL) ALL` .在下面一行添加 `xxx ALL=(ALL:ALL) ALL` （这里xxx是你的用户名),然后在最下面一行输入`:wq`, 保存退出.
![屏幕快照 2018-07-21 下午3.14.06.png](https://upload-images.jianshu.io/upload_images/13089440-1b74bd4a3c052d93.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4.撤销文件的写权限。也就是输入命令`chmod u-w /etc/sudoers`

最后新增用户也就有了 sudo 权限：![linux.gif](https://upload-images.jianshu.io/upload_images/13089440-08995238355db831.gif?imageMogr2/auto-orient/strip)

[推荐给初学者一点关于 v i 的退出命令](https://www.cnblogs.com/sharpest/p/7427460.html)

[Linux 权限管理和目录配置说明](https://www.cnblogs.com/bangbangjiang/p/4080434.html)

刘月林
写于湖北沙洋
2018/07/21

