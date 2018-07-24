![](https://upload-images.jianshu.io/upload_images/13089440-c61d8080a5f329ce.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###问题描述

最近两周在环境配置的过程中总是会碰到一个类似的问题：`zsh: command not found`，笔者小白在 react-native, gitbook 的安装和 Hexo 创建博客的过程中都碰到了上述问题，导致根本无法按照教案的流程继续进行下去。到网上搜索解决方法，很多并不能与自己的问题匹配，网上还有很多重复的直接 copy 他人的博客（尤其是某度）。

因为 Mac 上安装 node.js 的默认路径是 `/usr/local/bin/node`，而这个经常导致某些权限问题，为了解决这个问题，作者按照网上的教案，指定 npm 的全局 package 安装目录为自己的 Home 目录下面的子目录。于是后来安装的 package 都到了 `/.npm-global `的目录下:
![](https://upload-images.jianshu.io/upload_images/13089440-87f0451dcaa8e9cf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

而作者从事编程学习将代码都放到了 `/Users/liuyuelin/Documents/workspace`目录下: ![](https://upload-images.jianshu.io/upload_images/13089440-d14485317caad0f3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

当作者在 Hexo 目录下输入 `hexo init blog` 的时候就再次遇到了 `zsh: command not found: Hexo` 这个恼人的家伙：![](https://upload-images.jianshu.io/upload_images/13089440-e164866b9619baa7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

几番尝试失败后，作者决定到`./npm-global` 目录下试试:![](https://upload-images.jianshu.io/upload_images/13089440-8bb08b5f55cb924c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
***
###解决过程

结果居然成功了，这时想到是不是环境变量 `$PATH` 没有设置好的缘故，在命令行中输入 `echo $PATH`进行查看：
![](https://upload-images.jianshu.io/upload_images/13089440-f17d83bcf0b9d088.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

果然并没有看到 hexo 的所安装的目录路径，怪不得在其他文档里会出现 `zsh: command not found: Hexo`， 这时在`.npm-global/bin`目录下输入 `pwd` 查看路径：![](https://upload-images.jianshu.io/upload_images/13089440-f7788959c11e3c74.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

然后将得到的路径添加到主目录下面的 `.profile` 文件中去[图片上传中...(屏幕快照 2018-07-23 下午4.40.50.png-f16595-1532335274711-0)]
(安装了 atom 或者 sublime 的同学可以使用  `atom .profile` 或者 `subl .profile` 打开文件):
![](https://upload-images.jianshu.io/upload_images/13089440-6c1a4e31614bfce0.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

保存后在命令行中输入`source .profile` 使之生效，再次输入 `echo $PATH` 查看路径是否添加到环境变量中：![](https://upload-images.jianshu.io/upload_images/13089440-2850fcdb7d91ade5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

随后` cd documents/workspace/Hexo` 来到 Hexo 目录下输入 `hexo init blog` :![](https://upload-images.jianshu.io/upload_images/13089440-5e2f6324994c24d9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

成功解决问题，编程小白的学习又可以继续进行了 :) 

***
#####资料
[PATH环境变量的作用和使用方法](https://blog.csdn.net/qlzx_syzx/article/details/53674823)

[npm使用过程中的一些错误解决办法及npm常用命令和技巧](https://www.cnblogs.com/kidsitcn/p/4557548.html)


刘月林
写于湖北沙洋
2018/07/23


