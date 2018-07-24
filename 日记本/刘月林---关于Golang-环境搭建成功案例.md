
![](https://upload-images.jianshu.io/upload_images/13089440-db34880e47201b82.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![go.gif](https://upload-images.jianshu.io/upload_images/13089440-6e9ec45e3631f976.gif?imageMogr2/auto-orient/strip)


```
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ brew install go
Updating Homebrew…
^C⇒ Downloading [https://homebrew.bintray.com/bottles/go-1.10.3.sierra.bottle.tar.g](https://homebrew.bintray.com/bottles/go-1.10.3.sierra.bottle.tar.g)

###### ################################################################## 100.0%

⇒ Pouring go-1.10.3.sierra.bottle.tar.gz
⇒ Caveats
A valid GOPATH is required to use the `go get` command.
If $GOPATH is not specified, $HOME/go will be used by default:
[https://golang.org/doc/code.html#GOPATH](https://golang.org/doc/code.html#GOPATH)

You may wish to add the GOROOT-based install location to your PATH:
export PATH=[图片上传失败...(image-48625e-1532350472293)]

{PATH}”
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ export PATH
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ source ~/.bash_profile
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ go get github.com/beego/bee
^[[A^C
✘ liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ go get github.com/beego/bee
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ go get github.com/astaxie/beego
^C
✘ liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ go get github.com/astaxie/beego
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ cd go/src
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ bee run quicstart
2018/07/23 20:25:41 ERROR ▶ 0001 You need to set GOPATH environment variable

* * *

| ***\
| |*/ / _**  ***|***\ / *\ / *\
| |*/ /| **/| **/
_**_/ \***| ___| v1.10.0
2018/07/23 20:25:41 FATAL ▶ 0002 GOPATH environment variable is not set or empty
✘ liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ cd ..
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go ⮀ cd ..
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ ls
2+3*4 Movies get-pip.py
Applications Music go
Creative Cloud Files Pictures helloWorld
Desktop Public nofly.txt
Documents abc.txt oddIndex.m
Downloads bcaon.txt simpson.m
FLUSH eclipse styles.less
IdeaProjects eclipse-workspace 百度云同步盘
Library first_app
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ cd go
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go ⮀ ls
bin pkg src
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go ⮀ cd ..
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ go get github.com/beego/bee
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ go get github.com/astaxie/beego
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ cd go
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go ⮀ cd bin
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/bin ⮀ ls
bee
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/bin ⮀ cd ..
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go ⮀ cd pkg
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/pkg ⮀ ls
darwin_amd64
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/pkg ⮀ cd ..
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go ⮀ cs src
zsh: command not found: cs
✘ liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go ⮀ cd src
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ ls
github.com golang.org gopkg.in
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ cd ..
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go ⮀ cd ..
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ go get github.com/beego/bee
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ man beego
No manual entry for beego
✘ liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ go get github.com/beego/bee
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ go get github.com/beego/bee
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ go get github.com/astaxie/beego
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~ ⮀ cd go/src
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ bee run quicstart
2018/07/23 20:28:47 ERROR ▶ 0001 You need to set GOPATH environment variable

* * *

| ***\
| |*/ / _**  ***|***\ / *\ / *\
| |*/ /| **/| **/
_**_/ \***| ___| v1.10.0
2018/07/23 20:28:47 FATAL ▶ 0002 GOPATH environment variable is not set or empty
✘ liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ echo $PATH
”/Users/liuyuelin/.npm-global/bin/:/Users/liuyuelin/go/bin:/Users/liuyuelin/.npm-global/bin:/Users/liuyuelin/.rvm/gems/ruby-2.3.3/bin:/Users/liuyuelin/.rvm/gems/ruby-2.3.3@global/bin:/Users/liuyuelin/.rvm/rubies/ruby-2.3.3/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Users/liuyuelin/.rvm/bin”
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ echo $GOPATH

liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ pwd
/Users/liuyuelin/go/src
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ export GOPATH=/Users/liuyuelin/go
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ echo $GOPATH
/Users/liuyuelin/go
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ bee run quicstart

* * *

| ***\
| |*/ / _**  ***|***\ / *\ / *\
| |*/ /| **/| **/
_**_/ \***| ___| v1.10.0
2018/07/23 20:41:29 FATAL ▶ 0001 No application ‘quicstart’ found in your GOPATH
✘ liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ bee new quickstarte

* * *

| ***\
| |*/ / _**  ***|***\ / *\ / *\
| |*/ /| **/| **/
_**_/ \***| ___| v1.10.0
2018/07/23 20:44:54 INFO ▶ 0001 Creating application…
create /Users/liuyuelin/go/src/quickstarte/
create /Users/liuyuelin/go/src/quickstarte/conf/
create /Users/liuyuelin/go/src/quickstarte/controllers/
create /Users/liuyuelin/go/src/quickstarte/models/
create /Users/liuyuelin/go/src/quickstarte/routers/
create /Users/liuyuelin/go/src/quickstarte/tests/
create /Users/liuyuelin/go/src/quickstarte/static/
create /Users/liuyuelin/go/src/quickstarte/static/js/
create /Users/liuyuelin/go/src/quickstarte/static/css/
create /Users/liuyuelin/go/src/quickstarte/static/img/
create /Users/liuyuelin/go/src/quickstarte/views/
create /Users/liuyuelin/go/src/quickstarte/conf/app.conf
create /Users/liuyuelin/go/src/quickstarte/controllers/default.go
create /Users/liuyuelin/go/src/quickstarte/views/index.tpl
create /Users/liuyuelin/go/src/quickstarte/routers/router.go
create /Users/liuyuelin/go/src/quickstarte/tests/default_test.go
create /Users/liuyuelin/go/src/quickstarte/main.go
2018/07/23 20:44:54 SUCCESS ▶ 0002 New application successfully created!
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ bee run quicstart

* * *

| ***\
| |*/ / _**  ***|***\ / *\ / *\
| |*/ /| **/| **/
_**_/ \***| ___| v1.10.0
2018/07/23 20:45:00 FATAL ▶ 0001 No application ‘quicstart’ found in your GOPATH
✘ liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/go/src ⮀ bee run quickstarte

* * *

| ***\
| |*/ / _**  ***|***\ / *\ / *\
| |*/ /| **/| **/
_**_/ \***| ___| v1.10.0
2018/07/23 20:45:37 INFO ▶ 0001 Using ‘quickstarte’ as ‘appname’
2018/07/23 20:45:37 INFO ▶ 0002 Initializing watcher…
quickstarte/controllers
quickstarte/routers
quickstarte
2018/07/23 20:45:39 SUCCESS ▶ 0003 Built Successfully!
2018/07/23 20:45:39 INFO ▶ 0004 Restarting ‘quickstarte’…
2018/07/23 20:45:39 SUCCESS ▶ 0005 ‘./quickstarte’ is running…
2018/07/23 20:45:39.738 [I] [asm_amd64.s:2361] http server Running on [http://:8080](http://:8080/)
2018/07/23 20:46:32.926 [D] [server.go:2694] | ::1| 200 | 1.7958ms| match| GET / r:/
2018/07/23 20:46:32.956 [D] [server.go:2694] | ::1| 200 | 175.803µs| match| GET /static/js/reload.min.js
2018/07/23 20:46:32.987 [D] [server.go:2694] | ::1| 404 | 375.565µs| nomatch| GET /favicon.ico
```

错误原因：
1+设置$GOPATH
2+没有新建项目
3+项目名称打错

刘月林
写于湖北沙洋
2018/07/23
