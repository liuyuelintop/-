今天在安装 gitbook 的过程中，遇到了与昨天类似的问题: zsh: command not found: gitbook.
安装的教程来源于https://www.jianshu.com/p/9f24f8e27fc6, 应该在命令行中使用 sudo npm install -g gitbook-cli 进行安装。但实际做了一点微调，选择没有加sudoi，原因是今天看的一篇文章，说不要使用sudo 避免出现权限问题。安装的结果如下![屏幕快照 2018-07-13 下午6.51.13.png](https://upload-images.jianshu.io/upload_images/13089440-3988361c6f222aec.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
继续按照流程走，输入 gitbook -v 进行版本查看，确认gitbook是否安装，结果就出现了 ![屏幕快照 2018-07-13 下午6.53.05.png](https://upload-images.jianshu.io/upload_images/13089440-b64623330b0964f9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
后来选择进入到安装目录进行查看列表信息![屏幕快照 2018-07-13 下午6.54.44.png](https://upload-images.jianshu.io/upload_images/13089440-ea3835b2c1a85073.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
可里面显示了存在 gitbook 和 react-native 的目录啊，到底是什么原因导致的 zsh: command : not found 的呢？

难道是没有加sudo 的原因吗？
第二次尝试 在命令行中输入 sudo npm install -g gitbook-cli ，迎来的是一连串的报错![屏幕快照 2018-07-13 下午6.32.46.png](https://upload-images.jianshu.io/upload_images/13089440-0fd5d54d2a8366b7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

刘月林
2018/07/13
写于湖北
