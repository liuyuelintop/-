####问题
由于一开始接触环境变量，还不太懂，按照网上的教程改写环境变量，就写的很乱，把我的环境变量写在了` ~/.bash_profile 和 ~/.profile `里面，按道理每次重启系统都会自动去执行一下这个文件的，可是却没有执行，非要手动 source 一下。
作为小白，很是不解，赶紧去查了一下原因。得到答案是切换到 zsh 后，并没有执行` ~/.bashprofile 和 ~/.profile `文件，并且不是简单的覆盖，毕竟我不止对PATH做了改动，还自己添加了环境变量，如果只是覆盖的话不可能 echo 不到我自定义的环境变量。
解决方法别人也给出了，切换到 zsh 后重启后系统会执行 `~/.zshrc`，只需要把 `source ~/.bash_profile`这一行加到.zshrc里面去就搞定了。
<br>
---
###步骤
![](https://upload-images.jianshu.io/upload_images/13089440-7380486d6a1ca977.gif?imageMogr2/auto-orient/strip)
<br>
---
###结果
![](https://upload-images.jianshu.io/upload_images/13089440-7c28ed176dad6e4a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---
刘月林
写于湖北沙洋
2018/07/24
